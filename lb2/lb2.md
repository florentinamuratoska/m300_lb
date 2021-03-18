# LB2 Florentina Muratoska


## **Inhaltsverzeichnis**
* Einleitung
* Grafische Übersicht
* Befehle
    * Vagrant
    * Linux
    * Git
* Testfälle
* Quellenverzeichnis

## **Einleitung**
Für meine LB2 erstelle ich mithilfe von Vagrant einen Webserver. Dort wird eine Webseite gehostet. 

## **Grafische Übersicht**
## **Befehle**
### **Git**
Lokales Repository erstellen:
```
cd <Name Verzeichnis>
git init
```
Lokales Repository klonen:
```
git clone <Servername>:<Pfad zum Repository> [Verzeichnis-Name]
```
Dateien oder ganze Verzeichnisse unter Git-Verwaltung stellen:
```
git add <Datei-/Verzeichnisname>
```
Aktuellen Projektstand sichern:
```
git commit
```
Repository-Status abfragen:
```
git status
```
Datei verschieben
```
git mv <Quelldatei> <Ziel>
```
Datei löschen
```
git rm <Datei> 
git rm -r <Verzeichnis>
```
Lokalen Arbeitsstand in das entfernte Repository einpflegen
```
git push
```
Aktuellen Dateiinhalt mit dem Stand des letzten Commits vergleichen:
```
git diff <Datei>
```
Versionsgeschichte betrachten
```
git log
```
### **Vagrant** 
Mit folgendem Befehl initialisiert man eine gewünschte Box
```
vagrant init Beispiel/Box
```
Starten der Vagrant Box
```
vagrant up
```
### **Vagrantfile**
Definition der Box
```
config.vm.box "Windows" oder "Ubuntu" ...
```
Welcher Anbieter die Maschine Hostet
```
config.vm.provider "Virtualbox" oder "VMware" ...
```
Netzwerk konfiguration der VM
```
config.vm.network "forwarded_port" 
config.vm.network "private_network"
config.vm.network "public_network"
```
Folgendes Beispiel Zeigt auf wie man direkt beim starten der VM das Betriebsystem
mit dem Service apache2 vorinstalliert startet.
```
config.vm.provision "shell", inline <<-SHELL
    apt-get update
    apt-get install -y apache2
SHELL
```
### **Linux** 
Hier ist eine Tabelle mit ein paar Linux Grundbefehlen 
| Befehl                             | Beschreibung                                         |
|:----------------------------------:|:----------------------------------------------------:|
| sudo apt-get install «Paket»       | Dieser Befehl dient um etwas zu installieren         |
| sudo cp «Dateiname» «Ziel»         | Kopiert ein gewünschtes File an einem bestimmten Ziel|
| ls                                 | Kann man sehen was in einem Ordnervorhanden ist      |
| sudo rm «Dateiname»                | Mann kann ein File löschen mit diesem Befehl         |
| sudo apt-get update                | Aktualisiert man das OS                              |
### **Testfälle**


