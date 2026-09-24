# 🦠 COVID-19 Exploratory Data Analysis (EDA)

![COVID-19 Analysis](https://img.shields.io/badge/Data_Analysis-COVID--19-blue?style=for-the-badge&logo=python)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Plotly](https://img.shields.io/badge/Plotly-%233F4F75.svg?style=for-the-badge&logo=plotly&logoColor=white)

## 📘 Project Objective
The goal of this project is to analyze the global COVID-19 dataset to uncover meaningful trends, correlations, and insights regarding the spread of the virus, its fatality, and the impact of vaccinations worldwide. 

## 🧠 Skills & Methodologies
- **Data Cleaning:** Handling missing values, standardizing datetime formats, dropping duplicates, and correcting data types.
- **Data Visualization:** Creating interactive and static visual plots to communicate findings (Matplotlib, Seaborn, Plotly).
- **Exploratory Data Analysis (EDA):** Statistical summarization, correlation analysis, and trend identification.

## 📂 Dataset Information
The dataset used in this project tracks global COVID-19 statistics.
- **Source:** [Our World in Data (OWID)](https://ourworldindata.org/covid-cases) / Kaggle
- **Key Columns:** `total_cases`, `new_cases`, `total_deaths`, `population`, `people_vaccinated`, `life_expectancy`, etc.
- *Note: Raw CSV data files are ignored in Git to save repository space, but can be downloaded and placed in `data/raw/`.*

## 📊 Key Findings & Insights
1. **Top Affected Nations:** The USA, India, and Brazil reported the highest cumulative numbers of total cases and total deaths.
2. **Infection Peaks:** The year 2021 and early 2022 recorded the most significant global spikes in daily new cases (largely due to new variants like Omicron).
3. **Vaccination Impact:** Countries with higher vaccination rates per hundred people demonstrated a noticeably lower mortality rate in subsequent waves.
4. **Economic Correlation:** There is a moderate positive correlation between GDP per capita and testing rates/vaccination rollout speeds.

## 🧰 Tech Stack & Tools
- **Python** 
- **Pandas** & **NumPy** for Data Manipulation
- **Matplotlib** & **Seaborn** for Static Visualizations
- **Plotly Express** for Interactive Visualizations
- **Jupyter Notebook** for interactive code execution

## 🚀 How to Run Locally

1. **Clone the repository:**
   ```bash
   git clone https://github.com/HimashMadushanka/COVID19_EDA.git
   cd COVID19_EDA
   ```

2. **Install required dependencies:**
   ```bash
   pip install pandas numpy matplotlib seaborn plotly jupyter
   ```

3. **Download the dataset:**
   - Download the COVID-19 dataset from OWID or Kaggle.
   - Place the CSV file in the `data/` or `data/raw/` directory and name it `covid_data.csv`.

4. **Run the Jupyter Notebook:**
   ```bash
   jupyter notebook notebooks/covid19_eda.ipynb
   ```

## 📁 Repository Structure
```text
COVID19_EDA/
├── data/                       # Contains dataset (gitignored)
├── figures/                    # Saved plots and visual outputs
├── notebooks/
│   └── covid19_eda.ipynb       # Main EDA Notebook
├── .gitignore                  # Hidden files and caches to ignore
└── README.md                   # Project documentation
```


