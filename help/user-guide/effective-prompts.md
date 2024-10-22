---
title: Effektive Eingabeaufforderungen schreiben
description: Erfahren Sie, wie Sie effektive Eingabeaufforderungen für Adobe GenStudio for Performance Marketing schreiben.
feature: Prompt, Generative AI, Brands Service, Personas Service, Products Service, Guidelines
exl-id: 0cd4db4f-d031-4c1f-a4e7-adc220f947fc
source-git-commit: 8fafd823d3d67cadfe095857723ba1e57e2a14fb
workflow-type: tm+mt
source-wordcount: '758'
ht-degree: 0%

---

# Effektive Eingabeaufforderungen schreiben

Die Kommunikation mit der generativen KI ist für eine effektive Arbeit in Adobe GenStudio for Performance Marketing unerlässlich.

GenStudio for Performance Marketing bietet eine generative KI-Eingabeaufforderung, sobald es möglich ist, ein Asset zu ändern. Die Komponenten einer effektiven Eingabeaufforderung sollten beschreibende Sprache, Beispiele und Informationen enthalten, die nicht über Ihre konfigurierten Richtlinien bereitgestellt werden.

Als Best Practice sollten Sie GenStudio for Performance Marketing mit [Richtlinien](/help/user-guide/guidelines/overview.md) mit Ihren Markeninformationen versorgen. Anschließend können Sie die generative KI vollständig nutzen, um markenorientierte Inhaltserlebnisse zu erstellen.

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

In GenStudio for Performance Marketing [[!DNL Create]](/help/user-guide/create/overview.md) können Sie im Eingabebereich **[!UICONTROL Eingabeaufforderungskriterien]** ([_Parameter_](/help/user-guide/create/overview.md#parameters) und eine Eingabeaufforderung) verwenden, um Details durch Auswahl hinzuzufügen und so die KI-Interpretation zu verbessern.

Bei [E-Mails](/help/user-guide/create/email-experiences.md) umfassen die Eingabeaufforderungskriterien möglicherweise das Hinzufügen von [guidelines](/help/user-guide/guidelines/overview.md) in _Parameter_, das Hochladen eines Assets zur Verwendung in den E-Mail-Varianten und eine beschreibende Eingabeaufforderung. Bei einer [Metaanzeige](/help/tutorials/create-meta-ad.md) umfassen die Eingabeaufforderungskriterien möglicherweise eine Markenrichtlinie in _Parameter_, die Auswahl oder den Upload eines vorhandenen Assets, Einstellungen im Zusammenhang mit Bildern oder Assets wie dem Seitenverhältnis und eine Eingabeaufforderung. Die tatsächliche Leistung beginnt mit [Konfigurieren von Führungslinien](/help/user-guide/guidelines/add-guidelines.md).

>[!NOTE]
>
>Wenn in _Parameter_ im Eingabeaufforderungsbereich Richtlinien hinzugefügt werden, müssen Sie in Ihrer Eingabeaufforderung keinen Verweis auf diese einfügen. GenStudio for Performance Marketing nutzt diese [!DNL Brands], [!DNL Products] und [!DNL Personas] bei der Inhaltserstellung.

### Richtlinien

GenStudio for Performance Marketing-Richtlinien helfen der generativen KI bei der Personalisierung Ihrer Asset-Komposition. Wenn Ihnen die Eingabeaufforderungskriterien angezeigt werden, können Sie eine [[!DNL Brand]](/help/user-guide/guidelines/brands.md), eine [[!DNL Persona]](/help/user-guide/guidelines/personas.md) und eine [[!DNL Product]](/help/user-guide/guidelines/products.md) aus Ihren konfigurierten Richtlinien auswählen.

>[!TIP]
>
>Sie steuern, wie und wann GenStudio for Performance Marketing Ihre [!DNL Brand] -Richtlinien verwendet. Informationen zum Konfigurieren und Verwalten Ihrer Markenrichtlinien finden Sie unter [Richtlinien](/help/user-guide/guidelines/overview.md) .

### Strukturierte Eingabeaufforderungen

Bei mehrteiligen E-Mails können Sie Aufforderungen strukturieren, um bereichsspezifische Anweisungen zur Generierung variierender Inhalte für jeden Bereich in einer [E-Mail](/help/user-guide/create/email-experiences.md) bereitzustellen. Strukturierte Eingabeaufforderungen sollten direkt auf [Abschnittsnamen in der E-Mail-Vorlage](/help/user-guide/content/email-template.md#multi-section-emails) verweisen, damit der generierte Inhalt in die entsprechenden Inhaltsplatzhalter eingefügt werden kann.

Beispielsweise können Sie GenStudio for Performance Marketing anweisen, Inhalte zu erstellen, die ein neues Produkt im ersten Teil einer E-Mail bewerben, und Inhalte zu generieren, die die kostensparenden Vorteile des Produkts im zweiten E-Mail-Abschnitt detailliert beschreiben.

Die strukturierte Eingabeaufforderung sollte:

- Verwenden Sie einen der folgenden Verweise auf den Abschnittsnamen in der E-Mail-Vorlage:
   - Pod
   - Gruppe
   - Abschnitt
   - Modul

  Wenn Ihre Vorlage beispielsweise `moduleA` oder `Group-3` als Abschnittsnamen verwendet, können Sie diese Abschnittsnamen in der Eingabeaufforderung referenzieren.

- Befolgen Sie die empfohlenen Regeln/Strukturen. Wenn die Eingabeaufforderungsstruktur nicht dem angegebenen Format entspricht, gilt die Eingabeaufforderung für die E-Mail-Abschnitte *Alle* und erleichtert weiterhin die Inhaltserstellung.
- Verwenden Sie die Abschnittsnamen als [definiert in Ihrer E-Mail-Vorlage](/help/user-guide/content/email-template.md#code-an-email-template). Die Eingabeaufforderungen müssen mit den Abschnittsnamen übereinstimmen, die in Ihrer E-Mail-Vorlage codiert sind.
- Beachten Sie nicht die Groß-/Kleinschreibung. Sie können beispielsweise `Pod` oder `pod` in Ihrer E-Mail-Vorlage und in der strukturierten Eingabeaufforderung verwenden.
- Verweisen Sie zuerst auf die generische Benutzeraufforderung und dann auf die bereichsspezifischen Anweisungen.
- Verwenden Sie einen Doppelpunkt, einen Bindestrich, ein Komma oder eine andere Abgrenzung (`,:;#$!~|@=-%&*^_`) als Trennung zwischen der Referenz zum Abschnittsnamen und der Anweisung. Beispielsweise können Sie Folgendes als eine bereichsspezifische Eingabeaufforderungsanweisung verwenden: `Pod1; Describe how to easily edit text and swap images.`

Im Folgenden finden Sie eine Beispielaufforderung, die die empfohlene Eingabeaufforderungsstruktur artikuliert und eine E-Mail-Vorlage verwendet, die den Identifizierungsbegriff `Pod` wie in `Pod1`, `Pod2` und `Pod3` verwendet.

```properties
Create an exciting multi-pod email focusing on Creative Cloud and its powerful generative AI capabilities.

Encourage customers to convert to Photoshop or use a free Photoshop trial. We want to better educate them about app features.

Pod1: Focus on Adobe Photoshop and its new generative AI tools that enable creators to bring images to life in minutes.

Pod2: Focus on Adobe Illustrator and its new generative AI tools, such as Generative Shape Fill, which allows you to quickly fill your vector outline and explore a variety of options that match the look and feel of your own artwork.

Pod3: Focus on Adobe Acrobat Pro. Make users aware that with Acrobat Pro they can edit images and text inside a PDF.
```

Siehe [Vorbereiten einer E-Mail-Vorlage](/help/user-guide/content/email-template.md#code-an-email-template).

## Erneut versuchen

Die Eingabeaufforderung ist ein iterativer Prozess. Wenn die Ergebnisse nicht Ihren Erwartungen entsprechen, überprüfen Sie Ihre Eingabeaufforderung und nehmen Sie einige Änderungen vor oder fügen Sie weitere Details hinzu. Sie können auch aus einer Kampagnenbeschreibung Abschnitte einfügen. Sie können sogar anfordern, dass GenStudio for Performance Marketing bestimmte Wörter, Elemente oder Designs vermeidet.

## Best Practices

Einige einfache Best Practices zum Erstellen effektiver Eingabeaufforderungen:

- Seien Sie spezifisch und geben Sie Details darüber an, was zu tun ist und was nicht.
- Stellen Sie Kontext mithilfe externer Verweise bereit.
- Nutzen Sie die GenStudio for Performance Marketing-Richtlinien.
- Die Richtlinien werden regelmäßig überprüft und angepasst.
- Iterieren und verfeinern Sie.
- Lernen Sie durch Experimente.
