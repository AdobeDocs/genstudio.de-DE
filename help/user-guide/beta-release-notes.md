---
title: Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen des Adobe GenStudio für Performance Marketingexperten.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: 5f729070a3a4c162ebac0fde9814c649c9984b4d
workflow-type: tm+mt
source-wordcount: '881'
ht-degree: 0%

---

# Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise

Diese Hinweise zeigen wichtige Adobe GenStudio für Fehlerbehebungen und Verbesserungen für Performance Marketers in der Woche, die am 13. September endet.

## Verbesserungen

* Die Inhaltsauswahl &quot;[!DNL Create]&quot; wurde überarbeitet, um das Laden von Assets zu verbessern. <!-- GS-2586 -->

## Bekannte Probleme

Die folgenden bekannten Probleme sollen in der GenStudio für Performance Marketers GA-Version behoben werden.

* Gelegentlich auftretende Latenzprobleme betreffen einige Vorgänge der Arbeitsfläche [!DNL Create]. <!-- GS-5203 -->

* Die Erstellung von E-Mails führt zu einer unvollständigen E-Mail. **Problemumgehung**: Aktualisieren Sie die Seite und erstellen Sie sie neu. <!-- GS-5209 -->

* Vorlagen können hochgeladen, aber nicht angezeigt werden. **Problemumgehung**: Erstellen oder laden Sie ein Asset hoch und geben Sie einen Asset-Gruppennamen in das Feld **[!UICONTROL Kampagnen]** ein. Wenn Sie das Asset einem [!DNL Campaign] zuweisen, wird der Metadatenwert für den Gruppennamen hinzugefügt. Laden Sie dann die Vorlage erneut hoch. <!-- GS-4815 -->

* Kampagnenminiaturansichten fehlen in [!DNL Insights]. <!-- GS-4648 -->

* Benutzer müssen sich bei einem Kanal-Metaanzeigen-Konto zweimal anmelden, wenn sie auch bei Facebook angemeldet sind. **Problemumgehung**: Melden Sie sich von Facebook ab, bevor Sie sich bei einem Kanal-Metadatenanzeigenkonto anmelden. <!-- GS-4806 -->

### Weitere Verbesserungen und behobene Probleme

* Die Arbeitsfläche [!DNL Create] rendert Bilder in Metaanzeigen falsch. <!-- GS-4864 -->

* Obwohl es zwischen der Vorschau von Meta Ads-Arbeitsfläche und den exportierten Ansichten Diskrepanzen geben kann, funktionieren exportierte Erlebnisse erwartungsgemäß. <!-- GS-4492 4401 -->

* Hochgeladene Bilder enthalten nicht immer die erwarteten Smart-Tags. <!-- GS-4856 -->

* Die CSV-Datei für Metadaten-Anzeigenexport enthält jetzt erwartungsgemäß Bilder. Zuvor enthielt die ZIP-Datei die CSV-Exportdatei und NULL-Dateien anstelle von Bildern.  <!-- GS-5107 -->

* Benutzer können jetzt Text wie erwartet in das Feld &quot;Vorlagendetailansicht&quot;**[!UICONTROL Hochgeladen von]** eingeben. Zuvor verhinderte das Ladesymbol die Eingabe von Text durch Benutzer. <!-- GS-4887 -->

* Benutzer werden nach dem Löschen der Marke nicht mehr zur Detailansicht einer Marke weitergeleitet. <!-- GS-2663 -->

* Bearbeiter erhalten nicht mehr den folgenden Fehler, wenn sie Varianten zur Überprüfung und Genehmigung senden: `You have no access to view comments on this Object`. <!-- GS-5140 -->

* Die E-Mail-Vorlage, die vom Workflow für Überprüfungen und Genehmigungen verwendet wird, wurde aktualisiert. <!-- GS-5239 -->

* GenStudio zeigt jetzt eine Fehlermeldung an, wenn beim Laden der Vorlagenauswahl ein Netzwerkfehler auftritt. <!-- GS-4682 -->

* Es wurden Probleme beim Navigieren von einem Asset, Erlebnis oder einer Vorlagenkarte zum ausgewählten Objekt behoben. <!-- GS-4390 -->

* Das Popup _Assets hinzufügen_ wird jetzt lokalisiert, wenn es über die Arbeitsfläche &quot;Erstellen&quot;geöffnet wird.  <!-- GS-4867 -->

* Die Markenvalidierung wird jetzt für neu generierte Varianten ausgelöst. Wenn ein Editor zuvor Varianten eines vorhandenen Entwurfs neu generiert hat, wurde die Validierung nicht ausgelöst. <!-- GS-3971 -->

## Frühere Beta-Versionen

Frühere Beta-Versionen umfassten die folgenden Highlights und Fehlerbehebungen.

### Highlights

* GenStudio unterstützt jetzt die Option zur Vorschau von Medien-Assets in der Tabellen- und Galerieansicht in [!DNL Insights]. Videominiaturen enthalten eine Schaltfläche **Abspielen** mit einer Stummschaltoption. <!-- GS-4398 -->

* Die Kanalrichtlinien von instagram und Facebook wurden zu Richtlinien für Meta-Marken zusammengefasst.

* [!DNL Create] Die Navigationselemente der Arbeitsfläche wurden optimiert. Auf der Landingpage [!DNL Create] wird das linke Navigationsfenster angezeigt. Benutzer verwenden jetzt jedoch die Schaltfläche **[!UICONTROL Zurück]** , um von anderen [!DNL Create] -Arbeitsbereichen aus zu diesem Bereich zu navigieren.

* Navigationselemente wurden verbessert, um den Benutzerfokus bei der Ausführung von Aufgaben im gesamten Produkt zu unterstützen, einschließlich der folgenden Produktbereiche:

   * Asset-, Erlebnis- und Vorlagendetails in [!DNL Content]
   * Erlebnis, Asset, Attributdetail in [!DNL Insights]
   * Markendetails in [!DNL Brands]
   * Produkt- und Personalisierungsdetails in &quot;Produkte und Personas&quot;

* Benutzer müssen nicht mehr auf die Schaltfläche **[!UICONTROL Aktualisieren]** klicken, um die Aktualisierungen an Erlebnissen in [!DNL Content] anzuzeigen.

* Die Seite _Erlebnisdetails_ rendert jetzt externe Asset-Miniaturansichten als HTML.

* Die Latenz der Benutzeroberfläche nach dem Hinzufügen oder Löschen von Assets und Erlebnissen wurde verbessert.

* Die Vorlagenvorschau enthält jetzt einen beschreibenden Standardtext. Siehe [Anpassen einer Vorlage](https://experienceleague.adobe.com/en/docs/genstudio/user-guide/content/templates/customize-template#template-preview).

* **Prozentsatzbasiertes Validierungsergebnis**: Bei der Markenvalidierung wird nun die Markenvalidierungsbewertung als Prozentsatz und nicht als Wert für Bestehen/Fehlschlagen angezeigt. (festgelegt am 16.8.2016)

* **Aktualisierte Benutzeroberfläche zur Markenextraktion**: Die Markenextraktion zeigt jetzt den Abschluss des Extraktionsvorgangs als Prozentsatz an. (festgelegt am 16.8.2016)

* **Inkrementelle Belastung der Marke während der Extraktion**: Die Markenrichtlinien werden jetzt schrittweise in die Benutzeroberfläche geladen. (festgelegt am 16.8.2016)

* **Erstellung von E-Mails mit mehreren Abschnitten**: Benutzer können jetzt E-Mails erstellen, die aus separaten Überschriften-, Bild-, Text- und CTA-Elementen bestehen. (festgelegt am 16.8.2016)

* **MetaAds-Größe ändern**: Bearbeiter können die Größe von MetaAd-Seitenverhältnissen ändern. (festgelegt am 16.8.2016)

* **Eingeschränkte [!DNL Insights] Anmeldekonten**: Die [!DNL Insights] -Anmeldung unterstützt jetzt nur ein Konto pro Kunde. (festgelegt am 16.8.2016)

### Weitere Verbesserungen und behobene Probleme

* Das Popup _Assets hinzufügen_ ist jetzt erwartungsgemäß lokalisiert. <!-- GS-3834 -->

* Probleme mit der Skalierung der Erlebnisvorlage für Meta-Anzeigen wurden behoben. <!-- GS-4174 -->

* Textfelder in der CSV-Exportdatei für mehrteilige E-Mails werden jetzt erwartungsgemäß sortiert. <!-- GS-4013 -->

* Das Suchfeld [!DNL Content] verschwindet nicht mehr, wenn ein Benutzer wiederholt die Taste **Rücktaste** drückt, um den Suchfeldtext zu löschen.  <!-- GS-4543 -->

* GenStudio for Performance Marketers lädt Benutzer jetzt erwartungsgemäß, wenn ein Mitarbeiter einem Kommentar eine `@` -Erwähnung hinzufügt. Zuvor wurden Benutzer nicht geladen und ein Fehler wurde angezeigt: `Unable to load users. Refresh the page`. <!-- GS-4113 -->

* GenStudio zeigt die Meldung **Irgendetwas ist schiefgelaufen** nicht mehr an, wenn ein Editor während der E-Mail-Erstellung im Eingabeaufforderungsbereich auf **Inhalt auswählen** klickt. <!-- GS-4879 -->

* Der Seitenname _Erlebnisdetails_ für die Feed-Platzierung gibt jetzt den Facebook- oder Instagram-Feed an. (festgelegt am 16.8.2016)

* Das Zuschneiden größerer Bilder und Videos ist jetzt konsistent, wenn der Benutzer von der Ansicht _Asset-Übersicht_ zur Ansicht _Asset-Detail_ navigiert. (festgelegt am 16.8.2016)

* Die Anzahl der Suchergebnisse des Bildschirms &quot;Attribute&quot;zeigt nicht mehr &quot;`0 of`&quot;an, bevor sich ein Benutzer anmeldet. (Korrektur am 16.8.2016) <!-- GS-3665 -->

* Wenn Sie auf das Zählerfeld **[!UICONTROL [!DNL Insights]]** > **[!UICONTROL Asset]** klicken, werden die Such- und Filtereinstellungen nicht mehr gelöscht. (Korrektur am 16.8.2016) <!-- GS-3476 -->

* GenStudio zeigt einen Fehler an, wenn ein Benutzer versucht, Anmeldeinformationen in der [!DNL Insights]-Ansicht einzugeben. (Korrektur am 29.8.19) <!-- GS-4689 -->

* Das Hochladen von Markenrichtlinien schlägt aufgrund von Problemen mit der AKP-Speicherplattform fehl. (Korrektur am 22.8.20) <!-- GS-4369 -->

* Im Dropdown-Menü Eingabeaufforderung [!DNL Brands] wird am Ende der Liste [!DNL Brands] bei der E-Mail-Erstellung ein Gewinner angezeigt. (Korrektur am 22.8.20) <!-- GS-4077 -->
