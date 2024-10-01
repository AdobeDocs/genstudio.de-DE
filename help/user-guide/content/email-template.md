---
title: E-Mail-Vorlage für Adobe GenStudio for Performance Marketing vorbereiten
description: Erfahren Sie, wie Sie eine benutzerdefinierte E-Mail-Vorlage für Adobe GenStudio for Performance Marketing erstellen.
level: Intermediate
feature: Templates, Content
exl-id: 8b1e8d32-5a23-45ce-a2d4-ae6de3698c45
source-git-commit: 54fd20fec553b545b2f5d64cdf9327098b16580f
workflow-type: tm+mt
source-wordcount: '459'
ht-degree: 0%

---

# E-Mail-Vorlage für Adobe GenStudio for Performance Marketing vorbereiten

In der Regel erstellt ein Designer das visuelle Design einer Vorlage in einem Designprogramm wie Adobe XD. Nachdem eine E-Mail-Vorlage entworfen, codiert und getestet wurde, können Sie sie für den Upload und die Verwendung in GenStudio for Performance Marketing vorbereiten.

Siehe [Vorlagenelemente](use-templates.md#template-elements).

## Richtlinien hinzufügen

Bevor Sie eine Meta-Anzeigenvorlage vorbereiten, stellen Sie sicher, dass Sie Ihrer GenStudio for Performance Marketing [Führungslinien](/help/user-guide/guidelines/overview.md) hinzugefügt und umfassende Informationen für relevante Marken bereitgestellt haben. Die [Markenrichtlinien](/help/user-guide/guidelines/brands.md) beeinflussen den generierten Inhalt direkt.

**Beispiel**: Wenn der Hauptteil einer E-Mail-Vorlage 500 Zeichen nicht überschreiten soll, fügen Sie diese Anforderung den [Kanalrichtlinien](/help/user-guide/guidelines/brands.md#channel-guidelines) für das Feld &quot;Hauptteil&quot;hinzu.

Wenn GenStudio for Performance Marketing keine Richtlinien hinzugefügt werden, werden Standardwerte verwendet.

## E-Mail-Vorlage kodieren

Nachdem eine Vorlage entworfen wurde, wird sie mit HTML und Inline-CSS codiert. Der Code sollte für verschiedene Geräte sauber und responsiv sein.

Siehe [Vorlagenbeispiele](/help/user-guide/content/customize-template.md#template-examples).

### E-Mails mit mehreren Abschnitten

Sie können während der Inhaltserstellung [strukturierte Eingabeaufforderungen](/help/user-guide/effective-prompts.md#structured-prompts) verwenden, um GenStudio for Performance Marketing anzuweisen, variierende Inhalte pro Abschnitt einer E-Mail zu generieren.

Wenn den Abschnitten in Ihrer E-Mail-Vorlage beispielsweise das Präfix &quot;`Pod`—`Pod1`&quot;und &quot;`Pod2`&quot;vorangestellt ist, kann die strukturierte Eingabeaufforderung für die Inhaltserstellung spezifische Anweisungen für diese E-Mail-Abschnitte enthalten. GenStudio for Performance Marketing stimmt die bereichsspezifische Anweisung in Ihrer Eingabeaufforderung mit dem entsprechenden E-Mail-Abschnitt überein und generiert Inhalte, die mit den Anweisungen übereinstimmen.

Siehe [Strukturierte Eingabeaufforderungen](/help/user-guide/effective-prompts.md#structured-prompts).

## Testen einer E-Mail-Vorlage

Verwenden Sie Ihre E-Mail-Versand- oder Testplattform, um Ihre E-Mail zu testen und sicherzustellen, dass sie über verschiedene E-Mail-Clients und -Geräte hinweg ordnungsgemäß dargestellt wird.

Testen Sie, ob Ihre E-Mail-Vorlage Folgendes erfüllt:

* Layoutanpassungen für verschiedene Bildschirmgrößen mithilfe von CSS-Medienabfragen
* Die Schaltflächen können angeklickt werden und navigieren zur vorgesehenen Stelle
* E-Mail-Vorlage ist lesbar und auf Mobilgeräten nutzbar

## Definieren generierter Inhaltsbereiche

Definieren Sie die Bereiche in Ihrer E-Mail-Vorlage, die dynamisch mit Inhalten aus GenStudio for Performance Marketing gefüllt werden sollen.

So definieren Sie generierte Inhaltsbereiche:

* Identifizieren Sie die Textelemente in der Vorlage, die von GenStudio for Performance Marketing automatisch generiert werden sollen, z. B. die Überschrift oder CTA.
* Passen Sie Ihre HTML-Vorlage an, indem Sie mithilfe der Handlebars-Syntax Platzhalter darin einfügen.

Siehe [Platzhalter für Inhalte](/help/user-guide/content/customize-template.md#content-placeholders).

## Vorschau der Vorlage

Mit integrierten Helfern können Sie die Sichtbarkeit bestimmter Inhaltsbereiche steuern. Sie können beispielsweise Tracking-Parameter zu Links in eine exportierte Vorlage einfügen und dabei saubere Vorschaulinks beibehalten.

Siehe [Vorlagenvorschau](/help/user-guide/content/customize-template.md#template-preview).

## Hochladen und Verwenden von Vorlagen

Nachdem Ihre Vorlage entworfen, codiert, getestet und in der Vorschau angezeigt wurde, können Sie sie zur Verwendung beim Generieren von brandneuen Marketinginhalten in GenStudio for Performance Marketing hochladen.

Siehe [Arbeiten mit Vorlagen](use-templates.md).
