# **Hospital and XR2 Deployment Analysis**

This project analyzes the geographic distribution of hospitals and XR2 robot deployments to identify coverage gaps and provide actionable recommendations for Omnicell. By integrating hospital data and XR2 deployment data, the analysis highlights regions with high potential for strategic expansion.

---

## **Project Objectives**
1. **Analyze Hospital Distribution:**
   - Examine the number of hospitals by state and region.
   - Identify high-density hospital areas.
2. **Evaluate XR2 Coverage:**
   - Highlight regions with minimal XR2 deployments.
   - Assess alignment between XR2 locations and hospital distribution.
3. **Provide Strategic Recommendations:**
   - Recommend deployment strategies for regions with significant coverage gaps.
   - Focus on actionable insights to support Omnicell’s growth.

---

## **Repository Structure**

| **Folder/File**           | **Description**                                                         |
|---------------------------|-------------------------------------------------------------------------|
| **data/**                 | Contains input datasets used in the analysis.                          |
| `Cleaned_Hospital_DF.csv`        | Hospital data with geographic locations and rankings.                  |
| `XR2_Locations_DF.csv`        | XR2 deployment locations with geographic coordinates.                  |
| `Recommendations_Table.csv`| Final recommendations table summarizing insights and suggestions.      |
| **notebooks/**            | Jupyter Notebook for data cleaning and exploratory data analysis (EDA). |
| `EDA.ipynb`      | Python notebook used for Exploritory Data Analysis.            |
| `Cleaning.ipynb`      | Python notebook used for preprocessing and data integration.            |
| **tableau/**              | Tableau dashboard file for visualizations.                             |
| `Hospital_and_XR2_Deployment_Analysis.twbx`     | Contains heat maps, ranking charts, and recommendation summaries.       |
| **README.md**             | This file, explaining the project structure and usage.                  |

---

## **Data Sources**

1. **Hospital Data:**
   - Source: [Kaggle](https://www.kaggle.com/datasets/thedevastator/hospitals-in-the-united-states-a-comprehensive-d?select=hospital_locations.csv).
   - Attributes: Geographic locations, hospital rankings.
2. **XR2 Location Data:**
   - Compiled manually from public sources:
     - LinkedIn
     - Google News
     - Omnicell investor pages.

---

## **Tools Used**

- **Python:** For data cleaning, handling missing values, and formatting (via Jupyter Notebook).
- **Excel:** For exploratory data analysis (EDA) and preliminary data checks.
- **Tableau:** For creating interactive visualizations and dashboards.
