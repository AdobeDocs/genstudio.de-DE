---
title: Erste Schritte mit Adobe GenStudio für Performance Marketingexperten
description: Erfahren Sie, wie Sie Ihre GenStudio für Performance Marketingexperten einrichten, um neue markenorientierte Marketinginhalte zu generieren.
level: Beginner
feature: Prompt, Brands Service, Personas Service, Products Service, Generative AI, Guidelines
exl-id: bcb03198-bbcb-45ae-af01-25c1e834b563
source-git-commit: dab19da0063d6f4f4497112c4063bfc9c285e651
workflow-type: tm+mt
source-wordcount: '1106'
ht-degree: 8%

---

# Erste Schritte mit Adobe GenStudio für Performance Marketingexperten

GenStudio for Performance Marketers ist eine umfassende Plattform zum Erstellen, Auswerten und Verwalten von Marketing-Erlebnissen, die Ihre Markenidentität widerspiegeln und berücksichtigen.

Der Zugriff der Stakeholder auf die vielen Funktionen wird durch zugewiesene _Benutzerrollen_ gesteuert. Ihre zugewiesene Benutzerrolle bestimmt die Aufgaben, die Sie in GenStudio für Performance Marketingexperten ausführen können. Ein Adobe-Systemadministrator weist Ihre Berechtigungen im GenStudio für das Produktprofil &quot;Performance Marketers&quot;in der Adobe Admin Console zu. Ihre Begrüßungs-E-Mail identifiziert Ihre zugewiesene Rolle.

Wenn Sie mit generativen KI-basierten Tools noch nicht vertraut sind oder sich einfach nur für die Kernprinzipien von GenStudio für Performance Marketers interessieren, finden Sie weitere Informationen unter [Konzepte](concepts.md) und [Effektive Eingabeaufforderungen schreiben](effective-prompts.md).

## Benutzerrollen

Die Erstellung und Bereitstellung moderner Marketing-Kampagnen erfordert die Zusammenarbeit zwischen Interessenträgern mit unterschiedlichen Verantwortlichkeiten und Kenntnissen.

Diese Vielfalt von Organisationsrollen wird von drei Benutzerrollen unterstützt, die GenStudio für Performance Marketers bietet. Berechtigungen sind auf jeden dieser Benutzertypen zugeschnitten und unterstützen die Verantwortlichkeiten der einzelnen Benutzer in der Marketing-Organisation.

**Die drei Benutzerrollentypen sind**:

* **Bearbeiter** verwenden die generativen KI-Funktionen von GenStudio für Performance Marketers, um Marketing-Kampagnen-Assets zu erstellen, Inhaltsüberprüfung und -genehmigung anzufordern und genehmigte Entwürfe zu veröffentlichen. Alle GenStudio-Benutzer können auf ein Asset zugreifen und es verwenden, nachdem es vom Ersteller im Inhalt gespeichert wurde.

* **Mitwirkende** sind der breiteste Bereich von GenStudio für Performance Marketers-Benutzer. Mitwirkende können Inhalte anzeigen und genehmigen. Dies ist ein wesentlicher Bestandteil des Workflows, der sicherstellt, dass die von Ihnen generierten Inhalte den Anforderungen und Standards Ihres Unternehmens entsprechen.

* **Systemmanager** verfügen über die umfassendsten Berechtigungen innerhalb von GenStudio für Performance Marketers. Systemmanager führen die grundlegende Onboarding-Aufgabe durch, die darin besteht, die grundlegenden Limits für die Erstellung und Implementierung von Kampagnen-Assets zu definieren. Systemmanager implementieren diese Limits, indem sie Marken- und organisationsspezifische Informationen wie [Markenrichtlinien](/help/user-guide/guidelines/overview.md) hochladen. GenStudio-Systemmanager sind berechtigt, Marken zu erstellen und zu veröffentlichen, haben jedoch keine Benutzerverwaltungsberechtigungen.

>[!NOTE]
>Bevor Benutzer für diese Rollen bereitgestellt werden, muss in der Adobe Admin Console ein Adobe-Systemadministrator benannt werden, der die einmalige Einrichtung durchführt. Diese Adobe-Administratorrolle funktioniert nur im Kontext der Adobe Admin Console. In der Benutzeroberfläche der GenStudio für die Performance Marketers-Plattform ist sie nicht relevant.

### GenStudio-Editoren

**Bearbeiter** verfügen über die grundlegenden Berechtigungen, die zum Erstellen von GenStudio für Performance Marketers [!DNL Brands], [!DNL Campaigns] und [!DNL Content] -Assets erforderlich sind. Sie können auch von ihnen erstellte Assets bearbeiten und löschen. GenStudio for Performance Marketers unterstützt die schnelle Erstellung von Hunderten von Inhaltselementen. Diese Benutzer können Inhaltsabschnitte oder ganze Erlebnisse generieren, die diskrete Teile genehmigter Inhalte orchestrieren, um die Anforderungen spezifischer Marketing-Kampagnen zu erfüllen.

Bearbeiter interagieren mit GenStudio für die generativen KI-Technologien von Performance Marketers über _Eingabeaufforderung_. Der Eingabeaufforderungsbereich auf der Arbeitsfläche bietet Tools, um Eingabeaufforderungen im Kontext der Richtlinien einer bestimmten Kampagne zu platzieren. Die Qualität und der Erfolg des erstellten Inhalts hängen daher teilweise von der Qualität der Markenrichtlinien ab, die Ihr Unternehmen hochgeladen hat, und von der Spezifität Ihrer Eingabeaufforderung.

Siehe [Effektive Eingabeaufforderungen schreiben](effective-prompts.md).

In der folgenden Tabelle werden die standardmäßigen Editor-Berechtigungen angezeigt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | nein | nein | nein | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | Nur Anzeigenverbindungen konfigurieren |    |     | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | ja | ja | ja | ja |

### GenStudio-Mitarbeiter

**Mitwirkende** können Assets in GenStudio für Performance Marketers anzeigen, aber diese Assets nicht erstellen, bearbeiten oder löschen. Mitwirkende sind Akteure, die für den Erfolg des Überprüfungs- und Genehmigungsprozesses für Inhalte unerlässlich sind, aber keine Inhalte erstellen oder direkt bearbeiten müssen. Juristische Fachleute und Manager von Schöpfern sind Beispiele für potenzielle Mitwirkende. Mitwirkende von GenStudio for Performance Marketers können möglicherweise berechtigt sein, Assets in anderen Creative Cloud-Produkten zu erstellen und anzuzeigen.

In der folgenden Tabelle werden die Standardberechtigungen für Mitwirkende angezeigt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | nein | nein | nein | ja |
| [!DNL Campaigns] | nein | nein | nein | ja |
| [!DNL Content] | nein | nein | nein | ja |
| [!DNL Insights] | nein | nein | nein | ja |
| [!DNL Personas] | nein | nein | nein | ja |
| [!DNL Products] | nein | nein | nein | ja |
| [!DNL Reviews and approvals] | nein | nein | nein | ja |

### GenStudio-Systemmanager

**GenStudio-Systemmanager** führen die ersten Aufgaben aus, die Ihr Unternehmen auf die Bereitstellung von GenStudio für Performance Marketers vorbereiten.

In der folgenden Tabelle sind die standardmäßigen Systemverwaltungsberechtigungen für GenStudio aufgeführt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | ja | ja | ja | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | ja | ja | ja | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | ja | ja | ja | ja |


## Vorbereiten von GenStudio für Leistungs-Marketingexperten zum Generieren von Inhalten

GenStudio-Systemmanager bereiten die GenStudio-Umgebung ihres Unternehmens für Performance-Marketer für Redakteure und Mitwirkende vor, um Kampagnen-Assets zu erstellen. Zu diesen vorbereitenden Aufgaben gehören:

1. [Fügen Sie Führungslinien für [!DNL Brands], [!DNL Products] und [!DNL Personas] hinzu. ](./guidelines/overview.md) Die Einrichtung der Schlüsselbausteine der Markenidentität Ihrer Organisation ist eine wesentliche Voraussetzung für die Arbeit von Erstellern und Mitwirkenden. Sie können entweder Markenrichtlinien-Dokumente hochladen oder manuell Markeninformationen eingeben.
   * **Bereiten Sie Ihre Führungslinien-Dokumente vor**. Je beschreibender und umfassender Ihre Markenrichtlinien sind, desto besser ist die Ausgabe. Binden Sie kurze Beispiele für Funktionen ein, die Sie für Ihre Marke als wesentlich erachten, und fügen Sie Verhaltensbeschreibungen hinzu, die Sie von der Inhaltserstellung ausschließen möchten. GenStudio for Performance Marketers extrahiert Informationen aus diesen hochgeladenen Dokumenten und beginnt mit der Erstellung Ihrer Marke. Informationen wie die Richtlinien zur Markensprache, zum Kanal und zu Bildern werden ausgefüllt, da GenStudio for Performance Marketers jede Richtlinie aus Ihren hochgeladenen Dokumenten zusammenstellt.
   * **Bearbeiten oder ergänzen Sie bei Bedarf die Felder der Markenrichtlinien**. Umfassende Markenrichtlinien bilden die Grundlage für das Verständnis der Marke Ihres Unternehmens durch GenStudio für Performance Marketingexperten. Nachdem GenStudio for Performance Marketers die benötigten Informationen aus Ihren Markenrichtlinien-Dokumenten extrahiert hat, werden Sie aufgefordert, die extrahierten Informationsfelder manuell zu bearbeiten oder auszufüllen. Geben Sie die einzelnen Produktschwerpunktbereiche für die Inhaltserstellung an, indem Sie eine &quot;[!DNL Product]&quot;hinzufügen. [!DNL Personas] Richtlinien helfen bei der Erstellung von Inhalten für definierte Kundensegmente.

   Obwohl die Einrichtung der Markenrichtlinien eines Unternehmens eine einmalige Aktion sein kann, müssen Sie diese Richtlinien möglicherweise überarbeiten und verbessern, basierend auf der Volatilität, dem Wachstum und den sich ändernden Marktbedingungen Ihres Unternehmens.

1. **[Vorlagen hochladen](./content/use-templates.md)**. Vorlagen bieten Tastaturbefehle und beschleunigen die Inhaltserstellung. Eine Vorlage enthält genehmigte Funktionen wie Kopf- und Fußzeilen und legt Limits für die Inhaltserstellung fest. Systemmanager laden normalerweise Vorlagen für ihre Organisation hoch und verwalten sie. Ersteller verwenden Vorlagen, um den Inhaltserstellungsprozess innerhalb der festgelegten Grenzen der Organisationsmarke zu starten.

1. **[Hochladen genehmigter Assets](./content/manage-assets.md)**. Genehmigte Assets in [!DNL Content] stehen allen GenStudio für Ersteller von Performance Marketers zur Verfügung. Sie können [!DNL Content] mit Assets testen, die Ersteller zum Erstellen neuer Erlebnisse oder Assets verwenden können.

1. **[Verbindung zu einem Meta (Facebook)-Konto herstellen](./insights/connect-channel.md)**. Konfigurieren Sie eine Verbindung zwischen GenStudio for Performance Marketers und den Social-Konten Ihres Unternehmens, um Daten von Ihren aktiven Marketing-Kampagnen, -Assets und -Erlebnissen zu erhalten. [[!DNL Insights]](./insights/overview.md) bietet Tools zur Analyse von kanalabgeleiteten Daten.
