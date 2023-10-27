# LB 324

## Aufgabe 2
Man muss zuerst überprüfen, ob Pre-commit bereits installiert ist, indem man den Befehl pre-commit --version ausführt.

1. Schritt: Falls Pre-commit noch nicht vorhanden ist, kann man es mithilfe von pip installieren:
pip install pre-commit

2. Schritt: pre-commit im Repository initialisieren: pre-commit install

Dadurch wird Pre-commit in Ihrem lokalen Git-Repository aktiviert und die in der .pre-commit-config.yaml-Datei definierten Hooks werden vor jedem Commit ausgeführt.
Mit diesen Schritten ist Pre-commit einsatzbereit und wird automatisch vor jedem Commit in Repository ausgeführt.
Mit dem Push: Der Code wird vor dem Push automatisch getestet.


## Aufgabe 4
Erklären Sie hier, wie Sie das Passwort aus Ihrer lokalen `.env` auf Azure übertragen.
