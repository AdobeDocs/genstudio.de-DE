---
title: Erstellen barrierefreier Vorlagen
description: Erstellen Sie Vorlagen in Adobe GenStudio for Performance Marketing, die mehr Zielgruppen erreichen und ein optimales Erlebnis bieten.
feature: Templates, Content
exl-id: eaaa5d9f-ad45-4fd0-826d-c250deb6d238
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '304'
ht-degree: 0%

---

# Erstellen barrierefreier Vorlagen

Adobe ist bestrebt, allen Zielgruppen ein optimales Erlebnis zu bieten. Siehe [Initiativen zur Barrierefreiheit auf Adobe](https://www.adobe.com/trust/accessibility/initiatives.html) für weitere Informationen.

In GenStudio for Performance Marketing können Sie Assets und Vorlagen hochladen, die die Inhaltserstellung für eine Vielzahl von Erlebnissen ermöglichen. Die Einhaltung von Barrierefreiheitsstandards hilft Ihnen, Ihre Inhalte an die gewünschte Zielgruppe anzupassen.

Bereiten Sie Ihre Vorlagen unter Verwendung optimaler Barrierefreiheitsstandards anhand der folgenden Empfehlungen vor.

## Alternativtext

Bieten Sie Textalternativen für nicht-textliche Inhalte wie Bilder.

```html
<img alt="Collage of ideas, books, man holding giant pencil, computer" src="card-create-assets.png">
```

![Collage von Ideen, Bücher, Mann mit Riesenstift, Computer](../../assets/card-create-assets.png){width="400"}

## Kontrastverhältnisse

Stellen Sie einen angemessenen Kontrast zwischen Text und Hintergrund bereit. Verwenden Sie die folgenden Mindestkontrastverhältnisse:

- Text und Bilder von Text: Kontrastverhältnis von mindestens 4,5:1
- Großer Text und Bilder von großformatigem Text: Kontrastverhältnis von mindestens 3:1

## Link-Zweck (nur Link)

Erstellen Sie einen klaren Link-Text, der den Zweck und die Position des Links beschreibt.

Beispielsweise beschreibt die Verwendung von Link-Text wie „Hier klicken“ oder „Mehr lesen“ nicht klar den Zweck des Links:

```html
<a href="product-site.html">Click here</a>
```

Als Best Practice sollten Sie Text verwenden, der klar beschreibt, wohin der Link führt. Ein besseres Beispiel könnte den Titel der Link-Quelle und den Zweck verwenden:

```html
<a href="product-site.html">Explore Product Site</a>
```

## Sprache

Viele Produkte und Dienstleistungen verwenden Sprache auf kreative oder einzigartige Weise. Vermeiden Sie Jargon, lange Sätze und komplexe Phrasen. Verwenden Sie eine klare, knappe, leicht verständliche Sprache, die mit Ihrer Zielgruppe kompatibel ist.

- Verwenden Sie nach Möglichkeit klare Beschreibungen, Inline-Definitionen oder verknüpfbare Beispiele. Es kann schwierig sein, eine einzigartige Fachsprache zu übersetzen.

- Schreiben Sie die ersten Instanzen eines Akronyms oder einer Abkürzung aus oder verknüpfen Sie sie mit einer Definition. Es kann schwierig sein, Abkürzungen zu übersetzen.

- Verwenden Sie visuelle Elemente, um Text oder komplexe Ideen nach Möglichkeit zu ergänzen.
