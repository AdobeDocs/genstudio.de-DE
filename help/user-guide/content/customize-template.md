---
title: Vorlagen anpassen
description: Erfahren Sie, wie Sie eine benutzerdefinierte Vorlage für GenStudio erstellen.
level: Intermediate
feature: Templates, Content
source-git-commit: 423956d6fdbf5b31041d44eb434f90d55a87d7c0
workflow-type: tm+mt
source-wordcount: '784'
ht-degree: 0%

---


# Vorlagen anpassen

Sie können Ihre HTML-Vorlagen für GenStudio mithilfe der Vorlagensprache _Handlebars_ anpassen. Die Handlebars-Syntax verwendet regulären Text mit doppelten Klammern als Inhaltsplatzhalter. Informationen zur Vorbereitung Ihrer Vorlage finden Sie unter [`What is Handlebars?`](https://handlebarsjs.com/guide/#what-is-handlebars) im _Handlebars-Sprachleitfaden_ .

## Vorlagenstruktur

<!-- This is for email. In the future, maybe use tabs to provide guidance for other template types.
-->

Wenn Sie noch keine HTML-Vorlage für GenStudio haben, können Sie die Struktur Ihrer E-Mail mit den HTML-Tags `DOCTYPE`, `html`, `head` und `body` definieren. Sie können CSS-Stile einbeziehen, um das Erscheinungsbild Ihrer E-Mail anzupassen.

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
>Fügen Sie in den nächsten Abschnitten Platzhalter für E-Mail-Felder hinzu, blenden Sie unnötige Elemente aus der Vorschau aus und verwalten Sie Links zu statischen Inhalten. Sobald Ihre Vorlage fertig ist, können Sie sie [in GenStudio](use-templates.md#upload-a-template) hochladen und mit der Generierung personalisierter E-Mails auf der Basis Ihrer benutzerdefinierten Vorlage beginnen.

## Inhalts-Platzhalter

Im Kopf- oder Textkörper der Vorlage können Sie die Handlebars-Syntax verwenden, um Platzhalter für Inhalte einzufügen, für die GenStudio die E-Mail mit dem tatsächlichen Inhalt füllen muss. GenStudio erkennt und interpretiert die Inhaltsplatzhalter automatisch basierend auf dem Feldnamen.

Beispielsweise können Sie mit `{{ headline }}` angeben, wo die Überschrift der E-Mail platziert werden soll:

```handlebars
<div>{{ headline }}</div>
```

Die maximal zulässige Anzahl von Feldern in einer benutzerdefinierten Vorlage beträgt zwanzig.

**Erkannte Feldnamen**:

| Feld | Rolle | Kanalvorlage |
| -------------- | ---------------------- | -------------------- |
| `pre_header` | Pre-Header | email |
| `headline` | Überschrift | email<br>Social-Anzeige |
| `body` | Textkopie | email<br>Social-Anzeige |
| `cta` | Aktionsaufruf | email<br>Social-Anzeige |
| `on_image_text` | Im Bildtext | Social Advertising |
| `image` | Bild | email<br>Social-Anzeige |
| `brand_logo` | Logo der ausgewählten Marke | Social Advertising |

>[!IMPORTANT]
>
>GenStudio stellt die E-Mail-Vorlage während des [!DNL Create]-Prozesses automatisch mit dem Feld &quot;`subject`&quot;bereit. Daher ist es nicht erforderlich, das Betrefffeld in Ihre E-Mail-Vorlage aufzunehmen.

+++Beispiel: Grundlegende Vorlage

Im Folgenden finden Sie ein Beispiel für eine HTML-Vorlage für E-Mails. Der Kopf enthält einfache Inline-CSS für die Formatierung. Der Hauptteil enthält einen Platzhalter `pre-header`, `headline` und `image`, der von GenStudio zum Einfügen von Inhalten während des E-Mail-Generierungsprozesses verwendet wird.

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

### Hintergrundbild

Beim Entwerfen einer Anzeige für Meta ist es wichtig, ein Hintergrundbild zu verwenden, das durch Text und eine Markenlogo-Überlagerung ergänzt wird. Um eine korrekte Skalierung des Bildes zu gewährleisten, müssen für Meta-Anzeigenvorlagen `aspect ratio` angegeben werden. In diesem Kontext können Sie nur ein Bildfeld angeben.

## Abschnitte oder Gruppen

_Abschnitte_ bieten eine Möglichkeit, GenStudio darüber zu informieren, dass Felder, die zu einem Abschnitt gehören, einen hohen Grad an Kohärenz erfordern. Durch diese Beziehung kann die KI Inhalte generieren, die mit den kreativen Elementen im Abschnitt übereinstimmen. Eine Vorlage kann bis zu drei Abschnitte enthalten.

Verwenden Sie ein Präfix Ihrer Wahl im Feldnamen, um anzugeben, dass dieses Feld Teil eines Abschnitts oder einer Gruppe ist. Sie können beispielsweise Inhalte in einem hervorgehobenen Bereich markieren. Sie können den Inhalt für diesen Bereich mit einem gemeinsamen Präfix identifizieren:

- `spotlight_headline`
- `spotlight_body`

Jeder Abschnitt kann nur einen Feldtyp aufweisen. Beispielsweise kann die obige Beispielgruppe mit dem Präfix `spotlight` nur ein Feld `spotlight_headline` aufweisen.

Wenn Sie mehrere Abschnitte haben (maximal drei):

- `headline`
- `body`
- `spotlight_headline`
- `spotlight_body`
- `news_headline`
- `news_body`

GenStudio versteht, dass `spotlight_headline` enger mit `spotlight_body` als mit `news_body` verwandt ist.

+++Beispiel: Vorlage mit mehreren Abschnitten

Im Beispiel oben ist dieselbe HTML-Vorlage zu sehen, jedoch mit zwei weiteren Abschnitten. Der Kopf enthält Inline-CSS zum Formatieren eines Pods. Der Text verwendet zwei Pods mit Inhalts-Platzhaltern, die ein Präfix verwenden.

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

## Vorschau der Vorlage

E-Mail-Vorlagen enthalten manchmal spezielle Inhalte, die für die Vorschau in GenStudio nicht erforderlich sind. Sie können die Sichtbarkeit dieses Inhalts mithilfe von integrierten Helfern steuern, bei denen es sich um spezielle Ausdrücke in der Vorlagensprache Handlebars handelt, mit denen bestimmte Aktionen durchgeführt werden können.

Der `_genStudio.browser` -Wert wird beim Rendern einer Vorlage festgelegt und der `genStudio.export` -Wert wird beim Exportieren einer Vorlage festgelegt. Sie können festlegen, dass bestimmte Inhalte oben in den E-Mails mit einem bedingten Wrapper eingefügt werden, z. B. wenn die Vorlage für den Export verwendet wird:

```handlebars
{{#if _genStudio.export}}
<%@ include view='emailParent' %>
{{/if}}
```

Ein weiteres Beispiel könnte sein, die Verwendung von Trackingcodes bei der Vorschau einer E-Mail-Vorlage in GenStudio zu verhindern. In diesem Beispiel wird gezeigt, wie Tracking-Parameter zu Links in der exportierten Vorlage hinzugefügt werden, während die Vorschau-Links sauber gehalten werden:

```handlebars
<a class="button" {{#if _genStudio.browser }}
   href="{{ link }}"{{/if}}{{#if _genStudio.export }}
   href="{{ link }}?trackingid=<%=getTrackingId()%>&mv=email"{{/if}}
   target="_blank">{{ cta }}</a>
```

## Statischer Inhalt

E-Mail- und Meta-Vorlagen verknüpfen häufig mit Bildern und CSS-Dateien, die außerhalb von GenStudio gehostet werden. Wenn GenStudio Miniaturansichten für diese Vorlagen oder daraus abgeleitete Erlebnisse generiert, können diese externen Ressourcen ignoriert werden, wenn sie nicht über die richtigen CORS-Kopfzeilen (Cross Origin Resource Sharing) verfügen.

Beachten Sie zwei Optionen, um sicherzustellen, dass diese Ressourcen während des Generierungsprozesses von Miniaturansichten verfügbar sind:

1. **CORS-Header verwenden**: Der Host-Server muss Antworten senden, deren `Access-Control-Allow-Origin`-Header für Produktionsumgebungen auf den Wert `https://experience.adobe.com` eingestellt ist. Auf diese Weise kann GenStudio auf die Ressourcen zugreifen und diese einschließen.
1. **Daten-URLs verwenden**: Betten Sie die externen Ressourcen mithilfe von Daten-URLs direkt in die Vorlage ein. Diese Methode umgeht CORS-Einschränkungen und stellt sicher, dass die Ressourcen während der Erstellung von Miniaturansichten verfügbar sind.
