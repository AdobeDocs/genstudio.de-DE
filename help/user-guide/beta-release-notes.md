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

Diese Hinweise zeigen wichtige Fehlerbehebungen und Verbesserungen in Adobe GenStudio for Performance Marketing für die am 4. Oktober endende Woche an.

## Neue Funktionen und Verbesserungen

* Die Filterfunktion im gesamten Produkt wurde verbessert. Probleme mit der Filterung nach Alter und Geschlecht in [!DNL Insights] wurden behoben.  <!-- GS-1198 -->

* Sie können Bild-Assets (JPG oder PNG) direkt mit Adobe Express bearbeiten. Inhaltseditoren können die Arbeitsfläche _[!UICONTROL Powered by Adobe Expreß]_ verwenden, um Hintergründe zu entfernen, generative Füllungen anzuwenden, Effekte anzupassen und Bilder zu beschneiden, ohne GenStudio for Performance Marketing zu verlassen. <!-- GS-4615 -->

* Verbesserte Leistung beim progressiven Laden für generierte Varianten, generierte E-Mails und kontextbezogene Nachrichten. <!-- GS-4651 3062-->

* Inhaltseditoren können jetzt die Funktion zum Anpassen des Zuschnitts verwenden, um gerenderte Bilder in Varianten zu beschneiden. <!-- GS-2342 -->

* Probleme mit der Größenanpassung und Duplizierung von Vorlagen wurden behoben. <!-- GS-4895 -->

* Bei der Markenvalidierung wird nun die Ursache für Fehler erläutert, die während der Validierung auftreten.

* In der Vorlagenvorschau wird jetzt erwartungsgemäß On-Image-Text angezeigt. <!-- GS-5917 -->

## Weitere Verbesserungen und behobene Probleme

* Die Arbeitsfläche [!DNL Create] rendert jetzt benutzerdefinierte Schriftarten aus Vorlagen wie erwartet. <!-- GS-3415 -->

* Die richtige Schriftart wird jetzt beim Meta-Anzeigenexport angewendet. <!-- GS-5875 -->

* Probleme mit dem Vorlagen-Upload, die zu einem erfolgreichen Upload führten, aber zu einer mangelnden Sichtbarkeit in der Produktoberfläche führten, wurden behoben. <!-- GS-4815 5650-->

* Benutzer können nun nach der Größenanpassung Meta-Anzeigen manuell zuschneiden. <!-- GS-5871 -->

* Benutzer müssen sich nicht mehr zweimal bei einem Kanal-Meta-Anzeigenkonto anmelden, wenn sie auch bei Facebook angemeldet sind. <!-- GS-3009 -->

* Die Leinwandansicht von Assets und Erlebnissen bleibt jetzt im gesamten Inhaltserstellungs-, Review- und Genehmigungsprozess konsistent. <!-- GS-5877 -->

* Auf der Arbeitsfläche werden jetzt nur vier Varianten angezeigt, wenn nach einer Größenanpassung eine Neuerstellung erfolgt. <!-- GS-5869 -->

* Browserbasierte Rechtschreibprüfung funktioniert jetzt wie erwartet auf der Arbeitsfläche [!DNL Create] . <!-- GS-5760 -->

* Display-Anzeigen werden jetzt als PNG-Dateien exportiert, wenn **[!UICONTROL Als PNG exportieren]** ausgewählt ist. Bisher wurden Display-Anzeigen als JPEG exportiert, wenn das PNG-Format ausgewählt wurde. <!-- GS-5545 -->

* Der Abstand zwischen der Schaltfläche **[!UICONTROL Manuelles Zuschneiden]** und der Schaltfläche **[!UICONTROL Erzeugen]** wurde erhöht. Zuvor war die Schaltfläche **[!UICONTROL Manuelles Zuschneiden]** teilweise verdeckt. <!-- GS-6084 -->

* In der Vorlagenvorschau werden jetzt Google-Schriftarten wie erwartet angezeigt. <!-- GS-5946 -->

* Importierte TypeKit- und Google-Schriftarten werden jetzt beim Export erwartungsgemäß geladen. <!-- GS-5948 -->

* Es wurden Probleme beim Generieren von Inhalten mit benutzerdefinierten Vorlagen behoben. Wenn ein Inhaltseditor zuvor versucht hat, ein Asset mit einer benutzerdefinierten Vorlage zu generieren, wurde das Popup zur Generierung nicht angezeigt und die Konsole zeigte Fehler an. <!-- GS-5262 -->

* Die Entwurfsarbeitsfläche von DisplayAds behält jetzt ihre Position bei, wenn ein Benutzer mit der rechten Maustaste auf die Arbeitsfläche klickt, bevor er mit der linken Maustaste aus dem Kontextmenü klickt. Zuvor wurde die Arbeitsfläche verschoben, als der Benutzer auf die linke Maustaste klickte, wodurch der Inhalt des Entwurfs teilweise unzugänglich wurde.  <!-- GS-5687 -->

* Das Laden von Schimmer-Effekten bleibt so lange bestehen, bis die Bildregeneration abgeschlossen ist.  <!-- GS-5811 -->

* Bewertungen der Markenvalidierung werden nicht mehr ungültig gemacht, nachdem ein Benutzer Änderungen an generierten E-Mail-, Meta-Anzeigen oder Display-Anzeigen vorgenommen hat. Zuvor war dieser Punktstand ausgeblendet. <!-- GS-5379 -->

* Vorlagen mit CSS-Stilen, die an ihr `body` -Element angehängt sind, werden jetzt beim Export von Erlebnissen erwartungsgemäß genutzt. <!-- GS-5947 -->

* Es wurden Probleme beim manuellen Zuschneiden großer Dimensionsbilder behoben. <!-- GS-6039 -->

* Es wird jetzt nur eine Popup-Meldung angezeigt, wenn ein Benutzer ein neues Asset in [!DNL Content] <!-- GS-5020 --> hinzufügt.

* Verbesserte Leistung der Arbeitsfläche bei der Textbearbeitung.  <!-- GS-5118 -->

* Es wurden fehlende Leerzeichen zwischen Zeichenfolgen in der [!DNL Create] E-Mail- oder Meta-Anzeigenarbeitsfläche hinzugefügt. <!-- GS-5019 -->

* Bearbeiter können jetzt eine Datei mit Namen speichern, die Sonderzeichen enthalten, nachdem sie sie in Express bearbeitet haben. <!-- GS-6131 -->

### Lokalisierung

Diese Version enthält Verbesserungen der Lokalisierung in der gesamten Produktoberfläche, einschließlich der folgenden Oberflächenbereiche:

* Die URL für das Optionsziel **[!UICONTROL Mehr erfahren]** im Eingabeaufforderungsmenü von [!DNL Create]. <!-- GS-5029 -->

* Zahlenformate neben den Sucheingabefeldern [!DNL Insights] > [!DNL Experience]. <!-- GS-4494 -->

## Bekanntes Problem

* Regenerierte E-Mail-Fragmente werden nach der Auswahl nicht in der Variante angezeigt. (Varianten werden jedoch nach dem erneuten Öffnen des Entwurfs angezeigt.) <!-- GS-5913 -->