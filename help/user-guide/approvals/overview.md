---
title: Adobe GenStudio for Performance Marketing-Überprüfungen und -Genehmigungen
description: Erfahren Sie mehr über den Überprüfungs- und Genehmigungsprozess von GenStudio for Performance Marketing.
feature: Approval
exl-id: c83f47c0-e8ae-4c54-84b3-c50f67d6b3c2
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '683'
ht-degree: 0%

---

# Adobe GenStudio for Performance Marketing-Überprüfungen und -Genehmigungen

Der Überprüfungs- und Genehmigungs-Workflow stellt sicher, dass alle Beteiligten - von Kreativ-Teams bis hin zu Rechtsexperten - Kampagnen-Assets und -Erlebnisse, einschließlich generativer KI-generierter Marken-Assets, effizient überprüfen und genehmigen können.

## Vorteile [!DNL Review and Approval] Workflows

* **Unterstützung für robuste, iterative Erstellung generativer KI-Inhalte**. Das Erstellen und Bereitstellen von markenorientierten Inhalten in einer Organisation ist ein hochgradig iterativer Prozess. Die generativen KI-Funktionen von GenStudio for Performance Marketing unterstützen die schnelle Erstellung von Hunderten von Asset-Varianten. Jeder Validierungsverantwortliche kann vor der Validierung mehrere Änderungen an einem Asset-Entwurf anfordern. Je mehr Validierungsverantwortliche dies tun, desto größer ist die Anzahl potenzieller Iterationen, bevor sich alle Stakeholder auf eine endgültige Variante einigen.

* **Unterstützung für kreative Integrität**. Genehmigungen schützen die kreative Integrität Ihrer Marken-Assets, indem sie die Ersteller von Inhalten am Genehmigungsprozess beteiligen. Indem Sie kreative Stakeholder (z. B. Ersteller von Inhalten und Creative Directors) in den Prüfungs- und Genehmigungsprozess einbinden, stellen Sie sicher, dass die endgültige Ausgabe mit Ihrer Vision und Ihrer Markenidentität übereinstimmt.

* **Einhaltung der Kampagnenziele und rechtlichen Anforderungen**. Der Validierungsprozess hilft sicherzustellen, dass Inhalte die Kampagnenziele unterstützen. Es stellt sicher, dass alle Marketingmaterialien rechtlichen und regulatorischen Standards entsprechen, wodurch Risiken und potenzielle rechtliche Probleme minimiert werden.

## Lebenszyklus der Überprüfung und Genehmigung

Zu den wichtigsten Phasen des Überprüfungs- und Genehmigungs-Workflows gehören:

* [Prüfung und Genehmigung der von Ihnen erstellten Inhalte anfordern](./request-review.md)
* [Inhalt überprüfen und bearbeiten](./review-and-edit.md)
* [Inhalt genehmigen](./approve-content.md)
* [Publish-Inhalte](./publish-content.md)

## Wer kann eine Überprüfung oder Genehmigung von Inhalten anfordern?

Wenn Sie ein Asset oder Erlebnis erstellt haben, können Sie andere Personen in der Genehmigungskette Ihres Unternehmens bitten, Ihre Arbeit formell zu überprüfen und zu kommentieren. Obwohl jedes GenStudio for Performance Marketing-Organisationsmitglied einen Entwurf überprüfen kann, können nur bestimmte genehmigende Personen einen Entwurf kommentieren oder genehmigen.

## [!DNL Content] Entwürfe

_Entwürfe_ sind vorläufige Versionen von Assets oder Erlebnissen, die dem Überprüfungs- und Genehmigungsprozess nicht unterzogen wurden. Entwurfsstatus : Gibt an, wo sich der Entwurf im Prüfungs- und Genehmigungsprozess befindet. Jeder Entwurf wird durch eine eindeutige Entwurfs-ID identifiziert. Diese ID ist gültig, bis ein Entwurf genehmigt und in [!DNL Content] veröffentlicht wird. Kommentare und Genehmigungen für einen Entwurf einer Überprüfung sind mit dieser einzelnen Entwurfs-ID verknüpft.

Wenn ein Entwurf den Überprüfungs- und Genehmigungsprozess abschließt und in [!DNL Content] veröffentlicht wird, läuft die Entwurfs-ID ab, und GenStudio for Performance Marketing speichert die zugehörigen Kommentare und Genehmigungsstatus nicht. Die Entwurfs-URL ist nicht mehr gültig.

Entwurfsstatus Erfasst den Status des Inhaltsentwurfs, während er den Prüfungs- und Genehmigungsprozess durchläuft. Der GenStudio for Performance Marketing-Inhaltseditor, der das zu überprüfende Asset erstellt hat, wird über alle angeforderten Änderungen an den Entwürfen oder Genehmigungen benachrichtigt. Genehmigende Personen ändern den Entwurfsstatus, um anzugeben, ob ein Entwurf weiter überarbeitet werden muss oder genehmigt werden kann. Alle designierten genehmigenden Personen müssen ein Asset oder Erlebnis genehmigen, bevor es veröffentlicht werden kann.

Verfügbare Entwurfsstatus:

**Benachrichtigt**: Der Inhaltseditor hat den Prüfungs- und Genehmigungsprozess gestartet, indem er die genehmigenden Personen darüber informiert, dass ein Entwurf zur Überprüfung bereit ist.
**Muss bearbeitet**: Gibt an, dass mindestens eine genehmigende Person Änderungen am Inhaltsentwurf angefordert hat. Inhalte mit diesem Status können nicht in [!DNL Content] gespeichert werden.
**Genehmigt**: Alle designierten genehmigenden Personen haben das Asset oder Erlebnis genehmigt. Der Inhaltseditor kann dem Asset oder Erlebnis jetzt Metadaten hinzufügen und es in [!DNL Content] speichern.

## Benachrichtigungen

Produktinterne GenStudio for Performance Marketing-Benachrichtigungen aktualisieren genehmigende Personen und Inhaltseditoren in Echtzeit von Asset-Statusänderungen und `@mention`. Benachrichtigungen unterstützen eine schnelle Iteration durch die verschiedenen Überprüfungs-, Bearbeitungs- und Genehmigungszyklen.

Bearbeiter und genehmigende Personen können sich für den Erhalt dieser Benachrichtigungen auf Slack anmelden. Siehe [Abonnieren von Diensten auf Experience Cloud](https://experienceleague.adobe.com/en/docs/core-services/interface/features/account-preferences#slack).

Von den Genehmigungsteilnehmern durchgeführte Aktionen Trigger für automatische produktinterne Benachrichtigungen und E-Mail-Benachrichtigungen. Wenn Sie einen Genehmigungsprozess starten, erhalten designierte genehmigende Personen sowohl E-Mail- als auch produktinterne Benachrichtigungen. Sie werden mit Produkt- und E-Mail-Benachrichtigungen auf dem Laufenden gehalten, wenn eine genehmigende Person `@mention` Kommentare hinzufügt oder eine Entscheidung trifft. Benachrichtigungen enthalten Links zum Inhaltsentwurf.

Wenn Sie den Überprüfungs- und Genehmigungsprozess für Inhalte initiiert haben, werden Sie über alle Genehmigungen und Überprüfungskommentare benachrichtigt. Genehmigende Personen werden jedoch nur über Kommentare benachrichtigt, die sie mit einem `@mention` enthalten.
