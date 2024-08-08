---
title: E-Mail-Vorlage für GenStudio vorbereiten
description: Erfahren Sie, wie Sie eine benutzerdefinierte E-Mail-Vorlage für GenStudio erstellen.
level: Intermediate
feature: Templates, Content
source-git-commit: 31f02218e02b1400ca9f32472acdecae03dbd304
workflow-type: tm+mt
source-wordcount: '353'
ht-degree: 0%

---


# E-Mail-Vorlage für GenStudio vorbereiten

In der Regel erstellt ein Designer das visuelle Design einer Vorlage in einem Designprogramm wie Adobe XD. Nachdem eine E-Mail-Vorlage entworfen, codiert und getestet wurde, können Sie sie für den Upload und die Verwendung in GenStudio vorbereiten.

Siehe [Anatomie einer Vorlage](/help/user-guide/content/use-templates.md#anatomy-of-a-template).

## Richtlinien hinzufügen

Bevor Sie eine Meta-Anzeigenvorlage vorbereiten, stellen Sie sicher, dass Sie Ihrer GenStudio [Führungslinien](/help/user-guide/guidelines/overview.md) hinzugefügt und umfassende Informationen für relevante Marken bereitgestellt haben. Die [Markenrichtlinien](/help/user-guide/guidelines/brands.md) beeinflussen den generierten Inhalt direkt.

**Beispiel**: Wenn der Hauptteil einer E-Mail-Vorlage 500 Zeichen nicht überschreiten soll, fügen Sie diese Anforderung den [Kanalrichtlinien](/help/user-guide/guidelines/brands.md#channel-guidelines) für das Feld &quot;Hauptteil&quot;hinzu.

Wenn GenStudio keine Richtlinien hinzugefügt werden, werden Standardwerte verwendet.

## E-Mail-Vorlage kodieren

Nachdem eine Vorlage entworfen wurde, wird sie mit HTML und Inline-CSS codiert. Der Code sollte für verschiedene Geräte sauber und responsiv sein.

Siehe [Vorlagenbeispiele](/help/user-guide/content/customize-template.md#template-examples).

## Testen einer E-Mail-Vorlage

Verwenden Sie Ihre E-Mail-Versand- oder Testplattform, um Ihre E-Mail zu testen und sicherzustellen, dass sie über verschiedene E-Mail-Clients und -Geräte hinweg ordnungsgemäß dargestellt wird.

Prüfen Sie, ob Ihre E-Mail-Vorlage Folgendes erfüllt:

* Layoutanpassungen für verschiedene Bildschirmgrößen mithilfe von CSS-Medienabfragen
* Die Schaltflächen können angeklickt werden und navigieren zur vorgesehenen Stelle
* E-Mail-Vorlage ist lesbar und auf Mobilgeräten nutzbar

## Definieren generierter Inhaltsbereiche

Definieren Sie die Bereiche in Ihrer E-Mail-Vorlage, die dynamisch mit Inhalten aus GenStudio gefüllt werden sollen.

So definieren Sie generierte Inhaltsbereiche:

* Identifizieren Sie die Textelemente in der Vorlage, die von GenStudio automatisch generiert werden sollen, z. B. die Überschrift oder CTA.
* Passen Sie Ihre HTML-Vorlage an, indem Sie mithilfe der Handblebars-Syntax Platzhalter darin einfügen.

Siehe [Platzhalter für Inhalte](/help/user-guide/content/customize-template.md#content-placeholders).

## Vorschau der Vorlage

Steuern Sie die Sichtbarkeit bestimmter Inhaltsbereiche mithilfe von integrierten Helfern. Sie können beispielsweise Tracking-Parameter zu Links in eine exportierte Vorlage einfügen und dabei saubere Vorschaulinks beibehalten.

Siehe [Vorlagenvorschau](/help/user-guide/content/customize-template.md#template-preview).

## Hochladen und Verwenden von Vorlagen

Nachdem Ihre Vorlage entworfen, codiert, getestet und in der Vorschau angezeigt wurde, können Sie sie zur Verwendung beim Generieren von brandneuen Marketinginhalten in GenStudio hochladen.

Siehe [Arbeiten mit Vorlagen](use-templates.md).
