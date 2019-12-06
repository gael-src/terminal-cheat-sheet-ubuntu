# Terminal-Cheat-Sheet-ubuntu

# Apollo 18 
## Terminal Cheat-Sheet (version 2)


### Navigation
> **pwd** print working directory ‚zeige aktuelles Directory‘

> **cd** steht for change directory und dient - unter Berücksichtigung von Groß- / Kleinschreibung! - zum Wechsel in ein (Unter-) Verzeichnis. cd ist ein eingebauter Befehl der Shell

> **cd /** is the only way to navigate to a directory to check log, execute a program/application/script and for every other task

> **cd ~ (alt-gr +)** cd ~ damit wird der Home Ordner bezeichnet, von dissen standpunkt aus kommt man zu smtlichen weiteren Verzeichnissen des PCs. In der regel Staret man auch an disen Punkt.

> **cd ..** Mariusz 15:01 Uhr
Wechselt ein Verzeichnis zurück (/media/disk -> /media)

> **cd -** wechselt zum letzten Arbeitsverzeichnis zurück


### Anzeigen
> **ls** list directory contents

> **ls -l** ist ein Befehl, der Dateien und Verzeichnisse in einem Verzeichnis auflistet

> **ls -a** Als Parameter können Verzeichnis- oder Dateinamen übergeben werden.  ls -a zeige alle Dateien und Verzeichnisse an - auch die "versteckten", deren Namen mit einem Punkt beginnen.

> **ls -la** Zeigt eine detaillierte Liste an, in der Eigentümer, Gruppe, Erstellungsdatum, Größe und andere Parameter einschließlich versteckter Dateien angezeigt werden


### Datei Manipulation
> **touch \<dateiname>** operating system which is used to create, change and modify timestamps of a file

> **mkdir \<ordnername>** steht für make directory und dient zum Anlegen von einem oder mehreren Verzeichnissen.

> **rm \<dateiname>**  is used to remove objects such as files on from the file system

> **rm -r \<ordnername>** To remove or delete a file.

> **cp \<dateiname> <ordnername>** It supports moving one or more files or folders with options for taking backups and preserving attributes

> **mv \<dateiname> <verzeichnisname>** Mit diesen befehl werden die Darten in ein Ortner verschomen die auf der gleichen ebene sind.

> **mv \<dateiname> \<anderer dateiname>** Mit diesen befehl werden die Darten Unbenant.
Wobei drauf zuachten ist das der neue nahme nicht schon vorhanden ist, den ansnsten wird diese datei überschriben.

> **xdg-open \<dateiname>** Datei oder URL mit dem Standard-Programm des Benutzers öffnen

> **less** Less ist ein Befehl, der den Inhalt einer Datei anzeigt oder einen Befehl seitenweise in Ihrem Terminal ausgibt. Less ist am nützlichsten, um den Inhalt großer Dateien oder die Ergebnisse von Befehlen anzuzeigen, die viele Ausgabezeilen erzeugen. Der von less angezeigte Inhalt kann durch Eingabe von Tastaturkürzeln navigiert werden.

> **strg-c** Das sind exit Befehle. Wenn man zum Beispiel mit dem less Befehl eine Datei anzeigt, kann man mit q wieder zurück zur normalen Konsole springen. Oft, wenn man sonst nicht weißt wie man zu der normalen Konsole zurück kommt hilft strg+c .

> **q** Das sind exit Befehle. Wenn man zum Beispiel mit dem less Befehl eine Datei anzeigt, kann man mit q wieder zurück zur normalen Konsole springen. Oft, wenn man sonst nicht weißt wie man zu der normalen Konsole zurück kommt hilft strg+c .


### Help
> **<command> --help** --help which is used for listing all possible commands that are pre-installed in Ubuntu

> **man <command>** man is used to display the user manual of any command that we can run on the terminal

### Nano
> **Nano <dateiname>** nano is an easy to use command line text editor for Unix and Linux operating systems

### npm

> **npm install -g <software name>** npm install -g \<software name>
Installiert Javascript Software oder Dateien mithilfe des node package managers. Mit dem flag -g sagen wir, dass er dieses Package global installieren soll. Also kann man es von überall aus dem Dateisystem verwenden.

> **npm uninstall -g \<software name>** Deinstalliert Javascript Programme oder Dateien die mit dem Node Package Manager global installiert wurden.

### Ubutnu
> **sudo** Kurz für als substiute user, do. Mit diesem Befehl kann man andere Befehle mit den Rechten Superusers (oder root User) starten. Oft wird man hierbei nach dem Passwort gefragt.

> **sudo apt update** Neueinlesen der Paketlisten

> **sudo apt install <software name>** Zeigt alle Pakete an, in deren Namen oder Beschreibung der Begriff SUCHBEGRIFF vorkommt

> **sudo apt install \<software name>** installiert das Paket PAKETNAME 

> **which \<software name>** which ist ein Befehl zum Auffinden der ausführbaren Datei

> **sudo apt remove \<software name>** "Apt remove" entfernt nur die Binärdateien eines Pakets. Es hinterlässt Restkonfigurationsdateien. Wenn Sie "apt remove" verwendet haben, um eine bestimmte Software zu entfernen und anschließend erneut zu installieren, enthält Ihre Software dieselben Konfigurationsdateien.

> **sudo apt autoremove** Wenn Sie ein Paket installieren, werden häufig zusätzliche Pakete installiert, bei denen es sich um die Abhängigkeiten handelt. Wenn Sie dieses Paket jetzt deinstallieren, bleiben die Abhängigkeiten im System erhalten. apt autoremove entfernt diese Abhängigkeiten, aber nur diejenigen, die von anderen installierten Paketen nicht benötigt werden.

### Mardown
> \# heading

> \## secondary heading

> \**bold*\* 

> \_italicized_

> *listenpunkt

> \> block code
