# Wordpress in Docker
 ###  Ziel
 - In dieser Aufgabe sollst du WordPress und eine MySQL-Datenbank in separaten Docker-Containern auf einer AWS EC2-Instanz in den AWS-Sandboxen bereitstellen. Der WordPress-Blog sollte über das Internet erreichbar sein. Verwende dafür Docker-Compose.


### EC2-Instanz erstellen:
 - Starte eine EC2-Instanz in AWS.

### Docker auf EC2 installieren:
 - Stelle sicher, dass Docker auf der EC2-Instanz installiert ist.

### MySQL-Container erstellen:
 - Verwende Docker, um einen MySQL-Container zu erstellen.
Lege die Datenbank und Benutzer fest.

### WordPress-Container erstellen:

 - Erstelle einen WordPress-Container und verbinde ihn mit dem MySQL-Container.

### Testen:
- Öffne einen Webbrowser und überprüfe, ob das WordPress-Blog über die öffentliche IP-Adresse der EC2-Instanz erreichbar ist.

- Richte den WordPress-Blog ein und mache dich mit ihm vertraut. 

## Herausforderungen

#### Nginx als Reverse-Proxy konfigurieren
- Installiere Nginx auf deiner EC2-Instanz.
Konfiguriere Nginx als Reverse-Proxy, um Anfragen an den WordPress-Blog in deinem Docker-Container weiterzuleiten.
#### Schütze deine App!
- Stelle sicher, dass die App nicht einfach aufgerufen werden kann. Konfiguriere NGINX so, sodass der Zugriff erst nach Eingabe von einem bestimmten Username und Passwort erfolgen kann (BasicAuth).

