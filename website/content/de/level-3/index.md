---
title: Level 3 - Skalierung
description: Ihre Kompetenz wächst, und Sie definieren Prozesse für die Skalierung.
---

## <i class="fas fa-users"></i> Personen

### Personen Überblick

Die Kompetenz des Teams wächst und es gibt ein Engagement in Entwicklung, Betrieb und Sicherheit. Sie formalisieren Expertise rund um ein Cloud-basiertes Kompetenzzentrum. Cloud-native wird zu einem primären Bestandteil Ihrer Strategie.

### Organisatorischer Wandel

Mit wachsender Kompetenz Ihrer Mitarbeiter ist nun eine Organisationsstruktur vorhanden, die Best Practices unterstützt. Sie werden formalisierte Verantwortlichkeiten haben. Ein häufig verwendetes Pattern für diese Struktur beruht auf Agilität und Scrum.

### Teams und Dezentralisierung

Sie sehen jetzt eine hohe Zentralisierung mit klaren und verstandenen Verantwortlichkeiten. Es kann jedoch zu einem Geschwindigkeitsrückgang und zu Engpässen im Prozess kommen. Die Dinge könnten langsamer werden.

### Sicherheit

Ihre Risikotoleranz wird sich darauf auswirken, auf welchem Level Sie sich auf Cloud-native-Security Trainings konzentrieren, damit Sie Ihre Mitarbeiter aktiv schulen.

### Agilität der Entwickler

Ihre Mitarbeiter haben Continuous Delivery für alle Umgebungen implementiert, auch für komplexe Releases und mit integrierten Compliance-Tests. Das Ops-Team ist jetzt in cross-funktionale Teams eingebunden, auch wenn die einzelnen Mitarbeiter nicht unbedingt alle Funktionen übernehmen können.

### Fortbildung der Entwickler

Implementieren Sie einen wiederholbaren Fehlerbehebungszyklus, damit Änderungen und Iterationen schnell durchgeführt werden können.

### CNCF-Zertifizierungen

Organisationen sollten die CKA- und CKAD-Prüfungen auf Level 2 und 3 in Betracht ziehen.

#### Certified Kubernetes Administrator (CKA)

Dieses Programm stellt sicher, dass CKAs über die Fähigkeiten, das Wissen und die Kompetenz verfügen, um die Aufgaben von Kubernetes-Administratoren zu erfüllen.

#### Certified Kubernetes Application Developer (CKAD)

Diese Prüfung bescheinigt, dass Benutzer Cloud-native-Anwendungen für Kubernetes entwerfen, erstellen, konfigurieren und bereitstellen können.

## <i class="fas fa-cogs"></i> Prozesse

### Prozesse Überblick

Sie implementieren eine Standardisierung im gesamten Unternehmen, um das Onboarding zu verbessern und Ihren Cloud-native-Footprint und Awareness zu erweitern. Sie erstellen eine Feedbackschleife und investieren in Wiederholbarkeit. Verfügen Sie über Tools, die für alle zugänglich sind? Verfügen Sie über Git-Services? Haben Sie die Zusammenarbeit im Arbeitsbereich eingeführt, um Zeit und Arbeit zu sparen oder Doppelarbeit zu vermeiden? Wie sieht Ihr Verfahren zur Messung der Ressourcennutzung aus? Auf Level 3 sollten Sie die Nutzung von Containern, CPU und Speicher (Laufzeit und Betriebszeit) messen. Die Automatisierung und die mit der Softwarefreigabe verbundenen Prozesse werden auch auf Plattformen ausgedehnt. Lebenszyklusvorgänge wie Upgrades und Patches, insbesondere CVEs und kritische Updates, werden von einer weiteren Automatisierung und der Einführung von Infrastructure-as-Code-Technologien profitieren.

### CI/CD

Sie implementieren ein Kompetenzzentrum für Ihren CI/CD-Prozess.

### Änderungsverfolgung

Ihre Codequalität, gemessen mit automatisierten Werkzeugen, verbessert sich und Sie sehen häufig CI- und Testerfolge.

### Sicherheit

Implementieren Sie eine automatische, kontinuierliche Überprüfung, um Fehlkonfigurationen oder Sicherheitsprobleme zu erkennen.

### Audit und Logs

Beginnen Sie mit der Prüfung und Umsetzung erster Warnmeldungen. Sie filtern Sie Rauschen heraus.

## <i class="fas fa-edit"></i> Policy

### Richtlinien Überblick

Sie werden Policy-as-Code implementieren und diese in Ihre CI-Pipeline einbauen.

### Richtlinien definieren

Erstellen Sie Richtlinien auf der Grundlage von Metriken, die auf Sicherheit, Effizienz und Zuverlässigkeit ausgerichtet sind.

### Compliance

Die Einhaltung und Prüfung von Richtlinien erfolgt durch automatisierte Mittel in Kubernetes. Dies wird wahrscheinlich die anfängliche Entwicklung von Policy-as-Code beinhalten.

## <i class="fas fa-server"></i> Technologie

### Technologie Überblick

Hier beginnen Sie zu skalieren. Ihre Palette an Werkzeugen ist stärker standardisiert. Sie bauen Ihre Release-Tools, Ihr Geheimhaltungsmanagement und Ihre Policy-Werkzeuge auf. Sie beginnen auch, ein gewisses Maß an Akzeptanz in Ihrem Unternehmen zu erreichen, was Sie weiter voranbringt. In dieser Phase werden Sie die meisten Werkzeuge einsetzen, da Sie sich mitten in der Evaluierung, Implementierung und im Produktionsbetrieb befinden.

### Infrastruktur

Um das Vertrauen in Ihre Cloud-Infrastruktur zu stärken, müssen Sie einen Überblick über die Aktivitäten Ihrer Infrastruktur gewinnen. Die Entwicklung Ihrer Überwachungs-, Warn- und Ressourcennutzungsfunktionen wird Ihr Schwerpunkt sein. Eine wichtige Überlegung dabei ist, dass Sie nicht nur maschinenspezifische Eigenschaften wie CPU, RAM usw. berücksichtigen, sondern auch Cluster-Ressourcenmetriken einbeziehen sollten. Außerdem werden Sie Komponenten ersetzen, wenn sie ausfallen, anstatt Zeit damit zu verbringen, Probleme in der Produktion zu beheben. Dies baut auf Level 2 auf. Dazu können Sie die Infrastruktur mit Kubernetes wie eine Software verwalten.

### Container- und Runtime-Management

Während Sie in Level 2 noch experimentiert haben, benötigen Sie in Level 3 mit zunehmender Arbeitslast und Skalierung konsistente Werkzeuge für alle Cluster, um eine kontinuierliche Sichtbarkeit Ihrer Kubernetes-Cluster zu erhalten. Dies sollte automatisches Scannen und die Möglichkeit zur Laufzeitbeobachtung der Vorgänge in Ihren Containern und Ihrem Cluster beinhalten. CNCF-Projekte sind hier eine gute Option. Sie verfügen über Alerting und Dashboards.

### Applikationsmuster und Refactoring

Kulturell hat Ihr Unternehmen begonnen, über Dienste und nicht über "Server" nachzudenken. Microservices werden in der Organisation angenommen und werden nun standardmäßig verwendet, wo es angebracht ist.

### Applikations-Releases und Betrieb

Da Konsistenz wichtig ist, beginnen Sie vielleicht damit, Helm Charts für Ihre Anwendungsreleases zu schreiben. Vielleicht machen Sie auch Ihre ersten Schritte in Richtung GitOps mit Flux und Argo, indem Sie Controller zur Verwaltung Ihrer Releases und Operationen einführen.

### Sicherheit und Policy

Es ist an der Zeit, die Leitplanken für die Bereitstellung und die bewährten Sicherheitsverfahren mit Policy-as-Code zu automatisieren. Legen Sie Ihre Strategie für die Durchsetzung fest. Beginnen Sie mit der Übernahme von Benchmarks und Standards von Drittanbietern, sofern diese relevant sind. Erwägen Sie auch den Einsatz von Technologien zur Erkennung von Anomalien und Bedrohungen.

### Testen und Erkennen von Problemen

Auf der Grundlage Ihrer Experimente in den vorherigen Leveln werden Sie dies in der Produktion implementieren und gute Warnmeldungen und Dashboards einbeziehen, um Ihre Beobachtungsfähigkeiten auszubauen.

## <i class="fas fa-building"></i> Unternehmerische Ergebnisse

In Level 3 wächst Ihre Kompetenz und Sie skalieren. Bis zu diesem Punkt haben sich Ihre Teams auf das Erlernen von Cloud-native konzentriert. In dieser Phase sind Ihre unternehmerischen Ergebnisse von der Erfahrung Ihres Teams abhängig. In dem Maße, wie das Team Vertrauen aufbaut, wächst seine Kompetenz in Bezug auf Sicherheit, Effizienz und Zuverlässigkeit, und es wird definierte Prozesse für die Skalierung implementieren. All dies wird sich auf Ihre Dienste und Anwendungen auswirken, wenn sich das Team verbessert. Wenn dies nicht der Fall ist, müssen Sie die Kommunikation verbessern, um diese Skalierung zu demonstrieren, oder die tatsächlichen Skalierungsergebnisse überprüfen, damit sie weiter optimiert werden können.

In Level 3 haben Sie Ihre Anwendung oder Ihren Dienst vor einem Single-Point-of-Failure oder einer enttäuschenden Leistung bewahrt.

Monitoring ist implementiert. Dies wird dem Unternehmen helfen, Berichte darüber zu erhalten, was funktioniert und was nicht. Das Monitoring kann zwar sehr spezifisch sein, bietet aber auch Einblicke in die Ressourcennutzung zur Kostenkontrolle und in die Leistung zur Sicherstellung der Verfügbarkeit.

Schließlich sollten Sie die Flexibilität und Skalierbarkeit von Cloud-native durch den Vergleich von alt und neu beobachten:

- Die Bereitstellung eines Servers dauert mit Infrastructure-as-Code Minuten statt Tage. Business-Übersetzung: kürzere Markteinführungszeit.
- Monitoring von Sicherheitsangriffen. Business-Übersetzung: weniger Risiko, gestohlene Daten.
- Observability: Logging, Metriken und Tracing. Business-Übersetzung: Schnellere Reaktionsfähigkeit auf Änderungen im Anwendungsverhalten oder in der Geschäftsnachfrage. Besseres Kundenerlebnis und weniger Umsatzeinbußen aufgrund von Serviceverschlechterungen.
- Verbesserte Wiederverwendbarkeit: Container und Microservices erleichtern die Wiederverwendung bereits vorhandener Komponenten aus früheren Projekten. Business-Übersetzung: 1. Gewährleistung eines konsistenten Markenimages und standardisierter Funktionalitäten in den verschiedenen Anwendungen; 2. eine niedrigere Lernkurve für Kunden, die diese Anwendungen nutzen.

