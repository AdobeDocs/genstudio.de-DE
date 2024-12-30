---
title: Effektive Eingabeaufforderungen schreiben
description: Erfahren Sie, wie Sie effektive Prompts für Adobe GenStudio for Performance Marketing schreiben.
feature: Prompt, Generative AI, Brands Service, Personas Service, Products Service, Guidelines
exl-id: 0cd4db4f-d031-4c1f-a4e7-adc220f947fc
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '758'
ht-degree: 2%

---

# Effektive Eingabeaufforderungen schreiben

Die Kommunikation mit der generativen KI ist für eine effektive Arbeit in Adobe GenStudio for Performance Marketing unerlässlich.

GenStudio for Performance Marketing bietet jedes Mal, wenn die Möglichkeit besteht, ein Asset zu ändern, eine generative KI-Eingabeaufforderung. Die Komponenten einer effektiven Eingabeaufforderung sollten eine beschreibende Sprache, Beispiele und Informationen enthalten, die nicht durch Ihre konfigurierten Richtlinien bereitgestellt werden.

Geben Sie als Best Practice Ihre Markendaten mithilfe von [Richtlinien](/help/user-guide/guidelines/overview.md) an GenStudio for Performance Marketing weiter und Sie können dann die generative KI vollständig nutzen, um markenorientierte Inhaltserlebnisse zu erstellen.

## Beschreibende Sprache

Man kann natürliche Sprache benutzen, um seine Ideen zu artikulieren, um Erlebnisse zu schaffen. Ihre Eingabeaufforderung leitet die KI an, um personalisierte Kanalinhalte und Bilder zu generieren, die Ihre Vision ergänzen. Je mehr Details Sie angeben, desto größer ist die Chance, ein Bild oder Erlebnis zu erstellen, das Ihren Anforderungen entspricht. Verwenden Sie eine klare und beschreibende Sprache, um so viele Details wie möglich bereitzustellen:

- Verwenden **Bilder** Wörter, die Ambiente, Stimmung, Farbe, Komposition und Stil beschreiben.
- Verwenden Sie für **copy** Wörter, die die Zielgruppe, den Zweck, neue Funktionsbeschreibungen, Beispiele und Aktionen beschreiben.

Im Folgenden finden Sie eine Beispielaufforderung, die Informationen zu Ihrer Absicht, Zielgruppe und Ihrem Stil ausgibt.

```bash
Write an email to motivate infrequent users of Photoshop to follow an in-app tutorial that teaches them to combine elements of two photos into a beautiful work of art. Highlight the generative AI capabilities of Photoshop and use references to natural imagery.
```

+++Siehe Beispielergebnisse

![Drei generierte E-Mails](/help/assets/sample-email.png)

+++

## Prompt-Kriterien

In GenStudio for Performance Marketing [[!DNL Create]](/help/user-guide/create/overview.md) können Sie **[!UICONTROL Prompt-Kriterien]** ([_Parameter_](/help/user-guide/create/overview.md#parameters) und eine Eingabeaufforderung) im Eingabeaufforderungsbereich verwenden, um Details durch Auswahl hinzuzufügen und so die KI-Interpretation zu verbessern.

Bei [E](/help/user-guide/create/email-experiences.md)Mails) können die Eingabeaufforderungskriterien das Hinzufügen [Richtlinien](/help/user-guide/guidelines/overview.md) in _Parameter_, das Hochladen eines Assets zur Verwendung in den E-Mail-Varianten und eine beschreibende Eingabeaufforderung umfassen. Bei einer [Meta-Anzeige](/help/tutorials/create-meta-ad.md) können die Aufforderungskriterien eine Markenrichtlinie in _Parameter_, die Auswahl oder das Hochladen eines vorhandenen Assets, Einstellungen in Bezug auf Bilder oder Assets wie das Seitenverhältnis und eine Aufforderung umfassen. Die wahre Macht beginnt mit [Konfigurieren von Richtlinien](/help/user-guide/guidelines/add-guidelines.md).

>[!NOTE]
>
>Wenn Richtlinien unter _Parameter_ im Eingabeaufforderungsbereich hinzugefügt werden, müssen Sie in Ihrer Eingabeaufforderung keinen Verweis darauf einfügen. GenStudio for Performance Marketing nutzt diese [!DNL Brands], [!DNL Products] und [!DNL Personas] bei der Inhaltserstellung.

### Richtlinien

Die GenStudio for Performance Marketing-Richtlinien helfen der generativen KI bei der Personalisierung Ihrer Asset-Komposition. Bei einer Präsentation mit Eingabeaufforderungskriterien können Sie einen [[!DNL Brand]](/help/user-guide/guidelines/brands.md), ein [[!DNL Persona]](/help/user-guide/guidelines/personas.md) und einen [[!DNL Product]](/help/user-guide/guidelines/products.md) aus Ihren konfigurierten Richtlinien auswählen.

>[!TIP]
>
>Sie steuern, wie und wann GenStudio for Performance Marketing Ihre [!DNL Brand] Richtlinien verwendet. Unter [Richtlinien](/help/user-guide/guidelines/overview.md) erfahren Sie, wie Sie Ihre Markenrichtlinien konfigurieren und verwalten.

### Strukturierte Eingabeaufforderungen

Bei E-Mails mit mehreren Abschnitten können Sie Eingabeaufforderungen strukturieren, um abschnittsspezifische Anweisungen bereitzustellen, mit denen für jeden Abschnitt in einer E-[ variierender Inhalt generiert ](/help/user-guide/create/email-experiences.md). Strukturierte Eingabeaufforderungen sollten direkt auf [Abschnittsnamen in der E-Mail](/help/user-guide/content/email-template.md#multi-section-emails)Vorlage verweisen, damit der generierte Inhalt in die entsprechenden Platzhalter für Inhalte eingefügt werden kann.

Sie können beispielsweise GenStudio for Performance Marketing anweisen, im ersten Abschnitt einer E-Mail Inhalte zu generieren, die ein neues Produkt bewerben, und im zweiten E-Mail-Abschnitt Inhalte zu generieren, die die Kosteneinsparungen des Produkts detailliert beschreiben.

Die strukturierte Eingabeaufforderung sollte

- Verwenden Sie einen der folgenden Verweise auf den Abschnittsnamen in der E-Mail-Vorlage:
   - Pod
   - Gruppe
   - Abschnitt
   - Modul

  Wenn Ihre Vorlage beispielsweise `moduleA` oder `Group-3` als Abschnittsnamen verwendet, können Sie in der Eingabeaufforderung auf diese Abschnittsnamen verweisen.

- Befolgen Sie die empfohlenen Regeln/Strukturen. Wenn die Eingabeaufforderungsstruktur nicht dem angegebenen Format entspricht, gilt die Eingabeaufforderung für *alle* E-Mail-Abschnitte und erleichtert weiterhin die Inhaltserstellung.
- Verwenden Sie Abschnittsnamen wie [in Ihrer E-Mail-Vorlage definiert](/help/user-guide/content/email-template.md#code-an-email-template). Eingabeaufforderungsreferenzen müssen mit den in Ihrer E-Mail-Vorlage kodierten Abschnittsnamen übereinstimmen.
- Achten Sie nicht auf Groß- und Kleinschreibung. Sie können beispielsweise `Pod` oder `pod` in Ihrer E-Mail-Vorlage und in der strukturierten Eingabeaufforderung verwenden.
- Verweisen Sie zuerst auf die generische Benutzeraufforderung und dann auf die abschnittsspezifischen Anweisungen.
- Verwenden Sie einen Doppelpunkt, einen Bindestrich, ein Komma oder eine andere Abgrenzung (`,:;#$!~|@=-%&*^_`) als Trennzeichen zwischen dem Abschnittsnamen und der Referenz. Beispielsweise können Sie Folgendes als abschnittsspezifische Eingabeaufforderungsanweisung verwenden: `Pod1; Describe how to easily edit text and swap images.`

Im Folgenden finden Sie eine Beispielaufforderung, die die empfohlene Aufforderungsstruktur artikuliert und eine E-Mail-Vorlage nutzt, die den Identifizierungsbegriff `Pod` wie in `Pod1`, `Pod2` und `Pod3` verwendet.

```properties
Create an exciting multi-pod email focusing on Creative Cloud and its powerful generative AI capabilities.

Encourage customers to convert to Photoshop or use a free Photoshop trial. We want to better educate them about app features.

Pod1: Focus on Adobe Photoshop and its new generative AI tools that enable creators to bring images to life in minutes.

Pod2: Focus on Adobe Illustrator and its new generative AI tools, such as Generative Shape Fill, which allows you to quickly fill your vector outline and explore a variety of options that match the look and feel of your own artwork.

Pod3: Focus on Adobe Acrobat Pro. Make users aware that with Acrobat Pro they can edit images and text inside a PDF.
```

Siehe [Vorbereiten einer E-Mail-Vorlage](/help/user-guide/content/email-template.md#code-an-email-template).

## Erneut versuchen

Die Eingabeaufforderung ist ein iterativer Prozess. Wenn die Ergebnisse nicht Ihren Erwartungen entsprechen, überprüfen Sie Ihre Eingabeaufforderung und nehmen Sie einige Änderungen vor oder fügen Sie weitere Details hinzu. Sie können auch Abschnitte aus einer Kampagnenübersicht einfügen. Sie können GenStudio for Performance Marketing sogar auffordern, bestimmte Wörter, Elemente oder Designs zu vermeiden.

## Best Practices

Einige einfache Best Practices für die Erstellung effektiver Eingabeaufforderungen:

- Seien Sie spezifisch und geben Sie Details darüber an, was zu tun und nicht zu tun ist.
- Kontext mithilfe von externen Referenzen bereitstellen.
- GenStudio for Performance Marketing-Richtlinien nutzen.
- Richtlinien regelmäßig überprüfen und anpassen.
- Iterieren und verfeinern.
- Lerne durch Experimentieren.
