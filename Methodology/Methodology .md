# *Rainfall Time Series Analysis and trend detection for ghod basin*
 📌 Overview

This repository contains a Google Colab–based Python workflow for **rainfall time-series analysis, trend detection, and visualization**.
The script processes daily rainfall data, performs **statistical trend analysis**, and generates **publication-quality plots** to support hydrological studies, dam safety assessments, and climate variability analysis.

The methodology is suitable for:

* Dam breach and hydrological studies
* Extreme rainfall analysis
* Climate trend assessment
* Academic and technical reporting

---

## 📂 Data Description

* **Input Data**: Daily rainfall time-series (CSV / spreadsheet)
* **Key Fields**:

  * `Date`
  * `Rainfall (mm)`

The data is assumed to be continuous daily observations with missing values handled during preprocessing.

---

## 🛠️ Tools & Libraries Used

* **Python**
* **Google Colab**
* **NumPy** – numerical operations
* **Pandas** – time-series handling and statistics
* **Matplotlib** – static, high-resolution plots
* **SciPy** – statistical analysis
* **PyMannKendall** – trend detection (Mann–Kendall test)

---

## 🔄 Methodology

### 1. Data Preprocessing

* Rainfall data is imported using **Pandas**
* Date column is converted to `datetime` format
* Missing or invalid rainfall values are handled
* Time series is sorted chronologically

### 2. Exploratory Time-Series Analysis

* Daily rainfall values are plotted against time
* Seasonal and inter-annual rainfall variability is visually examined
* Peak rainfall events are identified

### 3. Trend Detection (Mann–Kendall Test)

* The **Mann–Kendall non-parametric test** is applied to rainfall time series
* Key outputs include:

  * Trend direction (Increasing / Decreasing / No trend)
  * Kendall’s Tau
  * Z-value
  * p-value (statistical significance)

This test is widely accepted for **hydrological and climatological trend analysis**.

### 4. Slope Estimation (Sen’s Slope)

* Sen’s slope estimator is used to quantify:

  * Rate of change in rainfall over time
* Helps assess long-term increasing or decreasing rainfall tendencies

### 5. Visualization

* High-resolution rainfall time-series plots
* Trend line overlay for interpretation
* Clean axis labeling suitable for reports and publications

---

## 📊 Results Summary

* The rainfall time series shows **distinct seasonal variability** with multiple peak rainfall events.
* Mann–Kendall test results indicate:

  * **Trend direction**: (Increasing / Decreasing / No significant trend)
  * **Statistical significance** assessed using p-value
* Sen’s slope provides the **magnitude of rainfall change per unit time**.
* The generated plots clearly highlight:

  * Extreme rainfall events
  * Long-term rainfall behavior

These results are useful for:

* Flood risk assessment
* Dam safety and spillway design review
* Climate change impact studies

---

## 📈 Output

* Rainfall time-series plots
* Trend analysis statistics printed in console
* Summary tables for quick interpretation

---

## 🚀 Applications

* Dam breach and flood modeling studies
* Hydrological design validation
* Climate variability and change assessment
* Academic research and technical consultancy

---

## 📌 Notes

* The methodology follows **standard hydrological and statistical practices**
* The workflow is flexible and can be extended for:

  * Monthly / annual aggregation
  * Extreme rainfall indices
  * Multi-station comparison

---

## 👤 Author

**Satwik Udupi**
Hydrology | GIS | Remote Sensing | Dam Engineering

---

If you want, next I can:

* Add a **Methodology diagram (flowchart)**
* Rewrite this for **CWC / Dam Safety Review submission**
* Create a **separate `METHODOLOGY.md` or `RESULTS.md`**
* Help you polish figures to *journal / thesis quality*
* 
