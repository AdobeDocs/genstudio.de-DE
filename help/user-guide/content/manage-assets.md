---
title: Verwalten von Assets und Erlebnissen
description: Vereinfachen und verbessern Sie die Verwaltung von markengeprüften Assets zur Verwendung und Wiederverwendung in Ihrer Digital-Marketing-Journey.
feature: Content, Assets, Experiences
exl-id: e2ce8797-6d3b-46d4-b12f-f5f80e26c669
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '786'
ht-degree: 0%

---

# Verwalten von Assets und Erlebnissen

Adobe GenStudio for Performance Marketing [!DNL Content] vereinfacht und verbessert die Verwaltung markengenehmigter Assets zur Verwendung und Wiederverwendung in Ihrer Digital-Marketing-Journey.

## Galerie Assets

In der [!UICONTROL Assets] Galerie wird ein Inventar der bestätigten Assets angezeigt. Mit dem Filtersymbol (Trichter) oberhalb der linken Seite der Tabelle wird das Menü **[!UICONTROL Filter]** geöffnet, in dem Sie aus vielen Kategorien auswählen können, um die in der Galerie angezeigten Assets zu filtern. Klicken Sie auf das Suchsymbol (Lupe), um ein Keyword zum Suchen eines Assets zu verwenden.

Im Folgenden sehen Sie eine Suche nach dem Begriff `dog` in der Galerie [!UICONTROL Assets]:

![Assets-Ansicht mit Suche auf Hund](../../assets/content-assets.png)

### Assets-Speicherort

Standardmäßig werden Assets, die Sie [!DNL Content] über den [!DNL Create] oder durch Hochladen hinzufügen, im `GenStudio assets`-Repository gespeichert. Das `GenStudio assets`-Repository ist ein Lese-/Schreib-Repository in GenStudio for Performance Marketing. Das bedeutet, dass Sie Assets im `GenStudio assets`-Repository speichern, bearbeiten und löschen können.

Die **[!UICONTROL Standort]**-Liste über der Galerie auf der rechten Seite ermöglicht die Auswahl aus verbundenen Adobe Experience Manager (AEM) [!DNL Assets Content Hub] Repositorys. Wenn Sie ein AEM-Repository auswählen, zeigt die Galerie ein Inventar der Assets aus diesem Repository an, sodass Sie genehmigte Assets aus diesen Repositorys als Eingaben für die Inhaltserstellung nutzen können. Die Filteroptionen ändern sich entsprechend den in [!DNL AEM Assets Content Hub] konfigurierten Kategorien.

Das AEM-Repository ist schreibgeschützt, d. h. Sie können keine Entwürfe, neuen Assets oder Metadaten im AEM-Repository speichern. Alle Entwürfe und endgültigen Aktualisierungen für Assets, Erlebnisse und Vorlagen werden mit neuen [Systemmetadaten“ im `GenStudio assets`-Repository ](asset-details.md#system-metadata).

AEM Anleitungen [ Hinzufügen Ihres-Repositorys ](connect-aem-repo.md) GenStudio for Performance Marketing finden Sie unter „Verbinden eines [!DNL AEM Assets Content Hub]-Repositorys“.

## Verwaltung von Assets

In [!UICONTROL Content] können Marketing-Experten für Performance ihre digitalen Assets einfach speichern, abrufen und verwalten. Durch die Nutzung sowohl des `GenStudio assets`-Repositorys als auch der AEM-Repositorys können Benutzende sicherstellen, dass ihre Assets gut organisiert sind und für verschiedene Marketing-Kampagnen zugänglich sind. Dieser Ansatz mit mehreren Repositorys bietet Flexibilität und Kontrolle über die Asset-Nutzung in allen Umgebungen, sodass nur genehmigte und aktuelle Assets für die Marketing-Maßnahmen verwendet werden.

### Hinzufügen von Assets

Beim Hinzufügen von Assets zu [!DNL Content] werden diese standardmäßig im `GenStudio assets`-Repository gespeichert. Die Schaltfläche _[!UICONTROL Assets hinzufügen]_ ist nur verfügbar, wenn _[!UICONTROL Speicherort]_ das `GenStudio assets`-Repository ist.

![Standortfeld](../../assets/content-location.png){width="350" align="center"}

**Hinzufügen von Assets**:

1. Klicken Sie _[!DNL Content]_auf **[!UICONTROL Assets hinzufügen]**.

1. Legen Sie in _Ansicht „Genehmigte Assets hinzufügen_ eine oder mehrere Dateien im Ablagebereich ab. Optional können Sie mit „Durchsuchen“ aus lokalen Dateien **[!UICONTROL oder]** Dateien von Dropbox oder Microsoft OneDrive importieren.

1. Wählen Sie im _Details hinzufügen_ einen **[!UICONTROL Kampagnennamen]** oder geben Sie einen neuen Namen ein.

1. Um die Auffindbarkeit zu verbessern, fügen Sie optionale Details wie _Markenname_, _Personas_, _Region_ und _Keywords_ in den Abschnitt **Weitere Details** ein.

   Je mehr Details Sie angeben, desto zuverlässiger werden die Funktionen von GenStudio for Performance Marketing. Wählen Sie ein oder mehrere Details aus der Liste aus oder geben Sie gegebenenfalls ein neues ein, z. B. mit Schlüsselwörtern. Jedes hinzugefügte Detail wird unter der Liste angezeigt. Klicken Sie auf **`x`** , um ein Detail zu entfernen.

   Alle Details, die Sie hinzufügen, gelten für alle in dieser Aktion hinzugefügten Assets.

   Siehe [Metadatendetails](/help/user-guide/content/asset-details.md#system-metadata).

1. Klicken Sie **[!UICONTROL Assets hinzufügen]**.

1. Klicken Sie nach Abschluss des Asset-Uploads auf **Fertig**.

1. Um Ihre neu hochgeladenen Assets anzuzeigen, klicken Sie auf **[!UICONTROL Aktualisieren]** in der Benachrichtigung _Neue Assets verfügbar_ unten auf der Arbeitsfläche.

<!-- 
In the future, need guidance on template upload errors. For now, the UI just says error.
-->

### Durchsuchen von Inhalt

Die Filter- und Suchoberfläche ist schnell und reaktionsschnell und bietet ein produktives „Search-First“-Erlebnis. Jede [!DNL Content] bietet Filteroptionen, mit denen Sie Ihre Suche nach dem idealen Asset, Erlebnis oder einer Vorlage eingrenzen können. Für Assets und Erlebnisse können Sie eine Kampagne und bestimmte Richtlinien auswählen, z. B. für Inhalte, die für ein bestimmtes Produkt erstellt wurden.

Es gibt Filter, die auf [Keywords](asset-details.md#user-defined-metadata) und [Attributen](/help/user-guide/insights/attributes.md) basieren, um Suchergebnisse einzugrenzen. Vielleicht möchten Sie zum Beispiel ein Asset eines bestimmten Dateityps oder Betreffs suchen, um ein neues Erlebnis für Ihre Kampagne zu erstellen.

Bei der Suche nach _Erlebnissen_ können Sie den Filter **[!UICONTROL Erstellt von]** verwenden, um die Liste so einzuschränken, dass nur die von Ihnen oder einer bestimmten Person erstellten Erlebnisse angezeigt werden.

**So suchen Sie nach wiederzuverwendenden Inhalten**:

1. Wählen Sie in _[!DNL Content]_den Abschnitt **[!UICONTROL Assets]**aus.

1. Wählen Sie ein Asset-Repository aus der **[!UICONTROL Speicherort]**-Liste aus oder stellen Sie sicher, dass Sie das richtige Asset-Repository verwenden. `GenStudio assets` ist das Standard-Repository.

   >[!IMPORTANT]
   >
   >Die _Speicherort_-Liste ist nur verfügbar, wenn Sie [eine Verbindung zu einem AEM-Repository herstellen](connect-aem-repo.md).

1. Klicken Sie **[!UICONTROL Suche]** (Lupe), um ein Keyword oder eine Beschreibung einzugeben.

1. Grenzen Sie Ihre Suche ein, indem Sie eine Kategorie aus der Liste _[!UICONTROL Filter]_ auswählen. Wenn Sie beispielsweise nach einer PNG-Datei suchen, klicken Sie auf **[!UICONTROL Dateiformat]** und wählen Sie **PNG**.

   Je enger Sie Ihre Suche eingrenzen, desto weniger Filteroptionen stehen zur Verfügung. Klicken Sie auf **[!UICONTROL Alle löschen]**, um alle Filter zu entfernen.

1. Wählen Sie ein Asset für eine vollständige Ansicht und eine Liste mit Details aus.

   Klicken Sie **[!UICONTROL Herunterladen]** (Abwärtspfeil), um das Asset auf Ihrer lokalen Workstation zu verwenden.
