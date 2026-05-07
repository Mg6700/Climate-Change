# Temperature Rising — Climate Change Analysis Dashboard

**Tools:** Power BI, DAX  
**Domain:** Climate Analytics | Environmental Data | Long-term Trend Forecasting  
**Portfolio:** [mg67.vercel.app](https://mg67.vercel.app/) | **GitHub:** [Mg6700](https://github.com/Mg6700)

---

## Project Overview

This project analyzes global temperature data spanning from 1750 to 2023 — over 270 years of climate records — to visualize the trajectory of global warming. The dashboard tracks average temperatures by city and country, identifies cities experiencing the fastest temperature rise rates, and projects future temperature trends through 2050. It provides one of the longest temporal views possible in climate data analysis.

---

## Dashboard Preview

<img width="985" height="559" alt="image" src="https://github.com/user-attachments/assets/65764582-c840-4553-8014-e0e84b68e00e" />


---

## Dataset

| Field | Description |
|---|---|
| Period | 1750 – 2023 (historical) + forecast to 2050 |
| Coverage | Cities and countries worldwide |
| Metrics | Average temperature, temperature change, temperature rising rate (% per year) |
| Filters | Month, Year, Country |

---

## Key Metrics (Global Average)

| Metric | Value |
|---|---|
| Global Average Temperature | 18.18°C |
| Average Temperature Change | 20.60°C |
| Average Temperature Rising Rate | 0.021% per year |

---

## Dashboard Features

- **Month filter** — analyze temperature patterns by specific months
- **Year filter** — select any year from 1750 to 2023
- **Country filter** — isolate any nation for country-level analysis
- **Average Temperature Cities** — top 10 hottest cities by average temperature
- **Highest Temperature Change Cities** — cities with the largest absolute temperature increase
- **Highest Temperature Change Rate Cities** — cities ranked by annual rate of temperature rise (%)
- **Average Temperature over Years** — 270-year trend line with 2050 forecast projection
- **Average Temp by Country** — Bing Maps heatmap showing geographic temperature distribution

---

## Hottest Cities (Average Temperature)

| City | Avg Temperature |
|---|---|
| Umm Durman (Sudan) | 29°C |
| Madras (India) | 28°C |
| Jiddah (Saudi Arabia) | 28°C |
| Fortaleza (Brazil) | 27°C |
| Ho Chi Minh City (Vietnam) | 27°C |
| Bangkok (Thailand) | 27°C |
| Mogadishu (Somalia) | 27°C |
| Hyderabad (India) | 27°C |
| Surabaya (Indonesia) | 27°C |
| Rangoon (Myanmar) | 27°C |

---

## Cities with Highest Temperature Change

| City | Temperature Change |
|---|---|
| Seoul | 31°C |
| Jinan | 30°C |
| Nanjing | 29°C |
| Shanghai | 29°C |
| Wuhan | 28°C |
| Baghdad | 28°C |
| Ankara | 26°C |
| Mashhad | 25°C |
| Tokyo | 24°C |
| Kabul | 23°C |

---

## Cities with Highest Temperature Rising Rate

| City | Rising Rate (% per year) |
|---|---|
| Seoul | 0.049% |
| Jinan | 0.047% |
| Nanjing | 0.046% |
| Shanghai | 0.045% |
| Wuhan | 0.045% |
| Tokyo | 0.039% |
| Baghdad | 0.039% |
| Mashhad | 0.038% |
| Chongqing | 0.036% |
| Kabul | 0.034% |

---

## Key Findings

**1. Global temperature has risen from ~4°C in 1750 to ~21°C today — a 17°C increase over 270 years**
The 270-year trend line shows temperatures were extremely low in the pre-industrial era (1750–1800), with a dramatic acceleration beginning around 1900 coinciding with industrialization. The most recent data points show temperatures stabilizing around 19–21°C.

**2. The 2050 forecast projects continued rise to ~21-22°C**
The trend line's forward projection shows continued warming through 2050, though the forecast cone widens significantly — indicating increasing uncertainty in long-range climate projections.

**3. East Asian cities are warming fastest — Seoul leads at 0.049% per year**
Seoul, Jinan, Nanjing, Shanghai, and Wuhan all appear in both the highest temperature change AND highest rising rate rankings — suggesting East Asia is experiencing disproportionately accelerated warming relative to global averages.

**4. Hottest cities are equatorial, but fastest warming is in temperate zones**
The hottest cities (Umm Durman, Jiddah, Bangkok) are near the equator — but the fastest-warming cities (Seoul, Jinan, Tokyo) are in temperate East Asia. This highlights the difference between absolute heat and rate of change.

**5. The temperature spike in the early 1800s likely reflects volcanic activity**
The trend line shows an unusual spike around 1800 followed by a sharp dip — consistent with the documented cooling effect of major volcanic eruptions (e.g., 1815 Mount Tambora), providing historical validation of the dataset's accuracy.

**6. Baghdad and Kabul appear in both temperature change and rate rankings**
Middle Eastern cities experiencing rapid urbanization and regional climate shifts appear in multiple high-change categories — reflecting both climate change acceleration and urban heat island effects.

---

## 270-Year Temperature Trajectory

| Era | Approximate Avg Temp | Key Driver |
|---|---|---|
| 1750 | ~4°C | Pre-industrial baseline |
| 1800 | ~9°C | Early industrialization |
| 1850 | ~11°C | Coal era begins |
| 1900 | ~15°C | Industrial revolution peak |
| 1950 | ~17°C | Post-WWII economic expansion |
| 2000 | ~19°C | Globalization and emissions growth |
| 2023 | ~21°C | Current measurement |
| 2050 (forecast) | ~21-22°C | Projected continuation |

---

## Technical Highlights

- 270-year time series — one of the longest temporal ranges in any portfolio project
- Bing Maps heatmap for geographic temperature intensity visualization
- 2050 forecast projection with confidence interval on trend chart
- Three separate city ranking visuals (absolute temp, change, rate) enabling multi-dimensional comparison
- Month, Year, and Country slicers enabling full cross-dimensional filtering
- DAX measures for temperature change rate calculation and forecast modeling

---

## Data Source

Berkeley Earth Surface Temperature Dataset. NOAA Global Surface Temperature Records.

---

*Created by Mayur Goyal | [Portfolio](https://mg67.vercel.app/) | [LinkedIn](https://www.linkedin.com/in/mg67)*
