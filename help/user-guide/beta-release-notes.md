---
title: Versionshinweise zu Adobe GenStudio for Performance Marketing Beta
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen von Adobe GenStudio for Performance Marketing.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '586'
ht-degree: 2%

---

# Versionshinweise zu Adobe GenStudio for Performance Marketing Beta

In diesen Hinweisen werden wichtige Adobe GenStudio for Performance Marketing-Fehlerbehebungen und -Verbesserungen für die Woche bis zum 4. Oktober beschrieben.

## Neue Funktionen und Verbesserungen

* Die Filterfunktion für das gesamte Produkt wurde verbessert. Probleme mit der Filterung nach Alter und Geschlecht in [!DNL Insights] wurden behoben.  <!-- GS-1198 -->

* Sie können Bild-Assets (JPG oder PNG) direkt mit dem Adobe Expreß bearbeiten. Inhaltseditoren können die Arbeitsfläche _[!UICONTROL Basierend auf Adobe Expreß]_ verwenden, um Hintergründe zu entfernen, generative Füllungen anzuwenden, Effekte anzupassen und Bilder zuzuschneiden, ohne GenStudio for Performance Marketing zu verlassen. <!-- GS-4615 -->

* Das Erlebnis des progressiven Ladens generierter Varianten, generierter E-Mails und kontextueller Nachrichten wurde verbessert. <!-- GS-4651 3062-->

* Inhaltseditoren können jetzt die Funktion zum Anpassen des Zuschnitts verwenden, um gerenderte Bilder in Varianten zuzuschneiden. <!-- GS-2342 -->

* Probleme mit dem Ändern der Größe und dem Duplizieren von Vorlagen wurden behoben. <!-- GS-4895 -->

* In der Markenvalidierung werden nun die Ursachen von Fehlern erläutert, die bei der Validierung auftreten.

* Vorlagenvorschauen zeigen jetzt erwartungsgemäß Text auf dem Bild an. <!-- GS-5917 -->

## Zusätzliche Verbesserungen und behobene Probleme

* Die [!DNL Create]-Arbeitsfläche rendert jetzt benutzerdefinierte Schriftarten aus Vorlagen wie erwartet. <!-- GS-3415 -->

* Die richtige Schriftart wird jetzt beim Meta-Anzeigenexport angewendet. <!-- GS-5875 -->

* Es wurden Probleme mit dem Vorlagen-Upload behoben, die zu einem erfolgreichen Upload, aber zu mangelnder Sichtbarkeit in der Produktoberfläche führten. <!-- GS-4815 5650-->

* Benutzende können Meta-Anzeigen jetzt manuell zuschneiden, nachdem sie ihre Größe geändert haben. <!-- GS-5871 -->

* Benutzende müssen sich nicht mehr zweimal bei einem Meta-Ads-Kanalkonto anmelden, wenn sie auch bei Facebook angemeldet sind. <!-- GS-3009 -->

* Die Arbeitsflächen-Ansicht von Assets und Erlebnissen bleibt jetzt über den Inhaltserstellungs-, Prüfungs- und Genehmigungsprozess hinweg konsistent. <!-- GS-5877 -->

* Auf der Arbeitsfläche werden jetzt beim Regenerieren nach einem Größenänderungsvorgang nur vier Varianten angezeigt. <!-- GS-5869 -->

* Die browserbasierte Rechtschreibprüfung funktioniert jetzt wie erwartet auf der [!DNL Create]. <!-- GS-5760 -->

* Display-Anzeigen werden jetzt als PNG-Dateien exportiert, wenn **[!UICONTROL Als PNG exportieren]** ausgewählt ist. Zuvor wurden Display-Anzeigen als JPEG exportiert, wenn das PNG-Format ausgewählt wurde. <!-- GS-5545 -->

* Der Abstand zwischen der Schaltfläche **[!UICONTROL Manuelles Zuschneiden]** und der Schaltfläche **[!UICONTROL Generieren]** wurde erhöht. Zuvor war die Schaltfläche **[!UICONTROL Manuelles Zuschneiden]** teilweise verdeckt. <!-- GS-6084 -->

* Vorlagenvorschauen zeigen jetzt Google-Schriftarten erwartungsgemäß an. <!-- GS-5946 -->

* Importierte TypeKit- und Google-Schriftarten werden jetzt beim Export erwartungsgemäß geladen. <!-- GS-5948 -->

* Es wurden Probleme beim Generieren von Inhalten mit benutzerdefinierten Vorlagen behoben. Zuvor wurde beim Versuch eines Inhaltseditors, ein Asset mit einer benutzerdefinierten Vorlage zu generieren, das Generierungs-Popup nicht angezeigt und in der Konsole wurden Fehler angezeigt. <!-- GS-5262 -->

* Die Entwurfsarbeitsfläche „DisplayAds“ behält jetzt ihre Position bei, wenn ein Benutzer mit der rechten Maustaste auf die Arbeitsfläche klickt, bevor er mit der linken Maustaste aus dem Kontextmenü klickt. Zuvor wurde die Arbeitsfläche verschoben, wenn der Benutzer mit der linken Maustaste darauf klickte, wodurch der Entwurfsinhalt teilweise unzugänglich wurde.  <!-- GS-5687 -->

* Das Laden von Schimmereffekten bleibt nun so lange bestehen, bis die Bildregenerierung abgeschlossen ist.  <!-- GS-5811 -->

* Markenvalidierungsergebnisse werden nicht mehr ungültig, nachdem ein Benutzer Änderungen an generierten E-Mails, Meta-Anzeigen oder Display-Anzeigen vorgenommen hat. Zuvor war diese Punktzahl ausgeblendet. <!-- GS-5379 -->

* Vorlagen, bei denen CSS-Stile an ihr `body` angehängt sind, werden jetzt beim Export von Erlebnissen wie erwartet genutzt. <!-- GS-5947 -->

* Es wurden Probleme beim manuellen Zuschneiden von großen Dimensionsbildern behoben. <!-- GS-6039 -->

* Wenn ein Benutzer ein neues Asset in [!DNL Content] hinzufügt, wird jetzt nur noch eine Popup-Meldung angezeigt. <!-- GS-5020 -->

* Verbesserte Leistung der Arbeitsfläche bei der Textbearbeitung.  <!-- GS-5118 -->

* Es wurden fehlende Leerzeichen zwischen Zeichenfolgen auf der Arbeitsfläche für [!DNL Create]-E-Mails oder Meta-Anzeigen hinzugefügt. <!-- GS-5019 -->

* Editoren können jetzt nach der Bearbeitung in Express eine Datei mit Namen speichern, die Sonderzeichen enthalten. <!-- GS-6131 -->

### Lokalisierung

Diese Version umfasst Verbesserungen bei der Lokalisierung in der gesamten -Produktoberfläche, einschließlich der folgenden Schnittstellenbereiche:

* Die URL für das Ziel **[!UICONTROL Weitere Informationen]** der Option im Menü [!DNL Create]. <!-- GS-5029 -->

* Zahlenformate, die an die Eingabefelder [!DNL Insights] > Suche [!DNL Experience] angrenzen. <!-- GS-4494 -->

## Bekanntes Problem

* Regenerierte E-Mail-Fragmente werden nach der Auswahl nicht mehr in der Variante angezeigt. (Nach dem erneuten Öffnen des Entwurfs werden jedoch Varianten angezeigt.) <!-- GS-5913 -->