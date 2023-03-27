# Zelda Bingo Generator

Der Zelda Bingo Generator ist ein Python-Skript, das eine zufällige Bingo-Karte auf Basis einer Liste von Aufgaben aus der Datei "botw_input.txt" erstellt. Dieses Skript verwendet die Python Imaging Library (PIL), um die Bingo-Karte als Bild zu erstellen und anzuzeigen.

## Voraussetzungen
Um dieses Skript auszuführen, benötigen Sie die folgenden Abhängigkeiten:

Python 3.x
PIL (Pillow)
requests
Installieren Sie die Abhängigkeiten mit dem folgenden Befehl:
```
pip install pillow requests
```

## Verwendung

1. Legen Sie die Datei "botw_input.txt" im selben Verzeichnis wie das Skript ab. Diese Datei sollte eine Liste von Aufgaben enthalten, die durch Zeilenumbrüche getrennt sind.
2. Öffnen Sie das Skript und ändern Sie die Variablen image_url und avatar_url entsprechend Ihren Anforderungen.
3. Führen Sie das Skript aus, indem Sie dieses Git in Jupyter Notebook öffnen.

## Anpassungen

Sie können das Skript an Ihre Bedürfnisse anpassen, indem Sie die folgenden Variablen ändern:

* **seed_str**: Ändern Sie diesen Wert, um einen anderen Seed für die Zufallsfunktion zu verwenden. Dies führt zu einer anderen Aufgabenzuordnung auf der Bingo-Karte.
* **CARD_SIZE**: Ändern Sie die Größe der Bingo-Karte.
* **FONT_NAME**: Ändern Sie den Namen der Schriftart, die für den Text auf der Bingo-Karte verwendet wird.
* **image_url**: Ändern Sie die URL des Bildes, das auf der Bingo-Karte angezeigt wird.
* **avatar_url**: Ändern Sie die URL des Avatars, der auf der Bingo-Karte angezeigt wird.
