---
title: Vorlagen anpassen
description: Erfahren Sie, wie Sie eine benutzerdefinierte Vorlage für Adobe GenStudio für Performance Marketingexperten erstellen.
level: Intermediate
feature: Templates, Content
source-git-commit: 44390d551e638fcff47cff5844fcfda4ed9f98f3
workflow-type: tm+mt
source-wordcount: '0'
ht-degree: 0%

---


# Vorlagen anpassen

Passen Sie Ihre HTML-Vorlagen für Adobe GenStudio für Performance Marketingexperten mithilfe der Vorlagensprache _Handlebars_ an. Die Handlebars-Syntax verwendet regulären Text mit doppelten Klammern als Inhaltsplatzhalter. Informationen zur Vorbereitung Ihrer Vorlage finden Sie unter [`What is Handlebars?`](https://handlebarsjs.com/guide/#what-is-handlebars) im _Handlebars-Sprachleitfaden_ .

Wenn Sie keine HTML-Vorlage haben, die in GenStudio für Performance Marketers verwendet werden kann, können Sie mit der Definition der Vorlagenstruktur mit den HTML-Tags `DOCTYPE`, `html`, `head` und `body` beginnen. Im Folgenden finden Sie eine einfache E-Mail-Vorlage mit CSS-Stilen zum Anpassen des Erscheinungsbilds:

```html
<!DOCTYPE html>
<html>
<head>
    <title>Title</title>
    <style>
    </style>
</head>
<body>
</body>
</html>
```

>[!TIP]
>
>Fügen Sie in den nächsten Abschnitten Platzhalter für E-Mail-Felder hinzu, sehen Sie Beispielvorlagen, blenden Sie unnötige Elemente aus der Vorschau aus und verwalten Sie Links zu statischen Inhalten. Sobald Ihre Vorlage fertig ist, können Sie sie [für Performance Marketers in GenStudio hochladen](use-templates.md#upload-a-template) und mit der Generierung personalisierter E-Mails auf der Grundlage Ihrer benutzerdefinierten Vorlage beginnen.

## Inhalts-Platzhalter

Im Kopf- oder Textkörper einer Vorlage können Sie die Handlebars-Syntax verwenden, um Platzhalter für Inhalte einzufügen, für die Sie von GenStudio verlangen, dass Leistungs-Marketingexperten die Vorlage mit dem tatsächlichen Inhalt füllen. GenStudio für Performance Marketingexperten erkennt und interpretiert die Inhalts-Platzhalter automatisch auf Grundlage des Feldnamens.

Beispielsweise können Sie mit `{{ headline }}` angeben, wo die Überschrift der E-Mail platziert werden soll:

```handlebars
<div>{{ headline }}</div>
```

### Erkannte Feldnamen

Die maximal zulässige Anzahl von Feldern in einer benutzerdefinierten Vorlage beträgt zwanzig.

In der folgenden Tabelle sind die von GenStudio für Performance Marketers für die Population erkannten Feldnamen in Vorlagen aufgeführt.

| Feld | Rolle | Kanalvorlage |
| -------------- | ---------------------- | -------------------- |
| `pre_header` | Pre-Header | email (empfohlen) |
| `headline` | Überschrift | email (empfohlen)<br>Meta-Anzeige |
| `body` | Textkopie | email (empfohlen)<br>Meta-Anzeige |
| `cta` | Aktionsaufruf | email (empfohlen)<br>Meta-Anzeige |
| `on_image_text` | Im Bildtext | Metaanzeige (empfohlen) |
| `image` | Bild | email (empfohlen)<br>Meta-Anzeige (empfohlen) |
| `brand_logo` | Logo der ausgewählten Marke<br>Siehe [Feldname](#brand-logo-field-name) für die empfohlene Verwendung. | email<br>Meta-Anzeige |

GenStudio for Performance Marketers füllt bestimmte Felder automatisch in Vorlagen, sodass es nicht erforderlich ist, sie in Ihre Vorlagenentwürfe aufzunehmen:

- Feld `subject` (E-Mail-Vorlage)
- Felder `headline`, `body` und `CTA` (Meta-Anzeigenvorlage)

>[!WARNING]
>
>Bei Instagram-Anzeigen erscheint die generierte Überschrift nicht im endgültigen Erlebnis.

#### Feldname für Markenlogo

Die folgenden Beispiele zeigen zwei Methoden, mit denen das Markenlogo bedingt gerendert, die Quelle überprüft, ein standardmäßiges oder alternatives Logo bereitgestellt wird, falls das Markenlogo nicht verfügbar ist, und einen Stil anwenden:

_Beispiel_: in der Definition HTML `img src`

```html
<img src="{{#if brand_logo}}{{brand_logo}}{{else}}<default-image>{{/if}}" alt="img alt text" style="max-width: 88px; margin: 10px auto; display: block;"> 
```

_Beispiel_: in einer Handlebars-Bedingung

```handlebars
{{#if brand_logo}}
    <img src="{{brand_logo}}" alt="img alt text" style="width: 120px; height: 45px; margin: 10px auto; display: block;">
    {{else}}
    <img src="data:image/png;base64,iVBORw0KGgo..." alt="img alt text" style="width: 120px; height: 45px; margin: 10px auto; display: block;">
{{/if}}
```

#### Manuelle Feldnamen

Alle anderen Feldnamen werden als manuell ausgefüllte Felder behandelt. Um einen bearbeitbaren Abschnitt zu erstellen, fügen Sie um den Abschnittsnamen doppelte Klammern hinzu:

```handlebars
{{customVariable}}
```

## Abschnitte oder Gruppen

_Abschnitte_ informieren GenStudio für Leistungs-Marketingexperten darüber, dass die Felder in diesem Abschnitt einen hohen Grad an Kohärenz erfordern. Durch diese Beziehung kann die KI Inhalte generieren, die mit den kreativen Elementen im Abschnitt übereinstimmen.

Verwenden Sie ein Präfix Ihrer Wahl im Feldnamen, um anzugeben, dass ein Feld Teil eines Abschnitts oder einer Gruppe ist.

Sie können beispielsweise Inhalte in einem hervorgehobenen Bereich markieren:

- `spotlight_headline`
- `spotlight_body`

Jeder Abschnitt kann nur einen Feldtyp aufweisen. Im obigen Beispiel darf das Präfix `spotlight` nur ein `spotlight_headline` -Feld enthalten.

Eine Vorlage kann aus bis zu drei Bereichen bestehen:

- `headline`
- `body`
- `spotlight_headline`
- `spotlight_body`
- `news_headline`
- `news_body`

GenStudio for Performance Marketers erkennt, dass `spotlight_headline` enger mit `spotlight_body` als mit `news_body` verbunden ist.

## Vorlagenbeispiele

+++Beispiel: E-Mail-Vorlage mit einem Abschnitt

Im Folgenden finden Sie ein Beispiel für eine HTML-Vorlage für eine E-Mail, die nur einen Bereich enthält. Der Kopf enthält einfache Inline-CSS für die Formatierung. Der Hauptteil enthält einen `pre-header`-, `headline`- und `image` [Platzhalter](#content-placeholders) für GenStudio, damit Performance Marketers Inhalte während des E-Mail-Generierungsprozesses einfügen können.

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
        <div class="pod">
            <h2>{{ pod1_headline }}</h2>
            <p>This is Pod 1 content.</p>
        </div>
        <div class="pod">
            <h2>{{ pod2_headline }}</h2>
            <p>This is Pod 2 content.</p>
        </div>
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

## Vorschau der Vorlage

Mit integrierten Helfern (speziellen Ausdrücken in der Vorlagensprache Handlebars, die bestimmte Aktionen durchführen) können Sie die Sichtbarkeit von speziellen Inhalten steuern. Sie können beispielsweise Tracking-Parameter zu Links in der exportierten Vorlage hinzufügen, während Sie die Vorschau-Links sauber halten.

Der `_genStudio.browser` -Wert wird beim Rendern einer Vorlage festgelegt und der `genStudio.export` -Wert wird beim Exportieren einer Vorlage festgelegt. Sie können bestimmte Inhalte über einen bedingten Wrapper oben in einer E-Mail einfügen, z. B. wenn die Vorlage für den Export verwendet wird:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Ein weiteres Beispiel könnte sein, die Verwendung von Trackingcodes bei der Vorschau einer Vorlage in GenStudio zu verhindern. In diesem Beispiel wird gezeigt, wie Tracking-Parameter zu Links in der exportierten Vorlage hinzugefügt werden, während die Vorschau-Links sauber gehalten werden:

```handlebars
<a class="button" {{#if _genStudio.browser }}
   href="{{ link }}"{{/if}}{{#if _genStudio.export }}
   href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}}
   target="_blank">{{ cta }}</a>
```

## Statischer Inhalt

E-Mail- und Meta-Vorlagen verlinken häufig zu Bildern und CSS-Dateien, die außerhalb von GenStudio für Performance Marketers gehostet werden. Wenn GenStudio for Performance Marketers Miniaturansichten für diese Vorlagen oder die daraus abgeleiteten Erlebnisse generiert, können diese externen Ressourcen ignoriert werden, wenn sie nicht über die richtigen CORS-Header (Cross Origin Resource Sharing) verfügen.

Beachten Sie zwei Optionen, um sicherzustellen, dass diese Ressourcen während des Generierungsprozesses von Miniaturansichten verfügbar sind:

1. **CORS-Header verwenden**: Der Host-Server muss Antworten senden, deren `Access-Control-Allow-Origin`-Header für Produktionsumgebungen auf den Wert `https://experience.adobe.com` eingestellt ist. Diese Methode ermöglicht es GenStudio für Performance Marketingexperten, auf die Ressourcen zuzugreifen und sie einzuschließen.
1. **Daten-URLs verwenden**: Betten Sie die externen Ressourcen mithilfe von Daten-URLs direkt in die Vorlage ein. Diese Methode umgeht CORS-Einschränkungen und stellt sicher, dass die Ressourcen während der Erstellung von Miniaturansichten verfügbar sind.
