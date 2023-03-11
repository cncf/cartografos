# Cloud Native Maturity Model - Richtlinien

## Navigation

Das Cloud Native Maturity Model besteht aus sechs separaten Dokumenten - dem [Prolog](./prologue.md) und den fünf wichtigsten Referenzdokumenten:

* [Personen](./people.md)
* [Prozess](./process.md)
* [Richtlinien](./policy.md)
* [Technologie](./technology.md)
* [Business-Ergebnis](./business_outcomes.md)

## Einführung

Das Cloud Native Maturity Model umfasst vier Hauptdimensionen: Menschen, Prozesse, Richtlinien und Technologie. Dieses Papier befasst sich mit Richtlinien, der kritischen Umsetzung interner Anforderungen und der Einhaltung externer Vorschriften. Ihr Ziel als Cloud Native-Anwender sollte es sein, Richtlinien zu implementieren, die eine Verlagerung der Sicherheit nach links ermöglichen und fördern. Mit zunehmender Reife werden Sie versuchen, die Durchsetzung von Richtlinien in CI/CD zu automatisieren und die Einhaltung von Richtlinien in der Produktion kontinuierlich zu überwachen.

Wir sind uns bewusst, dass die Annahme von Richtlinien ein Gefälle aufweist. Jede Organisation hat eine andere Risikobereitschaft. Verwenden Sie dieses Dokument als Leitfaden für die Definition und Durchsetzung von Richtlinien. Mit Stufe 5 haben Sie die volle Richtlinienreife erreicht, aber das kann sich ändern.

* Level 1: Sie verfügen über eine begrenzte Anzahl dokumentierter Richtlinien zur Unterstützung der Dienste, die Sie in der Cloud aufbauen.

* Level 2: Wenn sich Ihre Dienste der Produktion nähern, haben Sie erste Richtlinien als Standard vereinbart, die meist dokumentiert sind.

* Level 3: Sie werden policy-as-code implementieren und in Ihre CI-Pipeline einbauen.

* Level 4: Sie haben nun SLAs für Richtlinien und Abhilfemaßnahmen definiert.

* Level 5: Auf der Grundlage der gewonnenen Erkenntnisse werden Sie Ihre Richtlinien mit zunehmender Reife Ihres Unternehmens verfeinern und Technologien wie maschinelles Lernen nutzen, um die Erkennung und Durchsetzung zu verbessern.

## Richtliniengestaltung

Sie müssen die Richtlinien und Compliance-Anforderungen Ihres Unternehmens auf Ihre  Cloud-Native-Umgebung übertragen.

* Level 1: Nehmen Sie sich Zeit, um die funktionalen und architektonischen Anforderungen Ihrer Anwendung zu verstehen.

* Level 2: Definieren Sie erste Ressourcenmetriken und beginnen Sie mit der Datenerfassung.

* Level 3: Erstellen Sie Richtlinien auf der Grundlage von Metriken, die auf Sicherheit, Effizienz und Zuverlässigkeit ausgerichtet sind.

* Level 4: Passen Sie die Richtlinien an die Anforderungen Ihres Unternehmens an und minimieren Sie Ausnahmen.

* Level 5: Beitrag zu Strategien für die Open-Source-Community und aktives Engagement für Regulierungsbehörden und andere externe Interessengruppen.

## Compliance

Vor allem in stark regulierten Branchen benötigen Sie Richtlinien, um die Einhaltung der Vorschriften zu gewährleisten. Bei der Einhaltung der Vorschriften gibt es ein gewisses Gefälle, was erreichbar ist.

* Level 1: Nehmen Sie sich Zeit, um Ihre Compliance-Anforderungen zu verstehen: CIS, NIST, PCI zum Beispiel. Entwickeln Sie SLOs und Prioritäten für die Einhaltung. Dies wird Zeit in Anspruch nehmen und ist möglicherweise keine Vorbedingung für die Produktion, wird aber mit dem Übergang zur Produktion zunehmen.

* Level 2: Erstprüfung, die manuell oder durch einfache Skripte durchgeführt wird.

* Level 3: Die Einhaltung von Richtlinien und die Prüfung erfolgt durch automatisierte Mittel in Kubernetes. Dies wird wahrscheinlich die anfängliche Entwicklung von "Policy-as-Code" beinhalten.

* Level 4: Erweiterung des Policy-Toolings auf Anwendungen wie Traffic Proxies, Service Mesh, Message Buses und Linux. Dies wird den Anwendungsbereich der verwalteten Richtlinien erweitern, aber auch dazu beitragen, sie durch deklarative Konfigurationen unter Kontrolle zu haben.

* Level 5: Compliance hört nie auf! Sie werden die Feedbackschleife mit den Stakeholdern straffen und die Vorteile des fortschrittlichen maschinellen Lernens und anderer Tools nutzen, um zu verstehen, was in Ihrer Umgebung normal ist, und um sicherzustellen, dass Anomalien in einer großen Menge von Compliance-Daten sichtbar werden.
