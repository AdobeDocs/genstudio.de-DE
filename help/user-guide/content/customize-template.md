---
title: Anpassen einer Vorlage
description: Erfahren Sie, wie Sie Ihre Vorlage für Adobe GenStudio for Performance Marketing personalisieren und optimieren können.
level: Intermediate
feature: Templates, Content
exl-id: 292c1689-1b12-405d-951e-14ee6aebc75a
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '1032'
ht-degree: 0%

---

# Anpassen einer Vorlage

Passen Sie Ihre HTML-Vorlagen für Adobe GenStudio for Performance Marketing mithilfe der Vorlagensprache _Handlebars_ an. Die [!DNL Handlebars] Syntax verwendet regulären Text mit doppelten Klammern als Platzhalter für Inhalte. Siehe [`What is [!DNL Handlebars]?`](https://handlebarsjs.com/guide/#what-is-handlebars) im _Handlebars-Sprachhandbuch_, um zu erfahren, wie Sie Ihre Vorlage vorbereiten.

In den nächsten Abschnitten wird erläutert, wie Sie Platzhalter für Inhalte hinzufügen, unnötige Elemente aus der Vorschau ausblenden und Links zu statischen Inhalten verwalten. Sobald Ihre Vorlage fertig ist, können Sie sie [in GenStudio for Performance Marketing hochladen](use-templates.md#upload-a-template) und mit der Erstellung personalisierter E-Mails beginnen, die auf Ihrer benutzerdefinierten Vorlage basieren.

## Platzhalter für Inhalte

GenStudio for Performance Marketing erkennt bestimmte [Elemente](use-templates.md#template-elements) innerhalb einer Vorlage, jedoch nur, wenn Sie sie mit einem erkannten Feldnamen identifizieren.

Im Kopf oder Text einer Vorlage können Sie die [!DNL Handlebars] als Platzhalter für Inhalte verwenden, bei dem GenStudio for Performance Marketing die Vorlage mit tatsächlichem Inhalt füllen muss. GenStudio for Performance Marketing erkennt und interpretiert die Platzhalter für Inhalte anhand des [erkannten _Feld_ Namens](#recognized-field-names).

Sie können beispielsweise `{{ headline }}` mit der [!DNL Handlebars] Syntax verwenden, um anzugeben, wo die Überschrift der E-Mail platziert werden soll:

```handlebars
<div>{{headline}}</div>
```

### Erkannte Feldnamen

In der folgenden Tabelle sind die Feldnamen aufgeführt, die von GenStudio for Performance Marketing zum Auffüllen in Vorlagen erkannt werden. Fügen Sie diese Feldnamen mithilfe der [!DNL Handlebars] zu Ihrer Vorlage hinzu, wenn GenStudio for Performance Marketing Inhalte generieren soll.

| Feld | Rolle | Kanalvorlage |
| -------------- | ---------------------- | ------------------------------ |
| `pre_header` | Pre-Header | email |
| `headline` | Überschrift | email <br>Meta-Anzeige |
| `body` | Textkörper | email <br>Meta-Anzeige |
| `cta` | Handlungsaufforderung | email <br>Meta-Anzeige |
| `on_image_text` | Bei Bildtext | Meta-Anzeige |
| `image` | Bild | email <br>Meta-Anzeige |
| `brand_logo` | Logo der ausgewählten Marke<br> Siehe [Feldname für das Markenlogo](#brand-logo-field-name) für die empfohlene Verwendung. | email<br>Meta-Anzeige |

GenStudio for Performance Marketing füllt bestimmte Felder in den folgenden Vorlagen automatisch:

- **E-Mail** Vorlage: Erfordert nicht, dass das `subject` Feld identifiziert wird
- **Meta-Anzeigenvorlage** erfordert nicht, dass Sie die Felder `headline`, `body` und `CTA` identifizieren

<!--
- **Display Ads template** does not require you to idenitify the `CTA` field
-->

>[!WARNING]
>
>Bei Instagram-Anzeigen wird die generierte Überschrift nicht im endgültigen Erlebnis angezeigt.

Beim Hochladen einer Vorlage in GenStudio for Performance Marketing gibt es eine Beschränkung von 20 Feldern. Da das `subject` automatisch in einer E-Mail generiert wird, zählt es als ein Feld. Das bedeutet, dass in einer E-Mail-Vorlage 19 Felder zulässig sind.

>[!TIP]
>
>Sie können Ihre Vorlage mithilfe der [Vorlagenvorschau](#template-preview) in GenStudio for Performance Marketing überprüfen.

#### Feldname für das Markenlogo

Derzeit können Sie das Markenlogo für den Vorlagen-Upload nicht auswählen. Die folgenden Beispiele zeigen zwei Methoden, die das Markenlogo bedingt rendern. Jede Methode überprüft die Quelle, liefert ein Standard- oder Alternativbild für den Fall, dass das Markenlogo nicht verfügbar ist, und wendet einen Stil an:

**Beispiel 1**: Verwenden [!DNL Handlebars] integrierten Helper-Bedingung direkt im HTML-`img src`:

```html
<img src="{{#if brand_logo}}{{brand_logo}}{{else}}<default-image>{{/if}}" alt="img alt text" style="max-width: 88px; margin: 10px auto; display: block;">
```

**Beispiel 2**: Verwenden [!DNL Handlebars] integrierten Bedingungsanweisung zum Umschließen des HTML-`img`-Tags:

```handlebars
{{#if brand_logo}}
    <img src="{{brand_logo}}" alt="img alt text" style="width: 120px; height: 45px; margin: 10px auto; display: block;">
    {{else}}
    <img src="data:image/png;base64,iVBORw0KGgo..." alt="img alt text" style="width: 120px; height: 45px; margin: 10px auto; display: block;">
{{/if}}
```

#### Manuelle Feldnamen

Alle anderen Feldnamen werden als manuell ausgefüllte Felder behandelt.

Um einen bearbeitbaren Abschnitt zu erstellen, fügen Sie doppelte Klammern um den Abschnittsnamen hinzu:

```handlebars
{{customVariable}}
```

### Abschnitte oder Gruppen

_Abschnitte_ informieren GenStudio for Performance Marketing, dass die Felder in diesem Abschnitt ein hohes Maß an Kohärenz erfordern. Durch Festlegen dieser Beziehung kann die KI Inhalte generieren, die den kreativen Elementen im Abschnitt entsprechen.

Verwenden Sie ein Präfix Ihrer Wahl im Feldnamen, um anzugeben, dass ein Feld Teil eines Abschnitts oder einer Gruppe ist. Beispielsweise können Sie Inhalte markieren, die in einem hervorgehobenen Bereich angezeigt werden:

- `pod1_headline`
- `pod1_body`

Jeder Abschnitt kann nur einen der Feldtypen verwenden. Im obigen Beispiel kann der Abschnitt `pod1` nur ein `pod1_headline` verwenden.

Eine Vorlage kann bis zu drei Abschnitte enthalten:

- `headline`
- `body`
- `pod1_headline`
- `pod1_body`
- `pod2_headline`
- `pod2_body`

GenStudio for Performance Marketing weiß, dass `pod1_headline` enger mit `pod1_body` als mit `pod2_body` verbunden ist.

## Vorlagenvorschau

Wenn Sie [eine Vorlage hochladen](use-templates.md#upload-a-template) durchsucht GenStudio for Performance Marketing die HTML-Datei nach erkannten Feldern. Verwenden Sie die Vorschau, um Ihre [Vorlagenelemente](use-templates.md#template-elements) zu überprüfen und sicherzustellen, dass Sie sie ordnungsgemäß mit den [erkannten Feldnamen“ ](#recognized-field-names).

Beispielvorschau für eine E-Mail-Vorlage:

![Vorschau der Felder erkannt](../../assets/template-detected-fields.png){width="650"}

### Vorschau steuern

Sie können die Sichtbarkeit spezieller Inhalte mithilfe integrierter Helper (spezielle Ausdrücke in der [!DNL Handlebars]-Vorlagensprache, die bestimmte Aktionen ausführen) steuern. Sie können beispielsweise eine bedingte Anweisung hinzufügen, die Tracking-Parameter zu Links in der exportierten Vorlage hinzufügt, während die Vorschau-Links sauber bleiben.

Der `_genStudio.browser` wird beim Rendern einer Vorlage festgelegt und der `genStudio.export` wird beim Exportieren einer Vorlage festgelegt. Sie können sich dafür entscheiden, bestimmte Inhalte am Anfang einer E-Mail mit einem bedingten Wrapper einzuschließen, z. B. wenn die Vorlage für den Export verwendet wird:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Ein weiteres Beispiel könnte sein, die Verwendung von Trackingcodes bei der Vorschau einer Vorlage in GenStudio for Performance Marketing zu verhindern. Das folgende Beispiel zeigt, wie Sie Tracking-Parameter zu Links in der exportierten Vorlage hinzufügen und dabei die Vorschau-Links sauber halten:

```handlebars
<a class="button" {{#if _genStudio.browser }}
   href="{{ link }}"{{/if}}{{#if _genStudio.export }}
   href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}}
   target="_blank">{{ cta }}</a>
```

## Statischer Inhalt

E-Mail- und Meta-Vorlagen sind häufig mit Bildern und CSS-Dateien verknüpft, die außerhalb von GenStudio for Performance Marketing gehostet werden. Wenn GenStudio for Performance Marketing Miniaturansichten für diese Vorlagen oder die daraus abgeleiteten Erlebnisse generiert, kann es diese externen Ressourcen ignorieren, wenn sie nicht die richtigen CORS-Kopfzeilen (Cross-Origin Resource Sharing) haben.

Um sicherzustellen, dass diese Ressourcen während des Generierungsprozesses von Miniaturansichten verfügbar sind, sollten Sie zwei Optionen in Betracht ziehen:

1. **CORS-Header verwenden**: Der Host-Server muss Antworten senden, bei denen der `Access-Control-Allow-Origin`-Header für Produktionsumgebungen auf `https://experience.adobe.com` Wert festgelegt ist. Auf diese Weise kann GenStudio for Performance Marketing auf die Ressourcen zugreifen und sie einbeziehen.

1. **Daten-URLs verwenden**: Betten Sie die externen Ressourcen mithilfe von Daten-URLs direkt in die Vorlage ein. Diese Methode umgeht CORS-Einschränkungen und stellt sicher, dass die Ressourcen während der Generierung von Miniaturansichten verfügbar sind.

## Vorlagenbeispiele

+++Beispiel: E-Mail-Vorlage mit einem Abschnitt

Im Folgenden finden Sie ein einfaches Beispiel für eine HTML-Vorlage für eine E-Mail, die einen Abschnitt enthält. Der Kopf enthält einfaches Inline-CSS für die Formatierung. Der Textkörper enthält einen `pre-header`, einen `headline` und `image`[ Platzhalter](#content-placeholders), der von GenStudio for Performance Marketing verwendet wird, um während des E-Mail-Generierungsprozesses Inhalte einzufügen.

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

Im Folgenden sehen Sie dieselbe HTML-Vorlage wie im obigen Beispiel, jedoch mit zwei weiteren Abschnitten. Die Kopfzeile enthält Inline-CSS für die Formatierung einer Gruppe. Der Textkörper verwendet zwei Gruppen mit [Inhalts-Platzhaltern](#content-placeholders) die ein Präfix verwenden.

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

Im Folgenden finden Sie ein einfaches Beispiel für eine Meta-Anzeigenvorlage. Der Kopf enthält Inline-CSS für die Formatierung. Der Textkörper verwendet [Inhalts-Platzhalter](#content-placeholders) mit einem Präfix.

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
