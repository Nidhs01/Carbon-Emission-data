# 🌍 Carbon Emission Data Analysis

This repository contains curated datasets and tools related to carbon emissions, with a primary focus on **analyzing patterns, visualizing trends, and understanding the impact of different sectors and regions on global carbon output**. My work within this repository aims to provide insights crucial for environmental sustainability and informed climate action.

---

## 🧭 Project Overview

This project analyzes global carbon emission trends using machine learning techniques. By transforming raw climate data into actionable insights, it supports environmental policy and sustainability efforts. Tools used include Python, Jupyter Notebooks, and Random Forest models. The analysis uncovers nonlinear relationships, country-specific outliers, and sector-wise emission patterns to inform better decision-making.

---

## 🗺️ Pipeline Overview

Here’s a high-level view of the project workflow:


---

## 📁 Dataset

The main dataset I utilize is `data_cleaned.csv`. This file represents a structured and cleaned version of raw information on carbon emissions. It includes key fields that I have prepared for analysis:

* **Country or Region**
* **Year**
* **CO₂ Emissions (in metric tons)**
* **Emissions per Capita**
* **Sector-wise Emissions** (e.g., Energy, Transport, Industry)

The initial raw data, `climate_change_download_0.xls`, was the starting point for this cleaned dataset.

---

## 💡 Methodology

I followed a systematic methodology to ensure comprehensive analysis and robust model development:

1. **Data Collection and Initial Acquisition:**
   - Acquired raw data from `climate_change_download_0.xls`.
   - Cloned the GitHub repository using:
     ```
     git clone https://github.com/<your-username>/<your-repo-name>.git
     cd <your-repo-name>
     ```

2. **Data Preprocessing and Preparation:**
   - Conducted in `1_data_preparation (1).ipynb`.
   - Cleaned and structured the dataset into `data_cleaned.csv`.
   - Removed irrelevant features like "Population count" to focus on key variables.

3. **Exploratory Data Analysis (EDA):**
   - Performed in `2_data_exploration (1).ipynb`.
   - Found strong linearity between CO₂ per capita and energy use.
   - Identified nonlinear patterns and outlier clusters (e.g., UAE).

4. **Model Selection:**
   - Chose **Random Forest** due to its ability to handle nonlinearities and grouped data.
   - Avoided linear models like Linear Regression due to poor fit for the data structure.

5. **Model Development and Training:**
   - Implemented in `3_model_building.ipynb`.
   - Trained Random Forest models with **Cross-Validation (CV)** and **Hyperparameter Tuning (HPT)** for optimal performance.

6. **Evaluation:**
   - While not explicitly detailed in the notebooks, models were likely evaluated using:
     - **R² Score**
     - **Mean Absolute Error (MAE)**
     - **Root Mean Squared Error (RMSE)**

7. **Prediction and Application:**
   - Enabled time-series forecasting, cross-country comparisons, and emissions vs GDP/population studies.
   - Recommended visualization tools: **Matplotlib**, **Tableau**, or **D3.js**.

---

## 🧪 Applications

The data and the analytical framework developed in this repository can support various analytical and visualization projects, providing crucial insights for engineers and policymakers:

* **Time-series trend analysis**: Understanding how emissions change over time.
* **Cross-country emission comparisons**: Identifying leading emitters and effective mitigation strategies.
* **Emissions vs GDP/population correlation studies**: Exploring relationships between economic activity, population, and emissions.
* **Data visualization projects**: Using tools like Matplotlib, Tableau, or D3.js for clear communication of findings.
* **Exploratory work in climate science, sustainability, and environmental policy**: Informing policy decisions and scientific research.

---

## 🛠️ Technologies Used

- Python (Pandas, NumPy, Scikit-learn, Matplotlib)
- Jupyter Notebook
- Git & GitHub
- Excel (for initial data)
- Optional: Tableau or D3.js for advanced visualization

---

## ⚙️ Usage

To get started with this repository and explore the analyses I've performed, follow these steps:

1. **Clone the repository:**
   git clone https://github.com/Srinidhi davuluri/Carbon-Emission-data.git

2. **Navigate into the repository directory:**
   cd Carbon-Emission-data


The project's code is primarily written in **Jupyter Notebook**, making it accessible and easy to follow the analytical steps.

---

## 📌 Future Enhancements

- Add interactive dashboards using **Plotly Dash** or **Streamlit**
- Integrate real-time emissions data APIs
- Expand model comparison with XGBoost or Gradient Boosting Machines
- Deploy as a web app for public access

---


