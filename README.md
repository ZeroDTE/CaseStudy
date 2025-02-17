# Süßigkeiten-Analyse Projekt

## Übersicht
Dieses Projekt analysiert einen Datensatz von Süßigkeiten und deren Eigenschaften, um die Beliebtheit (Gewinnprozent) vorherzusagen. Es verwendet maschinelles Lernen, um die wichtigsten Faktoren zu identifizieren, die den Erfolg einer Süßigkeit beeinflussen.

## Funktionen
- Datenanalyse von Süßigkeiteneigenschaften
- Implementierung eines linearen Regressionsmodells mit Gradient Descent
- Generierung synthetischer Süßigkeiten-Kombinationen
- Visualisierung der Modellergebnisse
- Detaillierte Analyse der Modellkoeffizienten

## Hauptkomponenten
1. **Datenvorverarbeitung**
   - Standardisierung der Features
   - Train-Test-Validation Split
   - Feature-Engineering mit Interaktionstermen

2. **Modellierung**
   - Lineares Regressionsmodell
   - Gradient Descent Optimierung
   - Regularisierung zur Vermeidung von Überanpassung

3. **Synthetische Daten**
   - Generierung realistischer Süßigkeiten-Kombinationen
   - Implementierung von Domain-Constraints
   - Preis- und Eigenschaftsanpassungen

## Ergebnisse
- Trainings-R²: 0.64
- Validierungs-R²: 0.38
- Test-R²: 0.20

## Technische Anforderungen
- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn

## Verwendung
1. Jupyter Notebook starten
2. Alle Zellen sequentiell ausführen
3. Visualisierungen und Analysen betrachten

## Datensatz
Der verwendete Datensatz enthält folgende Eigenschaften:
- Schokolade
- Fruchtgeschmack
- Karamell
- Nüsse/Mandeln
- Nougat
- Knusprige Waffel
- Zuckergehalt
- Preisanteil
- Gewinnprozent (Zielvariable)

Der Datensatz stammt von FiveThirtyEight und ist verfügbar unter:
https://github.com/fivethirtyeight/data/tree/master/candy-power-ranking

Lizenziert unter der Creative Commons Attribution 4.0 International license:
https://creativecommons.org/licenses/by/4.0/


