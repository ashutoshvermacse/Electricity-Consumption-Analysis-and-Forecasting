<details>
  <summary><strong>🇩🇪 Projektbeschreibung (Deutsch)</strong></summary>
   
Dieses Projekt befasst sich mit der Analyse des Stromverbrauchs über einen Zeitraum von rund 14 Jahren mithilfe der PJM Hourly Energy Consumption Data von Kaggle. Ziel ist es, Muster, Trends und Saisonalitäten im Datensatz zu identifizieren und Prognosemodelle zu entwickeln, um den zukünftigen Energieverbrauch vorherzusagen.

**Durchgeführte Analysen:**

1. **Visualisierung des täglichen Stromverbrauchs:**
   - Grafische Darstellung der täglichen Verbrauchsmuster zur Identifizierung von Hoch- und Niedrigverbrauchsphasen.

2. **Visualisierung des monatlichen Stromverbrauchs:**
   - Visualisierung der monatlichen Verbrauchstrends zur Analyse langfristiger Entwicklungen.

3. **Saisonalitätsprüfung mittels ACF-Plot:**
   - Erstellung eines Autocorrelation Function (ACF) Plots des monatlichen Stromverbrauchs zur Untersuchung saisonaler Muster.

4. **Vergleich monatlicher Verbrauchstrends:**
   - Gegenüberstellung und Analyse der monatlichen Verbrauchstrends der Jahre 2005, 2010 und 2015.

5. **Zeitreihenzerlegung (Decomposition):**
   - Aufschlüsselung der monatlichen Daten in Trend-, Saison- und Restkomponenten zur besseren Interpretation des Verbrauchsverhaltens.

**Modellierung und Prognose:**

Zur Vorhersage des Stromverbrauchs wurden vier verschiedene Modelle entwickelt:

- **ARIMA (AutoRegressive Integrated Moving Average)**
- **SARIMAX (Seasonal AutoRegressive Integrated Moving-Average with eXogenous factors)**
- **Exponential Smoothing**
- **RNN (Recurrent Neural Network)**

Unter diesen Modellen lieferte Exponential Smoothing die besten Ergebnisse. Darauf basierend wurde der Stromverbrauch für die nächsten 24 Monate mit hoher Genauigkeit prognostiziert.
</details>

---

<details>
  <summary><strong>🇬🇧 Project Description (English)</strong></summary>

This project focuses on analyzing electricity consumption over a span of approximately 14 years using the PJM Hourly Energy Consumption Data from Kaggle. The objective is to explore patterns, trends, and seasonality in the data, and to build predictive models to forecast future consumption.

**Key Analyses Performed:**

1. **Visualization of Daily Electricity Consumption:**
   - Graph displaying daily usage patterns to identify high and low consumption periods.

2. **Visualization of Monthly Electricity Consumption:**
   - Monthly consumption trends highlighted through visual plot.

3. **Seasonality Check using ACF Plot:**
   - Autocorrelation Function (ACF) plot of monthly electricity consumption to assess seasonality.

4. **Comparison of Monthly Consumption Trends:**
   - Examination of monthly electricity consumption trends in the years 2005, 2010, and 2015.

5. **Decomposition of Monthly Electricity Consumption:**
   - Breaking down monthly consumption data into seasonal, trend, and residual components.

**Model Building and Forecasting:**

Four different models were developed to predict electricity consumption:
- **ARIMA (AutoRegressive Integrated Moving Average)**
- **SARIMAX (Seasonal AutoRegressive Integrated Moving-Average with eXogenous factors)**
- **Exponential Smoothing**
- **RNN (Recurrent Neural Network)**

Among these, the Exponential Smoothing model provided the best results. Using this model, electricity consumption was forecasted for the next 24 months with a high degree of accuracy.

</details>
