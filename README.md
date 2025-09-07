# 🌞 Solar Synergy: Solar Data Analysis

Welcome to **Solar Synergy's** project repository!  

This repo contains code for analyzing the disparities in renewable solar energy adoption in the world and how we can use these insights to provide affordable solar energy to underserved regions.

## Project Overview  
**Core Interest**: Improving solar energy adoption in underdeveloped or low-access regions.
* Regions with high solar potential but low deployment due to cost or infrastructure barriers.
* Goal: Use data-driven insights to design low-cost, scalable solar solutions.

## Repository Structure  
```text
solar-analysis/
├── data/
│   ├── dataset1.csv
│   ├── dataset2.csv
│   └── dataset3.csv
├── outputs/
│   └── output.csv
├── analysis.ipynb
├── README.md
└── requirements.txt
```

## Datasets
Here are the datasets used for this project:
* #01 renewable-share-energy.csv: Records the share of total energy consumption that comes from renewable sources (solar, wind, hydro, bioenergy, etc.) for each country from 1965 to 2022.
* #02 modern-renewable-energy-consumption.csv: Records the annual consumption of modern renewable energy (solar, wind, hydro, geothermal, bioenergy, etc.) in TWh for each country from 1965 to 2022.
* #03 modern-renewable-prod.csv: It records the annual electricity generation (in TWh) from solar, wind, hydro, and other renewables (like bioenergy) for each country from 1965 to 2022
* #04 share-electricity-renewables.csv: Records the percentage share of electricity generation from renewable sources (solar, wind, hydro, bioenergy, etc.) for each country from 1965 to 2022.
* #12 solar-energy-consumption.csv: Tracks the total amount of solar energy consumed annually by each country, typically in terawatt-hours (TWh).
* #13 installed-solar-PV-capacity.csv: Shows the cumulative installed solar photovoltaic (PV) capacity per country per year, likely in megawatts or gigawatts.
* #14 solar-share-energy.cstv: Measures the percentage of a country’s total primary energy derived from solar sources, adjusted for fossil fuel equivalence.
* #15 share-electricity-solar.csv: Indicates the percentage of a country’s electricity generation that comes specifically from solar power.
* Inequality in Education (Around the World): Differentiates low-income versus high-income countries according to their Human Development Index (HDI) rank.


### Local Setup
```
git clone solar-analysis
cd solar-analysis
pip install -r requirements.txt
jupyter notebook analysis.ipynb
```

### GitHub Branch Strategy:
```text
main                   
├── dev
```

### Daily Workflow:
**Start work (everyone does this)**
```
git checkout dev
git pull origin dev
```

**Push progress**
```
git add .
git commit -m "Progress on analysis"  
git push origin dev
```
