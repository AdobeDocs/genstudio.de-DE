---
title: Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen beim Adobe GenStudio.
source-git-commit: 5505e3fdc78e217dd1eb73ed5bffa5e43d4f3084
workflow-type: tm+mt
source-wordcount: '356'
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

### Einblicke

* Videos können nicht von _Assets_ abgespielt werden. <!-- GS-3846 -->

* Benutzer müssen sich zweimal anmelden, wenn sie auch bei Facebook angemeldet sind. **Problemumgehung**: Melden Sie sich vor der Anmeldung bei Insights von Facebook ab.

* Die Werte **Ausgaben auf Kampagnenebene** sind nicht korrekt. Die Daten zwischen Facebook Ads Manager und dem Data Lake sind derzeit nicht konsistent. <!-- GS-3202 -->

### Überprüfungen und Genehmigungen

* Ersteller können Assets nach der Genehmigung vor der Veröffentlichung ändern. Genehmiger werden über diese Änderungen nicht benachrichtigt.

