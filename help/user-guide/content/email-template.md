---
title: E-Mail-Vorlage für Adobe GenStudio für Performance Marketers vorbereiten
description: Erfahren Sie, wie Sie eine benutzerdefinierte E-Mail-Vorlage für Adobe GenStudio für Performance Marketingexperten erstellen.
level: Intermediate
feature: Templates, Content
source-git-commit: c9d09801f0bd3732611b01d4a98cc7ebf38884d7
workflow-type: tm+mt
source-wordcount: '383'
ht-degree: 0%

---


# E-Mail-Vorlage für Adobe GenStudio für Performance Marketingexperten vorbereiten

In der Regel erstellt ein Designer das visuelle Design einer Vorlage in einem Designprogramm wie Adobe XD. Nachdem eine E-Mail-Vorlage entworfen, codiert und getestet wurde, können Sie sie für den Upload und die Verwendung in GenStudio für Performance Marketers vorbereiten.

Siehe [Anatomie einer Vorlage](/help/user-guide/content/use-templates.md#anatomy-of-a-template).

## Richtlinien hinzufügen

Bevor Sie eine Meta-Anzeigenvorlage vorbereiten, stellen Sie sicher, dass Sie Ihren GenStudio for Performance Marketers [guidelines](/help/user-guide/guidelines/overview.md) hinzugefügt und diese mit umfassenden Informationen für relevante Marken ausgefüllt haben. Die [Markenrichtlinien](/help/user-guide/guidelines/brands.md) beeinflussen den generierten Inhalt direkt.

**Beispiel**: Wenn der Hauptteil einer E-Mail-Vorlage 500 Zeichen nicht überschreiten soll, fügen Sie diese Anforderung den [Kanalrichtlinien](/help/user-guide/guidelines/brands.md#channel-guidelines) für das Feld &quot;Hauptteil&quot;hinzu.

Wenn GenStudio für Performance Marketers keine Richtlinien hinzugefügt werden, werden Standardwerte verwendet.

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

Definieren Sie die Bereiche in Ihrer E-Mail-Vorlage, die dynamisch mit Inhalten aus GenStudio für Performance Marketers gefüllt werden sollen.

So definieren Sie generierte Inhaltsbereiche:

* Identifizieren Sie die Textelemente in der Vorlage, die von GenStudio für Performance Marketers automatisch generiert werden sollen, z. B. die Überschrift oder CTA.
* Passen Sie Ihre HTML-Vorlage an, indem Sie mithilfe der Handblebars-Syntax Platzhalter darin einfügen.

Siehe [Platzhalter für Inhalte](/help/user-guide/content/customize-template.md#content-placeholders).

## Vorschau der Vorlage

Steuern Sie die Sichtbarkeit bestimmter Inhaltsbereiche mithilfe von integrierten Helfern. Sie können beispielsweise Tracking-Parameter zu Links in eine exportierte Vorlage einfügen und dabei saubere Vorschaulinks beibehalten.

Siehe [Vorlagenvorschau](/help/user-guide/content/customize-template.md#template-preview).

## Hochladen und Verwenden von Vorlagen

Nachdem Ihre Vorlage entworfen, codiert, getestet und in der Vorschau angezeigt wurde, können Sie sie für Performance Marketingexperten in GenStudio hochladen, um neue Marketinginhalte zu generieren.

Siehe [Arbeiten mit Vorlagen](use-templates.md).
