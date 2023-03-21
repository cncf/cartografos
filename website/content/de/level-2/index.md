---
title: Level 2 - Betrieb
description: Die Cloud-native-Basis ist etabliert und Sie gehen in die Produktion über.
---

## <i class="fas fa-users"></i> Mitarbeiter 

### Mitarbeiter Überblick

Jeder Einzelne investiert Zeit in Ausbildung und Qualifikation. Auf diese Weise entstehen kleine Gruppen von Fachexperten und Fachleuten. DevOps hat mit der Integration von Ingenieuren mit Cloud-Kenntnissen und Entwicklergruppen mit Plattform-Knowhow begonnen. Die Führungsebene unterstützt die Cloud-native-Bemühungen aktiv.

### Organisatorischer Wandel

Organisatorische Veränderungen finden statt. Sie werden Projektteams definieren, agile Projektgruppen bilden und schnelle Feedback-/Testschleifen erzeugen.

### Teams und Dezentralisierung

Die Formalisierung zentraler Dienste und Zuständigkeiten beginnt, einschließlich der Konsolidierung von Werkzeugen sowie der Aussonderung oder Ablösung von nicht cloudbasierten Werkzeugen.

### Sicherheit

Ihr Team muss klären, wer für die Sicherheit des Kubernetes-Clusters verantwortlich ist und wie sie verwaltet werden soll. Dazu muss das Sicherheitsteam einbezogen werden.

### Agilität der Entwickler

Das Team ist mit technisch anspruchsvollen Problemen vertraut und weiß, wie Cloud-native helfen kann. Es gibt eine organisatorische Verpflichtung zur Dezentralisierung und zum automatisierten Testen von Builds, mit automatischen Deployments einiger Umgebungen.

### Fortbildung von Entwicklern

Ihr breiteres Entwicklungsteam ist in der Lage, Kubernetes grundlegend zu bedienen, einschließlich:
- Verbinden eines Operators mit der Kubernetes API
- sich mit Kubectl-Befehlen vertraut machen
- Verstehen, wie man Ressourcen auflistet und anzeigt
- Ausführen grundlegender Aktionen (mechanisches Vorgehen mit begrenztem Verständnis der Funktionsweise)

### CNCF-Zertifizierungen

Organisationen sollten die CKA- und CKAD-Prüfungen für die Stufen 2 und 3 in Betracht ziehen.

#### Certified Kubernetes Administrator (CKA)

Dieses Programm gewährleistet, dass CKAs die Fähigkeiten, das Wissen und die Kompetenz besitzen, um die Aufgaben eines Kubernetes-Administrators zu erfüllen.

#### Certified Kubernetes Application Developer (CKAD)

Diese Prüfung bescheinigt, dass Benutzer Cloud-native Anwendungen für Kubernetes entwerfen, erstellen, konfigurieren und bereitstellen können.

## <i class="fas fa-cogs"></i> Prozesse

### Prozessüberblick

Sie werden sich auf die Produktivnahme von einfachen Anwendungen konzentrieren. Dazu gehört, dass Sie mit Git und CI vertraut sind. Außerdem führen Sie strukturierte Build- und Deployment-Prozesse ein, die die Qualitäten eines Cloud- und Container-nativen CI/CD-Systems aufweisen.

### CI/CD

Für Ihre Anwendung werden Sie strukturierte Build- und Deployment-Prozesse einrichten, die die Qualitäten eines Cloud- und Container-nativen CI/CD-Systems aufweisen.

### Änderungsverfolgung

Sie entwickeln ein grundlegendes Verständnis des Arbeitsablaufs, von der Versionsverwaltung (SCM) bis zur Bereitstellung und haben Zugang zu Merge/Tag Commits im Versionsmanagement, um Deployments zu starten.

### Sicherheit

Integrieren Sie Sicherheit in Ihren CI-Prozess, einschließlich Container- und Configuration-Scanning.

### Audit und Logs

Nehmen Sie sich Zeit für die Definition der Log-Aggregation.


## <i class="fas fa-edit"></i> Richtlinien

### Richtlinienüberblick

Während sich ihre Dienste der Produktion nähern, haben Sie erste Richtlinien als Standard vereinbart, die meist auch dokumentiert sind.

### Richtlinien definieren

Definieren Sie erste Ressourcenmetriken und beginnen Sie mit der Datenerfassung.

### Compliance

Beginnendes Auditieren, das manuell oder durch einfache Skripte durchgeführt wird.

## <i class="fas fa-server"></i> Technologie

### Technologieüberblick

Dies ist Ihr erster Schritt in die Produktion. Sie haben hart gearbeitet, um Ihre Grundlagen in Stufe 1 zu schaffen, und jetzt gehen Sie in die Produktion über. Vielleicht haben Sie mit etwas relativ Kleinem und Einfachem begonnen, aber dieser Sprung in die Produktion hat Sie sicherlich dazu gezwungen, einige wichtige Schritte zu unternehmen. Wahrscheinlich mussten Sie Monitoring und Observability in Ihre Workloads einbauen. Sie haben wichtige Observability-Tools eingeführt und begonnen, Ihre Cluster auf Standardmetriken wie RAM, CPU usw. zu untersuchen. Auch wenn Sie mit der Evaluierung von Application Tracing beginnen, sollten Sie sich nicht zu viele Gedanken darüber machen, wenn Sie damit begonnen haben, Kernmetriken zu sammeln. Ihr Hauptaugenmerk liegt darauf, eine Anwendung in Produktion zu bringen und über ausreichende Plattformressourcen, Observability- und Betriebskapazitäten zu verfügen, um sie innerhalb Ihres Unternehmens zu nutzen.

### Infrastruktur

Da Ihr Ziel die Produktion ist, haben Sie Kubernetes-Cluster für die Produktion mit dem Schwerpunkt auf Zuverlässigkeit und Sicherheit aufgebaut.

### Container und Runtime-Management

Sie arbeiten jetzt in der Produktion. Sie werden mit Werkzeugen experimentieren, um die Grundlagen in der Produktion zu erweitern, um bei Sicherheit, Richtlinien-Management, Workload-Fehlkonfigurationen, Ressourcen-Anforderungen und -Limitierungen zu helfen. Die wichtigsten Sicherheitspraktiken für die Container-Hygiene werden integriert.

### Applikationsmuster und Refactoring

Sie sind in Produktion und haben Ihre ersten APIs offengelegt. Ziehen Sie die Entwicklung eines Microservices-first-Frameworks in Betracht, insbesondere wenn Ihre erste Wahl immer ein Microservices-Ansatz ist. Wenn dies nicht der Fall ist, ziehen Sie Anwendungen in Betracht, die für Lift-and-Shift geeignet sind, oder migrieren Sie die Anwendung erst später.

### Applikations-Releases und Betrieb

Für Ihre ersten Schritte in die Produktion werden Sie CI- oder Release-Tools, kubectl und kustomize verwenden, um möglicherweise Ihre ersten kleineren Anwendungen zu deployen. Jetzt ist es wirklich wichtig, dass Sie grundlegende Fähigkeiten in der Konfiguration von Kubernetes entwickeln.

### Sicherheit und Richtlinien

Stellen Sie sicher, dass Ihre Entwicklungs- und Betriebsgruppen sich an gute Praktiken für Container, Secrets und Sicherheit halten. Da Sie in der Produktion sind, sollten Sie sicherstellen, dass Sie auch die Verschlüsselung sowie die Authentifizierung und Autorisierung im Griff haben.

### Testen und Erkennen von Fehlern

Jetzt, wo Sie in Produktion sind, werden Sie mit Werkzeugen experimentieren, die Ihnen bei der Sicherheit, Richtlinienverwaltung, Fehlkonfigurationen der Arbeitslast, Ressourcenanforderungen, Grenzen und Observability in Ihrer Staging- oder Entwicklungsumgebung helfen.

## <i class="fas fa-building"></i> Geschäftsnutzen

Cloud-native ist nun etabliert und Ihre Technologen gehen in Produktion über. Während das technische Ergebnis von Stufe 2 eine voll funktionsfähige Anwendung oder eine Gruppe von Anwendungen ist, die auf Cloud Native-Tools und -Praktiken migriert wurden, ist der Geschäftsnutzen die Fähigkeit, die Vorteile der Migrationen zu bewerten. Dies ist auch die Stufe, die die meisten Kunden/Unternehmen erreichen und auf der sie stehen bleiben. Hier zeigt ein Cloud-native-Maturity-Model seinen wahren Wert.

Anhand der in Stufe 1 festgelegten KPIs messen Sie den Erfolg und teilen ihn den Stakeholdern mit.

In der Betriebsphase konzentrieren Sie sich auf den Übergang zur Produktion. Sie haben Standards für die Technologie festgelegt, Ihre Mitarbeiter nutzen sie und führen Richtlinien und Verfahren ein. Ihr Geschäftsnutzen wird sich um die Migration in Produktion drehen. Die Geschäftsleitung Ihres Unternehmens will wissen, welche Anwendungen migriert werden und warum. Sie sind in der Lage, ihr die Pläne klar zu vermitteln. Bei der Arbeit der Teams in Stufe 2 werden sich auch wiederholbare Muster herausbilden. Diese werden auf Ihre Geschäftsergebnisse angewandt, sodass die Vorteile, die Sie bei einer migrierten Anwendung sehen, ohne großen Aufwand auf eine andere Anwendung übertragen werden können. Diese Muster werden dazu beitragen, die Abläufe in Ihren Entwicklungs-, Sicherheits- und Betriebsteams zu optimieren.

Zu Ihren KPIs kann auch Ihre Kapitalrendite (ROI) gehören, aber Sie sollten sich darüber im Klaren sein, dass Ihre ROI in Stufe 2 niedriger sein wird als in Stufe 5. Das liegt daran, dass Sie viel in den Erwerb von Werkzeugen, den Aufbau des richtigen Teams und der richtigen Fähigkeiten investieren, während Sie in Stufe 5 optimieren.
