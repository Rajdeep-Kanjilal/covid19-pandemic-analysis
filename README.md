# 🦠 COVID-19 Pandemic Analysis

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.8%2B-blue?logo=python&logoColor=white" />
  <img src="https://img.shields.io/badge/Pandas-Data%20Analysis-150458?logo=pandas" />
  <img src="https://img.shields.io/badge/Matplotlib-Visualization-blue" />
  <img src="https://img.shields.io/badge/Jupyter-Notebook-orange?logo=jupyter" />
</p>

<p align="center">
  <strong>Exploring the COVID-19 pandemic through data analysis and visualization.</strong>
  <br>
  An exploratory data analysis project focused on understanding global COVID-19 trends, country-level patterns, mortality rates, and socioeconomic factors.
</p>

---

## 📌 About the Project

The COVID-19 pandemic affected countries differently in terms of infection rates, recoveries, mortality, and healthcare impact.

In this project, I explore global COVID-19 data using Python and data analysis techniques to understand how the pandemic evolved across different regions.

The analysis combines COVID-19 case records from JHU CSSE with socioeconomic indicators from the World Bank.

The main focus is on:

- Understanding global and continental COVID-19 trends.
- Comparing confirmed cases, recoveries, deaths, and active cases.
- Exploring country-level mortality patterns.
- Studying relationships between socioeconomic indicators and pandemic statistics.
- Creating meaningful visualizations to communicate findings.

## 🎯 Project Objectives

1. Analyze the progression of COVID-19 across countries and continents.
2. Identify countries with higher confirmed cases and mortality.
3. Understand daily changes and growth patterns.
4. Explore relationships between GDP, population, healthcare expenditure, and COVID-19 outcomes.
5. Present observations through charts, graphs, and statistical analysis.

## 📂 Data Sources

| Source | Purpose |
|---|---|
| JHU CSSE COVID-19 | Confirmed cases, recoveries and deaths |
| World Bank | GDP and population indicators |
| World Bank | Urban and rural population |
| World Bank | Life expectancy |
| World Bank | Healthcare expenditure |
| Datahub | Country and continent mapping |

**Dataset period:** December 2019 – October 2020.

## 🛠️ Tools & Technologies

- **Python** – Core programming language
- **Pandas** – Data manipulation and analysis
- **NumPy** – Numerical operations
- **Matplotlib** – Data visualization
- **Seaborn** – Statistical visualization
- **SciPy** – Statistical analysis
- **Jupyter Notebook** – Exploratory analysis and documentation

## 🔍 Project Workflow

### 1. Data Collection
- Collected COVID-19 case data from JHU CSSE.
- Retrieved socioeconomic indicators from World Bank.
- Used country and continent mapping information.

### 2. Data Cleaning & Wrangling
- Processed country-level COVID-19 records.
- Handled missing values and date formats.
- Organized confirmed, recovered, and death records.
- Calculated active cases and mortality rates.

### 3. Exploratory Data Analysis
- Examined global case progression.
- Compared pandemic trends across continents.
- Analyzed country-level statistics.
- Explored mortality patterns.

### 4. Feature Engineering
- Calculated daily changes in confirmed cases.
- Compared countries based on days since reaching 100 confirmed cases.
- Prepared country-level summary statistics.
- Combined socioeconomic indicators with pandemic data.

### 5. Data Visualization
Created visual representations to understand:
- Global case progression.
- Continental comparisons.
- Country-level trends.
- Mortality distribution.
- Socioeconomic correlations.

## 📊 Notebooks Included

| Notebook | Analysis |
|---|---|
| `Data-wrangling.ipynb` | Data preparation and processing |
| `Exploratory-analysis-globally.ipynb` | Global and continental trends |
| `Exploratory-analysis-mortality.ipynb` | Country-level mortality analysis |
| `Exploratory_analysis_socioeconomic.ipynb` | Socioeconomic relationships |
| `Exploratory_analysis_fancy_plot.ipynb` | Advanced data visualization |

## 📈 Key Observations

The analysis explores several patterns from the early pandemic period:

- Global confirmed cases approached 35 million by October 2020.
- India played a significant role in the growth of cases across Asia.
- COVID-19 impact varied considerably across countries.
- Mortality patterns differed between countries.
- Socioeconomic indicators showed varying relationships with reported pandemic outcomes.

*Note: These observations refer to the historical analysis period, not current COVID-19 statistics.*

## ⚙️ Installation & Setup

Clone the repository:

```bash
git clone https://github.com/Rajdeep-Kanjilal/covid19-pandemic-analysis.git
```

Move into the project directory:

```bash
cd covid19-pandemic-analysis
```

Install the required libraries:

```bash
pip install -r requirements.txt
```

Launch Jupyter Notebook:

```bash
jupyter notebook
```

Open the notebooks and execute the required cells after ensuring the necessary datasets and project dependencies are available.

## 🚧 Project Status

The repository setup and notebook upload are in progress. Notebook execution and output verification are pending for some files.

## 👨‍💻 Author

**Rajdeep Kanjilal**

- GitHub: [Rajdeep-Kanjilal](https://github.com/Rajdeep-Kanjilal)
- Portfolio: [rajdeepprojects.com](https://rajdeepprojects.com)
