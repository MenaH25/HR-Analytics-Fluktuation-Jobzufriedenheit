# HR-Analytics-Fluktuation-Jobzufriedenheit
Mini-Projekt in Power BI: Analyse von Fluktuation, Jobzufriedenheit und Work-Life-Balance im HR-Kontext mit DAX-Measures und Visualisierungen
# Projektziel (Deutsch)
Dieses Mini-Projekt demonstriert, wie HR-Daten mit **Power BI** und **DAX** analysiert und visualisiert werden können. Im Fokus stehen Fluktuationsraten, Jobzufriedenheit und Work-Life-Balance nach Abteilungen und Geschlecht. Ziel ist es, Muster sichtbar zu machen, die für **HR-Entscheidungen** relevant sind.
# Project Goal (English)
This mini-project demonstrates how HR data can be analyzed and visualized using **Power BI** and **DAX**. The focus is on employee attrition, job satisfaction, and work-life balance across departments and gender. The aim is to highlight patterns that are relevant for **HR decision-making**.
# Technologien (Deutsch)
Power BI Desktop
DAX (Measures für Kennzahlen)
SQL (geplant für erweiterte Analysen)
Python (geplant für erweiterte Analysen)
# Technologies (English)
Power BI Desktop
DAX (Measures for KPIs)
SQL (planned for data preparation)
Python (planned for extended analytics)
# Visualisierungen / Visualizations
1. Kündigungsrate nach Geschlecht / Attrition by gender
2. Kündigungsrate pro Abteilung / Attrition by department
3. Durchschnittliche Work-Life-Balance nach Abteilung und Geschlecht / Average work-life balance by department and gender
4. Durchschnittliche Jobzufriedenheit nach Abteilung und Geschlecht / Average job satisfaction by department and gender
# Screenshots
# DAX-Measures
1 Kündigungsrate nach Geschlecht = DIVIDE(CALCULATE(COUNTROWS('HRData'), 'HRData'[Attrition] = "YES"), CALCULATE(COUNTROWS('HRData')),0)
1 Kündigungsrate pro Abteilung = DIVIDE(CALCULATE(COUNTROWS('HRData'), 'HRData'[Attrition] = "Yes"), CALCULATE(COUNTROWS('HRData')),0)
1 Durchschnittliche Work Life Balance = Average('HRData'[WorkLifeBalance])
1 Durchschnittliche Jobzufriedenheit = Average('HRData'[JobSatisfaction])



