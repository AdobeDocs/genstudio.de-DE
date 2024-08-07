---
title: Arbeiten mit Vorlagen
description: Erfahren Sie, wie Sie mit Vorlagen ansprechende Erlebnisse in GenStudio erstellen können.
feature: Templates, Content
source-git-commit: 6870f1b7056219d03cabbcc4e5ddbfa436b1a56d
workflow-type: tm+mt
source-wordcount: '443'
ht-degree: 2%

---


# Arbeiten mit Vorlagen

GenStudio-Vorlagen sind unverzichtbar, damit Inhaltsersteller schnell konsistente On-Brand-Marketing-Inhalte erstellen können. Durch die Verwendung von Vorlagen wird der Zeit- und Arbeitsaufwand für die Erstellung neuer Inhalte erheblich reduziert, da ein Ausgangspunkt mit vorkonfigurierten Layouts und Designelementen bereitgestellt wird.

In diesem Handbuch finden Sie detaillierte Informationen zu folgenden Themen:

* Vorbereiten einer [E-Mail-Vorlage](email-template.md) oder einer Meta-Anzeigenvorlage
* [Vorlagen anpassen](customize-template.md) für GenStudio
* [ Vorlagen hochladen](#upload-a-template) in GenStudio
* [Verwenden von Vorlagen zum Erstellen von Erlebnissen](#use-a-template)

## Anatomie einer Vorlage

Das grundlegende Vorlagendesign umfasst die folgenden Elemente:

| Element | Funktion | Kanalvorlage |
| ------------ | ---------------------- | -------------------- |
| Preheader | Zwischen 40-50 Zeichen <br>fungiert als sekundäre Betreffzeile, die die Hauptbetreffzeile <br>im Posteingang neben dem Betreff anzeigt, bevor die E-Mail geöffnet wird | email |
| Kopfzeile | Der obere Bereich des E-Mail-Empfängers sieht beim Öffnen des E-Mail-Tons <br>Legt den Ton fest und liefert Kontext für den eingeschlossenen Inhalt | email |
| Überschrift | Erster Inhaltsempfänger sieht <br>Sollte überzeugend sein, Interesse zu erwischen | Meta-Anzeige |
| body | Hauptinhaltsbereich, in dem die primäre Nachricht übermittelt wird <br>Kann Text, Bilder und andere Medien enthalten | email<br>Meta-Anzeige |
| CTA | Aktionsaufruf, der den Empfänger dazu ermutigt, bestimmte Maßnahmen zu ergreifen, z. B. das Klicken auf einen Link oder das Beenden eines Kaufs | email<br>Meta-Anzeige |
| Bilder | Verbessert die visuelle Anziehungskraft <br>Aufschlüsseln von Text <br>Unterstützt die Meldung <br>Sollte qualitativ hochwertig und auffällig sein | email<br>Meta-Anzeige |
| Fußzeile | Enthält zusätzliche Informationen wie Kontaktdetails, Social-Media-Links, Haftungsausschlüsse und Abmeldeoptionen | email |
| Textüberlagerung | Text auf einem Bild <br>Sollte Überschrift und Hauptteil unterstützen und verbessern | Meta-Anzeige |

>[!NOTE]
> 
>Es wird empfohlen, bestimmte Felder in den Inhalt jedes Kanals einzuschließen, um sicherzustellen, dass GenStudio Text für Platzhalter für Inhalte generieren kann. Siehe [Erkannte Feldnamen ](customize-template.md#recognized-field-names) , um zu sehen, welche Felder zur Aufnahme empfohlen werden.

## Vorlage hochladen

GenStudio akzeptiert Vorlagen im HTML-Format.

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

   ![Liste der Inhaltsvorlagen](../../assets/content-templates.png)

1. Wählen Sie eine Vorlage für eine vollständige Ansicht und eine Detailliste aus.

>[!TIP]
>
>Vollständige Tutorials mit Vorlagen finden Sie unter [[!DNL Create] ein E-Mail-Erlebnis](/help/tutorials/create-email-experience.md) oder [[!DNL Create] ein Meta-Anzeigenerlebnis](/help/tutorials/create-meta-ad.md) .

<!--  The create button in Content Template view does not work yet.
1. Click **[!UICONTROL Create Experience]** (paintbrush) from the upper right corner to use the template.
-->
