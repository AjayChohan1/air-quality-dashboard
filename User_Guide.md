# User Guide – Pollution Analytics Dashboard For Local Health Authorities

## 1. Getting Started
Open the Power BI Dashboard (shared as a .pbix file or via Power BI Service). The dashboard loads with the pollution dataset as the baseline reference.

## 2. Exploring Pollution Data (Baseline)
- **Overview Page:** Summary of pollution across all cities.  
- **Trends Page:** Time-series changes in pollutants (daily, monthly, yearly).  
- **Breakdown Page:** Concentrations of pollutants by region.  
- **Filters:** Use City, Date Range, or Pollutant Type to narrow the dataset.  

## 3. Transposing Your Health Data
This dashboard is designed as a template. Local Health authorities can transpose their own health dataset to explore relationships between air pollution and specific diseases.

### Step A: Prepare Your Health Data
- Save in Excel or CSV format.  
- Required fields: `Date (YYYY-MM-DD)`, `City/Region` (matching dashboard naming), `Health Indicator` (e.g., asthma admissions, COPD cases, cardiovascular events).  
- Ensure clean data: remove blanks, duplicates, and standardize formats.  

### Step B: Import Health Data into Power BI
1. Open the Power BI file (.pbix).  
2. Go to **Home → Get Data → Excel/CSV**.  
3. Select your local health dataset and load it.  

### Step C: Link Health Data to Pollution Data
1. Switch to **Model view** in Power BI.  
2. Create relationships: `Date → Date`, `City/Region → City/Region`.  
3. Save the updated model.  

## 4. Analyzing Pollution–Health Relationships
Once your health data is linked, use the **Health Relationship page** (template visuals provided).  
- Compare pollutant levels against health outcomes side by side.  
- Apply filters for city, pollutant, or timeframe.  
- Use scatterplots or correlation visuals to explore possible associations.  

**Example:** Filter to a single city and compare daily NO2 with asthma admissions to check for patterns in spikes.  

## 5. Exporting Insights
- Use **Export → PDF or PowerPoint** to create reports.  
- Export combined pollution and health tables to Excel for advanced analysis.  
- Get AI to help with generating insights from raw data, highlighting subtle patterns professionals may miss.  

## 6. Important Notes
- The dashboard does not contain health data by default; each city must supply and import its own dataset.  
- The tool highlights possible correlations but does not establish causation.  
- All health data remains under the control of the local authority.  
