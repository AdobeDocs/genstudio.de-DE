---
title: Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen des Adobe GenStudio für Performance Marketingexperten.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: 7085fa5a12a6ed36c9310f8f691969d9c1366d36
workflow-type: tm+mt
source-wordcount: '1348'
ht-degree: 0%

---

# Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise

Diese Hinweise zeigen wichtige Adobe GenStudio für Fehlerbehebungen und Verbesserungen für Performance Marketers in der Woche, die am 19. September endet.

## Neue Funktionen und Verbesserungen

* **Integration mit Adobe Experience Manager Assets**. Der schreibgeschützte Zugriff auf Adobe Experience Manager Assets ist jetzt verfügbar. <!-- GS-2432 -->

* **Verbesserungen am Workflow Vorlage aktualisieren**.  Benutzer, die Vorlagen aktualisieren, wählen nun den Kanal aus, für den sie die Vorlage verwenden möchten. <!-- GS-4029 -->

* **Verbesserte Leistung beim Laden von Seiten erstellen**. Nicht verwendete Abhängigkeiten wurden aus dem Seitenladeprozess entfernt. <!-- GS-3630 -->

* **Unterstützung mehrteiliger E-Mails**. Bearbeiter können jetzt E-Mails erstellen, die mehrere Abschnitte und Bilder enthalten. Sie können auch bestimmte Fragmente einer generierten E-Mail (z. B. eine Überschrift) regenerieren. <!-- GS-2436 -->

* **Wechsel zwischen Desktop- und Mobilgeräteansicht während der Erstellung**. Benutzer können jetzt zwischen der Desktop- und der Mobile-Ansicht wechseln, um E-Mail-Erlebnisvarianten in der Vorschau anzuzeigen. <!-- GS-4314 -->

* Der Inhalt generiert jetzt Bilder mit Zuschnittdimensionen, die relativ zu den ursprünglichen Asset-Dimensionen sind. <!-- GS-3150 -->

* Benutzer können jetzt generierte Bildvarianten auswählen und die Funktion &quot;Zuschneiden anpassen&quot;verwenden, um sie während des Erstellungsarbeitsablaufs zu beschneiden. <!-- GS-5538 2342 -->

* In der Detailansicht eines genehmigten Erlebnisses wird jetzt ein Miniaturbild und der Status aller Assets angezeigt, auf die in diesem Erlebnis verwiesen wird. <!-- GS-3783 -->

## Bekannte Probleme

Die folgenden bekannten Probleme sollen in der GenStudio für Performance Marketers GA-Version behoben werden.

* Gelegentlich auftretende Latenzprobleme betreffen einige Vorgänge der Arbeitsfläche [!DNL Create]. <!-- GS-5203 -->

* Die Erstellung von E-Mails führt zu einer unvollständigen E-Mail. **Problemumgehung**: Aktualisieren Sie die Seite und erstellen Sie sie neu. <!-- GS-5209 -->

* Vorlagen können hochgeladen, aber nicht angezeigt werden. **Problemumgehung**: Laden Sie ein Asset hoch, in dem das Feld **[!UICONTROL Kampagnen]** ausgefüllt ist. Laden Sie dann die Vorlage erneut hoch. <!-- GS-4815 -->

* Benutzer müssen sich bei einem Kanal-Meta-Anzeigen-Konto zweimal anmelden, wenn sie auch bei Facebook angemeldet sind. **Problemumgehung**: Melden Sie sich von Facebook ab, bevor Sie sich bei einem Kanal-Meta-Anzeigenkonto anmelden. <!-- GS-4806 -->

### Weitere Verbesserungen und behobene Probleme

* Drag &amp; Drop funktioniert nun wie erwartet im Eingabeaufforderungsbereich. <!-- GS-3977 -->

* Es wurden Probleme bei der Verwendung der Tabulatortaste zur Navigation durch Elemente in der linken Navigationsleiste behoben. Zuvor waren mehrere Klicks erforderlich, um von einem Element zum nächsten aktiven Element zu navigieren.  <!-- GS-2639 -->

* GenStudio speichert jetzt Erlebnisnamen, wenn Benutzer den Namen bearbeiten, während das Erlebnis geladen wird. <!-- GS-5242 -->

* Benutzer können jetzt einen Erlebnistitel erfolgreich bearbeiten. Zuvor wurde der Titeltext standardmäßig auf den Originaltext umgestellt, nachdem ein Benutzer versucht hatte, ihn zu bearbeiten. <!-- GS-5246 -->
* Ausgewählte Bilder werden jetzt auf der Arbeitsfläche während der mehrteiligen E-Mail-Erstellung erwartungsgemäß dargestellt. <!-- GS-5263 -->

* Alle Zeichenfolgen auf der Detailseite [!DNL Content] Erlebnisse sind jetzt lokalisiert. <!-- GS-5016 -->

* Benutzer können jetzt ein Produkt löschen, dessen Detailansicht in [!DNL Products] geöffnet ist. <!-- GS-5057 -->

* Die Meldung, die GenStudio anzeigt, wenn eine Suche keine übereinstimmenden Ergebnisse liefert, wurde verbessert. <!-- GS-4544 -->

* `aria-label` -Attributwerte für Suchfilterwerte werden jetzt erwartungsgemäß übersetzt. <!-- GS-5388 -->

* Benutzer können jetzt doppelte Assets im Eingabeaufforderungsbereich der Arbeitsfläche [!DNL Create] erfolgreich löschen.  <!-- GS-5233 -->

* Der Kontofilter funktioniert jetzt wie erwartet mit Erlebnissen, Assets und Attributen. <!-- GS-4812 -->

* Schriftprobleme bei Meta-Anzeigenvorlagen wurden behoben, um Lesbarkeit und Barrierefreiheit zu verbessern. <!-- GS-5354 -->

* Änderungen an Entwurfstiteln bleiben nun erwartungsgemäß erhalten. Zuvor wurden Titel nach der Bearbeitung auf den Standardnamen zurückgesetzt. <!-- GS-2951 -->

#### Fehlerbehebungen für Vorlagen

* Die Größenänderungsfunktion funktioniert jetzt wie erwartet mit mehreren Bildern in Meta-Anzeigenvorlagen. Zuvor hat GenStudio die Bildgröße nicht für alle ausgewählten Vorlagen geändert. <!-- GS-4696 -->

* Beim Löschen einer Vorlage wird die Seite &quot;[!DNL Content]&quot; jetzt wie erwartet aktualisiert. <!-- GS-5397 -->

* Benutzer können jetzt nur Werte für [!DNL Personas], [!DNL Brands] oder [!DNL Products] aus dem Dropdown-Menü auswählen. Zuvor konnten Benutzer im Dialogfeld _Vorlagen-Upload_ beliebige Namen für [!DNL Persona], [!DNL Brand] oder [!DNL Product] eingeben. <!-- GS-5072 5071-->

* Die Schaltfläche **[!UICONTROL Zurück]** ist jetzt beim Hochladen der Vorlage deaktiviert. <!-- GS-5358 -->

* Alle Zeichenfolgen in der Detailansicht &quot;[!DNL Create] Vorlage auswählen&quot;sind jetzt lokalisiert. <!-- GS-5025 -->

## Frühere Beta-Versionen

Frühere Beta-Versionen umfassten die folgenden Highlights und Fehlerbehebungen.

### Highlights

* Die Inhaltsauswahl &quot;[!DNL Create]&quot; wurde überarbeitet, um das Laden von Assets zu verbessern. <!-- GS-2586 -->

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

* **Größe von Metaanzeigen ändern**: Bearbeiter können die Größe von Meta-Anzeigenseitenverhältnissen ändern. (festgelegt am 16.8.2016)

* **Eingeschränkte [!DNL Insights] Anmeldekonten**: Die [!DNL Insights] -Anmeldung unterstützt jetzt nur ein Konto pro Kunde. (festgelegt am 16.8.2016)

### Weitere Verbesserungen und behobene Probleme

* Die Arbeitsfläche [!DNL Create] rendert jetzt Bilder in Meta-Anzeigen korrekt. (Korrektur 9/13) <!-- GS-4864 -->

* Obwohl es zwischen der Vorschau von Meta Ads Canvas und den exportierten Ansichten Diskrepanzen geben kann, funktionieren exportierte Erlebnisse erwartungsgemäß. (Korrektur 9/13) <!-- GS-4492 4401 -->

* Hochgeladene Bilder enthalten jetzt die erwarteten Smart-Tags. (Korrektur 9/13) <!-- GS-4856 -->

* Die CSV-Datei für den Export von Meta-Anzeigen enthält jetzt Bilder wie erwartet. Zuvor enthielt die ZIP-Datei die CSV-Exportdatei und NULL-Dateien anstelle von Bildern. (Korrektur 9/13) <!-- GS-5107 -->

* Benutzer können jetzt Text wie erwartet in das Feld &quot;Vorlagendetailansicht&quot;**[!UICONTROL Hochgeladen von]** eingeben. Zuvor verhinderte das Ladesymbol die Eingabe von Text durch Benutzer. (Korrektur 9/13) <!-- GS-4887 -->

* Benutzer werden nach dem Löschen der Marke nicht mehr zur Detailansicht einer Marke weitergeleitet. (Korrektur 9/13) <!-- GS-2663 -->

* Bearbeiter erhalten nicht mehr den folgenden Fehler, wenn sie Varianten zur Überprüfung und Genehmigung senden: `You have no access to view comments on this Object`. (Korrektur 9/13) <!-- GS-5140 -->

* Die E-Mail-Vorlage, die vom Workflow für Überprüfungen und Genehmigungen verwendet wird, wurde aktualisiert. (Korrektur 9/13) <!-- GS-5239 -->

* GenStudio zeigt jetzt eine Fehlermeldung an, wenn beim Laden der Vorlagenauswahl ein Netzwerkfehler auftritt. (Korrektur 9/13) <!-- GS-4682 -->

* Es wurden Probleme beim Navigieren von einem Asset, Erlebnis oder einer Vorlagenkarte zum ausgewählten Objekt behoben. (Korrektur 9/13) <!-- GS-4390 -->

* Das Popup _Assets hinzufügen_ wird jetzt lokalisiert, wenn es über die Arbeitsfläche &quot;Erstellen&quot;geöffnet wird. (Korrektur 9/13) <!-- GS-4867 -->

* Die Markenvalidierung wird jetzt für neu generierte Varianten ausgelöst. Wenn ein Editor zuvor Varianten eines vorhandenen Entwurfs neu generiert hat, wurde die Validierung nicht ausgelöst. (Korrektur 9/13) <!-- GS-3971 -->

* Das Popup _Assets hinzufügen_ ist jetzt erwartungsgemäß lokalisiert. (Korrektur 9/5) <!-- GS-3834 -->

* Probleme mit der Skalierung der Erlebnisvorlage für Meta-Anzeigen wurden behoben. (Korrektur 9/5) <!-- GS-4174 -->

* Textfelder in der CSV-Exportdatei für mehrteilige E-Mails werden jetzt erwartungsgemäß sortiert. (Korrektur 9/5) <!-- GS-4013 -->

* Das Suchfeld [!DNL Content] verschwindet nicht mehr, wenn ein Benutzer wiederholt die Taste **Rücktaste** drückt, um den Suchfeldtext zu löschen. (Korrektur 9/5) <!-- GS-4543 -->

* GenStudio for Performance Marketers lädt Benutzer jetzt erwartungsgemäß, wenn ein Mitarbeiter einem Kommentar eine `@` -Erwähnung hinzufügt. Zuvor wurden Benutzer nicht geladen und ein Fehler wurde angezeigt: `Unable to load users. Refresh the page`. (Korrektur am 29.8.19) <!-- GS-4113 -->

* GenStudio zeigt die Meldung **Irgendetwas ist schiefgelaufen** nicht mehr an, wenn ein Editor während der E-Mail-Erstellung im Eingabeaufforderungsbereich auf **Inhalt auswählen** klickt. <!-- GS-4879 -->

* Der Seitenname _Erlebnisdetails_ für die Feed-Platzierung gibt jetzt den Facebook- oder Instagram-Feed an. (festgelegt am 16.8.2016)

* Das Zuschneiden größerer Bilder und Videos ist jetzt konsistent, wenn der Benutzer von der Ansicht _Asset-Übersicht_ zur Ansicht _Asset-Detail_ navigiert. (festgelegt am 16.8.2016)

* Die Anzahl der Suchergebnisse des Bildschirms &quot;Attribute&quot;zeigt nicht mehr &quot;`0 of`&quot;an, bevor sich ein Benutzer anmeldet. (Korrektur am 16.8.2016) <!-- GS-3665 -->

* Wenn Sie auf das Zählerfeld **[!UICONTROL [!DNL Insights]]** > **[!UICONTROL Asset]** klicken, werden die Such- und Filtereinstellungen nicht mehr gelöscht. (Korrektur am 16.8.2016) <!-- GS-3476 -->

* GenStudio zeigt einen Fehler an, wenn ein Benutzer versucht, Anmeldeinformationen in der [!DNL Insights]-Ansicht einzugeben. (Korrektur am 29.8.19) <!-- GS-4689 -->

* Das Hochladen von Markenrichtlinien schlägt aufgrund von Problemen mit der AKP-Speicherplattform fehl. (Korrektur am 22.8.20) <!-- GS-4369 -->

* Im Dropdown-Menü Eingabeaufforderung [!DNL Brands] wird am Ende der Liste [!DNL Brands] bei der E-Mail-Erstellung ein Gewinner angezeigt. (Korrektur am 22.8.20) <!-- GS-4077 -->
