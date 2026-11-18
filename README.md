
<h1 align="center">TSA Passenger Complaint Hotspots and Operational Improvement Opportunities</h1>

<p align="center">
  <img src="TSA%20Complaint%20Screenshot.png" alt="TSA Passenger Complaints Power BI Dashboard" width="650">
</p>

<p align="center">
  <strong>Microsoft Power BI | Operational Analytics | Geographic Visualization | Complaint Trend Analysis | Business Intelligence</strong>
</p>

---

## Project Overview

This project uses Microsoft Power BI to analyze Transportation Security Administration (TSA) passenger complaints across U.S. airports. The dashboard examines complaint volumes, geographic concentrations, complaint categories and subcategories, and historical trends to support data-driven operational assessment.

The goal is to help identify airports and complaint areas that may warrant further investigation, prioritize opportunities for operational improvement, and communicate findings through an interactive business intelligence dashboard.

**Project Type:** Operational Analytics and Data Visualization  
**Primary Tool:** Microsoft Power BI  
**Deliverable:** Interactive Power BI Dashboard  
**Repository:** [tsa-passenger-complaints-analysis](https://github.com/crisevilindsey/tsa-passenger-complaints-analysis)

## Business Problem

Passenger complaints provide an important source of feedback about airport security screening and related TSA services. However, complaint records spanning multiple airports, categories, and reporting periods can be difficult to interpret without a consolidated analytical view.

This project addresses that challenge by organizing complaint information into an interactive dashboard that helps users explore:

- Which airports have the highest reported complaint volumes?
- Where are complaints geographically concentrated?
- Which complaint categories and subcategories account for the greatest volumes?
- How do complaint patterns change across reporting years?
- Which areas may benefit from additional operational review or process improvement?

## Data Overview

The dashboard uses TSA passenger complaint data organized by airport, reporting period, complaint category, and complaint subcategory.

The report displays the following summary indicators:

| Dashboard Indicator | Displayed Value |
| --- | ---: |
| Distinct Airports | 167 |
| Distinct Airports with TSA Complaints | 400 |
| Total Complaints | 563,700 |
| Years of Complaint Data | 10 |

**Data interpretation note:** These values are reproduced from the dashboard as displayed. The distinction between the two airport-count measures requires validation against their underlying Power BI definitions before they should be interpreted as directly comparable counts. Dashboard totals may also depend on filters and data-model relationships.

### Large Source Dataset

The **Complaints by Subcategory** source dataset is stored on Google Drive because its file size exceeds GitHub's browser upload limit.

**[Download Complaints by Subcategory Dataset (Google Drive)](https://drive.google.com/file/d/1lzjLYsJIqgxujVW4TR-bSBdbH8lsBbgb/view?usp=drive_link)**

Other supporting source files are included in the repository where available.

Users who download the Power BI report may need to update local data source paths before refreshing the data.

## Dashboard Features

### 1. Executive Summary and KPI Monitoring

The dashboard provides high-level summary cards displaying airport coverage, complaint volume, and the reporting period represented in the analysis.

These indicators provide an overview before users explore individual airports and complaint classifications.

### 2. Geographic Concentration of TSA Complaints

An interactive Azure Maps visualization displays the geographic distribution of passenger complaints across the United States.

This visual supports:

- Identifying geographic concentrations of complaints
- Exploring differences among airport locations
- Recognizing potential regional patterns
- Supporting geographically focused operational investigation

Geographic concentrations should be interpreted as complaint volumes, not necessarily complaint rates or measures of airport performance.

### 3. Top 10 Airports by Complaint Volume

A horizontal bar chart ranks the ten airports with the highest complaint counts.

This view helps identify airports that account for relatively large complaint volumes and may warrant further investigation.

Airport rankings are based on reported counts and do not independently account for passenger traffic or screening volume.

### 4. Complaint Categories Over Time

A matrix visual displays complaint categories across reporting years, allowing users to examine changes in category-level complaint volumes.

The analysis supports comparisons of:

- Complaint categories
- Historical reporting periods
- Concentrations within specific categories
- Changes in complaint distribution over time

### 5. Complaint Category Distribution

A box-and-whisker visualization compares complaint distributions across major complaint categories.

This view helps illustrate variation, spread, and potential outliers within the complaint data.

### 6. Top Complaint Subcategories

A horizontal bar chart highlights leading complaint subcategories by volume.

This provides a more detailed view of recurring complaint topics and helps identify specific areas for operational review.

### 7. Interactive Filtering

The dashboard includes slicers for:

- Region name
- Airport code
- Airport name
- Complaint category

These controls allow users to narrow the analysis and explore complaint patterns across selected dimensions.

## Analytical Approach

The project applies business intelligence and descriptive analytics techniques to TSA complaint records.

The dashboard design includes:

1. Organizing complaint data into dimensions suitable for airport, geographic, category, and time-based analysis.
2. Using Power BI to create summary indicators and comparative visualizations.
3. Exploring complaint volumes across airports and complaint classifications.
4. Visualizing geographic concentrations using Azure Maps.
5. Comparing category-level distributions and historical trends.
6. Combining multiple analytical perspectives into an interactive report intended to support operational decision-making.

The repository's Power BI file provides the report and associated data model for further inspection.

## Business Value and Operational Improvement Opportunities

The dashboard demonstrates how complaint data can support operational reporting and continuous improvement.

**Potential applications include:**

- **Operational prioritization:** Identify high-volume complaint areas for additional review.
- **Airport-level monitoring:** Compare reported complaints across airports and locations.
- **Trend analysis:** Examine whether complaint volumes and category distributions change over time.
- **Root-cause investigation:** Identify complaint categories and subcategories that warrant deeper analysis.
- **Executive reporting:** Present multiple operational indicators through a consolidated, interactive dashboard.
- **Resource planning:** Inform further investigation into where operational attention may be needed.

These are potential applications of the analysis rather than verified operational outcomes or documented TSA interventions.

## Tools and Technologies

| Tool / Technique | Application |
| --- | --- |
| Microsoft Power BI Desktop | Dashboard development and interactive reporting |
| Azure Maps | Geographic visualization of airport complaint concentrations |
| Power BI Data Modeling | Organization of complaint information for analytical reporting |
| KPI Reporting | High-level operational performance summaries |
| Descriptive Analytics | Complaint volume, category, and trend comparisons |
| Data Visualization | Bar charts, matrix, box-and-whisker plots, and interactive filters |

## How to View the Project

### Option 1: Preview the Dashboard

View the dashboard screenshot at the top of this README.

### Option 2: Open the Interactive Power BI Report

1. Download the Power BI `.pbix` file from this repository.
2. Open the file using Microsoft Power BI Desktop.
3. Allow the report visuals to load.
4. If necessary, sign in to Power BI to display the Azure Maps visualization.
5. Use the dashboard slicers to explore airports, regions, and complaint categories.

### Option 3: Access the Large Dataset

Download the [Complaints by Subcategory dataset](https://drive.google.com/file/d/1lzjLYsJIqgxujVW4TR-bSBdbH8lsBbgb/view?usp=drive_link) from Google Drive.

If refreshing the Power BI report, update the data source connections to the corresponding downloaded files.

## Scope and Limitations

- The analysis is descriptive and does not establish the underlying causes of passenger complaints.
- Airports with larger passenger volumes may also have larger complaint counts. Complaint rates would require appropriate passenger-volume denominators.
- Complaint records represent reported experiences and may not capture all passenger concerns.
- Data completeness, reporting practices, and classification changes may affect comparisons across airports and years.
- The dashboard's airport-count measures require further definition-level verification before direct comparison.
- Azure Maps may require Microsoft account authentication and appropriate Power BI settings.
- Refreshing the report outside the original development environment may require updating source file paths.
- Operational recommendations should be validated through additional investigation before implementation.

## Author

**Criselvi Lindsey**  
Data Analytics and Business Intelligence Leader  
MBA, Business Analytics | M.S. Data Science

[GitHub Profile](https://github.com/crisevilindsey)

---

<p align="center">
  <em>Transforming passenger complaint data into actionable operational insights through business intelligence and data visualization.</em>
</p>
