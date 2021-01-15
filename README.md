# Erzeugen von synthetischen Trainingsdaten für maschinelle Lernverfahren in Anwendung in der Landwirtschaft


- AirSim (Speicherort: ...\documents):
    - settings.json: Von AirSim bereitgestellte Datei, die stark bearbeitet wurde. Sie legt Fahrzeug, Bildgröße, Bildtyp und Belichtung fest



- script (Speicherort: ...\Microsoft Visual Studio\2019\Community\AirSim\PythonClient): <br> Stand der Dateien während die Bilder eine Menge von Pflanzen zeigten.
    - setup_path.py: Gegebene Datei von AirSim
    - cocoformat.py: speichert Informationen im Cocoformat
    - script.py: Positioniert die Kamera und speichert Bilder <br> Ausführung wird in der Datei gezeigt


- newscript (Speicherort: ...\Microsoft Visual Studio\2019\Community\AirSim\PythonClient): <br> Neuester Stand der Dateien. Kann sowohl Einzelpflanzen als auch eine Menge verarbeiten.
    - placement.py: Setzt die Pflanzen an gegebene Positionen, ermöglicht das Löschen der Pflanzen <br> Die Funktionen werden einzeln im Unreal Editor aufgerufen
    - pictures.py: Positioniert die Kamera und speichert Bilder <br> Ausführung wird in der Datei gezeigt
    - cococrowd.py: speichert Informationen im Cocoformat, geeignet für eine Pflanzenmenge
    - cocosingle.py: speichert Informationen im Cocoformat, geeignet für Einzelpflanzen

