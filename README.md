# Global Vaccination Coverage Analysis (1980–2021)
Python analysis of global childhood vaccination coverage (1980–2021). Interactive Plotly maps and charts reveal historical progress, COVID disruptions, and persistent inequities in core and newer vaccines.


Python-based exploratory data analysis of childhood immunization rates worldwide using WHO/Our World in Data dataset.

**Key Insights**
- Core vaccines (DTP3, MCV1, Pol3, BCG) rose from ~20% in 1980 to ~81–86% by 2019, with a dip to ~81% in 2021 due to COVID disruptions.
- Global DTP3 recovered to 85% by 2024 (latest WHO/UNICEF estimates), but progress has plateaued.
- Newer vaccines (PCV3, RotaC, Hib3) show clear adoption delays — many countries still below 50% in 2021.
- Persistent inequities: High coverage in Europe/Americas/East Asia (>90%); low in parts of Africa and conflict zones (<70%).

## Visualizations

### 1. Global DTP3 Coverage Evolution (1980–2021)
Interactive animated choropleth map showing, 40+ years of progress.

<img width="1340" height="622" alt="vaccine12" src="https://github.com/user-attachments/assets/b5f7c3e6-7656-438c-8d74-954f22ff1660" />


### 2. Global Vaccination Trends (Core Vaccines)
Average coverage over time.


<img width="662" height="812" alt="vaccine3" src="https://github.com/user-attachments/assets/38d8f7a3-f866-475f-8dae-7bd47ae9c039" />

### 3. Country-Level Vaccine Coverage Over Time
All vaccines for selected countries (examples).

**Rwanda** 

<img width="1326" height="732" alt="vaccine11" src="https://github.com/user-attachments/assets/64795df1-8c22-4a4d-9a33-d275ba3d8cbb" />

**Nigeria** – Progress with gaps in newer vaccines  

<img width="1476" height="737" alt="vaccine7" src="https://github.com/user-attachments/assets/d99c1a13-f463-493b-826a-9481094431e6" />


### 4. DTP3 Coverage by Country (2021)
Static choropleth highlighting geographic inequities.
<img width="1340" height="622" alt="vaccine12" src="https://github.com/user-attachments/assets/c440bf4f-9721-40c2-92eb-cd3dfdece9d4" />


## Tech Stack
- Python
- Pandas (data cleaning)
- Plotly Express (interactive visualizations)
- Jupyter Notebook

## Dataset
Source: [Our World in Data - Global Vaccination Coverage](https://ourworldindata.org/vaccination)

## Related Article
Full analysis published on Medium:  
(https://medium.com/@danisinator123/the-hidden-story-in-global-vaccination-data-a-triumph-interrupted-and-why-2026-matters-f0445135a50e)

## Setup & Run
```bash
git clone https://github.com/yourusername/global-vaccination-analysis.git
cd global-vaccination-analysis
jupyter notebook vaccinereal.ipynb
