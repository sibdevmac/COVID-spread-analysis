# 🌍 COVID-19 Global Spread Analysis

## 📌 Overview

The COVID-19 pandemic affected the world severely, spreading rapidly from one nation to another. Media narratives often became polarized, but data-driven analysis provides clearer insights into how the virus actually propagated globally.

This project analyzes the global spread of COVID-19 using timeline-based visualizations and statistical insights.

## 📂 Dataset

Johns Hopkins University CSSE COVID-19 Dataset:

https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/time_series_covid19_confirmed_global.csv

---

# 🔎 Key Findings

---

## 1️⃣ First Reported Cases (January 22, 2020)

The first confirmed cases outside China were reported on:

- China  
- Japan  
- United States  
- Thailand  
- South Korea  

📌 Insight:
The timing coincided with the Chinese New Year, a period of high international travel and migration. This strongly suggests mobility played a critical role in early global transmission.

---

## 2️⃣ Early Growth Acceleration

Initial global case count progression:

| Date | Total Countries with Cases |
|------|----------------------------|
| Jan 22 | 6 |
| Jan 23 | 9 |
| Jan 24 | 10 |
| Jan 25 | 12 |
| Jan 26 | 13 |

- Growth on Jan 23: 50%
- Growth on Jan 26 (relative surge): 116.67%

📌 Insight:
The acceleration phase demonstrates early exponential growth characteristics typical of infectious disease spread.

---

## 3️⃣ Rapid Global Expansion (First 3–4 Months of 2020)

<img width="629" height="470" alt="image" src="https://github.com/user-attachments/assets/14590ce9-120f-4767-a726-de352c45f1e4" />

The graph **"Number of Countries with COVID Over Time"** shows:

- Extremely rapid spread in Q1 2020
- Plateau phase after lockdown implementations
- Continued case growth but slower geographic expansion

📌 Policy Observation:
Many countries introduced lockdowns in March 2020 (e.g., India), which contributed to stabilization.

---

## 4️⃣ Early Phase Growth Differences by Country

Early exponential growth comparison:

- United States: 10920.69
- Spain: 2155.91
- Italy: 2075.38

📌 Interpretation:
Countries that delayed border controls and mobility restrictions experienced significantly higher early growth.

Countries like:
- New Zealand  
- India  
- Israel  

implemented stronger containment measures early on.

---

## 5️⃣ Spread Across Nations (First 3 Months)

The number of affected nations increased sharply before stabilizing.

📌 Insight:
Social distancing and travel restrictions significantly reduced the rate of geographic spread after initial acceleration.

---

## 6️⃣ Phase-Based Spread Patterns

<img width="629" height="470" alt="image" src="https://github.com/user-attachments/assets/25e64727-d41c-4f7a-a39f-5d8845f3aea1" />

The graph **"Fastest Growing Countries – Early Phase"** reveals:

- 🟢 Green Line: Rapid mid-2020 acceleration and later Omicron spike
- 🔴 Red & 🟣 Purple Lines: Delayed but strong 2021–2022 surges
- 🟠 Orange Line: Controlled spread

📌 Interpretation:
Spread patterns varied depending on:
- Lockdown timing
- Vaccination campaigns
- Population density
- Border control policies

---

## 7️⃣ Continental Spread Speed

Average time to widespread infection:

| Continent | Days to Major Spread |
|-----------|----------------------|
| Asia | 34.5 days |
| Europe | Faster than Americas |
| South America | Moderate |
| North America | Moderate |
| Africa | Slower |
| Oceania | 297 days |

📌 Key Insight:
Oceania slowed spread approximately **8.6× slower than Asia**, largely due to strict border policies and geographic isolation.

---

## 8️⃣ Estimated Early-Phase R₀ Proxy

The reproduction proxy showed high early spread in small island nations such as:

- Nauru  
- Tuvalu  
- Micronesia  
- Marshall Islands  

📌 Statistical Insight:
Smaller populations tend to show higher proportional growth due to denominator effects.

The graph **"Average Early-Phase R₀ Proxy by Continent"** confirms that microstates can display higher apparent transmission rates despite overall continental containment.

---

## 9️⃣ Seasonal Peak Observation

Peak global spread trends were observed around:

- February–March cycles

Possible reasons:
- Relaxation of restrictions
- Emergence of new variants (e.g., Omicron)
- Seasonal mobility increases

---

# 📊 Methodology

- Data Cleaning & Transformation using Python (Pandas)
- Time-Series Aggregation
- Growth Rate Calculation
- R₀ Proxy Estimation
- Geographic Animation (Plotly)
- Comparative Continental Analysis

---

# 🎯 Conclusion

This analysis demonstrates that:

- Early international mobility accelerated spread.
- Policy timing significantly influenced outbreak intensity.
- Small population countries show amplified proportional growth.
- Geographic isolation (Oceania) delayed widespread transmission.
- COVID spread must be analyzed in phases rather than as a single wave.

Data-driven investigation provides clearer insight than narrative-based interpretation.

---

# 🛠 Tools Used

- Python
- Pandas
- Plotly
- Time-Series Analysis
- Geographic Visualization

---

# 👨‍💻 Author

Sibankar Saha
