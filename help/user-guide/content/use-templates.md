---
title: Arbeiten mit Vorlagen
description: Erfahren Sie, wie Sie mit Vorlagen ansprechende Erlebnisse in Adobe GenStudio für Performance-Marketer erstellen können.
feature: Templates, Content
source-git-commit: 0cd877737f8ed4d38201c832d454795206505de2
workflow-type: tm+mt
source-wordcount: '473'
ht-degree: 2%

---


# Arbeiten mit Vorlagen

GenStudio-Vorlagen ermöglichen es Erstellern von Inhalten, schnell konsistente On-Brand-Marketinginhalte zu erstellen. Durch die Verwendung von Vorlagen wird der Zeit- und Arbeitsaufwand für die Erstellung neuer Inhalte erheblich reduziert, da ein Ausgangspunkt mit vorkonfigurierten Layouts und Designelementen bereitgestellt wird.

In diesem Handbuch finden Sie detaillierte Informationen zu folgenden Themen:

* Vorbereiten einer [E-Mail-Vorlage](email-template.md) oder einer Meta-Anzeigenvorlage
* [Anpassen von Vorlagen](customize-template.md) für GenStudio für Performance Marketers
* Befolgen Sie die Anleitungen unter [Zugreifbare Vorlagen erstellen](accessibility-for-templates.md)
* [Hochladen von Vorlagen](#upload-a-template) in GenStudio für Performance Marketingexperten
* [Verwenden von Vorlagen zum Erstellen von Erlebnissen](#use-a-template)

## Anatomie einer Vorlage

Das grundlegende Vorlagendesign umfasst die folgenden Elemente:

| Element | Funktion | Kanalvorlage |
| ------------ | ---------------------- | -------------------- |
| Preheader | Zwischen 40 und 50 Zeichen <br>fungiert als sekundäre Betreffzeile, die die im Posteingang angezeigte Hauptbetreffzeile <br>vor dem Öffnen der E-Mail neben dem Betreff erweitert | email |
| Kopfzeile | Der obere Bereich des E-Mail-Empfängers sieht beim Öffnen des E-Mail-Tons <br>Legt den Ton fest und liefert Kontext für den eingeschlossenen Inhalt | email |
| Überschrift | Erster Inhaltsempfänger sieht <br>Sollte überzeugend sein, Interesse zu erwischen | Meta-Anzeige |
| body | Hauptinhaltsbereich, in dem die primäre Nachricht übermittelt wird <br>Kann Text, Bilder und andere Medien enthalten | email<br>Meta-Anzeige |
| CTA | Aktionsaufruf, der den Empfänger dazu ermutigt, bestimmte Maßnahmen zu ergreifen, z. B. das Klicken auf einen Link oder das Beenden eines Kaufs | email<br>Meta-Anzeige |
| Bilder | Verbessert die visuelle Anziehungskraft <br>Aufschlüsseln von Text <br>Unterstützt die Meldung <br>Sollte qualitativ hochwertig und auffällig sein | email<br>Meta-Anzeige |
| Fußzeile | Fußbereich mit zusätzlichen Inhalten wie Kontaktdetails, Social-Media-Links, Haftungsausschlüssen und Abmeldeoptionen | email |
| Textüberlagerung | Text auf einem Bild <br>Sollte Überschrift und Hauptteil unterstützen und verbessern | Meta-Anzeige |

>[!NOTE]
>
>Es wird empfohlen, dass Sie bestimmte Felder in den Inhalt jedes Kanals einschließen, um sicherzustellen, dass GenStudio for Performance Marketers Text für Inhaltsplatzhalter generieren kann. Siehe [Erkannte Feldnamen ](customize-template.md#recognized-field-names) , um zu sehen, welche Felder zur Aufnahme empfohlen werden.

## Vorlage hochladen

GenStudio for Performance Marketers akzeptiert Vorlagen im HTML-Format.

**So fügen Sie eine Vorlage hinzu**:

1. Wählen Sie in _[!DNL Content]_den Abschnitt **[!UICONTROL Vorlagen]**aus.

1. Klicken Sie auf **[!UICONTROL Vorlage hinzufügen]**.

1. Suchen Sie im Bereich _[!UICONTROL Genehmigte Vorlage hinzufügen]_ nach der HTML-Vorlagendatei oder ziehen Sie die HTML-Vorlagendatei auf die Ablagefläche. Klicken Sie auf **[!UICONTROL Weiter]**.

1. Überprüfen Sie im Bereich _[!UICONTROL Struktur-Detail überprüfen]_ , ob Sie die richtige Vorlage verwenden und ob alle Details erwartungsgemäß sind. Klicken Sie auf **[!UICONTROL Weiter]**.

1. Benennen Sie im Bereich _[!UICONTROL Details Ihrer Vorlage hinzufügen]_ Ihre Vorlage und wählen Sie den Typ **[!UICONTROL Kanal]** aus.

   Vorlagenname und Kanaltyp sind erforderlich.

   * **Meta**: erfordert Seitenverhältnis
   <!-- **Display ads**: requires Dimensions -->

1. Fügen Sie so viele Details wie möglich hinzu, um die Vorlagenerkennung bei der Suche und Filterung zu verbessern.

1. Klicken Sie auf **[!UICONTROL Fertig]**.

## Vorlage verwenden

Suchen und verwenden Sie eine vorhandene Vorlage, um Erlebnisse zu erstellen.

**So erstellen Sie ein Erlebnis mit einer Vorlage**:

1. Wählen Sie in _[!DNL Content]_den Abschnitt **[!UICONTROL Vorlagen]**aus.

   ![Liste der Inhaltsvorlagen](../../assets/content-templates.png){width="650" zoomable="yes"}

1. Wählen Sie eine Vorlage für eine vollständige Ansicht und eine Detailliste aus.

>[!TIP]
>
>Vollständige Tutorials mit Vorlagen finden Sie unter [[!DNL Create] ein E-Mail-Erlebnis](/help/tutorials/create-email-experience.md) oder [[!DNL Create] ein Meta-Anzeigenerlebnis](/help/tutorials/create-meta-ad.md) .
<!--  The create button in Content Template view does not work yet.
1. Click **[!UICONTROL Create Experience]** (paintbrush) from the upper right corner to use the template.
-->
