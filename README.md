# 🌍 COVID-19 Global Trends Analysis

![Dashboard Preview](assets/preview.png) *(Optional screenshot)*

## 📌 Project Description
A data analysis project tracking COVID-19 cases, deaths, and vaccination progress across multiple countries using real-world datasets from Our World in Data. The project includes time-series analysis, country comparisons, and interactive visualizations.

## 🎯 Objectives
- Import and clean global COVID-19 data
- Analyze temporal trends in cases, deaths, and vaccinations
- Compare metrics across countries/regions
- Visualize trends with charts and maps
- Communicate findings through an interactive report

## 🛠️ Tools & Libraries
python
pandas      # Data manipulation
matplotlib  # Basic visualizations
seaborn     # Advanced statistical plots
plotly      # Interactive visualizations
jupyter     # Notebook interface
ipywidgets  # Interactive controls (optional)
🚀 How to Run
Basic Setup
Clone repository:

bash
git clone https://github.com/yourusername/covid-analysis.git
Install dependencies:

bash
pip install -r requirements.txt
Launch Jupyter Notebook:

bash
jupyter notebook COVID_Analysis.ipynb
Alternative Viewing
HTML Report: Open COVID_Analysis.html in any browser

Interactive Dashboard (if implemented):

bash
streamlit run dashboard.py
🔍 Key Insights
Vaccination Impact: Countries with >50% vaccination coverage (like UK) showed 60% lower death rates compared to sub-20% coverage countries

Regional Patterns: South American countries (Brazil) had consistently higher death rates (2.8%) than African nations (Kenya at 1.5%)

Data Gaps: Developing nations showed significant reporting lags in vaccination data

📂 Project Structure
/covid-analysis
├── data/                   # Raw and processed data
│   └── owid-covid-data.csv
├── analysis/               # Notebooks and reports
│   ├── COVID_Analysis.ipynb
│   └── COVID_Analysis.html
├── assets/                 # Visualizations
├── dashboard.py            # Streamlit app (optional)
└── requirements.txt        # Dependencies
💡 Reflections
Challenge: Inconsistent data reporting across countries required careful missing-value handling

Learning: Time-series visualization techniques effectively reveal pandemic waves

Extension: Adding mobility data could enhance analysis of lockdown impacts
