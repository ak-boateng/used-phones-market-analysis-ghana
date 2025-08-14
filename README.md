# 📱 Used iPhone Market Analysis – Ghana

## 📌 Project Overview
This project investigates profit margins in the Ghanaian used iPhone market by scraping online marketplace data, collecting spare parts pricing, and calculating potential profitability for different iPhone models.

It demonstrates a **full data science workflow**:  
- Data collection via web scraping  
- Data cleaning and preprocessing  
- Exploratory Data Analysis (EDA)  
- Business insight modeling  
- Visualization and dashboard creation

The insights will be used for a YouTube video titled:  
> **"I Investigated the Used iPhone Black Market in Ghana"**

---

## 🎯 Objectives
- Identify the most profitable iPhone models to flip in Ghana.
- Understand the cost structure (purchase + repair) vs resale value.
- Analyze pricing trends based on model, storage size, and condition.
- Provide recommendations for small-scale phone resellers.

---

## 📊 Data Sources
1. **Used iPhone Listings**  
   - Platforms: Tonaton, Jiji Ghana, Facebook Marketplace.  
   - Fields: Model, Storage, Condition, Listed Price, Seller Location, Date Listed.  

2. **Spare Parts Prices**  
   - Collected from local repair shops and online parts sellers.  
   - Parts: Screen, Battery, Camera, Motherboard.

---

## 🔄 Workflow
1. **Data Collection** – Web scraping scripts for used phone listings; manual/online spare parts price gathering.
2. **Data Cleaning** – Remove duplicates, standardize model names, format prices, handle missing values.
3. **Data Analysis** – Profit margin calculation, model rankings, condition impact analysis.
4. **Visualization** – Graphs, charts, and interactive dashboards (Streamlit/Plotly).
5. **Insights & Recommendations** – Top profitable models, risks, and market trends.

---

## 📈 Key Metrics
- **Profit Margin**:  
  \[
  \text{Profit Margin} = \frac{(Resale\ Price - Purchase\ Price - Repair\ Cost)}{Purchase\ Price} \times 100
  \]
- ROI per iPhone model.
- Price distribution by model, condition, and storage capacity.

---

## 🛠 Tools & Libraries
- **Python**: `requests`, `BeautifulSoup`, `Selenium` (scraping)  
- **Pandas**, **NumPy** (data cleaning & analysis)  
- **Matplotlib**, **Seaborn**, **Plotly** (visualization)  
- **Streamlit/Plotly Dash** (dashboard)  
- **Jupyter Notebook** (exploration)

---

## 📂 Project Structure

