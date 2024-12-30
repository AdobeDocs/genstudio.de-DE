---
title: Verbindung zu einem  [!DNL AEM Assets Content Hub] -Repository herstellen
description: Erfahren Sie, wie Sie Adobe GenStudio for Performance Marketing mit einem Adobe Experience Manager (AEM)- [!DNL Content Hub]  verbinden und vorhandene genehmigte Inhalte nutzen können.
level: Experienced
feature: Assets, Content
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '263'
ht-degree: 0%

---

# Herstellen einer Verbindung zu einem [!DNL AEM Assets Content Hub] Repository

Wenn Sie Assets in Adobe Experience Manager (AEM) haben, können Sie diese Schritte ausführen, um sie in GenStudio for Performance Marketing verfügbar zu machen.

>[!BEGINSHADEBOX]

**Voraussetzungen**:

Für die folgenden Schritte ist ein administrativer Zugriff auf Admin Console und AEM Assets as a Cloud Service erforderlich.

>[!ENDSHADEBOX]

## Schritt 1: [!DNL AEM Assets Content Hub] aktivieren

Befolgen Sie **Selbstbedienungsprozess &quot;Content Hub bereitstellen** um [!DNL Content Hub] für Ihre bestehende AEM Assets in Cloud Manager zu aktivieren. Siehe [Bereitstellen [!DNL Content Hub]](https://experienceleague.adobe.com/de/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub) in der Dokumentation zu _AEM as a Cloud Service_.

Nach der Aktivierung von [!DNL AEM Assets Content Hub] haben Sie eine neue Instanz mit dem `contenthub` Suffix in [!DNL AEM Assets as a Cloud Service] auf Admin Console.

## Schritt 2: Onboarding von GenStudio-Benutzern

Fügen Sie in der [!DNL Admin Console] GenStudio-Benutzende oder -Benutzergruppen zu den [!DNL AEM Assets Content Hub] Produktprofilen hinzu. [!DNL AEM Assets Content Hub] Benutzer können Assets anzeigen, aber keine Assets hinzufügen oder vorhandene Assets ändern.

- [Onboard [!DNL Content Hub] administrator](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-administrator)
- [Onboard [!DNL Content Hub] users](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/deploy-content-hub#onboard-content-hub-users)

## Schritt 3: Assets genehmigen

Genehmigen von Assets für die Verwendung in [!DNL AEM Assets Content Hub], wodurch sie in GenStudio for Performance Marketing verfügbar werden. Siehe [Genehmigen von Assets im Experience Manager AEM as a Cloud Services ](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/dynamicmedia/dynamic-media-open-apis/approve-assets) in der Dokumentation zu __.

## Schritt 4: Asset-Sichtbarkeit konfigurieren

Überprüfen Sie unter _[!DNL AEM Assets Content Hub]_Konfigurationsoptionen jeden Satz von Konfigurationsoptionen für Filter, Asset-Details, Suche und Branding. Siehe [Konfigurieren der Benutzeroberfläche von Content Hub](https://experienceleague.adobe.com/en/docs/experience-manager-cloud-service/content/assets/content-hub/configure-content-hub-ui-options) in der Dokumentation zu_ AEM as a Cloud Service _.

## Schritt 5: Verbindung überprüfen

Im GenStudio for Performance Marketing-Inhalt _[!UICONTROL die Liste]_ Speicherort“ über der Galerie auf der rechten Seite verfügbar. Die Liste ist nicht verfügbar, wenn Sie keinen Zugriff haben oder Ihre Organisation kein [!DNL AEM Assets Content Hub]-Repository bereitgestellt und verbunden hat.
