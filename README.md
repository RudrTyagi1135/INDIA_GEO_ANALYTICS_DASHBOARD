# 🇮🇳 India Geo Analytics Dashboard

An **interactive geospatial data visualization system** built using **Streamlit + Plotly**, designed to analyze and explore **district-level indicators across India**.

This project demonstrates **geospatial analytics**, **data-driven UI design**, and **interactive dashboard engineering**, forming a strong base for **ML-integrated analytical systems**.

---

## 🚀 Features

- 🌍 **Interactive geospatial visualization (Mapbox-based)**
- 📊 **Multi-parameter analysis using size + color encoding**
- 🎯 **State-level and national-level filtering**
- ⚡ **Dynamic UI with sidebar controls**
- 📍 **District-level data exploration**
- 🧩 **Simple and extensible architecture**

---

## 🧠 What This Project Demonstrates

This project highlights the following **analytics and system design skills**:

- **Geospatial visualization using Plotly Mapbox**
- **Interactive dashboard development using Streamlit**
- **Multi-dimensional data encoding (size + color)**
- **User-driven data exploration via UI controls**
- **Handling structured datasets using Pandas**
- **Foundation for ML-powered geospatial systems**

---

## 📂 Project Structure

```
INDIA-GEO-ANALYTICS-DASHBOARD/
│
├── app.py              # Main Streamlit application
├── india.csv           # District-level dataset
├── requirements.txt    # Dependencies
├── README.md           # Documentation
├── .gitignore
└── .venv/              # Virtual environment (ignored)
```

---

## ⚙️ Architecture Overview

The project follows a **geospatial analytics pipeline**.

```
Dataset (india.csv)
        │
        ▼
Data Processing (Pandas / NumPy)
        │
        ▼
Feature Selection (User Input - Sidebar)
        │
        ▼
Visualization Layer (Plotly Mapbox)
        │
        ▼
Streamlit Application (app.py)
        │
        ▼
Interactive Dashboard (Browser)
```

### Design Principles

- **Separation of data processing and visualization**
- **User-driven parameter selection**
- **Multi-dimensional encoding for insights**
- **Scalable dashboard structure**

---

## 📊 Core Concept

The system maps numerical features onto geography:

| Visual Element | Meaning |
|--------------|--------|
| Bubble Size | Primary parameter |
| Color Intensity | Secondary parameter |
| Location | District coordinates |

This enables **multi-dimensional analysis in a single view**.

---

## 🎮 How to Use

1. Open sidebar controls  
2. Select:
   - State (or Overall India)
   - Primary parameter (size)
   - Secondary parameter (color)  
3. Click **"Plot Graph"**  
4. Analyze district-level patterns  

---

## 🛠 Installation

### Clone repository

```bash
git clone https://github.com/your-username/INDIA-GEO-ANALYTICS-DASHBOARD.git
cd INDIA-GEO-ANALYTICS-DASHBOARD
```

### Create virtual environment

```bash
python -m venv .venv
```

### Activate environment (Windows)

```bash
.venv\Scripts\activate
```

### Install dependencies

```bash
pip install -r requirements.txt
```

---

## ▶️ Running the Application

```bash
streamlit run app.py
```

---

## 📈 Potential Improvements

Future enhancements could include:

- Add **caching (`@st.cache_data`) for performance**
- Integrate **real-world APIs (Govt / World Bank)**
- Add **time-series slider for temporal analysis**
- Implement **ML models (clustering, anomaly detection)**
- Add **backend API for data ingestion**
- Deploy on **AWS / Streamlit Cloud**
- Use **Mapbox token for advanced styling**

---

## 🧰 Tech Stack

| Technology | Purpose |
|-----------|--------|
| Python | Programming language |
| Streamlit | Web dashboard framework |
| Plotly | Geospatial visualization |
| Pandas | Data processing |
| NumPy | Numerical computation |

---

## 🎯 Learning Outcomes

This project helped build understanding of:

- **Geospatial data visualization techniques**
- **Interactive dashboard development**
- **Multi-dimensional data encoding**
- **User-driven analytics systems**
- **Foundation for ML-integrated dashboards**

---

## 👤 Author

**Rudra Tyagi**

B.Tech Final Year Student  
Aspiring **ML Systems / MLOps / AI Infrastructure Engineer**