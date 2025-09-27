# 🐧 Palmer Penguins Data Analysis Dashboard

An interactive Streamlit dashboard for performing **exploratory data analysis (EDA)** on the Palmer Penguins dataset.  
The dataset provides biological measurements for penguin species observed in the Palmer Archipelago, Antarctica.  

[![Open in Streamlit](https://static.streamlit.io/badges/streamlit_badge_black_white.svg)](https://roy-gdp-dashboard.streamlit.app/)

## 📊 Features
- Interactive filters: filter penguins by **species**, **island**, **sex**, and **body mass range**.  
- Key metrics: total penguins in dataset, average bill length (mm), and average body mass (kg).  
- Visualizations: scatter plot of **Bill Length vs. Bill Depth** (color-coded by species) and bar chart of **Average Body Mass by Species**.  
- Raw data view with expandable table.  
- Data source: [Palmer Penguins Dataset](https://allisonhorst.github.io/palmerpenguins/).  

## 🚀 How to Run Locally
Clone this repository, install dependencies, and run the Streamlit app:
```bash
git clone https://github.com/your-username/your-repo.git
cd your-repo
pip install -r requirements.txt
streamlit run streamlit_app.py
