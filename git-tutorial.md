# Kleine Git / Github  Einführung

## Wichtige Befehle

### git init

### git status

### git add 'Dateiname' || (add . --> alle Dateien)

### git commit -m "message"

### git log
#### --pretty=oneline

### git revert [commit id]
- einen commit rückgängig machen
- ältere commits können zu merge Konflikten führen

### git reset --hard HEAD~2 
- letzte zwei commits löschen

### git reset --soft HEAD~1
- den letzten commit in die staging area zurücksetzten (letzten commit bearbeiten)