# UK Road Accident Analysis (2019–2022)

This repository offers a comprehensive exploration of the patterns, causes, and impacts of road accidents across the United Kingdom between 2019 and 2022. Using advanced data analytics and visualization tools like Tableau, we aim to uncover actionable insights that can drive improvements in road safety and public awareness.

---

## 1. Project Objective

The UK sees thousands of road accidents each year, affecting lives, property, and the broader community. The objective of this project is to:
- **Visualize accident trends** over time and geography
- **Identify risk factors** (weather, road type, time, vehicle category, etc.)
- **Spot regional variations** and accident hotspots
- **Support policy formulation** for improved safety and resource allocation
- **Educate stakeholders** (public, authorities, researchers) on accident dynamics

---

## 2. Dataset

**Source:**  
- [UK Vehicle Accident Database 2019-2022 (Kaggle)](https://www.kaggle.com/datasets/charliescott556/uk-vehicle-accident-database-2019-2022)

**Contents:**  
- >1.3 million accident records
- Accident date, time, and location (lat/lon, region, local authority)
- Severity (fatal, serious, slight)
- Types of vehicles involved
- Environmental and weather conditions
- Road surface, lighting, and junction details
- Casualty demographics

**Why This Dataset?**  
- Up-to-date and broad coverage
- Standardized and detailed fields
- Suitable for mapping, temporal analysis, and statistical modeling

---

## 3. Repository Structure

- `Final Project.twbx`  
  Tableau workbook containing interactive dashboards, charts, and maps.

- `Group 9 _ Final Report (1).pptx`  
  PowerPoint presentation summarizing project goals, methodology, key findings, and recommendations.


- README and documentation files

---

## 4. Methodology

### Data Preparation
- **Cleaning:** Removal of duplicates, handling missing values, standardizing field names.
- **Enrichment:** Deriving new features (e.g., accident hour, weather category, risk index).
- **Integration:** Combining multiple CSV files if necessary.

### Analysis & Visualization
- **Spatial Analysis:**  
  - Mapping accidents by region, local authority, and coordinates  
  - Identifying hotspots using heatmaps and kernel density estimation

- **Temporal Analysis:**  
  - Accident counts by year, month, day of week, and hour  
  - Seasonality and trend decomposition

- **Severity Analysis:**  
  - Fatal, serious, and slight accident rates  
  - Correlation with contributing factors

- **Factor Analysis:**  
  - Impact of weather, lighting, road type, junction control, and vehicle type  
  - Demographic analysis of casualties

- **Recommendations:**  
  - Policy and engineering suggestions  
  - Educational and enforcement strategies

---

## 5. Key Findings & Dashboards

The Tableau dashboards reveal:
- **Geographical patterns:** Urban areas and major intersections are high-risk zones.
- **Temporal spikes:** Accidents peak during rush hours, weekends, and adverse weather.
- **Severity clusters:** Certain regions have disproportionately high fatality rates.
- **Contributing factors:** Poor lighting, wet road surfaces, and junction types play significant roles.
- **Vehicle types:** Motorcycles and bicycles show higher fatality rates per accident.

*See the Tableau workbook for interactive maps, filters, and detailed charts.*

---

## 6. How to Use This Repository

### For Viewers:
- Open `Final Project.twbx` in Tableau Desktop or Tableau Public.
- Review the `Group 9 _ Final Report (1).pptx` for a narrative summary and recommendations.

### For Analysts/Researchers:
- Download the dataset from Kaggle and place it in your working directory.
- Use or adapt scripts for additional analysis.
- Fork the repository to contribute new insights or methods.


---

