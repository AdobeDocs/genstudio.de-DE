---
title: Effektive Eingabeaufforderungen schreiben
description: Erfahren Sie, wie Sie effektive Eingabeaufforderungen für GenStudio schreiben.
feature: Prompt, Generative AI, Brands Service, Personas Service, Products Service, Guidelines
source-git-commit: 5e17996ee3a86cf664ee468d6b9cf178c8853992
workflow-type: tm+mt
source-wordcount: '483'
ht-degree: 0%

---


# Effektive Eingabeaufforderungen schreiben

Die Kommunikation mit der generativen KI ist für eine effektive Arbeit in GenStudio unerlässlich.

GenStudio bietet eine generative KI-Eingabeaufforderung, sobald es möglich ist, ein Asset zu ändern. Die Komponenten einer effektiven Eingabeaufforderung sollten beschreibende Sprache, Beispiele und Informationen enthalten, die nicht über Ihre konfigurierten Richtlinien bereitgestellt werden.

Als Best Practice sollten Sie GenStudio mit [Richtlinien](/help/user-guide/guidelines/overview.md) mit Ihren Markeninformationen versorgen. Anschließend können Sie die generative KI vollständig nutzen, um markenorientierte Inhaltserlebnisse zu erstellen.

## Beschreibende Sprache

Sie können die natürliche Sprache verwenden, um Ihre Ideen zu artikulieren und Erlebnisse zu schaffen. Ihre Eingabeaufforderung leitet die KI, um personalisierte Kanalinhalte und Bilder zu generieren, die Ihre Vision ergänzen. Je mehr Details Sie bereitstellen, desto größer ist die Chance, ein Bild oder Erlebnis zu erzeugen, das Ihren Anforderungen entspricht. Verwenden Sie eine klare und beschreibende Sprache, um so viele Details wie möglich bereitzustellen:

- Verwenden Sie für **Bilder** Wörter, die Ambiance, Stimmung, Farbe, Komposition und Stil beschreiben.
- Verwenden Sie für **copy** Wörter, die die Zielgruppe, den Zweck, die Beschreibung neuer Funktionen, Beispiele und Aktionen beschreiben.

Im Folgenden finden Sie eine Beispielaufforderung, die Informationen zu Ihrer Absicht, Zielgruppe und Ihrem Stil artikuliert.

```bash
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery.
```

+++ Beispielergebnisse anzeigen

![drei generierte E-Mails](/help/assets/sample-email.png)

+++

## Eingabekriterien

In GenStudio [[!DNL Create]](/help/user-guide/create/overview.md) können Sie im Eingabebereich **[!UICONTROL Eingabeaufforderungskriterien]** ([_Parameter_](/help/user-guide/create/overview.md#parameters) und eine Eingabeaufforderung) verwenden, um Details durch Auswahl hinzuzufügen und so die KI-Interpretation zu verbessern.

Bei [E-Mails](/help/tutorials/create-email-experience.md) umfassen die Eingabeaufforderungskriterien möglicherweise das Hinzufügen von [guidelines](/help/user-guide/guidelines/overview.md) in _Parameter_, das Hochladen eines Assets zur Verwendung in den E-Mail-Varianten und eine beschreibende Eingabeaufforderung. Bei einer [Metaanzeige](/help/tutorials/create-meta-ad.md) umfassen die Eingabeaufforderungskriterien möglicherweise eine Markenrichtlinie in _Parameter_, die Auswahl oder den Upload eines vorhandenen Assets, Einstellungen im Zusammenhang mit Bildern oder Assets wie dem Seitenverhältnis und eine Eingabeaufforderung. Der wahre Strom beginnt mit [Konfigurieren der GenStudio-Richtlinien](/help/user-guide/guidelines/add-guidelines.md).

>[!NOTE]
>
>Wenn in _Parameter_ im Eingabeaufforderungsbereich Richtlinien hinzugefügt werden, müssen Sie keine Verweise auf die in Ihrer Eingabeaufforderung einfügen. GenStudio nutzt diese [!DNL Brands], [!DNL Products] und [!DNL Personas] bei der Inhaltserstellung.

### Richtlinien

GenStudio-Richtlinien helfen der generativen KI bei der Personalisierung Ihrer GenStudio-Asset-Komposition. Wenn Ihnen die Eingabeaufforderungskriterien angezeigt werden, können Sie eine [[!DNL Brand]](/help/user-guide/guidelines/brands.md), eine [[!DNL Persona]](/help/user-guide/guidelines/personas.md) und eine [[!DNL Product]](/help/user-guide/guidelines/products.md) aus Ihren konfigurierten Richtlinien auswählen.

>[!TIP]
>
>Sie steuern, wie und wann GenStudio Ihre [!DNL Brand] -Richtlinien verwendet. Informationen zum Konfigurieren und Verwalten Ihrer Markenrichtlinien finden Sie unter [Richtlinien](/help/user-guide/guidelines/overview.md) .

## Erneut versuchen

Die Eingabeaufforderung ist ein iterativer Prozess. Wenn die Ergebnisse nicht Ihren Erwartungen entsprechen, überprüfen Sie Ihre Eingabeaufforderung und nehmen Sie einige Änderungen vor oder fügen Sie weitere Details hinzu. Sie können Ihre Eingabeaufforderung verfeinern, indem Sie eine URL als Beispiel oder Quelle für weitere Informationen angeben.

```bash
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery.

Use information from https://www.adobe.com/products/photoshop.html to inspire users with the latest features.
```

Sie können auch aus einer Kampagnenbeschreibung Abschnitte einfügen. Sie können sogar anfordern, dass GenStudio bestimmte Wörter, Elemente oder Designs vermeidet.

## Best Practices

Einige einfache Best Practices zum Erstellen effektiver Eingabeaufforderungen in GenStudio:

- Seien Sie spezifisch und geben Sie Details darüber an, was zu tun ist und was nicht.
- Stellen Sie Kontext mithilfe externer Verweise bereit.
- Nutzen Sie die GenStudio-Richtlinien.
- Die Richtlinien werden regelmäßig überprüft und angepasst.
- Iterieren und verfeinern Sie.
- Lernen Sie durch Experimente.
