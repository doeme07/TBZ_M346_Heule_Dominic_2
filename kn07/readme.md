# KN07

## A) Datenbank im PAAS Modell

PaaS und SaaS
Die Nutzung von PaaS oder SaaS für Datenbanken bietet zahlreiche Vorteile gegenüber einer eigenen Installation:

![](1.PNG)

Weniger Aufwand: Anbieter übernehmen Einrichtung, Wartung, Updates und Backups.

Skalierbarkeit: Ressourcen passen sich automatisch an den Bedarf an.

Kosteneffizienz: Keine hohen Anfangsinvestitionen oder Betriebskosten, Bezahlung nach Nutzung.

Sicherheit: Integrierte und aktuelle Sicherheitslösungen.

Hohe Verfügbarkeit: Garantierte Redundanz und Ausfallsicherheit.

Schnelle Bereitstellung: Datenbanken können sofort genutzt werden.

Fokus auf Kerngeschäft: Keine Ablenkung durch technische Verwaltung.

PaaS und SaaS sind ideal für Projekte mit begrenzten Ressourcen oder flexiblen Anforderungen. Eine eigene Datenbank lohnt sich nur bei speziellen Anforderungen wie vollständiger Kontrolle oder strengen Datenschutzvorgaben.

## B) PAAS Applikation erstellen

![](2.PNG)
![](3.PNG)
![](4.PNG)
![](5.PNG)
![](6.PNG)
![](7.PNG)
![](8.PNG)
![](9.PNG)
![](10.PNG)
![](11.PNG)
![](12.PNG)
![](13.PNG)

### Was ist CloudFormation?
CloudFormation ist ein Infrastruktur-als-Code (IaC)-Service von AWS, der es ermöglicht, Ressourcen in der Cloud automatisch zu erstellen, zu verwalten und zu konfigurieren. Dabei wird eine deklarative Syntax verwendet (meistens JSON oder YAML), um eine Vorlage zu erstellen, die die Infrastruktur definiert.
Mit CloudFormation können komplexe Architekturen einfach bereitgestellt werden, einschliesslich EC2-Instanzen, Datenbanken, Netzwerken und anderen AWS-Diensten.

Vorteile von CloudFormation:

Automatisierung: Erstellen, Aktualisieren und Löschen von Ressourcen erfolgt automatisiert.

Versionierung: Änderungen in der Infrastruktur können versioniert und zurückgesetzt werden.

Abhängigkeiten: CloudFormation löst automatisch Abhängigkeiten zwischen Ressourcen (z. B. Netzwerke vor Datenbanken).

Wiederverwendbarkeit: Vorlagen können mehrfach verwendet werden, um identische Umgebungen zu erstellen.