# IPL Auction 2023 Data Analysis Project

This project performs **end-to-end data analysis on the IPL Auction 2023 dataset** using Python. The objective is to clean the data, engineer meaningful features, visualize patterns, and analyze the **top 10 players with the highest jump from base price to final price**.


## 📌 Project Objectives

- Load and clean the IPL Auction 2023 dataset  
- Handle missing values efficiently  
- Perform feature engineering for deeper insights  
- Visualize auction patterns using multiple charts  
- Identify the **top 10 players with the highest price jump**


## 🛠️ Technologies & Libraries Used

- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  


## 📂 Project Workflow

### 1️⃣ Data Loading  
- Dataset loaded using Pandas.

### 2️⃣ Data Cleaning  
- Fixed incorrect data types  

### 3️⃣ Handling Missing Values  
- Missing values in key columns were handled using:
  - Replacement

### 4️⃣ Feature Engineering  
New meaningful features were created:
- `difference` → Final Price − Base Price  
- `final > base` → Boolean feature indicating demand 
- `is_sold` → Binary target variable  
- `jump` → Price jump ratio  

### 5️⃣ Data Visualization  
The following plots were created:
- ✅ Pie Chart  
- ✅ Bar Plot  
- ✅ Histogram  
- ✅ Scatter Plot  

These were used to visualize:
- Player style distribution  
- Franchise behavior  
- Price variations  
- Demand patterns  

### 6️⃣ Data Analysis  
- Identified the **Top 10 players with the highest price jump from base price**
- Analyzed:
  - Player demand
  - Franchise investment behavior
  - Retained vs sold price dynamics

---

## 📊 Key Insight

The players with the **highest difference between base price and final price** represent:
- Maximum demand  
- High market valuation  
- Strong franchise competition  


## ✅ Final Output

- Cleaned dataset  
- Engineered features  
- Visual insights  
- List of **Top 10 highest jump players**
