---
title: "Level 1 - Build"
description: >
   Sie haben eine grundlegende Cloud-Native-Implementierung eingerichtet und befinden sich in der Testphase.
---

## <i class="fas fa-users"></i> Mitarbeiter 

### Mitarbeiter Sicht

Ihre geschäftlichen und technischen Ziele werden von einem cloudbasierten Framework bestimmt. Sie und Ihr Team sind neu in der Technologie, verfügen jedoch über ein gewisses technisches Grundverständnis und einige bereits vorhandene Qualifikationen. Die Unternehmensleitung versteht die Vorteile von Cloud Native.

### Organisatorischer Wandel

Bei der Umstellung werden Sie nur über eine begrenzte organisatorische Unterstützung verfügen und sich in einer Proof-of-Concept-Phase (POC) befinden oder sich auf nur eine Anwendung konzentrieren.

### Teams und Dezentralisierung

Die Teams testen Cloud-native Tools, vor allem Kubernetes. Dies geschieht jedoch nicht nur um des Ausprobieren willens, sondern mit dem Ziel der Produktivnahme. Alle Arbeiten finden im Allgemeinen im Rahmen eines formellen MVP-Programms statt.

### Sicherheit

Die Personen, die Cloud Native implementieren, konzentrieren sich auf Security. Es werden Standard-Sicherheitseinstellungen verwendet, die in der Testphase funktionieren werden. Sie werden Zeit darauf verwenden, Ihre Open-Source-Sicherheitslage zu ermitteln und einen Sicherheits-POC der Test-Umgebung durchzuführen, damit sowohl die Entwicklungs- und Betriebsabteilung als auch der Security-Bereich verstehen, was bei Cloud Native Workloads erforderlich ist.

### Agilität der Entwickler

Ihr Unternehmen hat sich der Dezentralisierung verschrieben und wird "Teams von Teams" einsetzen. Dies ist eine wesentliche Anforderung an Ihre Mitarbeiter. In den verschiedenen Reifegraden werden die Mitarbeiter Tools für automatisierte Tests, Metriken und Feedback implementieren.

Die Entwickler haben vielleicht das Agile Manifest kennengelernt und das Scrum-Framework übernommen, ohne es notwendigerweise den operativen Bereich einzubeziehen. Die Entwickler versuchen möglicherweise, externe Abhängigkeiten selbst zu lösen, was das Feedback verlangsamt und zu unvollständigen Features im Sprint führt.

### Upskilling von Entwicklern

Zum Reifegrad Ihrer Mitarbeiter gehört auch die Fortbildung des Entwicklungsteams.

Ihr Anwendungsteam wird in 12-Faktor-Anwendungen, Microservice- und Cloud-Native-Mustern geschult werden. Außerdem benötigen Sie Entwickler, die mit Cloud-Native-Konzepten und Werkzeugen wie kubectl vertraut sind, um Ihr Entwicklungsteam zu verstärken.

### CNCF-Zertifizierungen

Die Cloud Native Computing Foundation (CNCF) dient als herstellerneutrale Heimat für viele der am schnellsten wachsenden Open-Source-Projekte, darunter Kubernetes, Prometheus und Envoy.

Damit Sie ein nachhaltiges Ökosystem für Cloud Native Infrastructure aufbauen können, ist es wichtig, dass Ihr Team in die CNCF-Zertifizierungen investiert. Es ist unwahrscheinlich, dass Sie die Zertifizierungen in Stufe 1 erreichen werden.

## <i class="fas fa-cogs"></i> Prozess

### Prozess-Übersicht

Sie erstellen eine Übersicht über die Anwendungsanforderungen, sowohl über die funktionalen (Anwendungsfunktionen und -code) als auch über die nicht-funktionalen, wie Leistung, Kapazität und Verfügbarkeit, und legen fest, wie Ihr Unternehmen skaliert werden soll. Das Feedback erfolgt manuell, z. B. per Slack, E-Mail und Telefon, und Sie werden auch manuell Korrekturen vornehmen. Wiederholbarkeit wird durch den Einsatz von Git-Workflows sichergestellt. Plattform- und Technologie-Lebenszyklen und -Updates, insbesondere Sicherheitsupdates, müssen regelmäßig durchgeführt werden, da anfällige Systeme ein besonderes Risiko darstellen.Diese Updates können adhoc und per Hand, aber auch im Rahmen der Updatemechanismen der Distributionen stattfinden. 

### CI/CD

Ein zentraler Punkt bei der Umstellung auf die Cloud ist die Einführung von CI/CD. CI/CD unterstützt Sie beim Erstellen, Testen und Bereitstellen von Anwendungen auf der Grundlage moderner Softwareentwicklungsverfahren. Ihr CI/CD-Prozess wird mit der Zeit reifen.

Wenn Sie bereits CI/CD anwenden, müssen Sie es in Ihre Cloud Native-Umgebung übertragen. Dazu gehören ihre Best Practices und Sie bauen auf ihnen auf.

### Änderungskontrolle

Es wird eine Änderungsontrolle für Deployments eingeführt. Es gibt noch keinen Prozess dafür, die Änderungen werden ad-hoc durchgeführt.

### Sicherheit
Es ist entscheidend für die Sicherheit ihrer Cloud Native-Umgebung, dass sie möglichst frühzeitig Sicherheitstools und -praktiken in Ihre native Cloud-Umgebung integrieren, sei es in Form einer Praxis oder eines Prozesses. Wir verwenden häufig den Begriff "Shift Left", wenn es darum geht, Test- oder Sicherheit-praktiken, so früh wie möglich in einen Prozess einzubinden. Sicherheit wird in allen Abschnitten des Cloud Native Maturity Model behandelt und jeder Abschnitt mit Menschen, Prozessen, Richtlinien und Technologie kann kombiniert werden, um das Sicherheitsteam bei der Reifung der Cloud Native Security des Unternehmens zu unterstützen.

Werden Sie aktiv: Ihre Sicherheitsreise beginnt hier. Berücksichtigen Sie die Sicherheit in allen Aspekten der Implementierung und machen Sie sie zu einem Bürger erster Klasse.
 
### Auditierung und Logs

Ihr Prozess enthält Logging und die Auditierung. Dies kann auf internen Anforderungen beruhen oder Ihre Compliance-Vorgaben unterstützen.

Manuelles Log-Scraping findet wahrscheinlich ad-hoc statt, und es fehlt vielleicht noch eine zentrale Logging-Infrastruktur oder ein SIEM.

## <i class="fas fa-edit"></i> Richtlinien

### Überblick über die Richtlinien

Wir sind uns bewusst, dass das Etablieren von Richtlinien graduell stattfindet. Jede Organisation hat eine andere Risikobereitschaft. Verwenden Sie dieses Dokument als Leitfaden für die Definition und Durchsetzung von Richtlinien. Mit Stufe 5 haben Sie die volle Reife der Richtlinien erreicht, aber das Ergebnis kann unterschiedlich sein.

Sie verfügen dann über eine begrenzte Anzahl dokumentierter Richtlinien zur Unterstützung der Dienste, die Sie in der Cloud aufbauen.

### Erstellung von Richtlinien

Sie müssen die Richtlinien und Konformitätsanforderungen Ihres Unternehmens auf Ihre native Cloud-Native-Umgebung übertragen.

Nehmen Sie sich Zeit, um die funktionalen und architektonischen Anforderungen Ihrer Anwendungen zu verstehen.

### Einhaltung der Compliance

Vor allem in stark regulierten Branchen sind Richtlinien erforderlich, um die Compliance zu gewährleisten. Bei Compliance ist die Reichweite fliessend.

Nehmen Sie sich Zeit, um Ihre Compliance-Anforderungen zu verstehen: zum Beispiel aus CIS, NIST oder PCI. Entwickeln Sie Service Level Objectives und Prioritäten für die Compliance. Dies wird einige Zeit in Anspruch nehmen und ist möglicherweise keine Vorbedingung für die Pre-Production, wird aber in Richtung Produktion zunehmen.

## <i class="fas fa-server"></i> Technologie

### Technologie-Übersicht

Sie werden die ersten Experimente mit Kubernetes machen und es übernehmen. Sie werden mit relativ einfachen Tools und Technologien beginnen. Sie werden Ihr bestehendes Toolset bewerten, um zu sehen, wie es in die neue Landschaft passt (was passt gut zu Cloud Native, was nicht?). Sie verfügen über eine begrenzte Automatisierung, aber keine Sorge, das kommt schon noch! Ihr Fokus liegt auf der Implementierung der Basistechnologie, und Sie sind noch nicht in Produktion.

### Infrastruktur

Sie bauen Ihre Cloud-Infrastruktur entweder vor Ort oder extern auf. Es zahlt sich aus, wenn Sie sich frühzeitig Gedanken über Ihre unterstützende Technologie wie Ihr Netzwerk, Firewalls und IAM, Zugriffskontrollen und Richtlinien machen (und ob Sie diese ändern müssen). Viele Themen werden sich aus Ihren ersten Experimenten mit Kubernetes ergeben, also stellen Sie sicher, dass Sie diese im Auge behalten - sie sind die "Brotkrumen", denen Sie folgen werden, wenn Sie sich in Richtung Cloud Native bewegen. Dazu gehören RBAC-Richtlinien, Load Balancer- und/oder Ingress-Konfiguration, Cluster-Dashboards, privilegierter Zugriff (oder dessen Fehlen!) und Container-Protokollierung. Ihr Ziel ist es, von "Pets" zu "Cattle" überzugehen, also investieren Sie in deklarative Lösungen für Ihre Infrastructure as a Service mit Infrastructure as Code (IaC)-Tools. Wenn Sie noch nicht über eine konsolidierte DevOps-Praxis auf dieser Ebene verfügen, sollten Sie Ihr künftiges Betriebsteam einbeziehen, um es mit der Materie vertraut zu machen.

### Container- und Laufzeitmanagement

Zunächst werden Sie sich auf die Erstellung von Containern konzentrieren wollen. Einer Ihrer ersten Schritte wird sein, Container-Builds zu Ihrem CI für Ihre Anwendung hinzuzufügen. Außerdem sollten Sie eine Container-Registry für Ihre Images einrichten und sich Gedanken über die Versionierung und das Tagging machen, um sicher zu wissen, welcher Code verwendet wird.

### Application Patterns und Refactoring

Wenn möglich starten Sie mit einer klassischen Microservice-Anwendung, und stellen Sie sicher, dass sie läuft und Ihre Mitarbeiter damit vertraut sind. Sie können es mit einer bestehenden oder monolithischen Anwendung versuchen, wenn dies sinnvoll ist, da dies die Werkzeuge und Abhängigkeiten, die Sie auf Ihrer Reise zu Cloud Native haben werden, wie kubectl, Netzwerkkonnektivität und andere Themen, identifizieren wird.

Ihr Unternehmen muss Microservice-Muster und -Architekturen prüfen und die Besonderheiten Ihrer Anwendungen verstehen. Nicht-funktionale Anforderungen wie Latenz, Ausfallsicherheit, Skalierung und Tools von Drittanbietern sollten unbedingt berücksichtigt werden. Wenn Sie einen Monolithen migrieren, kann dies zu einer erheblichen Umgestaltung der Anwendung führen, da für die bestehenden Anforderungen möglicherweise nicht die technischen Ressourcen zur Verfügung stehen. Prüfen Sie Ihr Zustandsmanagement, da das Refactoring eines Monolithen hier Aufwand erfordern kann. Stellen Sie sicher, dass das Wissen mit dem Code erhalten bleibt und die bestehenden Entwickler, die mit dem Code bereits vertraut sind, an der Migration in die Cloud teilnehmen. Minimieren Sie die Divergenz zwischen der Cloud und Ihrer existierenden Lösung, um allen zu zeigen, dass der Weg in zu Cloud Native verbindlich ist.

### Anwendungsfreigabe und Betrieb

Die Verwaltung eines Clusters mit Infrastructure as Code (IaC) unterscheidet sich von der Verwaltung der Anwendungsfreigabe und -bereitstellung, aber viele der gleichen Techniken und Tools sind für beide gleich.
Wenn Sie mit Kubernetes beginnen, ist es wichtig, dass Sie zunächst so viel praktische Erfahrung wie möglich sammeln. Zu Beginn werden Sie Ad-hoc-Bereitstellungen mit kubectl und kustomize durchführen.

### Sicherheit und Richtlinien

Beginnen Sie mit dem Aufbau einer sicheren CI-CD-Pipeline, falls Sie noch keine haben, und vergessen Sie nicht, dass das, was Sie heute mit VMs tun, in Zukunft ganz anders aussehen wird.

### Testen und Erkennen von Problemen

Wenn Sie gerade erst anfangen, wird ein Großteil Ihrer Tests manuell an Ihrer Geschäftsanwendung durchgeführt, die Sie als ersten Produktionskandidaten identifiziert haben. Bei Kubernetes werden Sie sich auf die allgemeine Netzwerkkonnektivität konzentrieren und sicherstellen, dass Sie Ihre Anwendungen bereitstellen können. Sie werden Smoke-Tests und UAT-Tests haben.

## <i class="fas fa-building"></i> Geschäftsergebnisse

Auf Level 1 des Cloud Native Maturity Model verfügt Ihr Team über eine Basisimplementierung und Sie befinden sich in der Pre-Production. Hier haben Sie einen erfolgreichen POC abgeschlossen. Auf der Grundlage des POC sollten Sie erste Erkenntnisse darüber haben, wie Cloud Native zur Verbesserung Ihrer Anwendung beitragen wird. In einer Entwicklungsumgebung könnten Sie zum Beispiel Folgendes festgestellt haben:
- Eine Anwendung verbraucht weniger Ressourcen (Kosteneinsparungen / effizientere Nutzung)
- Eine neue Funktion wurde schneller ausgeliefert (kürzere Markteinführungszeit und damit höhere Einnahmen)
- Es gab keine Ausfallzeiten (verbesserte Zuverlässigkeit für Kunden)
- Verbesserte Geschäftskontinuität dank resilienter Cloud-Architekturen

Dies sind nur Beispiele, sie sind keine Garantie für Ihre Umgebung, da die Ergebnisse variieren können.

In dieser Phase legen Sie fest, wie Sie den Erfolg Ihrer Cloud Native Journey messen (Ihre anfänglichen KPIs) und, was ebenso wichtig ist, wie Sie ihn den Stakeholdern demonstrieren werden. Dies ist ein wichtiges Ergebnis von Stufe 1, da der gesamte Erfolg der Reise auf diese Messung abgestimmt werden sollte. Denken Sie daran, dass dies nicht sofort an Tag 1 der Fall sein wird. Einige quantitative und qualitative Beispiele für KPIs könnten sein
- Reduzierung der Ausgaben für die App-Infrastruktur um 25 % durch Kostenoptimierung
- Verringerung der Entwicklungskosten um 10%
- Reduzierung des Teamfokus auf die Anwendungsinfrastruktur um 15 % durch weitestgehende Automatisierung
- Erhöhte Sicherheit für die Anwendung durch Automatisierung der CVE-Identifizierung in Containern
- Verbesserte Compliance, da Sie den Zugriff auf die Anwendung einschränken und verfolgen können; Nachweis der Compliance mit SOC 2
- Beschleunigte Entwicklungslebenszyklen durch Implementierung von CI/CD-Pipelines, die 10 % mehr Funktionen pro Quartal bereitstellen
- Migrationsplan - dies hängt von Ihrem Unternehmen ab, aber Sie sollten einen Migrationsplan haben. Unabhängig davon, ob Sie zuerst eine oder mehrere Anwendungen migrieren wollen, sollten Sie diesen Plan bereits erstellt haben.
- Verbessertes Kundenerlebnis, gemessen an höheren Leistungskennzahlen
- Beseitigung von Informationssilos: Abteilungen sind nicht mehr isoliert, sondern verfügen über ein einziges, integriertes Ökosystem.
- Abstimmung von Geschäfts- und IT-Zielen: Jeder ist involviert und weiß Bescheid, so dass die Ressourcen besser eingesetzt werden können, um diese Ziele effizient zu erreichen.
- Verbesserte interne Kommunikation: Die gegenseitige Befruchtung bietet neue Perspektiven mit gemeinsamem Wissen.

In dieser Phase ist es wichtig, dass die Geschäftsergebnisse untersucht und den Geschäftsinteressenten erläutert werden. Es sollte eine Diskussion mit der technischen Leitung, dem Eigentümer der Anwendung (Finanzen, Marketing usw.), dem CEO und sogar dem Vorstand stattfinden. Ohne diese Diskussionen und Abstimmung wird der Übergang zu den nächsten Phasen auf wenig Gegenliebe und möglicherweise sogar Skepsis stoßen.
