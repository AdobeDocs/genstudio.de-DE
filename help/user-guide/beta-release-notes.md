---
title: Versionshinweise zu Adobe GenStudio for Performance Marketing Beta
description: Erfahren Sie mehr über die neuesten Funktionen und Verbesserungen von Adobe GenStudio for Performance Marketing.
exl-id: 2ae60dcb-ac95-4ed4-bceb-84b396f7fa4e
source-git-commit: c95a99d4fa8030a35b7fe3690235102e1827422f
workflow-type: tm+mt
source-wordcount: '606'
ht-degree: 0%

---

# Versionshinweise zu Adobe GenStudio for Performance Marketing Beta

Diese Hinweise heben wichtige Fehlerbehebungen und Verbesserungen in Adobe GenStudio for Performance Marketing für die am 27. September endende Woche hervor.

## Neue Funktionen und Verbesserungen

* GenStudio kann jetzt Persona- und Produktinformationen aus einer hochgeladenen PDF extrahieren und entsprechende Felder ausfüllen. <!-- GS-3806 -->

* Benutzer können jetzt [!DNL Content] Assets und Erlebnisse nach dem Namen des Benutzers filtern, der das Asset hochgeladen hat. <!-- GS-1808 -->

* Der Meta-Anmeldefluss enthält jetzt die Schaltfläche **[!UICONTROL Aktualisieren]** , mit der Benutzer Popups während der Anmeldung entsperren können.

* Der Abschnitt [!DNL Additional details] wurde von der Detailseite [!DNL Persona] entfernt. <!-- GS-5133 5134 -->

* Der Abschnitt [!DNL Additional details] wurde auf der Detailseite [!DNL Products] in [!DNL Messaging preferences] umbenannt. <!-- GS-5133 5134 -->

* Der Seite _Erste Person hinzufügen_ wurde die Schaltfläche [!DNL Add persona] hinzugefügt. <!-- GS-5132 -->

## Bekannte Probleme

Die folgenden bekannten Probleme sind für die Lösung in der GenStudio for Performance Marketing GA-Version geplant.

* Vorlagen können hochgeladen, aber nicht angezeigt werden. **Problemumgehung**: Laden Sie ein Asset hoch, in dem das Feld **[!UICONTROL Kampagnen]** ausgefüllt ist. Laden Sie dann die Vorlage erneut hoch. <!-- GS-4815 5650-->

* Benutzer können nach der Größenanpassung keine Meta-Anzeigen manuell zuschneiden. <!-- GS-5871 -->

* Benutzer können neue [!DNL Campaign] aus [!DNL Content] Workflows erstellen. <!-- GS-5650 -->

* Benutzer müssen sich bei einem Kanal-Meta-Anzeigen-Konto zweimal anmelden, wenn sie auch bei Facebook angemeldet sind. Problemumgehung: Melden Sie sich von Facebook ab, bevor Sie sich bei einem Kanal-Meta-Anzeigenkonto anmelden. <!-- GS-3009 -->

### Weitere Verbesserungen und behobene Probleme

* Gelegentliche Latenzprobleme mit einigen [!DNL Create] Arbeitsflächenvorgängen wurden behoben. <!-- GS-5203 -->

* Benutzer müssen sich nicht mehr zweimal bei einem Kanal-Meta-Anzeigenkonto anmelden, wenn sie auch bei Facebook angemeldet sind. <!-- GS-4806 -->

* Die E-Mail-Generierung führt jetzt länger zu einer unvollständigen E-Mail. <!-- GS-5209 -->

* Beim Erstellen einer Kampagne im Vorlagen-Workflow werden jetzt Kennungen erwartungsgemäß gespeichert.  <!-- GS-4923 -->

* Der Multi-Repository-Selektor listet Repositorys jetzt in alphabetischer Reihenfolge auf. <!-- GS-5553 -->

* Probleme mit CSV-Exportdateiformaten für nicht englische Sprachen wurden behoben. <!-- GS-5141 -->

* Benutzer können jetzt auf die Schaltfläche [!DNL Create] _Zuletzt verwendete Arbeit_ Bereich **[!UICONTROL Alle Entwürfe anzeigen]** klicken, während Entwürfe geladen werden. Zuvor führte das Klicken auf diese Schaltfläche, bevor alle Entwürfe geladen wurden, dazu, dass nur wenige Entwürfe geladen wurden und die Schaltfläche **[!UICONTROL Alle Entwürfe anzeigen]** nicht mehr verfügbar war. <!-- GS-3938 -->

* Auf der Arbeitsfläche [!DNL Create] wird nun die Schaltfläche **[!UICONTROL Alle Entwürfe anzeigen]** wie erwartet angezeigt, wenn die Arbeitsfläche mehr als vier Entwürfe anzeigt. <!-- GS-5588 -->

* Die Suche funktioniert nun wie erwartet auf der Registerkarte _Attribute_ . <!-- GS-5658 -->

* Die Shimmer-Animation wird jetzt beim Laden der Erlebnisse korrekt skaliert. <!-- GS-5574 -->

* Miniaturansichten für mehrteilige E-Mails werden jetzt wie erwartet in [!DNL Content] <!-- GS-5258 --> gerendert.

* Es wurde ein Workfront-bezogenes Problem mit der Schaltfläche **[!UICONTROL Zur Genehmigung senden]** behoben. <!-- GS-5847 -->

* Fehlerkorrektur - In der Ansicht &quot;[!DNL Create] Zuletzt verwendete Arbeit&quot;treten jetzt keine Fehler mehr auf. <!-- GS-5589 -->

* Wenn Sie einen Suchbegriff eingeben, wird jetzt nur ein Suchaufruf wie erwartet ausgeführt.  <!-- GS-2999 -->

* Die Bilddarstellung von Meta-Anzeigengenerierten Bildern wurde nach dem Export korrigiert. <!-- GS-5749 -->

* Das Symbol &quot;`%`&quot;wird jetzt in den Gebietsschemata DEU, FRA und ESP korrekt dargestellt, wenn Benutzer E-Mail-Varianten in der Arbeitsfläche C[!DNL Create] vergrößern oder verkleinern. <!-- GS-5007 -->


#### Lokalisierung

Diese Version enthält Verbesserungen an der Lokalisierung in der gesamten Produktoberfläche, insbesondere in [!DNL Create]. Die folgenden Oberflächenkomponenten wurden lokalisiert: <!-- GS-5295 -->

* Alle Zeichenfolgen im Bereich _Eingabeaufforderung_ (Parametername, Optionsnamen im Dropdown-Menü und Platzhalteraufforderungstext) <!-- GS-5027 -->

* Alle Zeichenfolgen im Fenster _Größe ändern_ für generierte Metaanzeigen in [!DNL Create] <!-- GS-5035 -->

* Alle Zeichenfolgen im Bereich _Letzte Arbeit_ in [!DNL Create] <!-- GS-5037 -->

* Die Optionszeichenfolgen für Marken, Personas und Produkte im Eingabeaufforderungsbereich <!-- GS-5293 -->

* Die Zeichenfolge **Zoom , um sie an den Bildschirm** anzupassen, die während der E-Mail- und Metadaten-Anzeigengenerierung angezeigt wird <!-- GS-5063 -->

* Datums- und Uhrzeitformate, **Untitled Draft** -Zeichenfolge und Fehlermeldungen in E-Mail- und Meta-Anzeigennamen <!-- GS-5023 5022 5048-->

* Die Anzeigefenstern und Prozentzeichen (%) <!-- GS-4983 4984--> auf der Registerkarte [!DNL Content] _Assets_

* Das Prozentsymbol (%), das in der Clickthrough-Rate für Einblicke > Erlebnisse verwendet wird <!-- GS-4279 -->

* Fehlermeldung angezeigt, wenn bei der Erstellung von E-Mail- oder Metaanzeigen ein Systemfehler auftritt<!-- GS-5061 -->

* Dezimaltrennzeichen für den Satz &quot;Wortzahl pro Satz&quot;auf der Seite &quot;Insights-Erlebnisdetails&quot;<!-- GS-4986 -->

* Zeichenfolgen im Menü &quot;Exportieren&quot;für eine mit einer Vorlage generierte Metadaten-Anzeige. <!-- GS-5031 -->

