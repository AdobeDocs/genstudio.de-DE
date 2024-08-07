---
title: GenStudio-Überprüfungen und -Genehmigungen
description: Erfahren Sie mehr über die Überprüfung und Genehmigung von GenStudio.
feature: Approval
source-git-commit: c9bd8bf434e493696e674900f403307260a65b02
workflow-type: tm+mt
source-wordcount: '608'
ht-degree: 0%

---


# GenStudio-Überprüfungen und -Genehmigungen

Der Arbeitsablauf für Überprüfungen und Genehmigungen von GenStudio stellt sicher, dass alle Interessengruppen - von Kreativteams bis hin zu Rechtsexperten - Kampagnenkomponenten, einschließlich generativer KI-produzierter Marken-Assets, effizient überprüfen und genehmigen können.

## [!DNL Review and Approval] Workflow-Vorteile

* **Unterstützung für die robuste, iterative Erstellung generativer KI-Inhalte**. Die Erstellung und Bereitstellung markenorientierter Inhalte in einer Organisation ist ein äußerst iterativer Prozess. Die generativen KI-Funktionen von GenStudio unterstützen die schnelle Erstellung von Hunderten von Asset-Varianten. Jeder Validierer kann mehrere Änderungen an einem Asset-Entwurf anfordern, bevor er ihn genehmigt. Je mehr Validierungsverantwortliche, desto größer ist die Anzahl möglicher Iterationen, bevor sich alle Beteiligten auf eine endgültige Variante einigen.

* **Unterstützung für kreative Integrität**. Genehmigungen schützen die kreative Integrität Ihrer Marken-Assets, indem sie die Ersteller von Inhalten am Genehmigungsprozess binden. Indem Sie kreative Akteure (z. B. Ersteller von Inhalten und kreative Regisseure) in den Review- und Genehmigungsprozess einbinden, stellen Sie sicher, dass die endgültige Ausgabe Ihrer Vision und Markenidentität entspricht.

* **Einhaltung der Campaign-Ziele und der gesetzlichen Anforderungen**. Der Validierungsprozess hilft zu überprüfen, ob der Inhalt Kampagnenziele unterstützt. Es stellt sicher, dass Inhalte der rechtlichen Authentizität entsprechen, wodurch Risiken und mögliche rechtliche Probleme minimiert werden.

## Review- und Genehmigungslebenszyklus

Die wichtigsten Phasen des Prüfungs- und Genehmigungs-Workflows sind:

[Überprüfung und Genehmigung des von Ihnen erstellten Inhalts anfordern](./request-review.md)

[Inhalt überprüfen und bearbeiten](./review-and-edit.md)

[Inhalt validieren](./approve-content.md)

[Publish-Inhalte](./publish-content.md)

## Wer kann einen Review anfordern oder Inhalte genehmigen?

Wenn Sie ein Asset oder eine Erfahrung erstellt haben, können Sie andere Personen in der Genehmigungskette Ihres Unternehmens bitten, Ihre Arbeit förmlich zu überprüfen und zu kommentieren. Nur diese benannten Genehmiger können den Entwurf überprüfen.

## Über [!DNL Content] Entwürfe

_Entwürfe_ sind vorläufige Versionen von Assets oder Erlebnissen, die nicht dem Überprüfungs- und Genehmigungsprozess unterzogen wurden. Der Entwurfsstatus gibt an, wo sich der Entwurf im Überprüfungs- und Genehmigungsprozess befindet. Eine eindeutige Entwurfs-ID identifiziert jeden Entwurf. Diese ID ist gültig, bis ein Entwurf genehmigt und in [!DNL Content] veröffentlicht wird. Überprüfungskommentare und -genehmigungen für einen Entwurf sind mit dieser individuellen Entwurfs-ID verknüpft.

Wenn ein Entwurf den Überprüfungs- und Genehmigungsprozess abgeschlossen und in [!DNL Content] veröffentlicht wird, läuft die Entwurfs-ID ab und GenStudio speichert die zugehörigen Kommentare und Genehmigungsstatus nicht. Die Entwurfs-URL ist nicht mehr gültig.

Der Entwurfsstatus erfasst den Status des Inhaltsentwurfs, während er sich durch den Überprüfungs- und Genehmigungsprozess bewegt. Alle vorgesehenen validierungsverantwortlichen Benutzer werden über Änderungen des Inhaltsstatus informiert, den sie überprüfen. Überprüfer ändern den Entwurfsstatus, um anzugeben, ob ein Entwurf einer weiteren Überarbeitung bedarf oder genehmigt werden kann. Alle vorgesehenen Genehmiger müssen ein Asset oder Erlebnis genehmigen, bevor es veröffentlicht werden kann.

Verfügbare Entwurfsstatus:

**Benachrichtigt**: Der Ersteller von Inhalten hat den Überprüfungsprozess gestartet, indem er die Prüfer darüber informiert, dass ein Entwurf zur Überprüfung bereit ist.
**Erfordert Arbeit**: Gibt an, dass ein oder mehrere Überprüfer Änderungen am Inhaltsentwurf angefordert haben. Inhalte in diesem Status können nicht in [!DNL Content] gespeichert werden.
**Genehmigt**: Alle vorgesehenen Genehmiger haben das Asset oder Erlebnis genehmigt. Der Ersteller von Inhalten kann dem Asset oder Erlebnis nun Metadaten hinzufügen und in [!DNL Content] speichern.

## Benachrichtigungen

Die produktinternen Benachrichtigungen von GenStudio aktualisieren Genehmiger und Ersteller von Inhalten in Echtzeit von Asset-Statusänderungen und prüfen Kommentare. Benachrichtigungen unterstützen eine schnelle Iteration durch die verschiedenen Prüfungs-, Bearbeitungs- und Genehmigungszyklen.

Die von den Validierungsteilnehmern durchgeführten Aktionen Trigger für automatische In-Produkt-Benachrichtigungen und E-Mail-Benachrichtigungen. Wenn Sie einen Genehmigungsprozess starten, erhalten vorgesehene Genehmiger sowohl E-Mail- als auch In-Produkt-Benachrichtigungen. Wenn ein Genehmiger Kommentare oder Genehmigungen hinzufügt, werden Sie mit In-Produkt-Benachrichtigungen in der Schleife aufbewahrt. Benachrichtigungen enthalten Links zum Inhaltsentwurf.

Wenn Sie den Überprüfungs- und Genehmigungsprozess für Inhalte eingeleitet haben, werden Sie über alle Genehmigungen und Überprüfungskommentare informiert. Genehmiger werden jedoch nur über Kommentare benachrichtigt, die sie mit einem `@mention` einschließen.
