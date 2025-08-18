# Air Quality Pollution

**Air Quality Pollution** This project analyzes air pollution data in the United States from **2000–2016**, focusing on regional and city-level trends.  
The goal is to explore minimum, maximum, and average pollution levels, generate both static visualisations (Matplotlib/Seaborn) and interactive dashboards (Plotly), and deliver actionable insights in a clear, reproducible workflow.  

The project was structured using Agile/Kanban best practices with Trello, GitHub, and automated workflows to ensure collaboration and timely delivery.

# ![CI logo](https://codeinstitute.s3.amazonaws.com/fullstack/ci_logo_small.png)


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

📦 AIR-QUALITY-DASHBOARD
┣ 📂 data
┃ ┣ raw/ # Raw dataset
┃ ┗ analysis.csv # Cleaned dataset
┣ 📂 notebooks
┃ ┗ EDA.ipynb # Exploratory Data Analysis
┣ 📂 scripts
┃ ┣ clean_data.py # Data cleaning pipeline
┃ ┗ generate_charts.py # Visualization generator
┣ 📂 visuals
┃ ┣ static/ # Matplotlib/Seaborn plots
┃ ┗ interactive/ # Plotly dashboards
┣ 📄 requirements.txt
┣ 📄 README.md
┗ 📄 LICENSE

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
* List all dashboard pages and their content, either blocks of information or widgets, like buttons, checkboxes, images, or any other item that your dashboard library supports.
* Later, during the project development, you may revisit your dashboard plan to update a given feature (for example, at the beginning of the project you were confident you would use a given plot to display an insight but subsequently you used another plot type).
* How were data insights communicated to technical and non-technical audiences?
* Explain how the dashboard was designed to communicate complex data insights to different audiences. 

## Unfixed Bugs
* Please mention unfixed bugs and why they were not fixed. This section should include shortcomings of the frameworks or technologies used. Although time can be a significant variable to consider, paucity of time and difficulty understanding implementation are not valid reasons to leave bugs unfixed.
* Did you recognise gaps in your knowledge, and how did you address them?
* If applicable, include evidence of feedback received (from peers or instructors) and how it improved your approach or understanding.

## Development Roadmap
* What challenges did you face, and what strategies were used to overcome these challenges?
* What new skills or tools do you plan to learn next based on your project experience? 

## Deployment
### Heroku

* The App live link is: https://YOUR_APP_NAME.herokuapp.com/ 
* Set the runtime.txt Python version to a [Heroku-20](https://devcenter.heroku.com/articles/python-support#supported-runtimes) stack currently supported version.
* The project was deployed to Heroku using the following steps.

1. Log in to Heroku and create an App
2. From the Deploy tab, select GitHub as the deployment method.
3. Select your repository name and click Search. Once it is found, click Connect.
4. Select the branch you want to deploy, then click Deploy Branch.
5. The deployment process should happen smoothly if all deployment files are fully functional. Click now the button Open App on the top of the page to access your App.
6. If the slug size is too large then add large files not required for the app to the .slugignore file.


## Main Data Analysis Libraries
* Here you should list the libraries you used in the project and provide an example(s) of how you used these libraries.


## Credits 

* In this section, you need to reference where you got your content, media and extra help from. It is common practice to use code from other repositories and tutorials, however, it is important to be very specific about these sources to avoid plagiarism. 
* You can break the credits section up into Content and Media, depending on what you have included in your project. 

### Content 

- The text for the Home page was taken from Wikipedia Article A
- Instructions on how to implement form validation on the Sign-Up page was taken from [Specific YouTube Tutorial](https://www.youtube.com/)
- The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)

### Media

- The photos used on the home and sign-up page are from This Open-Source site
- The images used for the gallery page were taken from this other open-source site



## Acknowledgements (optional)
* Thank the people who provided support through this project.