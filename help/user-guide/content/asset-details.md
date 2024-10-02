---
title: Asset-Details
description: Adobe GenStudio for Performance Marketing speichert genehmigte Inhalte mit Rich-Metadaten, um die Suche und das Performance-Tracking zu ermöglichen.
feature: Attributes, Assets
exl-id: 2be5cfee-f315-4ad6-8cf0-a8d3929b9ba3
source-git-commit: 059b464cb2a7b57557407bbaee6162b770107222
workflow-type: tm+mt
source-wordcount: '461'
ht-degree: 1%

---

# Asset-Details

Adobe GenStudio for Performance Marketing speichert genehmigte Inhalte mit Rich-Metadaten für die Erkennung und das Leistungstracking.

Jedes Asset (einschließlich Erlebnissen und Vorlagen) verfügt über zugewiesene _Details_ (Metadaten), die Ihnen helfen, die Inhaltsleistung zu identifizieren, zu verfolgen, zu verwenden und daraus zu lernen.

**So zeigen Sie Asset-Details an**:

1. Wählen Sie in _[!DNL Content]_ein Asset, Erlebnis oder eine Vorlage aus. Durch Klicken auf ein Asset wird eine fokussierte Ansicht des Assets geöffnet.

1. Überprüfen Sie in der Asset-Ansicht den Abschnitt _[!UICONTROL Details]_ auf der rechten Seite.

   >[!TIP]
   >
   >Wenn der Abschnitt _[!UICONTROL Details]_ nicht angezeigt wird, klicken Sie auf das Symbol **[!UICONTROL Informationen]** (i).

Asset-Details umfassen Metadaten, die während des Erstellungs- oder Upload-Prozesses angewendet werden. Asset-Metadatentypen umfassen [Systemmetadaten](#system-metadata) und [benutzerdefinierte Metadaten](#user-defined-metadata).

>[!NOTE]
>
>Assets aus AEM Repositorys zeigt unterschiedliche Metadaten an. Informationen zum Konfigurieren von [!DNL AEM Assets Content Hub] Asset-Details finden Sie unter [Konfigurieren der Asset-Sichtbarkeit](connect-aem-repo.md#step-4-configure-asset-visibility) .

## Systemmetadaten

Einige Asset-Metadaten werden beim Hochladen eines Assets automatisch erfasst. Sie können keine standardmäßigen Systemmetadaten bearbeiten.

Zu den Standardmetadaten, die für ein Asset gespeichert und erfasst werden, gehören der Name, die Dimensionen, die Quelle und mehr der Datei.

### Generierte Tags

Wenn Sie ein genehmigtes Asset in [!DNL Content] speichern, verwendet GenStudio for Performance Marketing Adobe AI- und maschinelles Lernen, um das Asset zu untersuchen und Tags anzuwenden, die auf den Asset-Funktionen basieren. Ein Bild einer Katze kann beispielsweise zu Attribut-Tags wie `pet photography` oder `cat` und Farb-Tags führen, die dominante Farben im Bild identifizieren. Tags können nicht bearbeitet werden.

Siehe [Insights-Attribute](/help/user-guide/insights/attributes.md).

### Generierte Inhaltsmetadaten

Die Informationen, die zum Generieren eines neuen Assets oder Erlebnisses verwendet werden, werden zu Metadaten, wie z. B. der verwendeten Eingabeaufforderung. Sie können die Eingabeaufforderung nach Genehmigung des Inhalts nicht mehr bearbeiten, sondern sie als Ausgangspunkt für die Generierung neuer Elemente verwenden.

## Benutzerdefinierte Metadaten

Benutzerdefinierte Metadaten fügen Marketingkontext zum Inhalt des Assets hinzu, sodass Marketing-Experten verstehen können, wie das Asset verwendet und genutzt werden kann.

Wenn Sie [ ein Asset hochladen](/help/user-guide/content/manage-assets.md#add-assets), können Sie einen Satz optionaler Asset-Details definieren, die in GenStudio for Performance Marketing als Metadaten vorhanden sind. Durch die Aufnahme weiterer Details kann die Asset-Identifizierung bei Suchvorgängen und Filtern verbessert werden.

### Metadatendetails

In der folgenden Tabelle sind die Metadaten (Asset-Details) aufgeführt, die Sie beim Erstellen eines Assets definieren können.

| Feld | Beschreibung |
| ------------- | ----------- |
| Kampagnen (Projektname) | Mit dem Asset erfasste und gespeicherte Standard-Metadaten |
| [!DNL Brands] | [[!DNL Brands]](/help/user-guide/guidelines/brands.md) wurde zu GenStudio for Performance Marketing hinzugefügt und zur Verwendung veröffentlicht |
| [!DNL Products] | [[!DNL Products]](/help/user-guide/guidelines/products.md) zur Verwendung zu GenStudio for Performance Marketing hinzugefügt |
| [!DNL Personas] | [[!DNL Personas]](/help/user-guide/guidelines/personas.md) zur Verwendung zu GenStudio for Performance Marketing hinzugefügt |
| Kanäle | Inhaltstypen in GenStudio for Performance Marketing, für die das Asset verwendet wird, z. B. E-Mail- und Metadatenanzeigen |
| Zeitrahmen | Zeitraum, für den das Asset verwendet wurde, z. B. Quartal, Saison, Jahr usw. Beispiel: `Winter 2023` |
| Region | Regionen, für die das Asset verwendet wird. Beispiele: `North America`, `APAC`, `Italy` |
| Sprache | Sprachen, für die das Asset verwendet wird. Beispiel: `Spanish` |
| Keywords | Schlüsselwörter, die zur weiteren Identifizierung von Asset-Eigenschaften und -Zweck verwendet werden |

<!-- ## History

Expand the _[!UICONTROL History]_ section to view a timeline of approvals and activity.

list other activity, show screenshot?
-->
