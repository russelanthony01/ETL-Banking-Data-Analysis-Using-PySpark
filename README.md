## 🏦 Global Banking Market Capitalization — PySpark Data Analysis (Simulation)

### 📌 Overview
This project analyzes global banking market capitalization data using **PySpark**, simulating an ETL and cloud-style workflow. The dataset contains top global banks ranked by market value, with exchange rate data to convert USD values into GBP, EUR, and INR.

The goal is to practice Spark-based data processing, financial analytics, and local cloud-style storage behavior. Outputs are saved in CSV and Parquet formats inside a **simulated S3 folder** (local directory only — no real AWS usage).

---

### 🧰 Tools & Technologies
- Python  
- PySpark  
- Pandas
- Plotly 
- Matplotlib  
- Local S3 directory simulation  

> ⚠️ Cloud note: AWS S3 is simulated locally to mimic cloud workflows.

---

### 🎯 Key Objectives
- Load and clean global banking dataset  
- Convert market caps into multiple currencies  
- Identify and rank top banks  
- Analyze market distribution and concentration  
- Generate visual insights (charts + statistics)  
- Export results in industry-friendly formats  

---

### 🧹 Data Preparation
- Cleaned and standardized columns  
- Checked and handled missing values  
- Mapped currency exchange rates  
- Categorized banks by market-cap tiers  
- Saved processed data locally in multiple formats  

---

### 📊 Analysis Highlights

#### 💰 Market Capitalization Insights
- Top banks by valuation  
- Market dominance & quartile analysis  
- Spread and outlier patterns  

#### 🌍 Currency Analysis
- USD → GBP / EUR / INR conversions  
- Comparative valuation view across regions  

#### 📈 Visual Insights
- Histograms, bar charts  
- Pie chart for market share  
- Box & violin plots for distribution  

---

### 📎 Data Source
Wikipedia — *List of largest banks by market capitalization*

> **Note:** In several steps, `.toPandas()` was used to convert Spark DataFrames to pandas DataFrames. This was done primarily to make the results easier to view and display clearly on GitHub and within the notebook environment. In real large-scale workloads, Spark display functions would be used instead to avoid unnecessary memory usage.

---

### 📜 License
Distributed under the **MIT License**.

---

### 👤 Author
**Russel Anthony Reynold Chandanshiv**
