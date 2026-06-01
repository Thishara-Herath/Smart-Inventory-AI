# Smart Inventory AI

AI-powered inventory management and demand forecasting system for grocery stores using FastAPI, MongoDB, Machine Learning, Bootstrap, and Chart.js.

---



https://github.com/user-attachments/assets/ad27e31f-c663-4053-8391-8922c2307b74



---

## 📌 Project Description

Smart Inventory AI helps grocery stores manage inventory efficiently by predicting future demand, detecting unusual sales spikes, identifying seasonal trends, and providing intelligent reorder recommendations to prevent stock shortages and overstocking.

---

## 🚀 Features

### 📈 AI Analytics
- Predict Demand
- Detect Sales Spikes
- Seasonal Trend Analysis
- Reorder Recommendation
- Demand Prediction Chart

### 🧠 AI Inventory Insights
- Low Stock Insights
- Top Selling Products
- Seasonal Trend Products

### ⚠ AI Inventory Risk Scanner
- Detects products that may run out of stock soon
- Generates proactive stock alerts

### 📦 Inventory Management
- Add New Products
- Update Products
- Delete Products
- Search Inventory
- Stock Status Indicators

### 🛒 Sales Management
- Record Product Sales
- Store Daily Sales History

### 📊 Data Visualization
- Prediction Chart
- Inventory Chart
- 7-Day Demand Forecast Chart
- Sales History Chart

### 📋 KPI Dashboard
- Total Products
- Low Stock Items
- Top Seller
- AI Risk Items

---

## 🛠 Technologies Used

### Backend
- Python
- FastAPI
- Scikit-learn
- NumPy

### Database
- MongoDB

### Frontend
- HTML5
- CSS3
- JavaScript
- Bootstrap 5

### Visualization
- Chart.js

---

## 🤖 AI Capabilities

### 1. Demand Prediction
Uses Linear Regression to predict future product demand based on historical sales data.

### 2. Sales Spike Detection
Detects unusual increases in sales compared with normal purchasing patterns.

### 3. Seasonal Trend Analysis
Identifies recurring demand variations and sales trends.

### 4. Reorder Recommendation
Calculates expected future demand and recommends stock replenishment before shortages occur.

---

## 🧠 How My AI Differs From Traditional Systems

Traditional inventory systems:
- Only store inventory data
- React after stock becomes low
- Require manual monitoring
- Do not learn from sales patterns

Smart Inventory AI:
- Predicts future demand
- Detects sudden sales spikes
- Identifies seasonal trends
- Generates proactive alerts
- Recommends reorder quantities before stockouts happen

---

## 📂 Project Structure

```text
smart_inventory_ai/
│
├── predict_api.py
│
├── frontend/
│   ├── index.html
│   ├── script.js
│   ├── style.css
│   └── login.html
│
├── sales_collection
├── inventory_collection
│
└── README.md
```

---

## ⚙ Installation

### Clone Repository

```bash
git clone https://github.com/yourusername/smart-inventory-ai.git
```

### Open Project

```bash
cd smart-inventory-ai
```

### Create Virtual Environment

```bash
python -m venv venv
```

### Activate Virtual Environment

```bash
venv\Scripts\activate
```

### Install Dependencies

```bash
pip install fastapi uvicorn pymongo numpy scikit-learn
```

### Run Backend

```bash
uvicorn predict_api:app --reload
```

Backend:

```text
http://127.0.0.1:8000
```

### Run Frontend

Open:

```text
frontend/index.html
```

or run using Live Server.

---

## 📊 Charts

### Prediction Chart
Shows:
- Current Sales
- Predicted Next-Day Sales

X-Axis:
- Today
- Tomorrow

Y-Axis:
- Units Sold

---

### Inventory Chart

Shows stock quantity of all products.

X-Axis:
- Product Names

Y-Axis:
- Quantity Available

---

### 7-Day Demand Forecast

Shows predicted demand for the next seven days.

X-Axis:
- Day +1 to Day +7

Y-Axis:
- Predicted Units Sold

---

### Sales History Chart

Shows historical sales records.

X-Axis:
- Day Numbers

Y-Axis:
- Units Sold

---

## 📈 KPI Dashboard

### Total Products
Number of products stored in inventory.

### Low Stock Items
Products below reorder level.

### Top Seller
Highest-selling product.

### AI Risk Items
Products likely to experience stock shortages.

---

## 🔮 Future Improvements

- Advanced Forecasting Models
- LSTM Deep Learning Prediction
- Automated Purchase Orders
- Supplier Integration
- Email Notifications
- Mobile Application
- Real-Time Dashboard Analytics

---

## 👨‍💻 Author

Final Year Computing Project

**Smart Inventory & Demand Forecasting System for Grocery Stores**

Developed using:
- FastAPI
- MongoDB
- Machine Learning
- Bootstrap
- Chart.js

---

## 📜 License

This project is developed for academic and educational purposes.
