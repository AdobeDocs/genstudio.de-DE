---
title: Erste Schritte mit Adobe GenStudio for Performance Marketing
description: Erfahren Sie, wie Sie GenStudio for Performance Marketing einrichten, um neue Marketing-Inhalte zu generieren, die auf Ihre Marken abgestimmt sind.
level: Beginner
feature: Prompt, Brands Service, Personas Service, Products Service, Generative AI, Guidelines
exl-id: bcb03198-bbcb-45ae-af01-25c1e834b563
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '1128'
ht-degree: 10%

---

# Erste Schritte mit Adobe GenStudio for Performance Marketing

Adobe GenStudio for Performance Marketing ist eine umfassende Plattform zur Erstellung, Bewertung und Verwaltung von Marketing-Erlebnissen, die Ihre Markenidentität widerspiegeln und berücksichtigen.

Der Zugriff der Stakeholder auf die vielen Funktionen wird durch zugewiesene _Benutzerrollen_ gesteuert. Die zugewiesene Benutzerrolle bestimmt die Aufgaben, die Sie in GenStudio for Performance Marketing ausführen können. Ein Adobe-Systemadministrator weist Ihre Berechtigungen im GenStudio for Performance Marketing-Produktprofil in der Adobe Admin Console zu. Ihre Begrüßungs-E-Mail identifiziert Ihre zugewiesene Rolle.

Wenn Sie mit generativen KI-basierten Tools noch nicht vertraut sind oder einfach nur neugierig auf die GenStudio for Performance Marketing-Kernprinzipien sind, finden Sie weitere Informationen unter [Konzepte](concepts.md) und [Effektive Eingabeaufforderungen schreiben](effective-prompts.md).

## Benutzerrollen

Das Erstellen und Bereitstellen moderner Marketing-Kampagnen erfordert die Zusammenarbeit von Stakeholdern mit unterschiedlichen Zuständigkeiten und Fähigkeiten.

Diese Vielfalt an organisatorischen Rollen wird durch drei Typen von GenStudio for Performance Marketing-Benutzerrollen unterstützt. Die Berechtigungen sind auf jeden dieser Benutzertypen zugeschnitten und unterstützen die Verantwortlichkeiten der einzelnen Benutzer in der Marketing-Organisation.

**Es gibt drei Typen von Benutzerrollen**:

* **Bearbeiter** Verwenden Sie die Funktionen der generativen KI von GenStudio for Performance Marketing, um Marketing-Kampagnen-Assets zu erstellen, die Inhaltsüberprüfung und -validierung anzufordern und genehmigte Entwürfe dieses Inhalts zu veröffentlichen. Alle GenStudio for Performance Marketing-Benutzer können auf ein Asset zugreifen und es verwenden, sobald es von seinem Ersteller im Inhalt gespeichert wurde.

* **Mitwirkende** sind die größte Auswahl an GenStudio for Performance Marketing-Benutzenden. Mitwirkende können Inhalte anzeigen und genehmigen und sind ein wesentlicher Teil des Workflows, der sicherstellt, dass die von Ihnen generierten Inhalte den Anforderungen und Standards Ihres Unternehmens entsprechen.

* **Systemmanager** verfügen über die umfassendsten Berechtigungen in GenStudio for Performance Marketing. Systemmanager führen die grundlegende Onboarding-Aufgabe aus, nämlich die Festlegung der grundlegenden Leitplanken für die Erstellung und Bereitstellung von Kampagnen-Assets. System-Manager setzen diese Schutzmechanismen um, indem sie marken- und organisationsspezifische Informationen wie z. B. [Markenrichtlinien) &#x200B;](/help/user-guide/guidelines/overview.md). GenStudio for Performance Marketing-System-Manager sind berechtigt, Marken zu erstellen und zu veröffentlichen, verfügen jedoch nicht über Administratorrechte.

>[!NOTE]
>Bevor Benutzende für diese Rollen bereitgestellt werden, muss in der Adobe Admin Console ein Adobe-Systemadministrator ernannt werden, um einmalige Einrichtungsaufgaben durchzuführen. Diese Adobe-Administratorrolle funktioniert nur im Kontext der Adobe Admin Console. In der Benutzeroberfläche der GenStudio for Performance Marketing-Plattform spielt sie keine Rolle.

### GenStudio for Performance Marketing-Editoren

**Bearbeiter** verfügen über die grundlegenden Berechtigungen, die zum Erstellen von GenStudio for Performance Marketing-[!DNL Brands], -[!DNL Campaigns] und -[!DNL Content] erforderlich sind. Sie können auch von ihnen erstellte Assets bearbeiten und löschen. GenStudio for Performance Marketing unterstützt die schnelle Erstellung von Hunderten von Inhalten. Diese Benutzer können Inhaltsabschnitte oder ganze Erlebnisse generieren, die einzelne Teile genehmigter Inhalte orchestrieren, um die Anforderungen bestimmter Marketing-Kampagnen zu erfüllen.

Editoren interagieren mit GenStudio for Performance Marketing-KI-Technologien für generative _über_. Der Eingabeaufforderungsbereich auf der Arbeitsfläche bietet Tools, um Eingabeaufforderungen im Kontext der Richtlinien einer bestimmten Kampagne zu platzieren. Daher hängen die Qualität und der Erfolg der generierten Inhalte teilweise von der Qualität der von Ihrem Unternehmen hochgeladenen Markenrichtlinien und der Spezifität Ihrer Eingabeaufforderung ab.

Siehe [Effektive Eingabeaufforderungen schreiben](effective-prompts.md).

In der folgenden Tabelle werden die standardmäßigen Editor-Berechtigungen angezeigt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | nein | nein | nein | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | Nur Anzeigenkonnektoren können konfiguriert werden |    |     | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | ja | ja | ja | ja |

### GenStudio for Performance Marketing-Mitarbeiter

**Mitwirkende** können Assets in GenStudio for Performance Marketing anzeigen, diese Assets jedoch nicht erstellen, bearbeiten oder löschen. Zu den Mitwirkenden gehören Stakeholder, die für den Erfolg des Überprüfungs- und Genehmigungsprozesses für Inhalte von entscheidender Bedeutung sind, aber keine Inhalte erstellen oder direkt bearbeiten müssen. Juristen und Manager von Erstellern sind Beispiele für potenzielle Mitarbeiter. Mitarbeiter von GenStudio for Performance Marketing sind möglicherweise berechtigt, Assets in anderen Creative Cloud-Produkten zu erstellen und anzuzeigen.

In der folgenden Tabelle werden die standardmäßigen Collaborator-Berechtigungen angezeigt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | nein | nein | nein | ja |
| [!DNL Campaigns] | nein | nein | nein | ja |
| [!DNL Content] | nein | nein | nein | ja |
| [!DNL Insights] | nein | nein | nein | ja |
| [!DNL Personas] | nein | nein | nein | ja |
| [!DNL Products] | nein | nein | nein | ja |
| [!DNL Reviews and approvals] | nein | nein | nein | ja |

### GenStudio for Performance Marketing-Systemmanager

**GenStudio-Systemmanager** Führen Sie die ersten Aufgaben aus, die Ihr Unternehmen auf die Bereitstellung von GenStudio for Performance Marketing vorbereiten.

In der folgenden Tabelle werden die standardmäßigen GenStudio for Performance Marketing System Manager-Berechtigungen angezeigt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | ja | ja | ja | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | ja | ja | ja | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | ja | ja | ja | ja |


## Vorbereiten von GenStudio for Performance Marketing zum Generieren von Inhalten

GenStudio for Performance Marketing-Systemmanager bereiten die GenStudio for Performance Marketing-Umgebung ihres Unternehmens für Bearbeiter und Mitarbeiter zum Erstellen von Kampagnen-Assets vor. Zu diesen vorbereitenden Einrichtungsaufgaben gehören:

1. [Richtlinien hinzufügen](./guidelines/overview.md) für [!DNL Brands], [!DNL Products] und [!DNL Personas]. Die Einrichtung der wichtigsten Bausteine für die Markenidentität Ihres Unternehmens ist eine wesentliche Voraussetzung für die Arbeit von Erstellern und Mitwirkenden. Sie können entweder Dokumente zu Markenrichtlinien hochladen oder Markeninformationen manuell eingeben.
   * **Bereiten Sie Ihre Richtlinien-Dokumente**. Je aussagekräftiger und umfassender Ihre Markenrichtlinien sind, desto besser ist der Output. Fügen Sie kurze Beispiele für Funktionen hinzu, die Sie für Ihre Marke als wesentlich erachten, und fügen Sie Beschreibungen von Verhaltensweisen hinzu, die Sie von der Inhaltserstellung ausschließen möchten. GenStudio for Performance Marketing extrahiert Informationen aus diesen hochgeladenen Dokumenten und beginnt mit der Erstellung Ihrer Marke. Informationen wie Markensprache, Kanal und Bildrichtlinien werden ausgefüllt, während GenStudio for Performance Marketing jede Richtlinie aus Ihren hochgeladenen Dokumenten zusammenstellt.
   * **Bearbeiten oder füllen Sie die Felder für die Markenrichtlinien nach Bedarf**. Umfassende Markenrichtlinien bilden die Grundlage für das Markenverständnis Ihres Unternehmens durch GenStudio for Performance Marketing. Nachdem GenStudio for Performance Marketing die benötigten Informationen aus den Dokumenten Ihrer Markenrichtlinien extrahiert hat, werden Sie aufgefordert, die Felder der extrahierten Informationen manuell zu bearbeiten oder auszufüllen. Geben Sie einzelne Produktfokusbereiche für die Inhaltserstellung an, indem Sie eine [!DNL Product] hinzufügen. [!DNL Personas] Richtlinien helfen bei der Anpassung der Inhaltserstellung an definierte Kundensegmente.

   Auch wenn das Einrichten der Markenrichtlinien einer Organisation eine einmalige Aktion sein kann, müssen Sie diese Richtlinien möglicherweise überarbeiten und verbessern, basierend auf der Volatilität, dem Wachstum und den sich ändernden Marktbedingungen Ihrer Organisation.

1. **[Hochladen von Vorlagen](./content/use-templates.md)**. Vorlagen bieten Tastaturbefehle und beschleunigen die Inhaltserstellung. Eine Vorlage enthält genehmigte Funktionen wie Kopf- und Fußzeilen und legt Schutzmaßnahmen für die Inhaltserstellung fest. System-Manager laden in der Regel Vorlagen für ihre Organisation hoch und verwalten diese. Ersteller verwenden Vorlagen, um den Prozess der Inhaltserstellung innerhalb der festgelegten Grenzen der Organisationsmarke zu beschleunigen.

1. **[Hochladen genehmigter Assets](./content/manage-assets.md)**. Genehmigte Assets in [!DNL Content] stehen allen GenStudio for Performance Marketing-Erstellern zur Verfügung. Sie können [!DNL Content] mit Assets testen, die Ersteller verwenden können, um neue Erlebnisse oder Assets zu erstellen.

1. **[Verbindung zu einem Meta-Konto (Facebook) herstellen](./insights/connect-channel.md)**. Konfigurieren Sie eine Verbindung zwischen GenStudio for Performance Marketing und den Social-Media-Konten Ihres Unternehmens, um Daten aus Ihren aktiven Marketing-Kampagnen, Assets und Erlebnissen zu erhalten. [[!DNL Insights]](./insights/overview.md) bietet Tools zum Analysieren von kanalabgeleiteten Daten.
