# Air Quality Pollution

**Air Quality Pollution** This project analyzes air pollution data in the United States from 2000–2016, focusing on regional and city-level trends.  
The goal is to explore minimum, maximum, and average pollution levels, generate both static visualisations (Matplotlib/Seaborn) and interactive dashboards (Plotly), and deliver actionable insights in a clear, reproducible workflow.  

The project was structured using Agile/Kanban best practices with Trello, GitHub, and automated workflows to ensure collaboration and timely delivery.

## Dataset Content
* The dataset contains U.S. air pollution measurements across multiple cities and regions between 2000 and 2016.
It includes minimum, maximum, and average daily pollutant levels for multiple pollutants.

- Raw Dataset: Original government-published dataset (large, multi-GB).
- analysis.csv: Cleaned dataset after handling missing values, standardizing column names, and removing duplicates.
- The dataset is a manageable size (under 100 MB) to ensure smooth version control and reproducibility.


## Business Requirements
- Understand long-term air quality trends across U.S. regions and cities.
- Identify most polluted and cleanest cities to support environmental policy analysis.
- Build reproducible pipelines for cleaning, analyzing, and visualizing air quality data.
- Provide stakeholders with interactive dashboards for exploration.

## Features
- **Data Cleaning & Validation**  
- Handle missing values and outliers  
- Standardize column names & formats  
- Produce a cleaned dataset (`analysis.csv`)  

- **Exploratory Data Analysis (EDA)**  
- Summary statistics by city and region  
- Trends over time (2000–2016)  
- Correlations and key metrics  

- **Visualizations**  
- Static charts (Matplotlib/Seaborn)  
- Interactive dashboards (Plotly)  
- Heatmaps, boxplots, and trend lines  

- **Project Management**  
- Trello board with milestones and workflows  
- Clear definition of completed  
- Automated task tracking (Butler, labels, checklists) 

## Hypothesis and how to validate?
-  Hypothesis 1: Air quality has improved overall from 2000–2016.
- Validate using trend line plots of average pollutant levels.
- Hypothesis 2: Some cities/regions remain consistently more polluted.
- Validate using max/min statistics and boxplots by city.
- Hypothesis 3: Pollution spikes follow seasonal patterns.
- Validate using time series plots with monthly/seasonal aggregation.

## Project Plan
- Data Collection & Cleaning – Raw data converted to cleaned analysis.csv.
- Exploratory Analysis – Summary stats and baseline plots.
- Advanced Visualization – Heatmaps, boxplots, regional trends.
- Reporting – Written insights, dashboards, final presentation.

![alt text](image.png)

## The rationale to map the business requirements to the Data Visualisations
- Identify cleanest/polluted regions → Top 10 bar charts & boxplots.
- Track long-term trends → Line charts of mean values per year.
- Support interactive exploration → Plotly dashboards for stakeholders.
- Compare variability → Boxplots to highlight seasonal/city-level variation.

## Analysis techniques used
- Summary Statistics: min, max, mean values.
- Visualization: static (Seaborn/Matplotlib), interactive (Plotly).
- Time Series Analysis: trends from 2000–2016.
- Heatmaps & Correlation Matrices: pollutant relationships across time.
## Limitations:
- Missing data in some regions required interpolation.
- Seasonal trends only partially visible in aggregated annual data.

## Ethical considerations
- Bias: Dataset covers only U.S. cities — findings may not generalize globally.
- Fairness: Ensure visualizations don’t exaggerate small differences.
- Transparency: Full cleaning pipeline is shared for reproducibility.

## Dashboard Design
- Homepage: Overview (national trends, key metrics).
- Regional Trends: Line charts per region.
- City Analysis: Top 10 polluted/cleanest cities.
- Heatmaps: Pollution levels over time.
- Designed for clarity & accessibility, targeting both policymakers (summary view) and analysts (deep dive).

## Unfixed Bugs
- Minor rendering issues in Plotly dashboards (browser-specific).
- Some missing pollutant data not imputed — left blank to avoid bias.

## Development Roadmap
- Phase 1: Data Cleaning & Setup.
- Phase 2: EDA & Basic Visualizations.
- Phase 3: Interactive Dashboards & Advanced Insights.
- Future: Add predictive modelling (forecast pollution levels).

## Main Data Analysis Libraries
- pandas → Data wrangling.
- numpy → Numeric operations.
- matplotlib & seaborn → Static charts.
- plotly → Interactive visualizations.
- scipy/statsmodels → Statistical analysis.


## Credits 

### Content 

-  Pollution dataset from U.S. Environmental Protection Agency (EPA).
- EDA inspiration from Towards Data Science tutorials.
- ChatGpt, CoPilot, Grok AI

### Media

- Icons via Font Awesome.
- Trello board structure influenced by Agile/Kanban templates.



## Acknowledgements (optional)
Thanks to mentors, peers, and open-source community contributors.
Special thanks to Code Institute for project structure inspiration.