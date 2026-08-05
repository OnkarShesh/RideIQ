# 🚖 RideIQ – Intelligent Demand Forecasting for Smart Mobility

A Machine Learning-based ride demand forecasting and analytics platform that analyzes historical taxi booking data to generate business insights, predict demand patterns, and visualize ride distribution across different locations.

---

## 📌 Project Overview

RideIQ is an end-to-end data analytics and machine learning project developed using Python and Scikit-learn. The system automatically processes ride booking datasets, performs exploratory data analysis, engineers predictive features, trains a Random Forest model for demand forecasting, and generates interactive visualizations to support fleet optimization and operational decision-making.

---

## ✨ Features

- 📊 Automated data preprocessing and cleaning
- 🚖 Ride demand forecasting using Random Forest Regressor
- 📈 Exploratory Data Analysis (EDA)
- 🗺️ Interactive geospatial visualization
- 💳 Payment method analysis
- 🚘 Vehicle-wise ride analytics
- ⭐ Driver and customer rating analysis
- ❌ Cancellation reason analysis
- 📅 Weekday vs Weekend demand comparison
- 📍 Automatic city detection from pickup locations
- 📁 Supports multiple datasets (Pune & NCR)

---

## 🛠️ Technology Stack

| Category | Technologies |
|----------|--------------|
| Programming Language | Python |
| Data Processing | Pandas, NumPy |
| Machine Learning | Scikit-learn (Random Forest Regressor) |
| Data Visualization | Matplotlib |
| Interactive Maps | Folium |
| Notebook | Jupyter Notebook |

---

## 📂 Project Structure

```
RideIQ/
│
├── README.md
├── requirements.txt
├── .gitignore
├── rideiq_analysis.ipynb
│
├── data/
│   ├── pune_ride_bookings.csv
│   └── ncr_ride_bookings.csv
│
├── outputs/
│   ├── pune/
│   └── ncr/
│
└── screenshots/
```

---

## 🔄 Project Workflow

```
Ride Booking Dataset
          │
          ▼
Data Cleaning & Preprocessing
          │
          ▼
Feature Engineering
          │
          ▼
Exploratory Data Analysis
          │
          ▼
Machine Learning Model
(Random Forest)
          │
          ▼
Demand Prediction
          │
          ▼
Business Insights &
Interactive Visualizations
```

---

## 🤖 Machine Learning Model

**Algorithm Used**

- Random Forest Regressor

**Input Features**

- Hour
- Day of Week
- Month
- Weekend Indicator
- Morning Rush Hour
- Evening Rush Hour
- Night Indicator
- Monsoon Indicator

**Output**

- Predicted Ride Demand

---

## 📊 Generated Outputs

The project automatically generates:

- Hourly Ride Demand Analysis
- Booking Status Distribution
- Vehicle Type Analysis
- Cancellation Analysis
- Payment Method Analysis
- Driver vs Customer Ratings
- Weekday vs Weekend Fare Analysis
- Feature Importance Analysis
- Actual vs Predicted Demand
- Interactive HTML Map

---

## 📸 Screenshots

### Dashboard
![Dashboard](screenshots/dashboard.png)

### Interactive Map
![Interactive Map](screenshots/popup.png)

### Hourly Demand Analysis
![Hourly Demand](screenshots/hourly_demand.png)

### ML Model Output
![ML Model](screenshots/ml_model.png)

---

## 🚀 How to Run

### Clone Repository

```bash
git clone https://github.com/yourusername/RideIQ.git
```

### Install Dependencies

```bash
pip install -r requirements.txt
```

### Select Dataset

Inside `rideiq_analysis.ipynb`:

```python
CSV_FILE = "data/pune_ride_bookings.csv"
```

or

```python
CSV_FILE = "data/ncr_ride_bookings.csv"
```

### Run

Execute all notebook cells.

Generated files will be saved inside:

```
outputs/
```

---

## 📈 Future Improvements

- Real-time ride demand prediction
- REST API using FastAPI
- React Dashboard
- PostgreSQL Integration
- Docker Deployment
- Cloud Deployment (AWS/Azure)

---

## 👨‍💻 Author

**Onkar Shesh**

B.Tech – Computer Science & Business Systems
