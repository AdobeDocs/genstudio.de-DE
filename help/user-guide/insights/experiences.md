---
title: Erlebnisse - Übersicht
description: Sehen Sie sich einen Überblick über Kundeninteraktion, Budget und Ausgaben für Erlebnisse und Asset-Leistung im Adobe GenStudio für Performance-Marketer an.
feature: Insights, Experiences
source-git-commit: ed0ddb10ee65c2691f8ecbfe23533508e9174bf9
workflow-type: tm+mt
source-wordcount: '708'
ht-degree: 0%

---


# Erlebnisse - Übersicht

Die Ansicht [!DNL Insights] _[!UICONTROL Erlebnisse]_ zeigt eine Liste von Anzeigen und Erlebnissen für das verbundene Kanal-Anzeigenkonto.

Die Tabelle [!UICONTROL Erlebnisse] ist nach [!UICONTROL Anzeigennamen] organisiert. Das Filtersymbol (Trichter) über der linken Seite der Tabelle öffnet das Menü **[!UICONTROL Filter]** , in dem Sie aus den Listen [!UICONTROL Konto] und [!UICONTROL Kampagne] auswählen können, um die Anzeigennamen in der Tabelle zu filtern.

![Erlebnisfilter und Tabelle](../../assets/insights-experiences-filter.png)

## Anzeigendetails

Wenn Sie einen Anzeigennamen auswählen, können Sie die Anzeigenleistungsmetriken und -attribute anzeigen, mit denen Sie die Metriken eines Erlebnisses basierend auf seiner Anzeigenplatzierung innerhalb eines bestimmten Datumsbereichs analysieren können.

Die Detailansicht enthält eine Metrik für die Gesamtanzeige mit `click-through rate`, `cost per click` und den Anteil des Budgets an der Anzeige mit `spent`. Da Anzeigen mehrere Platzierungen haben können, z. B. einen Feed oder ein Banner, können Sie für jede Anzeigenplatzierung eine Aufschlüsselung derselben Metriken sehen. Verwenden Sie die Links- und Rechtspfeile unter **[!UICONTROL Leistung durch Anzeigenplatzierung]** , um die Anzeigenplatzierungsmetriken zu durchlaufen.

![Anzeigendetails mit Metriken und Anzeigenplatzierungen](../../assets/insights-ad-details.png)

### Textattribute

Unter der Anzeigenvorschau befindet sich eine Liste mit [!UICONTROL Textattributen], die mit der Anzeige verknüpft sind. Wenn Assets und Erlebnisse in [!DNL Content] genehmigt und gespeichert werden, generiert GenStudio for Performance Marketers Tags basierend auf ihren inhärenten Funktionen. Weitere Informationen zu Systemmetadaten finden Sie unter [Asset-Details](../content/asset-details.md#system-metadata) .

### Anzeigenplatzierungen

Zum Zeitpunkt der Erstellung einer Kampagne mit Metaanzeigen haben Sie möglicherweise ausgewählt, wo Ihre Anzeigen basierend auf der Kampagne [Ziel](channels.md#objectives) ausgeführt werden sollen. Anzeigenplatzierungen erweitern die Reichweite der Zielgruppe für Ihre Anzeige.

GenStudio for Performance Marketers unterstützt Anzeigenformate wie Asset-Feeds, Link-Anzeigen sowie einzelne Bilder oder Videos. Im Folgenden finden Sie eine Liste der Anzeigenformate nach Plattform:

| Instagram | Facebook/Meta | Messenger | Zielgruppennetzwerk |
| --- | --- | --- | --- |
| Erkunden Sie die Startseite<br>Erkunden der Raster-Startseite<br>Feed<br>Rollen<br>Profil-Feed<br>Suche<br>Shop<br>Meldungen<br> | Business Explorer<br>Feed<br>In-Stream-Video<br>Marketplace<br>Reels<br>Reels Overlay<br>Rechts-Spalte<br>Suche<br>Meldungen<br>Video-Feeds<br>Anzeigen auf Facebook-Rollen | Posteingang<br>Meldungen | Nativ, Banner und Interstitial<br>Nativ<br>Belohntes Video |

## Metriken

Mit Insights-Metriken können Sie ermitteln, welche Erlebnisse zum Erfolg einer Kampagne beitragen und welche Anzeigenplatzierungen am effektivsten sind.

### Details zu Metriken

Die folgende Tabelle enthält Definitionen und Einblicke für wichtige digitale Marketingmetriken in der Ansicht [!UICONTROL Erlebnisse]. Jede Metrik enthält eine kurze Definition, da sie sich auf Anzeigennamen bezieht, wie die Metrik berechnet wird, und einen oder mehrere Einblicke, um deren Bedeutung und Auswirkung auf ein Erlebnis zu verstehen.

| Metrik | Definition | Insight |
| ---------------------- | ----------------------------- | -------------------------------- |
| **[!UICONTROL Kampagne]** | Eine Kampagne ist ein Satz von Erlebnissen und Anzeigen, die auf ein bestimmtes Ziel ausgerichtet sind. | |
| **[!UICONTROL Anzeigenplatzierungen]** | Zählung der Werbeanzeigen für die Anzeige oder das Erlebnis. | Anzeigenplatzierungen erhöhen die Reichweite der Zielgruppe. |
| **[!UICONTROL Assets]** | Die Anzahl der in der Anzeige oder im Erlebnis verwendeten Assets. | |
| **[!UICONTROL Impressionen]** | Impressionen werden jedes Mal gezählt, wenn Inhalt auf dem Bildschirm geladen wird, unabhängig von Interaktion oder Anzeige. | Eine hohe Impressionsanzahl kann auf eine breite Sichtbarkeit hinweisen. Für echte Leistungseinblicke sollten Sie jedoch andere Interaktionsmetriken berücksichtigen. |
| **[!UICONTROL Klicks]** | Anzahl der Interaktionen von Benutzern mit einem anklickbaren Element in einer Anzeige. Durch Klicken auf ein Seitenprofil oder ein Bild, eine Reaktion auf einen Beitrag, eine Freigabe oder Kommentare oder durch Anklicken können Medien auf den Vollbildmodus erweitert werden. | Eine hohe Klickanzahl weist auf starkes Interesse und Interaktion mit dem Inhalt hin, die effektiv sein können und die richtige Zielgruppe erreichen. |
| **[!UICONTROL CTR]** | Prozentsatz (%) der Benutzer, die auf eine Anzeige geklickt haben <br>**Berechnung**: `clicks` dividiert durch `impressions` | Eine hohe Clickthrough-Rate weist darauf hin, dass der Inhalt für die Zielgruppe in Messaging und Design hochgradig relevant und motivierend ist und effektiv auf die Interessen der Zielgruppe ausgerichtet ist. |
| **[!UICONTROL CPM]** | Leistungsmessung für Kosten ($) pro Tausend Anzeigenimpressionen.<br>**Berechnung**: Gesamtbetrag `spent` geteilt durch Reichweite, dann multipliziert mit 1000 | Ein niedriger Wert kann auf eine kostengünstige Sichtbarkeit hinweisen, insbesondere bei Kombination mit einer hohen Clickthrough-Rate. |
| **[!UICONTROL CPC]** | Durchschnittliche Kosten ($), die mit jedem Klick in einem Erlebnis verbunden sind.<br>**Berechnung**: Gesamtbetrag `spent` dividiert durch `clicks` | Niedrigere Durchschnittskosten können auf kosteneffiziente Anzeigenausgaben hinweisen, insbesondere im Vergleich zu einem Anstieg der Konversionen. |
| **[!UICONTROL Spend]** | Der Betrag, der in einem bestimmten Zeitraum aus dem Haushalt ausgegeben wurde. | Ein hoher Ausgabenbetrag in kurzer Zeit kann auf eine rasche Nutzung hindeuten, was zu einer frühzeitigen Erschöpfung der Ressourcen führen könnte. Verfolgen Sie den Ausgabenbetrag im Vergleich zu den wichtigsten Leistungsmetriken, um die Gesamtrendite zu überwachen. |
