# 🚗 NYC Traffic Collisions Analysis

A data analysis project examining 238,421 traffic collision records across New York City's five boroughs — identifying danger zones, peak periods, leading causes, and actionable safety recommendations.

---

## 📋 Table of Contents
- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Key Findings](#key-findings)
- [Recommendations](#recommendations)
- [Tools Used](#tools-used)
- [How to Use](#how-to-use)
- [Project Structure](#project-structure)
- [Author](#author)

---

## Project Overview

This project analyses NYC traffic collision data from 2021 to 2023 to identify:
- Which boroughs have the most collisions and fatalities
- Who is most at risk — pedestrians, cyclists, or motorists
- What causes the most accidents
- When collisions peak throughout the year
- Where safety interventions are most urgently needed

---

## Dataset

| Property | Detail |
|----------|--------|
| **File** | `NYC_Collisions.xlsx` |
| **Records** | 238,421 collisions |
| **Features** | 18 columns |
| **Period** | January 2021 – 2023 |

### Features include:
- **Location:** Borough, Street Name, Cross Street, Latitude, Longitude
- **Time:** Date, Time of collision
- **Cause:** Contributing Factor
- **Vehicle:** Vehicle Type
- **Victims:** Persons Injured, Persons Killed, Pedestrians Injured/Killed, Cyclists Injured/Killed, Motorists Injured/Killed

---

## Key Findings

### Overview
| Metric | Value |
|--------|-------|
| Total collisions | 238,421 |
| Total persons injured | 116,226 |
| Total persons killed | 635 |
| Injury rate | 48.8% |
| Fatality rate | 0.27% |

### Collisions by Borough
| Borough | Collisions | Deaths |
|---------|-----------|--------|
| Brooklyn | 76,416 | 183 |
| Queens | 63,751 | 161 |
| Bronx | 41,255 | 124 |
| Manhattan | 38,234 | 105 |
| Staten Island | 11,568 | 37 |

### Deaths by Road User Type
| Road User | Deaths |
|-----------|--------|
| Pedestrians | 286 (45%) |
| Motorists | 268 (42%) |
| Cyclists | 47 (7%) |

### Top Contributing Factors
| Factor | Incidents |
|--------|-----------|
| Driver Inattention/Distraction | 58,308 |
| Failure to Yield Right-of-Way | 16,555 |
| Following Too Closely | 15,519 |
| Improper Lane Usage | 10,733 |
| Unsafe Speed | 8,429 |

### Peak Collision Month
- **March** is the highest month with **25,099** collisions
- **December** is the lowest with **16,948** collisions

---

## Key Insights

1. **Driver inattention is the #1 cause** — 58,308 incidents, nearly 4x the next biggest factor. Mobile phone use and distractions are the primary problem.
2. **Brooklyn is the most dangerous borough** — leads in both total collisions (76,416) and deaths (183).
3. **Pedestrians are the most vulnerable** — 286 deaths (45% of all fatalities) despite not operating vehicles.
4. **March is the peak danger month** — 25,099 collisions, likely linked to weather transitions and increased activity.
5. **Passenger vehicles dominate** — 201,842 incidents (85% of all collisions).
6. **Massive data gap** — 58,262 incidents listed as "Unspecified" cause, hiding actionable patterns.

---

## Recommendations

1. **Launch a distracted driving campaign** — target phone use and inattention with enforcement and public awareness.
2. **Prioritise pedestrian safety in Brooklyn and Queens** — these boroughs lead in collisions and fatalities.
3. **Improve collision data quality** — 58,262 "Unspecified" causes must be reduced through better reporting systems.
4. **Increase traffic enforcement in March** — the peak month needs targeted patrols and speed controls.
5. **Expand protected cycling infrastructure** — cyclists are disproportionately vulnerable relative to their numbers.
6. **Target failure-to-yield hotspots** — second biggest cause at 16,555 incidents; junction design improvements can help.

---

## Tools Used

- **Microsoft Excel** — data storage,initial exploration,pivot table and interactive dashboard
- **Python (pandas)** — data analysis and statistical summaries
- **Claude AI** — insight generation and analysis support

---

## How to Use

1. Clone this repository:
   ```bash
   git clone https://github.com/okelewinifred/nyc-collisions-analysis.git
   ```

2. Open the dataset/dashboard:
   ```
   NYC_Collisions.xlsx

---

## Project Structure

```
📦 nyc-collisions-analysis
 ┣ 📄 README.md                      ← You are here
 ┣ 📊 NYC_Collisions.xlsx             ← Raw dataset amd dashboard
 ┗ 📁 outputs/                        ← Charts and reports
```

---

## Author

**Okelewinifred**
- GitHub: [@okelewinifred](https://github.com/okelewinifred)

---

*This project was completed as part of a data analytics portfolio.*
