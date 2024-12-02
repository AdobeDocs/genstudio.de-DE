---
title: Herstellen einer Verbindung zu einem [!DNL AEM Assets Content Hub] Repository
description: Erfahren Sie, wie Sie Adobe GenStudio for Performance Marketing mit einem Adobe Experience Manager (AEM) [!DNL Content Hub] Repository verbinden und vorhandene genehmigte Inhalte nutzen.
level: Experienced
feature: Assets, Content
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---

# Herstellen einer Verbindung zu einem [!DNL AEM Assets Content Hub]-Repository

Wenn Sie Assets in Adobe Experience Manager (AEM) haben, können Sie diese Schritte ausführen, um sie in GenStudio for Performance Marketing verfügbar zu machen.

>[!BEGINSHADEBOX]

**Voraussetzungen**:

Die folgenden Schritte erfordern Administratorzugriff auf Admin Console und AEM Assets as a Cloud Service.

>[!ENDSHADEBOX]

## Schritt 1: Aktivieren Sie [!DNL AEM Assets Content Hub]

Führen Sie den Self-Service-Prozess **Content Hub bereitstellen** aus, um [!DNL Content Hub] für Ihre vorhandene AEM Assets in Cloud Manager zu aktivieren. Siehe [Bereitstellen [!DNL Content Hub]](https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub) in der Dokumentation zu _AEM as a Cloud Service_.

Nachdem Sie [!DNL AEM Assets Content Hub] aktiviert haben, haben Sie eine neue Instanz mit dem Suffix `contenthub` innerhalb von [!DNL AEM Assets as a Cloud Service] auf der Admin Console.

## Schritt 2: Onboard GenStudio-Benutzer

Fügen Sie in der [!DNL Admin Console] GenStudio-Benutzer oder -Benutzergruppen zu den [!DNL AEM Assets Content Hub] -Produktprofilen hinzu. [!DNL AEM Assets Content Hub] -Benutzer können Assets anzeigen, aber keine Assets hinzufügen oder vorhandene Assets ändern.

- [Onboard [!DNL Content Hub] administrator](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-administrator)
- [Onboard [!DNL Content Hub] users](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-users)

## Schritt 3: Genehmigen von Assets

Genehmigen Sie Assets zur Verwendung in [!DNL AEM Assets Content Hub], wodurch sie in GenStudio for Performance Marketing verfügbar gemacht werden. Siehe [Genehmigen von Assets in Experience Manager](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/approve-assets) in der Dokumentation zu _AEM as a Cloud Service_ .

## Schritt 4: Konfigurieren der Asset-Sichtbarkeit

Überprüfen Sie in den Konfigurationsoptionen für _[!DNL AEM Assets Content Hub]_die einzelnen Konfigurationsoptionen für Filter, Asset-Details, Suche und Branding. Siehe [Konfigurieren der Content Hub-Benutzeroberfläche](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/configure-content-hub-ui-options) in der Dokumentation zu_ AEM as a Cloud Service _.

## Schritt 5: Verbindung überprüfen

In GenStudio for Performance Marketing Content ist die Liste _[!UICONTROL Position]_ rechts über der Galerie verfügbar. Die Liste ist nicht verfügbar, wenn Sie keinen Zugriff haben oder Ihr Unternehmen kein [!DNL AEM Assets Content Hub] -Repository bereitgestellt und verbunden hat.
