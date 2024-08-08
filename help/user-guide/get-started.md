---
title: Erste Schritte mit GenStudio
description: Erfahren Sie, wie Sie Ihre GenStudio einrichten, um neue markenorientierte Marketinginhalte zu generieren.
level: Beginner
feature: Prompt, Brands Service, Personas Service, Products Service, Generative AI, Guidelines
source-git-commit: c8fa0cf1633a5ca0ab94d9a0f33d9b7e7d6d61ed
workflow-type: tm+mt
source-wordcount: '1049'
ht-degree: 9%

---


# Erste Schritte mit GenStudio

GenStudio ist eine umfassende Plattform zum Erstellen, Auswerten und Verwalten von Marketing-Erlebnissen, die Ihre Markenidentität widerspiegeln und berücksichtigen.

Der Zugriff der Stakeholder auf die vielen Funktionen wird durch zugewiesene Benutzerrollen gesteuert. Ihre zugewiesene Benutzerrolle bestimmt die Aufgaben, die Sie in GenStudio ausführen können. Ein GenStudio-Administrator legt Ihre Berechtigungen fest, die in Ihrer Begrüßungs-E-Mail definiert sind.

Wenn Sie mit generativen KI-basierten Tools noch nicht vertraut sind oder sich lediglich für die Grundprinzipien von GenStudio interessieren, finden Sie weitere Informationen unter [GenStudio-Konzepte](concepts.md) und [Effektive Eingabeaufforderungen schreiben](effective-prompts.md).

## GenStudio-Benutzerrollen

Die Erstellung und Bereitstellung moderner Marketing-Kampagnen erfordert die Zusammenarbeit zwischen Interessenträgern mit unterschiedlichen Verantwortlichkeiten und Kenntnissen.

Drei Arten von GenStudio-Benutzerrollen unterstützen diese Vielfalt von Organisationsrollen. Berechtigungen sind auf jeden dieser Benutzertypen zugeschnitten und unterstützen die Verantwortlichkeiten der einzelnen Benutzer in der Marketing-Organisation.

**Die drei Benutzerrollentypen sind**:

* **Ersteller** verwenden die generativen KI-Funktionen von GenStudio, um Marketing-Kampagnen-Assets zu erstellen, Inhaltsüberprüfungen und -genehmigungen anzufordern und genehmigte Entwürfe dieses Inhalts zu veröffentlichen. Alle GensStudio-Benutzer können auf ein Asset zugreifen und es verwenden, nachdem es vom Ersteller im Inhalt gespeichert wurde.

* **Mitwirkende** sind der breiteste Bereich von GenStudio-Benutzern. Mitwirkende können GenStudio-Inhalte anzeigen und genehmigen. Dies ist ein wesentlicher Bestandteil des Workflows, der sicherstellt, dass von Ihnen generierte Inhalte den Anforderungen und Standards Ihres Unternehmens entsprechen.

* **Systemadministratoren** verfügen über die umfassendsten Berechtigungen in GenStudio. Systemadministratoren können Benutzer und Inhalte aus Genstudio hinzufügen und löschen. Administratoren führen die grundlegende Onboarding-Aufgabe aus, die darin besteht, die grundlegenden Limits für die Erstellung und Implementierung von Kampagnen-Assets zu definieren. Administratoren implementieren diese Limits, indem sie Marken- und organisationsspezifische Informationen wie [Markenrichtlinien](/help/user-guide/guidelines/overview.md) hochladen.

>[!NOTE]
>Bevor Benutzer in diese Rollen aufgenommen werden, muss ein Administrator in der Adobe Admin Console als Superuser benannt werden, um einmalige Einrichtungsaufgaben durchzuführen. Diese Superuser-Rolle funktioniert nur im Kontext der Adobe Admin Console. In der Benutzeroberfläche der GenStudio-Plattform spielt sie keine Rolle. Bei GenStudio-Rollenzuweisungen gibt es kein Superuser-Konzept.

### Ersteller

**Ersteller** verfügen über die Kernberechtigungen, die zum Erstellen von GenStudio [!DNL Brands]-, [!DNL Campaigns]- und [!DNL Content]-Assets erforderlich sind. Sie können auch von ihnen erstellte Assets bearbeiten und löschen. GenStudio unterstützt die schnelle Erstellung von Hunderten von Inhaltselementen. Diese Benutzer können Inhaltsfragmente oder ganze Erlebnisse generieren, die diskrete Teile genehmigter Inhalte orchestrieren, um die Anforderungen spezifischer Marketing-Kampagnen zu erfüllen.

Ersteller interagieren mit den generativen KI-Technologien von GenStudio über _Eingabeaufforderung_. Der Eingabeaufforderungsbereich von GenStudio auf der Arbeitsfläche bietet Tools zum Platzieren von Eingabeaufforderungen im Kontext der Richtlinien einer bestimmten Kampagne. Die Qualität und der Erfolg des erstellten Inhalts hängen daher teilweise von der Qualität der Markenrichtlinien ab, die Ihr Unternehmen hochgeladen hat, und von der Spezifität Ihrer Eingabeaufforderung.

Siehe [Effektive Eingabeaufforderungen schreiben](effective-prompts.md).

In der folgenden Tabelle sind die standardmäßigen GenStudio-Erstellungsberechtigungen aufgeführt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | nein | nein | nein | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | Nur Anzeigenverbindungen konfigurieren |    |     | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | ja | ja | ja | ja |

### Mitwirkende

**Mitwirkende** können Assets in GenStudio anzeigen, aber diese Assets nicht erstellen, bearbeiten oder löschen. Mitwirkende sind Akteure, die für den Erfolg des Überprüfungs- und Genehmigungsprozesses für GenStudio-Inhalte unerlässlich sind, aber keine Inhalte erstellen oder direkt bearbeiten müssen. Juristische Fachleute und Manager von Schöpfern sind Beispiele für potenzielle Mitwirkende. GenStudio-Mitwirkende sind möglicherweise berechtigt, Assets in anderen Creative Cloud-Produkten zu erstellen und anzuzeigen.

In der folgenden Tabelle sind die standardmäßigen GenStudio-Mitwirkerberechtigungen aufgeführt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | ja | ja | ja | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | nein | nein | nein | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | nein | nein | nein | ja |

### Administratoren

**Administratoren** erstellen und weisen Benutzer einer der von GenStudio unterstützten Rollen zu. Sie können einzelnen Erstellern oder Mitwirkenden bei Bedarf neue Berechtigungen zuweisen. Die wichtigste Aufgabe besteht darin, die ersten Onboarding-Aufgaben durchzuführen, die Ihr Unternehmen auf die Bereitstellung von GenStudio vorbereiten.

In der folgenden Tabelle sind die standardmäßigen Systemadministratorberechtigungen für GenStudio aufgeführt:

| Funktion | Erstellen | Update | Löschen | Anzeigen |
|-----------|----------------|----------------|----------------|----------------|
| [!DNL Brands] | ja | ja | ja | ja |
| [!DNL Campaigns] | ja | ja | ja | ja |
| [!DNL Content] | ja | ja | ja | ja |
| [!DNL Insights] | ja | ja | ja | ja |
| [!DNL Personas] | ja | ja | ja | ja |
| [!DNL Products] | ja | ja | ja | ja |
| [!DNL Reviews and approvals] | ja | ja | ja | ja |


## Vorbereiten von GenStudio zum Generieren von Inhalten

Systemadministratoren bereiten die GenStudio-Umgebung ihres Unternehmens für Ersteller und Mitwirkende vor, um Kampagnen-Assets zu erstellen. Zu diesen vorbereitenden Aufgaben gehören:

1. [Fügen Sie Führungslinien für [!DNL Brands], [!DNL Products] und [!DNL Personas] hinzu. ](./guidelines/overview.md) Die Einrichtung der wichtigsten Bausteine der Markenidentität Ihres Unternehmens ist eine wesentliche Voraussetzung für die Arbeit von GenStudio-Erstellern und -Mitarbeitern. Sie können entweder Markenrichtlinien-Dokumente hochladen oder manuell Markeninformationen eingeben.
   * **Bereiten Sie Ihre Führungslinien-Dokumente vor**. Je beschreibender und umfassender Ihre Markenrichtlinien sind, desto besser ist die Ausgabe von GenStudio. Binden Sie kurze Beispiele für Funktionen ein, die Sie für Ihre Marke als wesentlich erachten, und fügen Sie Verhaltensbeschreibungen hinzu, die Sie aus der Inhaltserstellung in GenStudio ausschließen möchten. GenStudio extrahiert Informationen aus diesen hochgeladenen Dokumenten und beginnt mit der Markenbildung. Informationen wie die Richtlinien zur Markensprache, zum Kanal und zu Bildern werden mit GenStudio gefüllt, das jede Richtlinie aus Ihren hochgeladenen Dokumenten zusammenstellt.
   * **Bearbeiten oder ergänzen Sie bei Bedarf die Felder der Markenrichtlinien**. Umfassende Markenrichtlinien bilden die Grundlage für das Verständnis der Marke Ihres Unternehmens durch GenStudio. Nachdem GenStudio die benötigten Informationen aus Ihren Markenrichtlinien-Dokumenten extrahiert hat, werden Sie aufgefordert, die extrahierten Informationsfelder manuell zu bearbeiten oder auszufüllen. Geben Sie die einzelnen Produktschwerpunktbereiche für die Inhaltserstellung an, indem Sie eine &quot;[!DNL Product]&quot;hinzufügen. [!DNL Personas] Richtlinien helfen bei der Erstellung von Inhalten für definierte Kundensegmente.

   Obwohl die Einrichtung der Markenrichtlinien eines Unternehmens eine einmalige Aktion sein kann, müssen Sie diese Richtlinien möglicherweise überarbeiten und verbessern, basierend auf der Volatilität, dem Wachstum und den sich ändernden Marktbedingungen Ihres Unternehmens.

1. **[Vorlagen hochladen](./content/use-templates.md)**. Vorlagen bieten Tastaturbefehle und beschleunigen die Inhaltserstellung. Eine Vorlage enthält genehmigte Funktionen wie Kopf- und Fußzeilen und legt Limits für die Inhaltserstellung fest. Administratoren laden in der Regel Vorlagen für ihre Organisation hoch und verwalten sie. Ersteller verwenden Vorlagen, um den Inhaltserstellungsprozess innerhalb der festgelegten Grenzen der Organisationsmarke zu starten.

1. **[Hochladen genehmigter Assets](./content/manage-assets.md)**. Genehmigte Assets in GenStudio [!DNL Content] stehen allen GenStudio-Erstellern zur Verfügung. Sie können [!DNL Content] mit Assets testen, die Ersteller zum Erstellen neuer Erlebnisse oder Assets verwenden können.

1. **[Verbindung zu einem Meta (Facebook)-Konto herstellen](./insights/connect-channel.md)**. Sie müssen eine Verbindung zwischen GenStudio und den Social-Konten Ihres Unternehmens konfigurieren, um Daten aus Ihren aktiven Marketing-Kampagnen, -Assets und -Erlebnissen zu erhalten. GenStudio [Insights](./insights/overview.md) bietet Tools zur Analyse kanalabgeleiteter Daten.
