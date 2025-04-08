
# Chemify Lab Analytics

_A data-driven solution for optimising lab efficiency_

## 📌 Project Overview

Chemify is creating a digital chemical future where the access to important molecules, drugs and new materials, currently unimaginable, are instantly accessible. 

By developing the world's most efficient, automated and versatile chemical manufacturing laboratory, Chemify will radically increase the speed of innovation and contribute to the quality of life for the benefit of humanity

This project aligns with that vision by:  

✅ Cleaning and synchronising lab experiment data from multiple sources  
✅ Analysing experiment success rates, chemical usage, and costs  
✅ Creating an AI-powered dashboard for lab analytics  

## 📂 Datasets  

To simulate realistic and large datasets, I created synthetic data with intentional **data inconsistencies** to reflect common challenges in data preprocessing, such as:

- 🧪**Lab Notebook Data**: 
  - Mixed date formats and inconsistent units.
  - Missing catalyst and success status values.
  - Outliers in success rates (e.g., negative values).

- 📡**IoT Sensor Logs**: 
  - Mixed time intervals and unit mismatches (e.g., kg vs grams).
  - Missing sensor data for specific timestamps.
  - Duplicate sensor readings.

- 📋**Procurement & Cost Reports**: 
  - Duplicate chemical orders.
  - Inconsistent cost values (e.g., "unknown" values).
  - Units switched between kilograms and grams.
 
### Datasets generated
#### 1. Lab Notebook Data
- Size: 50,000 rows
- Fields: Experiment ID, Chemical Used, Quantity (grams), Temperature, Pressure, Reaction Time, Success Status
- Key Inconsistencies: Inconsistent date formats, missing values, outliers in success rates.

#### 2. IoT Sensor Logs
- Size: 100,000 rows
- Fields: Timestamp, Sensor ID, Experiment ID, Reading Value, Unit
- Key Inconsistencies: Mixed time intervals, unit mismatches, missing sensor readings.

#### 3. Procurement & Cost Reports
- Size: 20,000 rows
- Fields: Order ID, Chemical Ordered, Supplier, Quantity Ordered, Cost, Order Date
- Key Inconsistencies: Duplicate chemical orders, inconsistent cost values.

### Purpose of Introducing Inconsistencies
These inconsistencies were added deliberately to simulate real-world scenarios where data cleaning and preprocessing are required. The goal is to demonstrate my ability to handle **messy data**, perform **data wrangling**, and **prepare datasets for analysis**.

## ⚙️ Technologies Used  

- Python – Data processing & analysis (pandas, numpy)
- SQL – Structured data management
- Flask/Dash – WebApp for lab analytics
- Machine Learning – Predictive analysis
- Matplotlib & Seaborn – Data visualization

## 🏆 Key Features  

🚀 Automated Data Cleaning & Synchronization  
📊 Real-time Lab Performance Dashboard  
💰 Cost & Resource Optimization Analysis  

## 📖 Project Structure

chemify-lab-analytics/  
│── data/               # Raw & cleaned datasets  
│── notebooks/          # Jupyter notebooks for analysis  
│── scripts/            # Python scripts for automation  
│── app/                # WebApp code (Flask/Dash)  
│── README.md           # Project documentation  
│── requirements.txt    # Dependencies  

## 🛠 Installation & Setup

To run this project locally, follow these steps:

1. Clone the repository

```
     git clone https://github.com/YOUR_USERNAME/chemify-lab-analytics.git
     cd chemify-lab-analytics
```

2. Create a Virtual Environment

```
    python -m venv env  
    source env/bin/activate   # On macOS/Linux
    env\Scripts\activate      # On Windows```
```

3. Install dependencies

```
   pip install -r requirements.txt
```

5. Run Jupyter notebook for analysis

```
     jupyter notebook
```

6. Launch the WebApp

```
   python app/app.py
```


## 👩‍💻 How to Use the Project

🔹 Data Cleaning & Synchronization: Run the scripts/data_cleaning.py file to preprocess lab data  
🔹 Data Analysis & Visualization: Use Jupyter notebooks in notebooks/ for exploratory analysis  
🔹 WebApp for Real-time Insights: Run app.py to access the lab analytics dashboard  

## 💡 Lessons Learned

This project helped me develop expertise in:  

✅ Data Cleaning & Synchronization – Handling inconsistent multi-source data  
✅ Database Management – Structuring lab data for analysis  
✅ Building Analytical Dashboards – Using Flask/Dash for real-time insights  
✅ Optimizing Lab Costs – Identifying efficiency opportunities with analytics  

## 👥 Contributors

🔹 [Sandra](https://github.com/sandramtzd) – Developer & Data Analyst
