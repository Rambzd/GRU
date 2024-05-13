# GRU-Aktienkursvorhersagemodell

## Beschreibung
Dieses Projekt entwickelt ein Modell zur Vorhersage der Aktienkurse mithilfe von Gated Recurrent Units (GRU). Es verwendet historische Aktienkursdaten sowie relevante wirtschaftliche Indikatoren und andere Datenquellen.

## Schritte

1. **Datensammlung**: Beschaffung historischer Aktienkursdaten sowie anderer relevanter Datenquellen wie Wirtschaftsindikatoren.
2. **Datenbereinigung und -vorverarbeitung**: Bereinigung von Daten von Ausreißern und fehlenden Werten sowie gegebenenfalls Durchführung von Transformationen oder Feature-Engineering.
3. **Modellentwicklung**: Implementierung eines GRU-Modells zur Vorhersage der Aktienkurse. Experimentieren mit verschiedenen Modellarchitekturen und Hyperparametern zur Optimierung der Leistung.
4. **Modellvalidierung**: Validierung des Modells mit Testdaten und geeigneten Metriken wie Mean Absolute Error (MAE) oder Root Mean Squared Error (RMSE). Vergleich der Leistung des Modells mit einer Baseline-Methode wie SARIMA und Vorstellung von Metriken wie MAE, RMSE und R² zur Bewertung der Effektivität.
5. **Ergebnispräsentation**: Erstellung einer Präsentation, die den Ansatz, die Modellarchitektur, die Ergebnisse und mögliche Einschränkungen des Vorhersagemodells darlegt. Präsentation der Ergebnisse vor der Klasse.

## Autor
Ramin Babazade  
Email: rambzd@gmail.com

## Inhaltsverzeichnis
- [Introduction](#Einführung)
- [Project Structure](#Projektstruktur)
- [Usage](#Verwendung)
- [Dependencies](#Abhängigkeiten)
- [Development](#Entwicklung)
- [License](#Lizenz)

## Dateien

- `GRU_Main.ipynb`: Hauptdatei für die Modellentwicklung.
- `GRU_Test.ipynb`: Testdatei für das entwickelte Modell.
- `AAPL.csv`: Historische Aktienkursdaten von AAPL (Beispiel).
- `NVDA.csv`: Historische Aktienkursdaten von NVDA (Beispiel).
- `playground.txt`: Beispieltextdatei.
## Einführung
Dieses Projekt zielt darauf ab, ein Modell zur Vorhersage der Aktienkurse mithilfe von Gated Recurrent Units (GRU) zu entwickeln. Durch die Nutzung historischer Aktienkursdaten sowie relevanter wirtschaftlicher Indikatoren und anderer Datenquellen streben wir an, präzise und effektive Vorhersagen für zukünftige Aktienkurse zu treffen. Dieses Modell kann Investoren und Finanzanalysten dabei unterstützen, fundierte Entscheidungen zu treffen und das Risiko von Investitionen zu minimieren.

## Projektstruktur
Die Projektstruktur besteht aus den folgenden Hauptkomponenten:

- `GRU_Main.ipynb`: Diese Jupyter Notebook-Datei enthält den Hauptcode für die Entwicklung des GRU-Aktienkursvorhersagemodells.
- `GRU_Test.ipynb`: In diesem Jupyter Notebook werden Tests für das entwickelte Modell durchgeführt, um seine Leistung zu überprüfen.
- `AAPL.csv` und `NVDA.csv`: Beispieldateien mit historischen Aktienkursdaten von AAPL und NVDA. Diese Dateien dienen zur Demonstration und können durch echte Daten ersetzt werden.
- `playground.txt`: Eine Beispieltextdatei, die für Testzwecke verwendet wird.

## Verwendung
Um das GRU-Aktienkursvorhersagemodell zu verwenden, führen Sie die folgenden Schritte aus:

1. Laden Sie die historischen Aktienkursdaten von Yahoo sowie relevante zusätzliche Daten herunter.
2. Führen Sie die `GRU_Main.ipynb`-Datei aus, um das Modell zu trainieren und Vorhersagen zu generieren.
3. Verwenden Sie bei Bedarf die `GRU_Test.ipynb`-Datei, um das Modell zu testen und seine Leistung zu bewerten.

## Abhängigkeiten
Das Projekt erfordert die folgenden Abhängigkeiten:

- Python 3.x
- Jupyter Notebook
- TensorFlow
- Pandas
- NumPy
- Matplotlib

Sie können die erforderlichen Pakete über pip installieren:

```
pip install tensorflow pandas numpy matplotlib
```

## Entwicklung
Bei der Entwicklung des Projekts können folgende Hinweise hilfreich sein:

- Überprüfen Sie regelmäßig die Leistung des Modells und experimentieren Sie mit verschiedenen Architekturen und Hyperparametern, um die Vorhersagegenauigkeit zu verbessern.
- Achten Sie auf eine sorgfältige Datenbereinigung und -vorverarbeitung, um die Qualität der Vorhersagen zu gewährleisten.
- Dokumentieren Sie Ihren Code und Ihre Experimente sorgfältig, um die Reproduzierbarkeit zu erleichtern.

## Lizenz
Dieses Projekt wird unter der MIT-Lizenz veröffentlicht. Weitere Informationen finden Sie in der `LICENSE`-Datei.
