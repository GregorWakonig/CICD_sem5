Wie können CI/CD Pipelines uns dabei unterstützen CI Anti-Patterns zu vermeiden?

Automatisierte Builds und Tests: Durch die Automatisierung von Builds und Tests kann sichergestellt werden, dass alle Änderungen bei jedem push/pull request geprüft werden. Dies verhindert, dass schädlicher Code in das System eingeführt wird.

Feedback-Schleifen: CI/CD Pipelines bieten schnelles Feedback, das es Entwicklern ermöglicht, Probleme frühzeitig zu erkennen und zu beheben. Dies hilft dabei, Code-Qualität und vor allem auch die Stabilität zu verbessern.

Überwachung und Überprüfung: CI/CD Pipelines bieten Überwachungsfunktionen, die es ermöglichen, den Status des Builds und der Deployments zu überwachen. Dies hilft, Probleme frühzeitig zu erkennen und zu beheben, bevor sie sich auf den produktiven Einsatz auswirken. Dabei kann während eines Builds der Status und die einzelnen Schritte des Builds verfolgt und nachvollzogen werden.

Standardisierte Prozesse: CI/CD Pipelines definieren standardisierte Prozesse für Builds, Tests und Deployments. Dies hilft dabei, dass alle Änderungen an der Codebasis nach denselben Regeln behandelt werden, was zu einer höheren Code-Qualität führt.

Wie weit kann Continuous Integration mit der aktuellen Übung erfüllt werden? Begründen Sie Ihre Antworten.

Grundsätzlich sind die wichtigsten Schritte für Continuous Integration erfüllt. Es werden automatisierte Builds gestartet und  es wird automatisch getestet. Das heißt, dass für eine vollständige Continuous Integration lediglich ein review des Projekts bzw. das automatisierte Deployment des Projekts auf eine Liveumgebung fehlt. Dazu würden aber noch weitere Punkte wie zb ein Server, auf dem das Projekt läuft, fehlen.

Schritte:
Demo Action von GitHub im Repo integriert
Project checkout action
maven build integriert
directory kopieren
chat style action integriert
automatische release action integriert
