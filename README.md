#  GDP Analysis using RandomForestRegressor

This project analyzes global GDP per capita using the **countries_of_the_world.csv** dataset.  
It includes **data cleaning, exploratory data analysis (EDA), correlation study, modeling using RandomForestRegressor**, and insights on factors influencing GDP.

---

##  Dataset Information

The dataset contains the following key columns:

- **Country**
- **Region**
- **Population**
- **Area (sq. mi.)**
- **Pop. Density (per sq. mi.)**
- **Coastline (coast/area ratio)**
- **Net migration**
- **Infant mortality (per 1000 births)**
- **GDP ($ per capita)**
- **Literacy (%)**
- **Phones (per 1000)**
- **Arable (%)**
- **Crops (%)**
- **Other (%)**
- **Climate**
- **Birthrate**
- **Deathrate**
- **Agriculture**
- **Industry**
- **Service**

---

##  Project Workflow

### **1. Importing Required Libraries**
Loading essential Python libraries such as:
- pandas  
- numpy  
- matplotlib & seaborn  
- scikit-learn (RandomForestRegressor, train_test_split, metrics)

---

### **2. Data Inspection**
- Displaying dataset head/tail  
- Understanding structure  
- Checking data types  

---

### **3. Handling Missing Values**
- Detecting missing values  
- Filling missing values using appropriate statistical techniques  
  (mean/median/imputed values based on distribution)

---

### **4. Exploratory Data Analysis (EDA)**
- Summary statistics  
- Visualizing key variables  
- Identifying outliers  
- Region-wise GDP analysis  

---

### ** Correlation Analysis**
- Constructing correlation matrix  
- Visualizing using heatmap  
- Identifying top factors affecting **GDP per capita**  

Key findings include:
- GDP highly correlated with **Phones per 1000**, **Literacy**, **Industry**, **Service**  
- Countries with **low Birthrate** and **low Infant Mortality Rate** generally show higher GDP

---

##  5. Modeling with RandomForestRegressor

### **Steps:**
- Select features & target variable  
- Train-test split  
- Model training  
- Model evaluation using:
  - R² Score  
  - MAE, MSE  

### **Visualizations:**
- Actual vs Predicted GDP  
- Feature importance plot

---

##  6. Total GDP & Top 10 Countries
- Calculated **Total GDP contribution** of each country  
- Identified **Top 10 countries** based on GDP  
- Bar chart comparisons included  

---


