# Tamil Nadu GDDP Summary Dashboard

An interactive Tableau dashboard to explore the **Gross District Domestic Product (GDDP)** trends across districts in Tamil Nadu from 2011 to 2020, and **sectorwise** for 2023.
  
## Dashboard Preview
[![Tamil Nadu GDDP Dashboard](https://public.tableau.com/static/images/QK/QKR4C8XRQ/1.png)](https://public.tableau.com/shared/QKR4C8XRQ)

## Visualization
- Top 5 Districts GDDP wise for 2011 to 2020 and 2021 to 2023
- Top 5 Sectors - District wise
- Sector wise top Districts
- Geo Visualization of districts with respect to sectors

## Datasets Used

1. **Tamil Nadu District-level GDDP Data (2011–2020)**  
   Source: [OpenCity.in Dataset](https://data.opencity.in/dataset/tamil-nadu-district-level-gddp-data)

2. **District Geographic Boundaries (KML)**  
   Source: [OpenCity.in - Tamil Nadu KML](https://data.opencity.in/dataset/6c8f66fe-11f8-440c-9c81-4a3ea9c6e049/resource/10d03f1a-6e30-488d-8afc-ed4616dcbbf4/download/tamil-nadu.kml)

---

## Data Challenges

- There were inconsistencies in district names between the spatial (map) file and the GDDP dataset, which required manual standardization.
- As new districts were formed over time, the data was split into two periods: 2011–2020 and 2021–2023. Each period has its own filters and visualizations to reflect administrative changes accurately and avoid misinterpretation.
- The GDDP dataset was pivoted (reshaped) appropriately to suit the visualizations in Tableau.<br>
Note: GDDP used in this Dashboard are current GDDP not constant GDDP
---

