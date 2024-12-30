---
title: Vorbereiten einer E-Mail-Vorlage für Adobe GenStudio for Performance Marketing
description: Erfahren Sie, wie Sie eine benutzerdefinierte E-Mail-Vorlage für Adobe GenStudio for Performance Marketing erstellen.
level: Intermediate
feature: Templates, Content
exl-id: 8b1e8d32-5a23-45ce-a2d4-ae6de3698c45
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '459'
ht-degree: 0%

---

# E-Mail-Vorlage für Adobe GenStudio for Performance Marketing vorbereiten

In der Regel erstellt ein Designer das visuelle Design einer Vorlage in einem Designprogramm wie Adobe XD. Nachdem eine E-Mail-Vorlage entworfen, codiert und getestet wurde, können Sie sie für das Hochladen und die Verwendung in GenStudio for Performance Marketing vorbereiten.

Siehe [Vorlagenelemente](use-templates.md#template-elements).

## Richtlinien hinzufügen

Bevor Sie eine Meta-Anzeigenvorlage vorbereiten, stellen Sie sicher, dass Sie [Richtlinien](/help/user-guide/guidelines/overview.md) zu Ihrer GenStudio for Performance Marketing hinzugefügt und diese mit umfassenden Informationen zu den entsprechenden Marken ausgefüllt haben. Die [Markenrichtlinien](/help/user-guide/guidelines/brands.md) beeinflussen direkt generierte Inhalte.

**Beispiel**: Wenn der Textkörper einer E-Mail-Vorlage nicht größer als 500 Zeichen sein soll, fügen Sie diese Anforderung zu den [Kanal-Richtlinien](/help/user-guide/guidelines/brands.md#channel-guidelines) für das Feld „Textkörper“ hinzu.

Wenn GenStudio for Performance Marketing keine Richtlinien hinzugefügt werden, werden Standardwerte verwendet.

## Codieren einer E-Mail-Vorlage

Nachdem eine Vorlage entworfen wurde, wird sie mit HTML und Inline-CSS codiert. Der Code sollte für verschiedene Geräte sauber und responsiv sein.

Siehe [Beispielvorlagen](/help/user-guide/content/customize-template.md#template-examples).

### E-Mails mit mehreren Abschnitten

Sie können [strukturierte Eingabeaufforderungen](/help/user-guide/effective-prompts.md#structured-prompts) während der Inhaltserstellung verwenden, um GenStudio for Performance Marketing anzuweisen, unterschiedliche Inhalte pro Abschnitt einer E-Mail zu generieren.

Wenn beispielsweise die Abschnitte in Ihrer E-Mail-Vorlage mit dem Präfix `Pod` - `Pod1` und `Pod2` versehen sind, kann die strukturierte Aufforderung zur Inhaltserstellung spezifische Anweisungen für diese E-Mail-Abschnitte enthalten. GenStudio for Performance Marketing ordnet die abschnittsspezifische Anweisung in Ihrer Eingabeaufforderung dem entsprechenden E-Mail-Abschnitt zu und generiert Inhalte, die mit den Anweisungen übereinstimmen.

Siehe [Strukturierte Eingabeaufforderungen](/help/user-guide/effective-prompts.md#structured-prompts).

## Testen einer E-Mail-Vorlage

Verwenden Sie Ihre E-Mail-Versand- oder Proofing-Plattform, um Ihre E-Mail zu testen und sicherzustellen, dass sie auf verschiedenen E-Mail-Clients und Geräten ordnungsgemäß gerendert wird.

Testen Sie , um sicherzustellen, dass Ihre E-Mail-Vorlage Folgendes erfüllt:

* Layout passt sich mithilfe von CSS-Medienabfragen an verschiedene Bildschirmgrößen an
* Die Schaltflächen können angeklickt werden und zur gewünschten Stelle navigieren.
* E-Mail-Vorlage ist lesbar und kann auf Mobilgeräten verwendet werden

## Definieren der generierten Inhaltsbereiche

Definieren Sie die Bereiche in Ihrer E-Mail-Vorlage, die dynamisch mit Inhalten aus GenStudio for Performance Marketing gefüllt werden sollen.

So definieren Sie generierte Inhaltsbereiche:

* Identifizieren Sie die Textelemente in der Vorlage, die GenStudio for Performance Marketing automatisch generieren soll, z. B. die Überschrift oder CTA.
* Passen Sie Ihre HTML-Vorlage an, indem Sie Platzhalter mithilfe der Handlebars-Syntax darin einfügen.

Siehe [Inhalts-Platzhalter](/help/user-guide/content/customize-template.md#content-placeholders).

## Vorschau der Vorlage

Steuern der Sichtbarkeit bestimmter Inhaltsbereiche mit integrierten Helfern. Sie können beispielsweise Tracking-Parameter zu Links in eine exportierte Vorlage einbeziehen, während die Vorschau-Links sauber bleiben.

Siehe [Vorlagenansicht](/help/user-guide/content/customize-template.md#template-preview).

## Hochladen und Verwenden der Vorlage

Nachdem Ihre Vorlage entworfen, codiert, getestet und in der Vorschau angezeigt wurde, können Sie sie in GenStudio for Performance Marketing hochladen, um sie für die Erstellung brandneuer Marketing-Inhalte zu verwenden.

Siehe [Arbeiten mit Vorlagen](use-templates.md).
