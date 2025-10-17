# 📱 Used Phone Market Analysis – Ghana

## 📌 Project Overview
This project analyzes the economics of the used phone market in Ghana.  
It involves **scraping data** from local peer-to-peer (P2P) marketplaces, collecting **spare parts pricing**, and comparing these with **market resale prices** to understand profitability and trends.

The goal is to uncover insights into:
- How pricing varies across phone brands and models.
- Which phones hold their value best.
- The potential profit margins in refurbishing and reselling used phones.

This project is part of a practical data science study and will also be featured in a YouTube video exploring Ghana’s vibrant second-hand phone ecosystem.

---

## 🎯 Objectives
- Collect and clean data from online used phone listings.
- Gather data on spare part prices (screens, batteries, cameras, etc.).
- Compare listed prices with resale and part replacement costs.
- Analyze profit margins, depreciation, and market demand patterns.

---

## 📊 Data Sources
1. **Used Phone Listings**
   - Local platforms such as Tonaton, Jiji Ghana, or Facebook Marketplace.
   - Key fields: Brand, Model, Storage, Condition, Listed Price, Seller Location, Date Listed.

2. **Spare Parts Prices**
   - Collected from online catalogs or in-person repair shops.
   - Parts: Screen, Battery, Camera, Motherboard, Charging Port.

3. **Market Resale Prices**
   - Verified retail shops or known resellers that deal in refurbished phones.

---

## 🔄 Project Workflow
1. **Data Collection**
   - Scrape used phone listings using Python (`requests`, `BeautifulSoup`, or `Selenium`).
   - Gather spare parts data manually or via scraping.
   - Store data in CSV or JSON format.

2. **Data Cleaning**
   - Remove duplicates, handle missing values, and standardize brand/model names.
   - Normalize prices and filter unrealistic listings.

3. **Data Analysis**
   - Explore pricing distribution by brand, model, and condition.
   - Compare average spare part cost with resale value.
   - Calculate estimated profit margins for refurbished phones.

4. **Visualization**
   - Create charts for:
     - Price trends by brand/model.
     - Cost vs resale value.
     - Top phones by potential ROI.
   - Optionally build a dashboard using **Streamlit** or **Plotly Dash**.

---

## 📈 Example Research Questions
1. Which phone brands and models retain their value the longest?  
2. What is the average profit margin for flipping used phones in Ghana?  
3. Are some phone models more cost-effective to repair than others?  
4. How do spare parts costs vary across brands?  
5. What condition (new, used, faulty) yields the highest resale return?  
6. Is there a correlation between location and phone prices?  
7. Which models are best suited for resale businesses?  

---

## 🛠 Tools & Libraries
- **Python**: `requests`, `BeautifulSoup`, `Selenium` – for scraping  
- **Pandas**, **NumPy** – for data cleaning and analysis  
- **Matplotlib**, **Seaborn**, **Plotly** – for data visualization  
- **Jupyter Notebook / Google Colab** – for exploration and documentation  
- **Streamlit / Plotly Dash** – for dashboard (optional)


