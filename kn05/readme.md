VPC (Virtual Private Cloud):
Eine VPC ist ein privates Netzwerk innerhalb einer Cloud-Umgebung, das logisch isoliert ist. Es dient als Basis für die Bereitstellung von Cloud-Ressourcen wie Servern, Datenbanken und Speicher. Die VPC hat einen definierten IP-Adressbereich (z. B. ein CIDR-Block wie 10.0.0.0/16), in dem sich alle Ressourcen befinden. Subnet:
Ein Subnet ist ein kleinerer Bereich innerhalb des IP-Adressbereichs der VPC, der Ressourcen gruppiert und logisch trennt. Subnets können in verschiedenen Availability Zones (AZs) einer Region existieren. Ein Subnet ermöglicht eine granulare Kontrolle über die Platzierung von Ressourcen und deren Netzwerkzugriff. Anzahl vordefinierter Subnets: Die Anzahl der Subnets hängt von der Architektur der VPC ab. Typischerweise werden in einer VPC mehrere Subnets vordefiniert:
Private Subnets (für interne Ressourcen wie Datenbanken). Public Subnets (für Ressourcen, die über das Internet erreichbar sein sollen). Die IP-Ranges der Subnets decken gemeinsam den gesamten IP-Adressbereich der VPC ab, aber kein einzelnes Subnet darf den gesamten Bereich abdecken (Subnetze dürfen sich nicht überlappen).
Unterschied zwischen öffentlicher und privater IP:
Öffentliche IP:
Diese IP-Adresse ist von überall im Internet erreichbar. Sie wird häufig für Server oder andere Ressourcen verwendet, die öffentlich zugänglich sein müssen (z. B. Websites oder APIs). Beispiel: 52.123.45.67.
Private IP:
Diese IP-Adresse ist nur innerhalb eines privaten Netzwerks (z. B. der VPC) erreichbar. Sie wird für die interne Kommunikation zwischen Ressourcen verwendet. Beispiel: 192.168.1.10. Statische IP: Eine statische IP ist eine IP-Adresse, die dauerhaft einer Ressource (z. B. einer EC2-Instanz) zugewiesen bleibt. Im Gegensatz zu einer dynamischen IP ändert sie sich nicht bei Neustarts oder anderen Ereignissen. Sie wird oft verwendet für:
DNS-Einträge, um konsistente Zugriffe zu gewährleisten. Verbindungen, die auf zuverlässigen IP-Adressen beruhen. Ein Beispiel für eine statische öffentliche IP in AWS ist eine Elastic IP (EIP).

Die Server haben in der Subnetz Sub-KN05 (Ip: 127.31.0.0/20) erstellt.
Webserver: 127.32.0.50
DB-Server: 127.32.0.60

![](1.PNG)
![](2.PNG)
![](3.PNG)
![](4.PNG)
![](5.PNG)
![](6.PNG)
![](7.PNG)
![](8.PNG)