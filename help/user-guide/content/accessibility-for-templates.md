---
title: Barrierefreie Vorlagen erstellen
description: Erstellen Sie Vorlagen, die alle Zielgruppen erreichen können, um sie in Adobe GenStudio für Performance Marketers zu verwenden.
feature: Templates, Content
source-git-commit: 26d1b9c7b392e93e87ffcd9444f391c2980d1c3c
workflow-type: tm+mt
source-wordcount: '257'
ht-degree: 0%

---


# Barrierefreie Vorlagen erstellen

Adobe setzt sich dafür ein, für alle Zielgruppen ein optimales Erlebnis zu bieten. Weitere Informationen finden Sie unter [Initiativen zur Barrierefreiheit unter Adobe](https://www.adobe.com/trust/accessibility/initiatives.html) .

In GenStudio für Performance Marketers können Sie Assets und Vorlagen hochladen, die die Inhaltserstellung für eine Vielzahl von Erlebnissen ermöglichen. Durch die Einhaltung von Barrierefreiheitsstandards können Sie Ihre Inhalte so weit wie möglich für Ihre Zielgruppe optimieren.

Verwenden Sie die folgenden Empfehlungen, um Ihre Vorlagen unter Verwendung optimaler Barrierefreiheitsstandards vorzubereiten.

## Alternativtext

Stellen Sie Textalternativen für nichttextuelle Inhalte bereit, z. B. Bilder.

```html
<img alt="Collage of ideas, books, man holding giant pencil, computer" src="card-create-assets.png">
```

![Collage von Ideen, Büchern, Mann mit einem riesigen Bleistift, Computer](../../assets/card-create-assets.png){width="400"}

## Link-Zweck (nur Link)

Erstellen Sie einen leeren Link-Text, der den Zweck und den Speicherort des Links beschreibt.

Die Verwendung von Link-Text wie &quot;Click here&quot;oder &quot;Read more&quot;beschreibt beispielsweise nicht eindeutig den Zweck des Links:

```html
<a href="product-site.html">Click here</a>
```

Als Best Practice sollten Sie Text verwenden, der deutlich beschreibt, wohin der Link führt. Ein besseres Beispiel könnte den Titel der Linkquelle und den Zweck verwenden:

```html
<a href="product-site.html">Explore Product Site</a>
```

## Sprache

Viele Produkte und Dienstleistungen verwenden Sprache kreativ oder einzigartig. Vermeiden Sie Jargon, lange Sätze und komplexe Ausdrücke. Verwenden Sie eine klare, knappe und leicht lesbare Sprache, die mit Ihrer Zielgruppe kompatibel ist.

- Verwenden Sie nach Möglichkeit klare Beschreibungen, Inline-Definitionen oder verknüpfungsfähige Beispiele. Es kann schwierig sein, eine einzigartige Tradition zu übersetzen.

- Definieren Sie eine Definition für die ersten Instanzen eines Akronyms oder einer Abkürzung oder verknüpfen Sie sie. Abkürzungen können schwer zu übersetzen sein.

- Verwenden Sie visuelle Elemente, um Text oder komplexe Ideen nach Möglichkeit zu ergänzen.
