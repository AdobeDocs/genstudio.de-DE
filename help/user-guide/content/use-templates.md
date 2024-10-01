---
title: Arbeiten mit Vorlagen
description: Hier erfahren Sie, wie Sie Vorlagen effektiv verwenden können, um Ihre kreativen Prozesse in Adobe GenStudio for Performance Marketing zu optimieren.
feature: Templates, Content
exl-id: 7705bb79-19ca-4c16-8f8b-95bf8687e96d
source-git-commit: 54fd20fec553b545b2f5d64cdf9327098b16580f
workflow-type: tm+mt
source-wordcount: '682'
ht-degree: 1%

---

# Arbeiten mit Vorlagen

GenStudio for Performance Marketing ermöglicht es Erstellern von Inhalten, mithilfe von _templates_ schnell konsistente On-Brand-Marketinginhalte zu erstellen. Eine Vorlage reduziert den Zeit- und Arbeitsaufwand für die Erstellung neuer Inhalte erheblich, indem sie einen Ausgangspunkt bietet, der vorkonfigurierte Layouts und Designelemente enthält.

## Vorlagenelemente

Eine Vorlage ist ein Satz von Anweisungen, die mit HTML und Inline-CSS definiert sind und zur Erstellung eines E-Mail- oder Meta-Anzeigenerlebnisses verwendet werden können.

Im Folgenden finden Sie eine Liste der Elemente, die in Vorlagen verwendet werden, sowie einige Details zu ihren Eigenschaften.

- **Preheader**

   - Betreffzeile in einer E-Mail, die den Hauptbetreff erweitert
   - Zwischen 40 und 50 Zeichen
   - Im Posteingang neben dem Betreff sichtbar, bevor die E-Mail geöffnet wird
   - In E-Mail-Vorlagen verwendet

- **Kopfzeile**

   - Oberer Bereich der E-Mail, den der Empfänger beim Öffnen der E-Mail sieht
   - Legt den Ton fest und liefert Kontext für den enthaltenen Inhalt
   - In E-Mail-Vorlagen verwendet

- **Überschrift**

   - Zuerst Inhalt, der dem Empfänger angezeigt wird
   - Muss zwingend zu Zinsen führen
   - Wird in Meta-Anzeigenvorlagen verwendet

- **Textkörper**

   - Hauptinhaltsbereich, in dem die primäre Nachricht übermittelt wird
   - Kann Text, Bilder und andere Medien enthalten
   - In E-Mail- und Meta-Anzeigenvorlagen verwendet

- **CTA (Aktionsaufruf)**

   - Ermutigt den Empfänger, eine bestimmte Aktion durchzuführen, z. B. auf einen Link zu klicken oder einen Kauf zu tätigen
   - In E-Mail- und Meta-Anzeigenvorlagen verwendet

- **Bilder**

   - Verbessert die visuelle Darstellung
   - Aufschlüsseln von Text
   - Nachricht unterstützen
   - Sollte von hoher Qualität sein und augenblicklich sein
   - In E-Mail- und Meta-Anzeigenvorlagen verwendet

- **Fußzeile**

   - Unterer Abschnitt mit zusätzlichem Inhalt, wie z. B. Kontaktdetails, Social-Media-Links, Haftungsausschlüsse und Abmeldeoptionen
   - In E-Mail-Vorlagen verwendet

- **Textüberlagerung**

   - Text auf einem Bild
   - Verwendung zur Unterstützung und Verbesserung von Überschrift und Körper
   - Wird in Meta-Anzeigenvorlagen verwendet

>[!TIP]
>
>Siehe [erkannte Feldnamen](customize-template.md#recognized-field-names), die GenStudio for Performance Marketing für Vorlagen der einzelnen Kanaltypen unterstützt.

## Konfigurieren von Kanalrichtlinien

Es empfiehlt sich, die [Kanalrichtlinien](../guidelines/brands.md#channel-guidelines) für jede Marke zu konfigurieren, bevor Vorlagen in GenStudio for Performance Marketing verwendet werden. Die Kanalrichtlinien beeinflussen direkt den Inhaltstyp, der bei Verwendung der Vorlage generiert wird. Sie können beispielsweise Zeichenbeschränkungen für den Text einer E-Mail festlegen.

![Textkörperspezifikationen](/help/assets/channel-email-body.png)

## Vorlage anpassen

Sie können Ihre Vorlage [ für die Verwendung in GenStudio for Performance Marketing anpassen, indem Sie Platzhalter für Inhalte oder Felder einfügen, die von der generativen KI zum Einfügen von Inhalten verwendet werden. ](customize-template.md) GenStudio for Performance Marketing erkennt bestimmte Felder, wie z. B. das Feld `body`, und hält sich an die für die ausgewählte Marke konfigurierten Kanalrichtlinien.

>[!TIP]
>
>Befolgen Sie die [Richtlinien für Barrierefreiheit beim Erstellen von Vorlagen](accessibility-for-templates.md), damit Sie mehr Zielgruppen erreichen und ein optimales Erlebnis bieten können.

## Vorlage hochladen

Verwenden Sie [Vorlagen anpassen](customize-template.md) als Anleitung zum Vorbereiten einer Vorlage für GenStudio for Performance Marketing. Eine Anleitung zur Bereitstellung eines besseren Erlebnisses für alle Zielgruppen finden Sie unter [Richtlinien für Barrierefreiheit für Vorlagen](accessibility-for-templates.md) .

**So fügen Sie eine Vorlage hinzu**:

1. Wählen Sie in _[!DNL Content]_den Abschnitt **[!UICONTROL Vorlagen]**aus.

1. Klicken Sie auf **[!UICONTROL Vorlage hinzufügen]**.

1. Suchen Sie im Bereich _[!UICONTROL Genehmigte Vorlage hinzufügen]_ nach der HTML-Vorlagendatei oder ziehen Sie die HTML-Vorlagendatei auf die Ablagefläche. Klicken Sie auf **[!UICONTROL Weiter]**.

1. Überprüfen Sie im Bereich _[!UICONTROL Erkannte Felder überprüfen]_ die erkannten Felder. Vergewissern Sie sich, dass Sie die richtige Vorlage verwenden und dass alle Details erwartungsgemäß sind. Klicken Sie auf **[!UICONTROL Weiter]**.

   Beispielvorschau für eine E-Mail-Vorlage:

   ![Vorschau der erkannten Felder anzeigen](../../assets/template-detected-fields.png){width="650"}

   >[!TIP]
   >
   >Wenn die Vorlage nicht korrekt ist, klicken Sie auf **[!UICONTROL Zurück]** und kehren Sie zum vorherigen Schritt zurück. Laden Sie die korrigierte Vorlagendatei hoch.

1. Benennen Sie Ihre Vorlage im Bereich _[!UICONTROL Vorlagendetails angeben und hochladen]_ , und wählen Sie den Typ **[!UICONTROL Kanal]** aus.

   Vorlagenname und Kanaltyp sind erforderlich. Weitere Anforderungen können Folgendes umfassen:

   - **Meta**: erfordert Seitenverhältnis
   <!-- - **Display ads**: requires Dimensions -->

1. Fügen Sie so viele Details wie möglich hinzu, um die Vorlagenerkennung bei der Suche und Filterung zu verbessern.

1. Klicken Sie auf **[!UICONTROL Fertig]**.

## Erstellen mit einer Vorlage

Suchen und verwenden Sie eine vorhandene Vorlage in GenStudio for Performance Marketing, um weitere Erlebnisse zu erstellen.

**So erstellen Sie ein Erlebnis mit einer Vorlage**:

1. Wählen Sie in _[!DNL Content]_den Abschnitt **[!UICONTROL Vorlagen]**aus.

   ![Liste der Inhaltsvorlagen](../../assets/content-templates.png){width="650" zoomable="yes"}

1. Wählen Sie eine Vorlage für eine vollständige Ansicht und eine Detailliste aus.

1. Klicken Sie in der oberen rechten Ecke auf **[!UICONTROL Erlebnis erstellen]** (Pinsel) , um die Vorlage zu verwenden.

1. Fahren Sie mit [Tutorials](/help/tutorials/tutorials.md) fort, um ein Erlebnis zu erstellen.
