---
title: Asset-Details
description: GenStudio speichert genehmigte Inhalte mit Rich-Metadaten, um die Suche und das Performance-Tracking zu ermöglichen.
feature: Attributes, Assets
source-git-commit: ba7dced9e62f797cd43a0bd8d8263828ec5c3d5e
workflow-type: tm+mt
source-wordcount: '405'
ht-degree: 7%

---


# Asset-Details

GenStudio speichert genehmigte Inhalte mit Rich-Metadaten für die Erkennung und das Leistungstracking.

Jedes Asset (einschließlich Erlebnissen und Vorlagen) verfügt über zugewiesene _Details_ (Metadaten), die Ihnen helfen, die Inhaltsleistung zu identifizieren, zu verfolgen, zu verwenden und daraus zu lernen.

Asset-Metadatentypen umfassen [Systemmetadaten](#system-metadata) und [benutzerdefinierte Metadaten](#user-defined-metadata).

## Systemmetadaten

Einige Asset-Metadaten werden beim Hochladen eines Assets automatisch erfasst. Sie können keine standardmäßigen Systemmetadaten bearbeiten.

Zu den Standardmetadaten, die für ein Asset gespeichert und erfasst werden, gehören der Name, die Dimensionen, die Quelle und mehr der Datei.

### Generierte Tags

Wenn Assets in [!DNL Content] genehmigt und gespeichert werden, verwendet GenStudio Adobe AI- und maschinelles Lernen, um Tags basierend auf den Asset-Funktionen wie Farbe und Ton oder Keywords zu generieren, die Asset-Funktionen identifizieren. Tags können nicht bearbeitet werden.

### Generierte Inhaltsmetadaten

Die Informationen, die zum Generieren eines neuen Assets oder Erlebnisses verwendet werden, werden zu Metadaten, wie z. B. der verwendeten Eingabeaufforderung. Sie können die Eingabeaufforderung nach Genehmigung des Inhalts nicht mehr bearbeiten, sondern sie als Ausgangspunkt für die Generierung neuer Elemente verwenden.

## Benutzerdefinierte Metadaten

Benutzerdefinierte Metadaten fügen Marketingkontext zum Inhalt des Assets hinzu, sodass Marketing-Experten die Verwendung und Interaktion des Assets besser verstehen können.

Wenn Sie [ ein Asset hochladen](/help/user-guide/content/manage-assets.md#add-assets), können Sie einen Satz optionaler Asset-Details definieren, die in GenStudio als Metadaten vorhanden sind.

### Metadatendetails

In der folgenden Tabelle werden die Metadaten (Asset-Details) aufgeführt, die Sie beim Erstellen eines Assets definieren können.

| Feld | Beschreibung | Bearbeitbar | Erforderlich |
| ------------- | ----------- | -------- | -------- |
| Kampagnenname (Projektname) | Mit Assets erfasste und gespeicherte Standard-Metadaten | J | N |
| Markenname | [[!DNL Brands]](/help/user-guide/guidelines/brands.md) wurde zu GenStudio hinzugefügt und zur Verwendung veröffentlicht | J | N |
| Produkte | [[!DNL Products]](/help/user-guide/guidelines/products.md) zur Verwendung zu GenStudio hinzugefügt | J | N |
| Personen | [[!DNL Personas]](/help/user-guide/guidelines/personas.md) zur Verwendung zu GenStudio hinzugefügt | J | N |
| Kanäle | Inhaltstypen in GenStudio, für die das Asset verwendet wird, z. B. E-Mail- und Metadatenanzeigen | J | N |
| Zeitrahmen | Zeitraum, für den das Asset verwendet wurde, z. B. Quartal, Saison, Jahr usw. Beispiel: `Winter 2023` | J | N |
| Region | Regionen, für die das Asset verwendet wird. Beispiele: `North America`, `APAC`, `Italy` | J | N |
| Sprache | Sprachen, für die das Asset verwendet wird. Beispiel: `Spanish` | J | N |
| Keywords | Schlüsselwörter zur Identifizierung des Asset-Zwecks | J | N |

## Asset-Details anzeigen

**So zeigen Sie Asset-Details an**:

1. Wählen Sie in _[!DNL Content]_ein Asset aus.

1. Überprüfen Sie in der Asset-Ansicht den Abschnitt _[!UICONTROL Details]_ auf der rechten Seite.

   Wenn der Abschnitt _[!UICONTROL Details]_ nicht angezeigt wird, klicken Sie auf das Symbol **[!UICONTROL Informationen]** (i).

>[!TIP]
>
>Sie können Asset-Details auch über [!DNL Insights] anzeigen. Insights bietet Nutzungsstatistiken und Leistungskontexte über Erlebnisse hinweg. Wählen Sie in _[!DNL Insights]_den Abschnitt **[!UICONTROL Assets]**aus.

<!-- ## History

Expand the _[!UICONTROL History]_ section to view a timeline of approvals and activity.

list other activity, show screenshot?
-->
