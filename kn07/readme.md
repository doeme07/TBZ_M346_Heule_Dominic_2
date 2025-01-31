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

### Was ist Cloud-Init?
Cloud-Init ist ein Open-Source-Tool, das hauptsächlich für die Initialisierung von Cloud-Instanzen (z. B. EC2-Instanzen) verwendet wird. Es ermöglicht die Ausführung von benutzerdefinierten Skripten oder Konfigurationen während des Startvorgangs einer Instanz. Cloud-Init ist unabhängig von einem spezifischen Cloud-Anbieter und unterstützt mehrere Plattformen wie AWS, Azure und Google Cloud.

Typische Funktionen von Cloud-Init:


Initialisierung von Instanzen: Festlegen von Hostnamen, Benutzerdaten und Netzwerkdetails.

Softwareinstallation: Automatische Installation und Konfiguration von Paketen.

Benutzerdefinierte Skripte: Unterstützung für Shell-Skripte und Cloud-Init-spezifische YAML-Syntax.

### Unterschiede


| **Merkmal**            | **CloudFormation**                                           | **Cloud-Init**                                        |
|------------------------|-------------------------------------------------------------|-----------------------------------------------------|
| **Anwendungsbereich**  | Infrastruktur-Management und Bereitstellung kompletter Systeme | Initialisierung und Konfiguration einzelner Instanzen |
| **Abhängigkeiten**     | Automatisches Management von Abhängigkeiten zwischen Ressourcen | Keine Unterstützung für Abhängigkeitsmanagement     |
| **Zielplattform**      | Speziell für AWS entwickelt                                   | Plattformunabhängig (AWS, Azure, Google Cloud usw.) |
| **Syntax**             | JSON/YAML                                                   | YAML oder Shell-Skripte                             |
| **Nutzungsebene**      | Höheres Abstraktionsniveau für ganze Architekturen           | Tieferes Niveau für die Konfiguration einzelner Instanzen |