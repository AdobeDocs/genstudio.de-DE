---
title: Arbeiten mit Vorlagen
description: Erfahren Sie, wie Sie Vorlagen effektiv verwenden können, um Ihren Kreativprozess in Adobe GenStudio for Performance Marketing zu optimieren.
feature: Templates, Content
exl-id: 7705bb79-19ca-4c16-8f8b-95bf8687e96d
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '682'
ht-degree: 1%

---

# Arbeiten mit Vorlagen

GenStudio for Performance Marketing ermöglicht es Inhaltserstellern, konsistente markeninterne Marketing-Inhalte schnell mithilfe von _Vorlagen_ zu erstellen. Eine Vorlage reduziert den Zeit- und Arbeitsaufwand für die Erstellung neuer Inhalte erheblich, indem sie einen Ausgangspunkt bereitstellt, der vorkonfigurierte Layouts und Design-Elemente umfasst.

## Vorlagenelemente

Eine Vorlage ist ein Satz von Anweisungen, die mit HTML und Inline-CSS definiert werden und zur Erstellung von E-Mail- oder Meta-Werbeanzeigen verwendet werden können.

Im Folgenden finden Sie eine Liste der Elemente, die in Vorlagen verwendet werden, sowie einige Details zu ihren Eigenschaften.

- **Preheader**

   - Dient als sekundäre Betreffzeile in einer E-Mail und erweitert die Hauptbetreffzeile
   - Zwischen 40 und 50 Zeichen
   - Im Posteingang neben dem Betreff sichtbar, bevor die E-Mail geöffnet wird
   - Wird in E-Mail-Vorlagen verwendet

- **Kopfzeile**

   - Oberer Abschnitt der E-Mail, den der Empfänger beim Öffnen der E-Mail sieht
   - Legt den Ton fest und liefert Kontext für den enthaltenen Inhalt
   - Wird in E-Mail-Vorlagen verwendet

- **Überschrift**

   - Erster Inhalt, den der Empfänger sieht
   - Sollte fesselnd sein, Interesse zu wecken
   - Wird in Meta-Anzeigenvorlagen verwendet

- **body**

   - Hauptinhaltsbereich, in dem die primäre Nachricht übermittelt wird
   - Kann Text, Bilder und andere Medien enthalten
   - Wird in E-Mail- und Meta-Anzeigenvorlagen verwendet

- **CTA (Aktionsaufruf)**

   - Ermuntert den Empfänger, eine bestimmte Aktion auszuführen, z. B. auf einen Link zu klicken oder einen Kauf zu tätigen
   - Wird in E-Mail- und Meta-Anzeigenvorlagen verwendet

- **Bilder**

   - Verbessert die visuelle Attraktivität
   - Text aufteilen
   - Unterstützen der Nachricht
   - Sollte qualitativ hochwertig und auffällig sein
   - Wird in E-Mail- und Meta-Anzeigenvorlagen verwendet

- **Fußzeile**

   - Unterer Abschnitt, der zusätzliche Inhalte wie Kontaktdaten, Social-Media-Links, Haftungsausschlüsse und Abmeldeoptionen enthält
   - Wird in E-Mail-Vorlagen verwendet

- **Textüberlagerung**

   - Text auf einem Bild
   - Verwenden Sie , um Überschrift und Hauptteil zu unterstützen und zu verbessern
   - Wird in Meta-Anzeigenvorlagen verwendet

>[!TIP]
>
>Siehe die [erkannten Feldnamen](customize-template.md#recognized-field-names) die GenStudio for Performance Marketing für Vorlagen jedes Kanaltyps unterstützt.

## Konfigurieren von Kanalrichtlinien

Es gilt als Best Practice, [Channel-Richtlinien](../guidelines/brands.md#channel-guidelines) für jede Marke zu konfigurieren, bevor Vorlagen in GenStudio for Performance Marketing verwendet werden. Die Kanalrichtlinien beeinflussen direkt den Inhaltstyp, der bei Verwendung der Vorlage generiert wird. Sie können beispielsweise Zeichenbeschränkungen für den Textkörper einer E-Mail festlegen.

![Technische Daten des Textkörpers](/help/assets/channel-email-body.png)

## Vorlage anpassen

Sie [Ihre Vorlage](customize-template.md) zur Verwendung in GenStudio for Performance Marketing anpassen, indem Sie Platzhalter oder Felder für Inhalte einfügen, die die generative KI zum Einfügen von Inhalten verwendet. GenStudio for Performance Marketing erkennt bestimmte Felder, z. B. das `body`, und hält sich an die für die jeweilige Marke konfigurierten Kanalrichtlinien.

>[!TIP]
>
>Befolgen Sie [Richtlinien für Barrierefreiheit beim Erstellen von Vorlagen](accessibility-for-templates.md), damit Sie mehr Personen Ihrer Zielgruppe erreichen und ein optimales Erlebnis bieten können.

## Hochladen einer Vorlage

Verwenden [ „Vorlagen anpassen](customize-template.md) als Anleitung beim Vorbereiten einer Vorlage für GenStudio for Performance Marketing. Eine Anleitung [ Bereitstellung eines besseren Erlebnisses für alle Zielgruppen finden Sie unter ](accessibility-for-templates.md)Barrierefreiheitsrichtlinien für Vorlagen“.

**So fügen Sie eine Vorlage**:

1. Wählen Sie _[!DNL Content]_den Abschnitt **[!UICONTROL Vorlagen]**aus.

1. Klicken Sie **[!UICONTROL Vorlage hinzufügen]**.

1. Suchen Sie im Bereich _[!UICONTROL Genehmigte Vorlage hinzufügen]_ nach der HTML-Vorlagendatei oder ziehen Sie die HTML-Vorlagendatei in den Ablagebereich. Klicken Sie auf **[!UICONTROL Weiter]**.

1. Überprüfen Sie _[!UICONTROL Bereich „Erkannte]_ überprüfen“ die erkannten Felder. Vergewissern Sie sich, dass Sie die richtige Vorlage verwenden und dass alle Details erwartungsgemäß sind. Klicken Sie auf **[!UICONTROL Weiter]**.

   Beispielvorschau für eine E-Mail-Vorlage:

   ![Vorschau der Felder erkannt](../../assets/template-detected-fields.png){width="650"}

   >[!TIP]
   >
   >Wenn die Vorlage nicht korrekt ist, klicken Sie auf **[!UICONTROL Zurück]** und kehren Sie zum vorherigen Schritt zurück. Laden Sie die korrigierte Vorlagendatei hoch.

1. Benennen _[!UICONTROL im Bereich „Vorlagendetails angeben und hochladen]_ Ihre Vorlage und wählen Sie einen **[!UICONTROL Kanal]** Typ aus.

   Vorlagenname und Kanaltyp sind erforderlich. Zusätzliche Anforderungen können Folgendes umfassen:

   - **Meta**: erfordert Seitenverhältnis
   <!-- - **Display ads**: requires Dimensions -->

1. Fügen Sie so viele Details wie möglich hinzu, um die Vorlagenidentifizierung bei Suchen und Filtern zu verbessern.

1. Klicken Sie auf **[!UICONTROL Fertig]**.

## Mit einer Vorlage erstellen

Suchen und verwenden Sie eine vorhandene Vorlage in GenStudio for Performance Marketing, um weitere Erlebnisse zu erstellen.

**So erstellen Sie ein Erlebnis mit einer Vorlage**:

1. Wählen Sie _[!DNL Content]_den Abschnitt **[!UICONTROL Vorlagen]**aus.

   ![Liste der Inhaltsvorlagen](../../assets/content-templates.png){width="650" zoomable="yes"}

1. Wählen Sie eine Vorlage für eine vollständige Ansicht und eine Liste mit Details aus.

1. Klicken **[!UICONTROL oben rechts auf Erlebnis]** Pinsel erstellen), um die Vorlage zu verwenden.

1. Fahren Sie mit [Tutorials](/help/tutorials/tutorials.md) fort, um ein Erlebnis zu erstellen.
