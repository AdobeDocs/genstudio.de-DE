---
title: Adobe GenStudio for Performance Marketing-Überprüfungen und -Genehmigungen
description: Erfahren Sie mehr über die Überprüfung und Genehmigung von GenStudio for Performance Marketing.
feature: Approval
exl-id: c83f47c0-e8ae-4c54-84b3-c50f67d6b3c2
source-git-commit: bd3c5c9ff12c962d4123ac992fb74cd94e184172
workflow-type: tm+mt
source-wordcount: '683'
ht-degree: 0%

---

# Adobe GenStudio for Performance Marketing-Überprüfungen und -Genehmigungen

Der Arbeitsablauf für Überprüfungen und Genehmigungen stellt sicher, dass alle Interessengruppen - von Kreativteams bis hin zu Rechtsexperten - effizient Kampagnen-Assets und -Erlebnisse, einschließlich generativer KI-produzierter Marken-Assets, überprüfen und genehmigen können.

## [!DNL Review and Approval] Workflow-Vorteile

* **Unterstützung für die robuste, iterative Erstellung generativer KI-Inhalte**. Die Erstellung und Bereitstellung markenorientierter Inhalte in einer Organisation ist ein äußerst iterativer Prozess. Generative KI-Funktionen von GenStudio for Performance Marketing unterstützen die schnelle Erstellung von Hunderten von Asset-Varianten. Jeder Validierer kann mehrere Änderungen an einem Asset-Entwurf anfordern, bevor er ihn genehmigt. Je mehr Validierungsverantwortliche, desto größer ist die Anzahl möglicher Iterationen, bevor sich alle Beteiligten auf eine endgültige Variante einigen.

* **Unterstützung für kreative Integrität**. Genehmigungen schützen die kreative Integrität Ihrer Marken-Assets, indem sie die Ersteller von Inhalten am Genehmigungsprozess binden. Indem Sie kreative Akteure (z. B. Ersteller von Inhalten und kreative Regisseure) in den Review- und Genehmigungsprozess einbinden, stellen Sie sicher, dass die endgültige Ausgabe Ihrer Vision und Markenidentität entspricht.

* **Einhaltung der Campaign-Ziele und der gesetzlichen Anforderungen**. Der Validierungsprozess hilft zu überprüfen, ob der Inhalt Kampagnenziele unterstützt. Dadurch wird sichergestellt, dass alle Marketingmaterialien rechtlichen und regulatorischen Standards entsprechen, wodurch Risiken und mögliche rechtliche Probleme minimiert werden.

## Review- und Genehmigungslebenszyklus

Die wichtigsten Phasen des Prüfungs- und Genehmigungs-Workflows sind:

* [Überprüfung und Genehmigung des von Ihnen erstellten Inhalts anfordern](./request-review.md)
* [Inhalt überprüfen und bearbeiten](./review-and-edit.md)
* [Inhalt validieren](./approve-content.md)
* [Publish-Inhalte](./publish-content.md)

## Wer kann einen Review anfordern oder Inhalte genehmigen?

Wenn Sie ein Asset oder eine Erfahrung erstellt haben, können Sie andere Personen in der Genehmigungskette Ihres Unternehmens bitten, Ihre Arbeit förmlich zu überprüfen und zu kommentieren. Obwohl jedes GenStudio for Performance Marketing-Organisationsmitglied einen Entwurf überprüfen kann, können nur benannte Genehmiger einen Entwurf kommentieren oder genehmigen.

## Über [!DNL Content] Entwürfe

_Entwürfe_ sind vorläufige Versionen von Assets oder Erlebnissen, die nicht dem Überprüfungs- und Genehmigungsprozess unterzogen wurden. Der Entwurfsstatus gibt an, wo sich der Entwurf im Überprüfungs- und Genehmigungsprozess befindet. Eine eindeutige Entwurfs-ID identifiziert jeden Entwurf. Diese ID ist gültig, bis ein Entwurf genehmigt und in [!DNL Content] veröffentlicht wird. Überprüfungskommentare und -genehmigungen für einen Entwurf sind mit dieser individuellen Entwurfs-ID verknüpft.

Wenn ein Entwurf den Überprüfungs- und Genehmigungsprozess abgeschlossen und in [!DNL Content] veröffentlicht wird, läuft die Entwurfs-ID ab und GenStudio for Performance Marketing speichert die zugehörigen Kommentare und Genehmigungsstatus nicht. Die Entwurfs-URL ist nicht mehr gültig.

Der Entwurfsstatus erfasst den Status des Inhaltsentwurfs, während er sich durch den Überprüfungs- und Genehmigungsprozess bewegt. Der GenStudio for Performance Marketing-Inhaltseditor, der das zu überprüfende Asset erstellt hat, wird über alle angeforderten Änderungen am Entwurf bzw. an den Genehmigungen informiert. Genehmiger ändern den Entwurfsstatus, um anzugeben, ob ein Entwurf einer weiteren Überarbeitung bedarf oder genehmigt werden kann. Alle vorgesehenen Genehmiger müssen ein Asset oder Erlebnis genehmigen, bevor es veröffentlicht werden kann.

Verfügbare Entwurfsstatus:

**Benachrichtigungen**: Der Inhaltseditor hat den Überprüfungs- und Genehmigungsprozess gestartet, indem er die Genehmiger darüber informiert, dass ein Entwurf zur Überprüfung bereit ist.
**Erfordert Arbeit**: Gibt an, dass ein oder mehrere Genehmiger Änderungen am Inhaltsentwurf angefordert haben. Inhalte in diesem Status können nicht in [!DNL Content] gespeichert werden.
**Genehmigt**: Alle vorgesehenen Genehmiger haben das Asset oder Erlebnis genehmigt. Der Inhaltseditor kann dem Asset oder Erlebnis nun Metadaten hinzufügen und in [!DNL Content] speichern.

## Benachrichtigungen

Produktinterne GenStudio for Performance Marketing-Benachrichtigungen aktualisieren Genehmiger und Inhaltseditoren in Echtzeit von Asset-Statusänderungen und `@mention` Kommentaren. Benachrichtigungen unterstützen eine schnelle Iteration durch die verschiedenen Prüfungs-, Bearbeitungs- und Genehmigungszyklen.

Inhaltseditoren und Genehmiger können sich für den Empfang dieser Benachrichtigungen in Slack anmelden. Siehe [Dienstanmeldung unter Experience Cloud](https://experienceleague.adobe.com/en/docs/core-services/interface/features/account-preferences#slack).

Die von den Validierungsteilnehmern durchgeführten Aktionen Trigger für automatische In-Produkt-Benachrichtigungen und E-Mail-Benachrichtigungen. Wenn Sie einen Genehmigungsprozess starten, erhalten vorgesehene Genehmiger sowohl E-Mail- als auch In-Produkt-Benachrichtigungen. Sie werden mit In-Produkt- und E-Mail-Benachrichtigungen immer dann in der Schleife gehalten, wenn ein Genehmiger `@mention` Kommentare hinzufügt oder eine Entscheidung trifft. Benachrichtigungen enthalten Links zum Inhaltsentwurf.

Wenn Sie den Überprüfungs- und Genehmigungsprozess für Inhalte eingeleitet haben, werden Sie über alle Genehmigungen und Überprüfungskommentare informiert. Genehmiger werden jedoch nur über Kommentare benachrichtigt, die sie mit einem `@mention` einschließen.
