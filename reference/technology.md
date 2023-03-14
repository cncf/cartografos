# Cloud Native Maturity Model - Technology

## Navigation

The Cloud Native Maturity Model is composed of six separate documents - the [Prologue](./prologue.md) and the five key reference documents:

* [People](./people.md)  
* [Process](./process.md)  
* [Policy](./policy.md)  
* [Technology](./technology.md)
* [Business Outcomes](./business_outcomes.md)

## Position on Included Technologies

***The Cloud Native Maturity Model includes references to only CNCF graduated or incubating projects. The Maturity Model’s default position on CNCF sandbox projects will be to exclude unless referenced in later stages of maturity (i.e. users that have achieved level 4 or 5). It does not and will not include any reference to commercial software.***

## Einführung

Das Cloud Native Maturity Model umfasst vier Hauptdimensionen: Menschen, Prozesse, Richtlinien und Technologie. Dieses Dokument befasst sich mit der Technologie - den praktischen Werkzeugen, aus denen Cloud Native-Anwendungen, Plattformen und Infrastrukturen bestehen. Dieses Papier bezieht sich nicht nur auf spezifische Technologien, sondern soll auch die Phasen aufzeigen, die Sie auf Ihrem Weg von den Anfängen bis hin zur Cloud Native Excellence durchlaufen können.

Dieses Dokument veranschaulicht nur einen Weg - aber alle Wege sind unterschiedlich. Das ist auch gut so, denn jedes Unternehmen beginnt an einem anderen Punkt und hat ein anderes Ziel (Geschäftsergebnis). Unterschiedliche Standorte, Größen, Ausgangspunkte (neue oder alteingesessene Unternehmen), regulatorische Umgebungen und natürlich Menschen beeinflussen die Cloud Native-Reise.

Der Technologieabschnitt des Cloud Native Maturity Model ist nicht vollständig. Wir freuen uns über Beiträge, um sicherzustellen, dass das Modell robust und für alle Benutzer nützlich ist.

## Die Technologie im Überblick

Wir gehen davon aus, dass Sie bereits über Kenntnisse, Erfahrungen und vielleicht auch Zugang zu Infrastrukturen wie virtuellen Maschinen verfügen. Sie verfügen wahrscheinlich über einige grundlegende Sicherheitskomponenten wie Firewalls, SIEM für Sicherheitsereignisse und -Protokollierung, ein Sicherheitskonzept, das sich wahrscheinlich für RBAC eignet, und einige Tools für die Identitäts- und Zugriffsverwaltung wie LDAP oder Active Directory-Verzeichnisse.

Am wichtigsten ist jedoch, dass Sie wissen, warum Sie die Cloud Native Technologie einführen wollen, d.h. welche Geschäftsergebnisse Sie erwarten. Klarheit darüber, warum Sie sich auf den Weg zu einer vollständigen Cloud Native Adoption machen wollen, ist Ihr größtes Kapital.
Auf einer hohen Ebene sehen die wichtigsten Schritte in ihrer Cloud Native-Reise in etwa folgendermaßen aus:

* Stufe 1: Sie experimentieren zunächst mit Kubernetes und führen es ein. Sie werden mit relativ grundlegenden Tools und Technologien beginnen. Sie werden Ihre vorhandenen Tools bewerten, um zu sehen, wie sie in die neue Landschaft passen (was funktioniert gut mit Cloud Native, was nicht?). Sie werden nur über eine begrenzte Automatisierung verfügen, aber keine Sorge, das kommt schon noch! Ihr Fokus liegt auf der Implementierung der Basistechnologie, und Sie werden noch nicht in Produktion sein.

* Stufe 2: Dies ist Ihr erster Schritt in die Produktion. Sie haben hart gearbeitet, um in Stufe 1 eine Grundlage zu schaffen, und jetzt gehen Sie in die Produktion über. Vielleicht haben Sie mit etwas relativ Kleinem und Einfachem begonnen, aber dieser Sprung in die Produktion hat Ihnen sicherlich einige wichtige Schritte abverlangt. Wahrscheinlich mussten Sie Monitoring und Observabilität in Ihre Workloads einbauen. Sie haben wichtige Beobachtungstools eingeführt und damit begonnen, Ihre Cluster auf Standardmetriken wie RAM, CPU usw. zu überwachen. Auch wenn Sie mit der Auswertung des Anwendungs-Tracing beginnen, sollten Sie sich nicht zu viele Gedanken darüber machen, wenn Sie damit begonnen haben, Kernmetriken zu sammeln. Ihr Hauptaugenmerk liegt hier darauf, eine Anwendung in Produktion zu bringen und über genügend Plattformressourcen, Beobachtungsmöglichkeiten und Betriebskapazitäten zu verfügen, um sie innerhalb Ihres Unternehmens zu unterstützen.

* Stufe 3: Hier beginnen Sie zu skalieren. Ihre Tool-Suite ist stärker standardisiert. Sie bauen Ihre Release-Tools, Ihr Secrets-Management und Ihre Policy-Tools auf. Sie beginnen auch, ein gewisses Maß an Akzeptanz in Ihrem Unternehmen zu erreichen, was Ihnen hilft, voranzukommen. In dieser Phase werden Sie die meisten Tools einsetzen, da Sie sich mitten in der Evaluierung, Implementierung und im Produktionsbetrieb befinden.

* Stufe 4: Sie haben die volle Kontrolle über Ihre Umgebung und haben durch die rasche Übernahme von Cloud-Native-Mustern für neue Anwendungen und Plattformen Ihr Vertrauen gewonnen. Sie haben auch das Engagement des Unternehmens für Cloud Native gewonnen, was Ihnen zusätzlichen Schwung verleiht. Sie haben das Gefühl, dass Sie "die Kluft überquert" haben.

* Stufe 5: Ihre Anstrengungen konzentrieren sich jetzt auf die Automatisierung in funktionalen und nicht-funktionalen Bereichen wie Scanning, Richtlinien, Sicherheit und Tests. Sie haben Operatoren, die Ihre Operationen für Sie erledigen, und Sie sind vollständig automatisiert.



## Infrastruktur

* Stufe 1: Sie bauen Ihre Cloud-Infrastruktur entweder On-Premise oder dezentral auf. Es zahlt sich aus, wenn Sie sich frühzeitig Gedanken über Ihre unterstützende Technologie wie Ihr Netzwerk, Firewalls und IAM, Zugriffskontrollen und Richtlinien machen (und ob Sie diese ändern müssen). Viele Themen werden sich aus Ihren ersten Experimenten mit Kubernetes ergeben, also stellen Sie sicher, dass Sie diese im Auge behalten - sie sind die "Brotkrumen", denen Sie folgen werden, während Sie sich in Richtung Cloud Native bewegen. Dazu gehören RBAC-Richtlinien, Load Balancer- und/oder Ingress-Konfiguration, Cluster-Dashboards, privilegierter Zugriff (oder dessen Fehlen!) und Container-Logging. Ihr Ziel ist es, von "Haustieren" zu "Nutztieren" überzugehen, also investieren Sie in deklarative Lösungen für Ihre Infrastructure as a Service mit Infrastructure as Code (IaC) Tooling. Wenn Sie auf dieser Stufe noch keine konsolidierte DevOps-Praxis haben, sollten Sie Ihr künftiges Betriebsteam einbeziehen, um sich mit der Materie vertraut zu machen.

* Stufe 2: Da die Produktivumgebung Ihr Ziel ist, haben Sie Kubernetes-Cluster für die Produktivumgebung aufgebaut, wobei der Schwerpunkt auf Zuverlässigkeit und Sicherheit liegt.

* Stufe 3: Um Vertrauen in Ihre Cloud-Infrastruktur zu schaffen, müssen Sie Einblick in die Aktivitäten Ihrer Infrastruktur gewinnen. Die Entwicklung Ihrer Monitoring-, Alarmierungs- und Ressourcenauslastungsfunktionen wird Ihr Schwerpunkt sein. Ein wichtiger Aspekt dabei ist, dass Sie nicht nur maschinenspezifische Eigenschaften wie CPU, RAM usw. berücksichtigen, sondern auch Cluster-Ressourcenmetriken einbeziehen müssen. Außerdem werden Sie Komponenten ersetzen, wenn sie ausfallen, anstatt Zeit damit zu verbringen, Probleme in der Produktivumgebung zu beheben. Dies setzt auf Stufe 2 auf. Des Weiteren können Sie mit Kubernetes auch Ihre Infrastruktur so verwalten, wie Sie es mit Software tun würden.

* Stufe 4: Kubernetes und seine API sind Ihnen inzwischen sehr vertraut. Mit Ihrer Infrastruktur und Ihren IaC-Tools werden Sie sich wahrscheinlich mit der ClusterAPI beschäftigen und diese für die Bereitstellung und Verwaltung des Lebenszyklus Ihrer Cluster verwenden. Da Sie die Kontrolle über Ihre Plattformen weiter verfeinern wollen, werden Sie daran arbeiten, Richtlinien für Ihre Infrastruktur-Kontrollebene und andere Infrastruktur-Controller zu implementieren.

* Stufe 5: Hier verwalten Sie den gesamten Lebenszyklus Ihrer Infrastruktur mithilfe von Software und Werkzeugen. Builds, Upgrades und Außerbetriebnahme erfolgen alle über Code.

## Anwendungspatterns und Refactoring

Beginnen Sie mit einer kanonischen Microservice-Anwendung, wenn Sie können, und bestätigen Sie, dass sie läuft und die Mitarbeiter damit vertraut sind. Versuchen Sie, mit einer Microservice-Anwendung auf Ihrem Weg in die Cloud zu beginnen, wenn Sie können. Sie können eine bestehende oder monolithische Anwendung ausprobieren, wenn dies sinnvoll ist, da dies die Werkzeuge und Abhängigkeiten, die Sie auf Ihrer Reise zu Cloud Native haben werden, wie kubectl, Netzwerkkonnektivität und andere Themen, hervorbringen wird.

Hier ist ein Arbeitsmodell für den Microservices-Pfad. Sie können es an Ihr Modell anpassen.

* Stufe 1: Ihr Unternehmen muss die Microservice-Muster und -Architektur prüfen und die Besonderheiten Ihrer Anwendungen verstehen. Nicht-funktionale Anforderungen wie Latenz, Resilienz, Skalierung und Tools von Drittanbietern sollten unbedingt berücksichtigt werden. Wenn Sie einen Monolithen umwandeln, kann dies zu einer erheblichen Umgestaltung der Anwendung führen, da für die bestehenden Anforderungen möglicherweise nicht die technischen Ressourcen zur Verfügung stehen. Berücksichtigen Sie Ihr Zustandsmanagement, da das Refactoring eines Monolithen hier Aufwand erfordern kann. Versuchen Sie sicherzustellen, dass das Wissen mit dem Code zusammenbleibt, also stellen Sie sicher, dass ein bestehender Entwickler, der mit dem Code vertraut ist, an der Migration in die Cloud teilnimmt. Minimieren Sie die Divergenz zwischen der Cloud und Ihrem bestehenden Bestand. Diese Maßnahme wird sicherstellen, dass alle Beteiligten verstehen, dass die Umstellung auf Cloud Native eine feste Entscheidung ist.

* Stufe 2: Sie sind in Produktion und haben Ihre ersten APIs offengelegt. Ziehen Sie die Entwicklung eines "Microservices First"-Frameworks in Betracht, vor allem, wenn Ihre erste Wahl immer ein Microservices-Ansatz ist. Wenn nicht, ziehen Sie Anwendungen in Betracht, die sich für Lift and Shift eignen, oder migrieren Sie die Anwendung erst später.

* Stufe 3: Kulturell hat Ihr Unternehmen begonnen, über Dienste und nicht über "Server" nachzudenken. Microservices werden innerhalb der Organisation akzeptiert und werden nun standardmäßig verwendet, wo es angebracht ist.

* Stufe 4: Microservices sind das bevorzugte Muster für Anwendungen geworden. Die Nutzung von APIs wird innerhalb der Organisation ausgeweitet, und andere interne Systeme können offengelegt und genutzt werden, und sie stehen für die allgemeine Nutzung zur Verfügung, offen in der gesamten Organisation über ein Dienstnetz. Das Unternehmen wird datenzentriert und API-zentriert, und die Daten können leichter genutzt werden.

* Stufe 5: Sofern die Anwendungen keine besonderen Anforderungen stellen, wie z. B. eine extrem niedrige Latenz, sind neue Anwendungen auf der grünen Wiese Cloud-nativ. Sie werden versuchen, Ihr bestehendes Anwendungsportfolio mit Hilfe Ihres bewährten Prozesses auf Ihre Cloud Native Plattform zu übertragen. Sie werden jetzt sehen, dass Ihre Anwendung den Stärken und Fähigkeiten Ihrer Plattform entspricht.

## Container- und Laufzeitmanagement

* Stufe 1: Anfangs werden Sie sich nur auf die Erstellung von Containern konzentrieren wollen. Einer Ihrer ersten Schritte wird sein, Container-Builds zur CI für Ihre Anwendung hinzuzufügen. Außerdem sollten Sie eine Container-Registry für Ihre Images einrichten und sich Gedanken über Versionierung und Tagging machen, um sicherzustellen, dass Sie genau wissen, welcher Code in Verwendung ist.

* Stufe 2: Sie arbeiten jetzt in Produktion. Sie werden mit Werkzeugen experimentieren, um die Grundlagen im Produktivbetrieb zu erweitern, die bei Sicherheit, Richtlinienverwaltung, Fehlkonfigurationen der Arbeitslast, Ressourcenanforderungen und -begrenzungen helfen. Die wichtigsten Sicherheitspraktiken für die Container-Hygiene werden integriert.

* Stufe 3: Während Sie in Stufe 2 experimentiert haben, benötigen Sie in Stufe 3 mit zunehmender Arbeitslast und Skalierung ein konsistentes Tooling für alle Cluster, um eine kontinuierliche Transparenz Ihrer Kubernetes-Cluster zu erhalten. Dies sollte automatisches Scannen und die Möglichkeit zur Laufzeitbeobachtung der Vorgänge in Ihren Containern und Ihrem Cluster beinhalten. CNCF-Projekte sind hier eine gute Option. Sie werden über Warnmeldungen und Dashboards verfügen.

* Stufe 4: Mit den Informationsquellen, die Sie auf Stufe 3 gewonnen haben, ist es Ihr Ziel, Ihre Datenquellen weiter zu integrieren und zusammen mit der Alarmierung Sichtbarkeit zu erlangen. Dies schließt die Feedback-Schleife zu Laufzeit und Betrieb und ermöglicht es Ihnen, schnell auf ungeplante Ereignisse zu reagieren.

* Stufe 5: Sie automatisieren jetzt die Reaktion auf Ereignisse und haben alle Ihre Sicherheitsdaten in einem zentralen Repository. Die Plattform ist in der Lage, auf Ereignisse zu reagieren.

## Anwendungs-Release und Betrieb

Die Verwaltung eines Clusters mit Infrastructure as Code (IaC) unterscheidet sich von der Verwaltung der Anwendungs-Release und -bereitstellung, aber viele der gleichen Techniken und Tools sind für beide anwendbar.

* Stufe 1: Wenn Sie mit Kubernetes beginnen, ist es wichtig, dass Sie zunächst so viel praktische Erfahrung wie möglich sammeln. Zu Beginn werden Sie Ad-hoc-Bereitstellungen mit kubectl und kustomize durchführen.

* Level 2: Für Ihre ersten Schritte in Produktion werden Sie CI oder Release-Tools, kubectl und kustomize verwenden, um möglicherweise Ihre ersten kleineren Anwendungen bereitzustellen. Jetzt ist es wirklich wichtig, dass Sie Schlüsselkompetenzen in der Kubernetes-Konfiguration entwickeln.

* Stufe 3: Da Konsistenz wichtig ist, beginnen Sie vielleicht damit, Helm Charts für Ihre Anwendungsreleases zu schreiben. Vielleicht machen Sie auch Ihre ersten Schritte in Richtung GitOps mit Flux und Argo und führen Controller zur Verwaltung Ihrer Releases und Operationen ein.

* Stufe 4: Sie verwenden GitOps-Operatoren nicht nur für die schnelle Bereitstellung, sondern vielleicht auch für Entwicklungs- und Testzwecke. Sie erwarten, dass der größte Teil Ihrer Software mit Helm verpackt wird und die Feedback-Schleife so schnell wie möglich geschlossen wird, um Konfigurationsabweichungen zu reduzieren.

* Stufe 5: Sie sind jetzt in voller Produktion mit GitOps-Operatoren und -Kontrollen, und Ihre Release- und Operations-Workflows finden in Git statt.

## Tests und Fehlererkennung

* Stufe 1: Wenn Sie gerade erst anfangen, wird ein Großteil Ihrer Tests manuell an Ihrer Geschäftsanwendung durchgeführt, die Sie als ersten Produktionskandidaten identifiziert haben. Bei Kubernetes konzentrieren Sie sich auf die allgemeine Netzwerkkonnektivität und stellen sicher, dass Sie Ihre Anwendungen bereitstellen können. Sie werden Smoke-Tests und UAT-Tests durchführen.

* Stufe 2: In der Produktivumgebung experimentieren Sie mit Tools für Sicherheit, Richtlinienverwaltung, Fehlkonfigurationen der Arbeitslast, Ressourcenanforderungen, Grenzen und Beobachtbarkeit in Ihrer Staging- oder Entwicklungsumgebung.

* Stufe 3: Auf der Grundlage Ihrer Experimente in der vorherigen Stufe implementieren Sie diese in der Produktivumgebung, einschließlich guter Warnsysteme und guter Dashboards, und bauen Ihre Überwachungsfähigkeiten aus.

* Stufe 4: Da Ihre Umgebung in Produktion immer komplexer wird, kann es sein, dass die Behebung von Problemen eine Anpassung Ihrer Policy-as-Code oder von Komponenten Ihrer Infrastructure-as-Code sowie Ihrer Anwendung erfordert. Probleme können sich auf mehr als eine Anwendung beziehen, so dass Sie alle Anwendungen zusammenfassen, um Trends zu ermitteln. Dabei kann es sich um Bugs wie Speicherlecks sowie um Sicherheits- oder Richtlinienprobleme handeln. Ihre Abhilfemaßnahmen können darin bestehen, sie an der Quelle zu beheben, idealerweise "so weit links" wie möglich, oder aber eine Automatisierung zu entwickeln, die in der Lage ist, sie zu beheben, wenn sie auftreten, und sie im Laufe der Zeit zu optimieren.

* Stufe 5: Hier optimieren wir die Automatisierung zur Behebung von Problemen weiter, indem wir verhindern, dass Fehler überhaupt erst in den Produktivbetrieb gelangen.

## Sicherheit und Policy

* Stufe 1: Beginnen Sie mit dem Aufbau einer gesicherten CI-CD-Pipeline, wenn Sie noch keine haben, und vergessen Sie nicht, dass das, was Sie heute mit VMs machen, in Zukunft ganz anders aussehen wird.

* Stufe 2: Stellen Sie sicher, dass Ihre Entwicklungs- und Betriebsgruppen bewährte Verfahren für Container, Secrets und Sicherheit anwenden. Da Sie sich in einer Produktivumgebung befinden, sollten Sie sicherstellen, dass auch die Verschlüsselung sowie die Authentifizierung und Autorisierung berücksichtigt werden.

* Stufe 3: Jetzt ist es an der Zeit, die Leitplanken für die Bereitstellung und die bewährten Sicherheitsverfahren mit Policy as Code zu automatisieren. Legen Sie Ihre Strategie für die Durchsetzung fest. Beginnen Sie mit der Übernahme von Benchmarks und Standards von Drittanbietern, sofern diese relevant sind. Erwägen Sie auch den Einsatz von Technologien zur Erkennung von Anomalien und Bedrohungen.

* Stufe 4: Wenden Sie Ihre Policy in der Produktivumgebung an, falls Sie das noch nicht getan haben. Sie werden Ihre Policies in der Produktivumgebung weiter abstimmen.

* Stufe 5: Hier erfolgt eine kontinuierliche Optimierung und Anpassung an neue Anforderungen, die mit der aktuellen Bedrohungslage in Einklang stehen. Ausnahmen von der Policy werden sowohl minimiert als auch formell kontrolliert. Sie können maschinelles Lernen als Teil Ihrer Verfahren zur Erkennung von Bedrohungen einbeziehen.
