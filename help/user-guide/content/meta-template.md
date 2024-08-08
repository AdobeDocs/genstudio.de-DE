---
title: Vorbereiten einer Meta-Anzeigenvorlage für GenStudio
description: Erfahren Sie, wie Sie eine benutzerdefinierte Meta-Anzeigenvorlage für GenStudio erstellen.
level: Intermediate
feature: Templates, Content
source-git-commit: 31f02218e02b1400ca9f32472acdecae03dbd304
workflow-type: tm+mt
source-wordcount: '387'
ht-degree: 0%

---


# Vorbereiten der Meta-Anzeigenvorlage für GenStudio

Das Erstellen einer Meta-Anzeigenvorlage umfasst einen strukturierten Ansatz, der auf Social Media zugeschnitten ist. Nachdem eine Meta-Anzeigenvorlage entworfen und getestet wurde, können Sie sie für den Upload und die Verwendung in GenStudio vorbereiten.

## Richtlinien hinzufügen

Bevor Sie eine Meta-Anzeigenvorlage vorbereiten, stellen Sie sicher, dass Sie Ihrer GenStudio [Führungslinien](/help/user-guide/guidelines/overview.md) hinzugefügt und umfassende Informationen für relevante Marken bereitgestellt haben. Die [Markenrichtlinien](/help/user-guide/guidelines/brands.md) beeinflussen den generierten Inhalt direkt.

**Beispiel**: Wenn der Hauptteil einer Meta-Anzeigenvorlage nicht größer als 500 Zeichen sein soll, fügen Sie diese Anforderung den [Kanalrichtlinien](/help/user-guide/guidelines/brands.md#channel-guidelines) für das Feld &quot;Hauptteil&quot;hinzu.

Wenn GenStudio keine Richtlinien hinzugefügt werden, werden Standardwerte verwendet.

## Erstellen einer Vorlage

In der Regel erstellt ein Designer das visuelle Design einer Vorlage in einem Designprogramm wie Adobe XD.

Siehe [Anatomie einer Vorlage](/help/user-guide/content/use-templates.md#anatomy-of-a-template) und [Vorlagenbeispiele](/help/user-guide/content/customize-template.md#template-examples).

### Anzeigenspezifikationen

GenStudio unterstützt diese Seitenverhältnisse für Meta-Anzeigen:

* Quadrat (1:1): 1080 x 1080 Pixel
* Vertikal (4:5): 1080 x 1350 Pixel
* Story (9:16): 1080 x 1920 Pixel

Wenn die Anzeige nicht in einem dieser Seitenverhältnisse erstellt wurde, schneidet GenStudio das Bild automatisch in die entsprechende Größe ab.

## Testen einer Meta-Anzeigenvorlage

Testen Sie Ihre Vorlage mit dem Creative Hub von Meta, um zu sehen, wie die Anzeige an verschiedenen Positionen aussieht, z. B. in einem Feed oder als Geschichte.

Verwenden Sie Ihre E-Mail-Versand- oder Testplattform, um Ihre E-Mail zu testen und sicherzustellen, dass sie über verschiedene E-Mail-Clients und -Geräte hinweg ordnungsgemäß dargestellt wird.

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
