Durch die Nutzung des Befehls sudo apt-get update werden die Paketlisten neu eingelesen und aktualisiert. 
Diese werden im Verzeichnis /etc/apt/sources.list hinterlegt und sind je nach Version unterschiedlich und mit verschiedenen Variablen am Ende versehen.

```
apt-get update
```

Der Befehl sudo apt-get upgrade führt das eigentliche „Update“, in diesem Fall als Upgrade des Systems bezeichnet, aus.
Installiert werden hier alle neuen Versionen eines Paketes, falls Aktualisierungen vorhanden sind.
Die Installation der Pakete erfolgt auf den bereits auf dem System vorhandenen Paketen. Es werden keine ausgetauscht und durch neue ersetzt.

```
apt-get upgrade
```
