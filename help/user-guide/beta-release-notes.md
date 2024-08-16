---
title: Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen des Adobe GenStudio für Performance Marketingexperten.
source-git-commit: cbae3aeb1b8282fb64f2a6405a7ad9e07a48dbbd
workflow-type: tm+mt
source-wordcount: '347'
ht-degree: 0%

---


# Adobe GenStudio für Performance Marketingexperten - Beta - Versionshinweise

Diese Hinweise zeigen wichtige Adobe GenStudio-Fehlerbehebungen und Verbesserungen für die am 16. August endende Woche.

## Highlights

Die Funktionsentwicklung ist schnell und kontinuierlich. Zu den wichtigen neuen Funktionen gehören:

### [!DNL Brands]

Das Validierungsbedienfeld [!DNL Brand] wurde erweitert, um das Benutzererlebnis zu verbessern, einschließlich der folgenden Änderungen:

* **Prozentsatzbasiertes Validierungsergebnis**: Bei der Markenvalidierung wird nun die Markenvalidierungsbewertung als Prozentsatz und nicht als Wert für Bestehen/Fehlschlagen angezeigt.

* **Aktualisierte Benutzeroberfläche zur Markenextraktion**: Die Markenextraktion zeigt jetzt den Abschluss des Extraktionsvorgangs als Prozentsatz an.

* **Inkrementelle Belastung der Marke während der Extraktion**: Die Markenrichtlinien werden jetzt schrittweise in die Benutzeroberfläche geladen.

* **Vereinfachung des Schemas &quot;Richtlinie kopieren&quot;**: Das Feld `unique attributes` und das Feld `frequent keywords` wurden aus dem Schema &quot;Richtlinie kopieren&quot;entfernt und vereinfachen so die Einrichtung der Richtlinie.

### [!DNL Create]

* **Erstellung von E-Mails mit mehreren Abschnitten**: Benutzer können jetzt E-Mails erstellen, die aus separaten Überschriften-, Bild-, Text- und CTA-Elementen bestehen.

* **Größe von Metadaten ändern**: Ersteller können die Größe von Meta-Anzeigenseitenverhältnissen ändern.

### [!DNL Insights]

* **Eingeschränkte Insights-Anmeldekonten**: Die Insights-Anmeldung unterstützt jetzt nur ein Konto pro Kunde.

## Verbesserungen und behobene Probleme

Diese Version umfasst die folgenden zusätzlichen Fehlerbehebungen.

### [!DNL Insights]

* Der Seitenname _Erlebnisdetails_ für die Feed-Platzierung gibt jetzt den Facebook- oder Instagram-Feed an.

* Das Zuschneiden größerer Bilder und Videos ist jetzt konsistent, wenn der Benutzer von der Ansicht _Asset-Übersicht_ zur Ansicht _Asset-Details_ navigiert.

* Die Anzahl der Suchergebnisse des Bildschirms &quot;Attribute&quot;zeigt nicht mehr &quot;`0 of`&quot;an, bevor sich ein Benutzer anmeldet. <!-- GS- 3665 -->

* Wenn Sie auf das Zählerfeld **[!UICONTROL [!DNL Insights]]** > **[!UICONTROL Asset]** klicken, werden die Such- und Filtereinstellungen nicht mehr gelöscht. <!-- GS-3476 -->

## Bekannte Probleme

Die folgenden bekannten Probleme werden durch die GenStudio für Performance Marketers GA-Version behoben.

### Analyse

* Aktionen, die durch die Schaltflächen **[!UICONTROL Vorlagen hinzufügen]** und **[!UICONTROL Hochladen]** ausgelöst werden, werden derzeit nicht verfolgt. <!-- GS-3505 -->

### [!DNL Insights]

* Videos können nicht von _Assets_ abgespielt werden. <!-- GS-3846 -->

* Benutzer müssen sich zweimal anmelden, wenn sie auch bei Facebook angemeldet sind. **Problemumgehung**: Melden Sie sich vor dem Anmelden bei [!DNL Insights] von Facebook ab.

* Die Werte **Ausgaben auf Kampagnenebene** sind nicht korrekt. Die Daten zwischen Facebook Ads Manager und dem Data Lake sind derzeit nicht konsistent. <!-- GS-3202 -->

### [!DNL Reviews and Approvals]

* Ersteller können Assets nach der Genehmigung vor der Veröffentlichung ändern. Genehmiger werden über diese Änderungen nicht benachrichtigt.

