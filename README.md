# QCTO-Workplace_Module_Global_Deforestation

# **Deforestation Analysis and Prediction**

---

## **Project Overview**
Deforestation is a significant global issue, impacting ecosystems, biodiversity, and contributing to climate change. This project analyzes deforestation trends and builds predictive models to estimate future deforestation rates based on historical data. The dataset used includes forest area measurements from various countries over multiple years, offering a comprehensive view of global deforestation trends.

---

## **Goals and Objectives**
1. **Data Analysis:** Explore and understand deforestation patterns over time and across regions.
2. **Prediction Models:** Develop machine learning models to predict forest area loss.
3. **Insights and Recommendations:** Provide actionable insights to aid in policymaking and conservation efforts.

---

## **Dataset Description**
- **Source:** The dataset, `forest_area_km.csv`, contains forest area data for multiple countries over several years.
- **Features:**  
  - `Country`: Name of the country.  
  - `Year`: Year of observation.  
  - `Forest Area (km²)`: Total forest area in square kilometers.
- **Size:** Includes several hundred records with numerical and categorical features.
- **Preprocessing:** Data cleaning included handling missing values, outlier removal, and feature scaling.

---

## **Technologies and Tools Used**
- **Programming Language:** Python
- **Libraries:**
  - **Data Manipulation:** Pandas, NumPy
  - **Visualization:** Matplotlib, Seaborn
  - **Machine Learning:** Scikit-learn
- **Development Environment:** Jupyter Notebook

---

## **Steps and Workflow**

1. **Data Loading:**  
   Load the `forest_area_km.csv` dataset into the environment.

2. **Data Cleaning:**  
   - Handled missing values.  
   - Removed outliers.  
   - Verified data integrity.

3. **Exploratory Data Analysis (EDA):**  
   - Visualized trends in forest area by country and year.  
   - Identified key patterns and anomalies.

4. **Model Development:**  
   - Built and compared three regression models:  
     - Linear Regression  
     - Decision Tree Regressor  
     - Random Forest Regressor  
   - Evaluated models using metrics such as Mean Squared Error (MSE) and R2 Score.

5. **Model Comparison:**  
   Random Forest Regressor emerged as the best model with high accuracy and low error rates.

6. **Insights and Recommendations:**  
   - Highlighted countries with significant forest loss.  
   - Suggested policies for forest conservation and reforestation.

---

## **Results**
- **Best Model:** Random Forest Regressor  
  - **MSE:** 409,658,271.28  
  - **R2 Score:** 0.9846  
- Predictive models demonstrated strong performance, with Random Forest being the most accurate.

---

## **Future Work**
- Incorporate more features like population growth, GDP, and climate variables to improve model accuracy.
- Explore deep learning models for better predictions.
- Extend the analysis to include socio-economic impacts of deforestation.
- Build a dashboard for interactive visualization and insights sharing.

---

## **How to Run**
1. Clone this repository:  
   ```bash
   git clone <repository-url>

2. Install the required dependencies:  
   ```bash
   pip install -r requirements.txt

3. Run the notebook:
    Open deforestation_analysis.ipynb in Jupyter Notebook and execute the cells.

## References
- Global Forest Watch: globalforestwatch.org
- Scikit-learn Documentation: scikit-learn.org
- Pandas Documentation: pandas.pydata.org

## Contributors
Author: Ntembeko Mhlungu
Contact: [Email](ntembekomhlungu1@gmail.com) | [LinkedIn](https://www.linkedin.com/in/ntembeko-mhlungu-6413a91bb/) | [GitHub] (https://github.com/Ntembeko-Ngwane)

