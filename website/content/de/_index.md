---
title: "Cloud-native-Maturity-Model"
---

![Frau auf einer Konferenz](/images/woman-at-conference.jpg)

Es ist kein Geheimnis, dass die Welt Cloud-native geworden ist! Die Autoren dieses Werks haben gesehen, dass viele Unternehmen ihre Cloud-native-Reise ohne einen wirklichen Rahmen für die Einführung dieser neuen Anwendungen und Plattformen beginnen. Die Autoren wollen diesen Rahmen für Ihren Erfolg anbieten.

Das Ziel dieses Modells ist es, Ihnen dabei zu helfen, sich von den Anfängen bis zur vollständigen Übernahme von Cloud-native-Technologien unter Verwendung der CNCF-Landschaft zu bewegen, um die vollen Vorteile der Ausführung skalierbarer Anwendungen in modernen, dynamischen Umgebungen in öffentlichen und hybriden Clouds zu erhalten.

## Zielpublikum

Die Hauptzielgruppe für dieses Modell ist breit gefächert und umfasst die folgenden Gruppen:

- Unternehmen, die sich auf den Weg der digitalen Transformation begeben oder diesen beginnen
- diejenigen, die sich in der riesigen CNCF-Landschaft zurechtfinden wollen, um ein Rahmenmodell zu finden, das sie implementieren und dem sie vertrauen können
- Open-Source- und CNCF-Projekte und Praktiker, die das Modell nutzen oder zu ihm beitragen möchten
- Führungsteams, die die Vorteile von Cloud-native, den Umfang des Aufwands und die Höhe der Investitionen verstehen möchten
- Technologen, die mit der Umstellung auf Cloud-native-Technologien beginnen möchten und den Weg, der vor ihnen liegt, im Detail verstehen sowie weitere Bereiche für Untersuchungen aufzeigen möchten

## Wie das Modell aufgeteilt ist

Die Entwicklung einer Cloud-native-Reife ist nicht nur eine technologische Reise, sondern eine, die von vier Hauptbereichen beeinflusst wird:

1. Mitarbeiter - Wie arbeiten wir, welche Fähigkeiten benötigen wir, wie sieht unsere Organisation aus, wenn wir diesen Prozess durchlaufen, und wie integrieren wir Sicherheit in die Arbeitsweise der Beteiligten?
2. Prozesse - Welche Prozesse brauchen wir, welche Technologien sind erforderlich, wie bilden wir Arbeitsabläufe und CI/CD unter Verwendung von Infrastructure-as-Code (IaC) ab und wie verlagern wir die Sicherheit so weit wie möglich nach links?
3. Richtlinien - Welche internen und externen Richtlinien sind erforderlich, um Sicherheits- und Compliance-Vorgaben zu erfüllen? Spiegeln diese Richtlinien die Betriebsumgebung Ihres Unternehmens wider?
4. Technologie - Welche Technologien sind erforderlich, damit Sie die Vorteile von Cloud-native nutzen und Menschen, Prozesse und Richtlinien sowie die Technologie für CI/CD, die Einführung von GitOps, Observability, Sicherheit, Speicherung, Vernetzung usw. unterstützen können?
5. Geschäftsnutzen - Was kann das Unternehmen von Cloud-native erwarten? Wie werden Sie die Vorteile dem CXO und/oder der Geschäftsleitung vermitteln?

## Aber was, wenn wir nicht in dieses Modell passen...

Entspannen Sie sich! Von keinem Projekt, keiner Organisation oder Person wird erwartet, dass sie alle Details des Modells perfekt erfüllen. Es ist bewusst so konzipiert, dass es viele verschiedene Szenarien abdeckt; alles von Start-ups bis hin zu Fortune-100-Unternehmen. Nehmen Sie das, was für Sie und Ihre Situation am relevantesten ist, und wenn es Ihnen hilft, sich für bestimmte Punkte oder Bereiche zu inspirieren (oder diese zwar zu berücksichtigen, dann aber auszuschließen), dann betrachten wir dies als Erfolg für Sie!

*Das Ziel dieses Modells ist es nicht, übermäßig präskriptiv zu sein, sondern vielmehr ein Werkzeug zu sein, das Sie auf Ihrer Reise begleitet. Die Cloud-native-Transformation ist keine exakte Wissenschaft, sondern lebt in Ihrem Projekt, in Ihrer Organisation und findet natürlich in einer bestimmten Zeit und an einem bestimmten Ort statt.*

## Voraussetzungen für das Cloud-native-Maturity-Model

Der erste und wohl wichtigste Schritt bei der Einführung von Cloud-native besteht darin, Ihre geschäftlichen und technologischen Ziele zu umreißen, insbesondere was sich Ihr Unternehmen von der Einführung verspricht.

Nur wenige Unternehmen beginnen mit einem völlig leeren Blatt Papier (oft als "grüne Wiese" bezeichnet). Möglicherweise haben Sie eine Situation wie die folgende:

- Ihr Unternehmen kann einige Monate, Jahre, Jahrzehnte oder sogar noch länger alt sein. Und Sie haben möglicherweise eine Reihe von technischen Schulden.
- Sie verfügen möglicherweise über einen beträchtlichen Bestand an Anwendungen, Plattformen und Infrastrukturen.
- Möglicherweise haben Sie sogar eine Migration zu Cloud-Service-Anbietern eingeleitet, vielleicht mit einem Lift-and-Shift-Ansatz für Ihren bestehenden Bestand.

Das Wichtigste, was Sie haben sollten, ist eine klare Vorstellung vom den Geschäftsnutzen, die Sie erreichen wollen. Diese werden Ihr "Nordstern" sein und Ihnen bei der Entscheidungsfindung helfen.

## Wann ist der richtige Zeitpunkt

Wenn Sie die folgenden Kriterien erfüllen, sind Sie vermutlich bereit, Ihre Reise in die Cloud zu beginnen:

### Mitarbeiter

- Sie haben eine deutliche Trennung zwischen Entwicklung und Betrieb, mit einer klaren personellen Abgrenzung zwischen Infrastruktur, Cloud, Anwendungsbetrieb und Entwicklung.
- Sie haben traditionell Ihre Betriebs- und Infrastrukturabteilungen und Ihre Anwendungsentwicklungsabteilungen getrennt. Dies kann durch regulatorische Anforderungen erzwungen worden sein.
- Diese Aufteilung mag für Sie gut funktioniert haben und sogar vorgeschrieben sein. Sie könnten jedoch auf zusätzliche Herausforderungen stoßen, da ein Großteil Ihrer Plattformen auf Code und Anwendungen ausgerichtet ist. Möglicherweise stellen Sie fest, dass Sie in Ihrem Plattformbereich Fähigkeiten benötigen, die traditionell in Ihren Anwendungsbereich gehörten.

### Prozesse

- Ihr Anwendungs-Deploy erfolgt in vielen Fällen manuell, oder Ihre Freigabeprozesse benötigen sehr viel Zeit, oft mit mehreren Versuchen.
- Sie unterstützen möglicherweise mehrere Versionen derselben Software und haben Schwierigkeiten, Upgrades oder Evaluierungen ohne erhebliche Ausfallzeiten durchzuführen.

### Richtlinien

- Richtlinien können in Form von Konventionen und Regeln vorliegen, die außerhalb der Anwendung und ihrer Plattform angesiedelt sind und nicht von Haus aus in Ihren Anwendungen und Ihrer Laufzeitumgebung durchgesetzt werden.
- Richtlinien können uneinheitlich und in Silos aufgebaut sein; Defense-in-Depth-Parität kann eher ein Zufall als Absicht sein.

### Technologie

- Sie werden wahrscheinlich VMs auf Abruf haben.
- Einige Automatisierungen sind verstreut.
- Sie verfügen über grundlegende Sicherheitskomponenten wie SIEM, RBAC-Konzepte und eine Art von Verzeichnis.
- Sie verfügen über eine gewisse Softwarepaketierung, die jedoch uneinheitlich sein kann.
- Sie verfügen über Perimetersicherheit und über Netzwerkzonen auf den Schichten 1-4, aber verspüren vielleicht einige Ängste rund um Sicherheitspraktiken.
- Ihre Erfahrung mit Verschlüsselung kann unterschiedlich sein - Sie haben z. B. einige Zertifizierungsstellen, aber sie werden vielleicht nicht ausgiebig genutzt, und die Einstiegshürde ist für viele hoch.
- Ihre Anwendungen sind möglicherweise auf Infrastrukturlösungen für eine hohe Verfügbarkeit angewiesen, was wiederum teurer sein kann, als Ihnen lieb ist.
- Ihr Serverbestand könnte von einzelnen physischen oder virtuellen Servern mit geringer Verfügbarkeit bis hin zu hochverfügbaren Clustern reichen. Die Skalierung kann eine echte Herausforderung darstellen und erhebliche Investitionen in Geld, Zeit und Planung erfordern.
- Sie haben vielleicht damit begonnen, in das Everything-as-Code-Modell einzutauchen. Zum Beispiel haben Sie bereits begonnen, Ihre Infrastruktur mit Terraform zu automatisieren.

![Frau auf einer Konferenz](/images/man-at-conference.jpg)

### Geschäftsnutzen

- Ihr Unternehmen wächst und muss in der Lage sein, die Nachfrage zu befriedigen.
- Ihr Unternehmen muss ein außergewöhnliches Kundenerlebnis verbessern und/oder bieten.
- Ihr Unternehmen muss Funktionen schneller auf den Markt bringen.

## Die Reise durch das Cloud-native-Maturity-Model

Das Cloud-native-Maturity-Model besteht aus fünf Stufen. Während Sie sich für eine Anwendung in Stufe 5 befinden, können Sie sich für eine andere Anwendung in Stufe 2 befinden. Behalten Sie das im Hinterkopf, wenn Sie Ihren Reifegrad ermitteln.

* **[Stufe 1 - Aufbau]({{< ref "/level-1" >}})**
Sie haben eine grundlegende Cloud-native-Implementierung eingerichtet und befinden sich in der Vorproduktionsphase.

* **[Stufe 2 - Betrieb]({{< ref "/level-2" >}})**
Die Cloud-native-Grundlage ist etabliert und Sie gehen in die Produktion über.

* **[Stufe 3 - Skalieren]({{< ref "/level-3" >}})**
Ihre Kompetenz wächst und Sie definieren Prozesse für die Skalierung.

* **[Stufe 4 - Verbessern]({{< ref "/level-4" >}})**
Sie verbessern die Sicherheit, die Richtlinien und die Verwaltung in Ihrer gesamten Umgebung.

* **[Stufe 5 - Optimieren]({{< ref "/level-5" >}})**
Sie überprüfen frühere Entscheidungen und überwachen Anwendungen und Infrastrukturen, um sie zu optimieren.

In jedem der folgenden Abschnitte werden wir die Kernkonzepte hervorheben und erörtern, was dies in den einzelnen Reifegraden für Menschen, Prozesse, Richtlinien und Technologien bedeutet.

Wir freuen uns über Feedback aus der Community zum Cloud-native-Maturity-Model!

## Position zu einbezogenen Technologien

Das Cloud-native-Maturity-Model bezieht sich nur auf Projekte, die von der CNCF graduiert wurden oder sich im Aufbau befinden. Die Standardposition des Reifegradmodells für CNCF-Sandbox-Projekte ist der Ausschluss, es sei denn, sie werden in späteren Reifegraden referenziert (d.h. Benutzer, die Level 4 oder 5 erreicht haben). Es enthält keinen Hinweis auf kommerzielle Software und wird dies auch in Zukunft nicht tun.
