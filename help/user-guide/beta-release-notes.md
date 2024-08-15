---
title: Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen beim Adobe GenStudio.
source-git-commit: 382026b07e123a1e49813b766f69496f6a8f38eb
workflow-type: tm+mt
source-wordcount: '392'
ht-degree: 2%

---


# Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise

Diese Hinweise zeigen wichtige Adobe GenStudio-Fehlerbehebungen und Verbesserungen für die am 16. August endende Woche.

## Highlights

Die Entwicklung von GenStudio-Funktionen ist schnell und kontinuierlich. Zu den wichtigen neuen Funktionen gehören:

### Marke

Das Bedienfeld zur Validierung von Marken wurde erweitert, um das Benutzererlebnis zu verbessern, einschließlich der folgenden Änderungen:

* _Prozentsatzbasiertes Validierungsergebnis_: Bei der Markenvalidierung wird nun die Markenvalidierungsbewertung als Prozentsatz und nicht als Wert für Bestehen/Fehlschlagen angezeigt.

* _Aktualisierte Benutzeroberfläche zur Markenextraktion_: Die Markenextraktion zeigt jetzt den Abschluss des Extraktionsvorgangs als Prozentsatz an.

* _Inkrementelle Belastung der Marke während der Extraktion_: Die Markenrichtlinien werden jetzt schrittweise in die Benutzeroberfläche geladen.

* _Vereinfachung des Schemas &quot;Richtlinie kopieren&quot;_: Das Feld `unique attributes` und das Feld `frequent keywords` wurden aus dem Schema &quot;Richtlinie kopieren&quot;entfernt und vereinfachen so die Einrichtung der Richtlinie.

* _Bildgenerierung: Kategorieauswahl_: Benutzer können jetzt die Bildrichtlinien auswählen, die für die Bildregenerierung spezifisch sind.

### Erstellen

* **Erstellung von E-Mails mit mehreren Abschnitten**: Benutzer können jetzt E-Mails erstellen, die aus separaten Überschriften-, Bild-, Text- und CTA-Elementen bestehen.

* **Größe von Metadaten ändern**: Ersteller können die Größe von Meta-Anzeigenseitenverhältnissen ändern.

### Einblicke

* **Eingeschränkte Insights-Anmeldekonten**: Die Insights-Anmeldung unterstützt jetzt nur ein Konto pro Kunde.

## Verbesserungen und behobene Probleme

Diese Version umfasst die folgenden zusätzlichen Fehlerbehebungen.

### Einblicke

* Der Seitenname _Erlebnisdetails_ für die Feed-Platzierung gibt jetzt den Facebook- oder Instagram-Feed an.

* Das Zuschneiden größerer Bilder und Videos ist jetzt konsistent, wenn der Benutzer von der Ansicht _Asset-Übersicht_ zur Ansicht _Asset-Details_ navigiert.

* Die Anzahl der Suchergebnisse des Bildschirms &quot;Attribute&quot;zeigt nicht mehr &quot;`0 of`&quot;an, bevor sich ein Benutzer anmeldet. <!-- GS- 3665 -->

* Wenn Sie auf das Feld **[!UICONTROL Insight]** > **[!UICONTROL Asset]** count klicken, werden die Such- und Filtereinstellungen nicht mehr gelöscht. <!-- GS-3476 -->

## Bekannte Probleme

Die folgenden bekannten Probleme werden durch die GenStudio für Performance Marketers GA-Version behoben.

### Analyse

* Aktionen, die durch die Schaltflächen **[!UICONTROL Vorlagen hinzufügen]** und **[!UICONTROL Hochladen]** ausgelöst werden, werden derzeit nicht verfolgt. <!-- GS-3505 -->

### Marke

* Ein Ersteller kann eine Marke erfolgreich veröffentlichen, die Mitglieder der Organisation können die Marke jedoch nicht sehen. <!-- XI-2197 -->

### Erstellen

* Das Zuschneiden von Bildern in Meta-Anzeigen ist inkonsistent. <!-- GS-3739 -->

* Vorlagen, die aus mehreren Gruppen von Seitenelementen bestehen, schlagen bei der Markenvalidierung fehl. <!-- GS-4037 -->

### Einblicke

* Fehler wegen Zugriffsverweigerung treten mit dem `/admin/addOffer` -Endpunkt (Bereitstellungsdienst) auf. **8/12** aufgelöst. <!-- GS-4047 -->

* Die Werte **Ausgaben auf Kampagnenebene** sind nicht korrekt. Die Daten zwischen Facebook Ads Manager und dem Data Lake sind derzeit nicht konsistent. <!-- GS-3202 -->

### Überprüfungen und Genehmigungen

* Ersteller können Assets nach der Genehmigung ändern, bevor sie sie veröffentlichen. Genehmiger werden über diese Änderungen nicht benachrichtigt.