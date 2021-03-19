# LB2 Florentina Muratoska

----------------------------------------------------------

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
### Nginx Oberfläche
Bild:

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
Startet VM
```
vagrant up
```
VM herunterfahren
```
vagrant halt
```
Zustand der VM
```
vagrant status
```
SSH Zugriff auf VM
```
vagrant ssh
```
Neustart der VM
```
vagrant reload
```
VM erstellen
```
vagrant init ubuntu/trusty64
```
Netzwerk konfiguration der VM
```
config.vm.network "forwarded_port" 
config.vm.network "private_network"
config.vm.network "public_network"
```

### **Linux** 
Hier ist eine Tabelle mit ein paar Linux Grundbefehlen 
| Befehl        | Beschreibung|
| ------------- |:-------------:|
| cd "Ordnername"     | Wechselt in den entsprechenden Ordner    |
| "Befehl" --help     | Zeigt Hilfe für den angegebenen Befehl an     |
| ls     | Zeigt den Inhalt des aktuellen Verzeichnisses an     |
|mkdir  | Erstellt einen Ordner |
| clear | Terminalausgabe löschen |
| nano "Datei" | Datei bearbeiten (ggf. erstellen) |

### **Testfälle**
#### Testfall 1

| ID            | 01            |
| ------------- |:-------------:|
| Beschreibung     |     |
| Erwartetes Ergebnis     |  |
#### Durchführung
| Tester/in          |          |
| ------------- |:-------------:|
| Datum     |    |
| Testergebnis     |      |
| Fehlerbeschreibung |    |

#### Testfall 2

| ID            | 02            |
| ------------- |:-------------:|
| Beschreibung     |     |
| Erwartetes Ergebnis     |  |
#### Durchführung
| Tester/in          |          |
| ------------- |:-------------:|
| Datum     |    |
| Testergebnis     |      |
| Fehlerbeschreibung |    |

#### Testfall 3

| ID            | 03            |
| ------------- |:-------------:|
| Beschreibung     |     |
| Erwartetes Ergebnis     |  |
#### Durchführung
| Tester/in          |          |
| ------------- |:-------------:|
| Datum     |    |
| Testergebnis     |      |
| Fehlerbeschreibung |    |

#### Testfall 4

| ID            | 04            |
| ------------- |:-------------:|
| Beschreibung     |     |
| Erwartetes Ergebnis     |  |
#### Durchführung
| Tester/in          |          |
| ------------- |:-------------:|
| Datum     |    |
| Testergebnis     |      |
| Fehlerbeschreibung |    |

#### Testfall 5

| ID            | 05           |
| ------------- |:-------------:|
| Beschreibung     |     |
| Erwartetes Ergebnis     |  |
#### Durchführung
| Tester/in          |          |
| ------------- |:-------------:|
| Datum     |    |
| Testergebnis     |      |
| Fehlerbeschreibung |    |


