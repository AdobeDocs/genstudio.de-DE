---
title: Anpassen einer Vorlage
description: Erfahren Sie, wie Sie Ihre Vorlage für Adobe GenStudio for Performance Marketing personalisieren und optimieren können.
level: Intermediate
feature: Templates, Content
exl-id: 292c1689-1b12-405d-951e-14ee6aebc75a
source-git-commit: 059b464cb2a7b57557407bbaee6162b770107222
workflow-type: tm+mt
source-wordcount: '1032'
ht-degree: 0%

---

# Vorlagen anpassen

Passen Sie Ihre HTML-Vorlagen für Adobe GenStudio for Performance Marketing mithilfe der Vorlagensprache _Handlebars_ an. Die Syntax [!DNL Handlebars] verwendet regulären Text mit doppelten Klammern als Platzhalter für Inhalte. Informationen zur Vorbereitung Ihrer Vorlage finden Sie unter [`What is [!DNL Handlebars]?`](https://handlebarsjs.com/guide/#what-is-handlebars) im _Handlebars-Sprachleitfaden_ .

In den nächsten Abschnitten wird beschrieben, wie Sie Platzhalter für Inhalte hinzufügen, unnötige Elemente aus der Vorschau ausblenden und Links zu statischen Inhalten verwalten. Sobald Ihre Vorlage fertig ist, können Sie sie [in GenStudio for Performance Marketing](use-templates.md#upload-a-template) hochladen und mit der Generierung personalisierter E-Mails auf der Basis Ihrer benutzerdefinierten Vorlage beginnen.

## Inhalts-Platzhalter

GenStudio for Performance Marketing erkennt bestimmte [Elemente](use-templates.md#template-elements) in einer Vorlage, jedoch nur, wenn Sie sie mit einem erkannten Feldnamen identifizieren.

Im Kopf- oder Textkörper einer Vorlage können Sie die Syntax [!DNL Handlebars] als Platzhalter für Inhalte verwenden, bei dem GenStudio for Performance Marketing die Vorlage mit dem tatsächlichen Inhalt füllen muss. GenStudio for Performance Marketing erkennt und interpretiert die Inhaltsplatzhalter basierend auf dem [erkannten _Feldnamen_ ](#recognized-field-names).

Sie können beispielsweise `{{ headline }}` mit der Syntax [!DNL Handlebars] verwenden, um anzugeben, wo die Überschrift der E-Mail platziert werden soll:

```handlebars
<div>{{headline}}</div>
```

### Erkannte Feldnamen

In der folgenden Tabelle sind die von GenStudio for Performance Marketing für die Population erkannten Feldnamen in Vorlagen aufgeführt. Fügen Sie diese Feldnamen mithilfe der Syntax [!DNL Handlebars] zu Ihrer Vorlage hinzu, wo GenStudio for Performance Marketing zum Generieren von Inhalten erforderlich ist.

| Feld | Rolle | Kanalvorlage |
| -------------- | ---------------------- | ------------------------------ |
| `pre_header` | Pre-Header | email |
| `headline` | Überschrift | email <br>Meta-Anzeige |
| `body` | Textkopie | email <br>Meta-Anzeige |
| `cta` | Aktionsaufruf | email <br>Meta-Anzeige |
| `on_image_text` | Im Bildtext | Meta-Anzeige |
| `image` | Bild | email <br>Meta-Anzeige |
| `brand_logo` | Logo der ausgewählten Marke<br>Siehe [Markenname des Logos](#brand-logo-field-name) für die empfohlene Verwendung. | email<br>Meta-Anzeige |

GenStudio for Performance Marketing füllt bestimmte Felder automatisch in den folgenden Vorlagen aus:

- **Für E-Mail-Vorlage** müssen Sie das Feld `subject` nicht identifizieren
- **Die Vorlage für Metaanzeigen** erfordert nicht, dass Sie die Felder `headline`, `body` und `CTA` identifizieren

<!--
- **Display Ads template** does not require you to idenitify the `CTA` field
-->

>[!WARNING]
>
>Bei Instagram-Anzeigen erscheint die generierte Überschrift nicht im endgültigen Erlebnis.

Beim Hochladen einer Vorlage in GenStudio for Performance Marketing sind 20 Felder erlaubt. Da das Feld `subject` automatisch in einer E-Mail generiert wird, zählt es als ein Feld. Das bedeutet, dass eine E-Mail-Vorlage 19 Felder zulässt.

>[!TIP]
>
>Sie können Ihre Vorlage mit der [Vorlagenvorschau](#template-preview) in GenStudio for Performance Marketing überprüfen.

#### Feldname für Markenlogo

Derzeit können Sie das Markenlogo für den Vorlagen-Upload nicht auswählen. Die folgenden Beispiele zeigen zwei Methoden, die das Markenlogo bedingt rendern. Jede Methode überprüft die Quelle, stellt ein standardmäßiges oder alternatives Bild bereit, falls das Markenlogo nicht verfügbar ist, und wendet einen Stil an:

**Beispiel 1**: Verwendung der integrierten Hilfsbedingung [!DNL Handlebars] direkt im Attribut HTML `img src`:

```html
<img src="{{#if brand_logo}}{{brand_logo}}{{else}}<default-image>{{/if}}" alt="img alt text" style="max-width: 88px; margin: 10px auto; display: block;">
```

**Beispiel 2**: Verwenden der integrierten Bedingungsanweisung [!DNL Handlebars], um das HTML `img` -Tag zu umbrechen:

```handlebars
{{#if brand_logo}}
    <img src="{{brand_logo}}" alt="img alt text" style="width: 120px; height: 45px; margin: 10px auto; display: block;">
    {{else}}
    <img src="data:image/png;base64,iVBORw0KGgo..." alt="img alt text" style="width: 120px; height: 45px; margin: 10px auto; display: block;">
{{/if}}
```

#### Manuelle Feldnamen

Alle anderen Feldnamen werden als manuell ausgefüllte Felder behandelt.

Um einen bearbeitbaren Abschnitt zu erstellen, fügen Sie um den Abschnittsnamen doppelte Klammern hinzu:

```handlebars
{{customVariable}}
```

### Abschnitte oder Gruppen

_Abschnitte_ informieren GenStudio for Performance Marketing darüber, dass die Felder in diesem Abschnitt einen hohen Grad an Kohärenz erfordern. Durch diese Beziehung kann die KI Inhalte generieren, die mit den kreativen Elementen im Abschnitt übereinstimmen.

Verwenden Sie ein Präfix Ihrer Wahl im Feldnamen, um anzugeben, dass ein Feld Teil eines Abschnitts oder einer Gruppe ist. Sie können beispielsweise Inhalte in einem hervorgehobenen Bereich markieren:

- `pod1_headline`
- `pod1_body`

Jeder Abschnitt kann nur einen Feldtyp verwenden. Im obigen Beispiel kann der Abschnitt `pod1` nur ein einziges `pod1_headline` -Feld verwenden.

Eine Vorlage kann aus bis zu drei Bereichen bestehen:

- `headline`
- `body`
- `pod1_headline`
- `pod1_body`
- `pod2_headline`
- `pod2_body`

GenStudio for Performance Marketing versteht, dass `pod1_headline` enger mit `pod1_body` als mit `pod2_body` verwandt ist.

## Vorschau der Vorlage

Wenn Sie [eine Vorlage hochladen](use-templates.md#upload-a-template), scannt GenStudio for Performance Marketing die HTML-Datei auf erkannte Felder. Verwenden Sie die Vorschau, um Ihre [Vorlagenelemente](use-templates.md#template-elements) zu überprüfen und sicherzustellen, dass Sie sie mit den [erkannten Feldnamen](#recognized-field-names) richtig identifiziert haben.

Beispielvorschau für eine E-Mail-Vorlage:

![Vorschau der erkannten Felder anzeigen](../../assets/template-detected-fields.png){width="650"}

### Control preview

Sie können die Sichtbarkeit von speziellen Inhalten mithilfe von integrierten Helfern steuern (spezielle Ausdrücke in der Vorlagensprache [!DNL Handlebars], die bestimmte Aktionen durchführen). Beispielsweise können Sie eine bedingte Anweisung hinzufügen, die Tracking-Parameter zu Links in der exportierten Vorlage hinzufügt, während die Vorschaulinks sauber bleiben.

Der `_genStudio.browser` -Wert wird beim Rendern einer Vorlage festgelegt und der `genStudio.export` -Wert wird beim Exportieren einer Vorlage festgelegt. Sie können bestimmte Inhalte über einen bedingten Wrapper oben in einer E-Mail einfügen, z. B. wenn die Vorlage für den Export verwendet wird:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Ein weiteres Beispiel könnte sein, die Verwendung von Trackingcodes bei der Vorschau einer Vorlage in GenStudio for Performance Marketing zu verhindern. Im folgenden Beispiel wird gezeigt, wie Tracking-Parameter zu Links in der exportierten Vorlage hinzugefügt werden, während die Vorschaulinks sauber gehalten werden:

```handlebars
<a class="button" {{#if _genStudio.browser }}
   href="{{ link }}"{{/if}}{{#if _genStudio.export }}
   href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}}
   target="_blank">{{ cta }}</a>
```

## Statischer Inhalt

E-Mail- und Meta-Vorlagen verknüpfen häufig mit Bildern und CSS-Dateien, die außerhalb von GenStudio for Performance Marketing gehostet werden. Wenn GenStudio for Performance Marketing Miniaturansichten für diese Vorlagen oder daraus abgeleitete Erlebnisse generiert, können diese externen Ressourcen ignoriert werden, wenn sie nicht über die richtigen CORS-Kopfzeilen (Cross Origin Resource Sharing) verfügen.

Beachten Sie zwei Optionen, um sicherzustellen, dass diese Ressourcen während des Generierungsprozesses von Miniaturansichten verfügbar sind:

1. **CORS-Header verwenden**: Der Host-Server muss Antworten senden, deren `Access-Control-Allow-Origin`-Header für Produktionsumgebungen auf den Wert `https://experience.adobe.com` eingestellt ist. Auf diese Weise kann GenStudio for Performance Marketing auf die Ressourcen zugreifen und diese einschließen.

1. **Daten-URLs verwenden**: Betten Sie die externen Ressourcen mithilfe von Daten-URLs direkt in die Vorlage ein. Diese Methode umgeht CORS-Einschränkungen und stellt sicher, dass die Ressourcen während der Erstellung von Miniaturansichten verfügbar sind.

## Vorlagenbeispiele

+++Beispiel: E-Mail-Vorlage mit einem Abschnitt

Im Folgenden finden Sie ein Beispiel für eine HTML-Vorlage für eine E-Mail, die nur einen Bereich enthält. Der Kopf enthält einfache Inline-CSS für die Formatierung. Der Hauptteil enthält einen `pre-header`-, `headline`- und `image` [Platzhalter](#content-placeholders) für die Verwendung durch GenStudio for Performance Marketing zum Einfügen von Inhalten während des E-Mail-Generierungsprozesses.

```handlebars {line-numbers="true" highlight="13"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
    </div>
</body>
</html>
```

+++

+++Beispiel: E-Mail-Vorlage mit mehreren Abschnitten

Im Beispiel oben ist dieselbe HTML-Vorlage zu sehen, jedoch mit zwei weiteren Abschnitten. Der Kopf enthält Inline-CSS zum Formatieren einer Gruppe. Der Hauptteil verwendet zwei Gruppen mit [Inhalts-Platzhaltern](#content-placeholders), die ein Präfix verwenden.

```handlebars {line-numbers="true" highlight="33"}
<!DOCTYPE html>
<html>
<head>
    <title>Adobe</title>
    <style>
        .container {
            width: 100%;
            padding: 20px;
            font-family: Arial, sans-serif;
        }
        .pod {
            background-color: #f8f8f8;
            margin: 10px;
            padding: 20px;
            border-radius: 5px;
        }
        .pod h2 {
            color: #333;
        }
        .pod p {
            color: #666;
        }
    </style>
</head>
<body>{{ pre_header }}
    <div class="container">
        <h1>{{ headline }}</h1>
        <p><img alt="{{ headline }}"
                src="{{ image }}"
                width="600" height="600"
                border="0"/></p>
        <p>{{ body }}</p>
    <!-- Pod1 -->
        <div class="pod">
            <h2>{{ pod1_header }}</h2>
            <p>{{ pod1_body }}</p>
        </div>
        <!-- End of Pod1 -->
    <!-- Pod2 -->
        <div class="pod">
            <h2>{{ pod2_header }}</h2>
            <p>{{ pod2_body }}</p>
        </div>
        <!-- End of Pod2 -->
    </div>
</body>
</html>
```

+++

+++Beispiel: Meta-Anzeigenvorlage

Im Folgenden finden Sie ein grundlegendes Beispiel für eine Meta-Anzeigenvorlage. Der Kopf enthält Inline-CSS für die Formatierung. Der Hauptteil verwendet [Inhalts-Platzhalter](#content-placeholders) mit einem Präfix.

```handlebars {line-numbers="true" highlight="33"}
<!DOCTYPE html>
<html>
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Adobe</title>
    <style>
        .ad-container {
            width: 300px;
            border: 1px solid #ddd;
            padding: 16px;
            font-family: Arial, sans-serif;
        }
        .ad-image {
            width: 100%;
            height: auto;
        }
        .ad-headline {
            font-size: 18px;
            font-weight: bold;
            margin: 12px 0;
        }
        .ad-body {
            font-size: 14px;
            margin: 12px 0;
        }
        .ad-cta {
            display: inline-block;
            padding: 10px 20px;
            background-color: #007bff;
            color: #fff;
            text-decoration: none;
            border-radius: 4px;
            text-align: center;
        }
    </style>
</head>
<body>
<div class="ad-container">
    <img src="{{ image }}" alt="Ad Image" class="ad-image">
    <div class="ad-headline">"{{ headline }}"</div>
    <div class="ad-body">"{{ body }}"</div>
    <a href="(https://example.com)" class="ad-cta">"{{ CTA }}"</a>
</div>
</body>
</html>
```

+++
