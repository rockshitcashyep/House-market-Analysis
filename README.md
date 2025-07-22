## 🏠 House Market Analysis Dashboard (Power BI + Google BigQuery)

This project presents a dynamic **Power BI dashboard** for analyzing trends in the housing market. It leverages **Google BigQuery** as the backend data source for fast and scalable querying of large housing datasets, with Power BI used for creating interactive and insightful visualizations.

---

### 🚀 Project Overview

The dashboard aims to uncover trends in property prices, regional variations, market growth, and buyer preferences. By combining **Power BI’s rich visual capabilities** with **BigQuery’s processing power**, this project delivers real-time insights into the real estate sector.

---

### 🧰 Tools & Technologies Used

- **Power BI** – For building interactive reports and visualizations  
- **Google BigQuery** – For querying large-scale housing datasets  
- **DAX** – For creating measures, KPIs, and calculated columns  
- **Power Query** – For in-model data transformations  
- **SQL (BigQuery Standard SQL)** – For pre-aggregations and filtering  

---

### 🧹 Data Pipeline

The data flow follows this structure:

1. **Google BigQuery**:
   - Connected to raw housing data (sales records, price histories, regions, etc.)
   - Performed data aggregation, filtering, and joins using SQL
2. **Power BI**:
   - Pulled preprocessed data via BigQuery connector
   - Additional transformations in Power Query Editor
   - Built relationships and calculated columns using DAX

---

### 📈 Dashboard Features

The dashboard includes:

- **Price Trends Over Time**: Median and average prices by year, month, and quarter  
- **Regional Analysis**: Heatmaps and bar charts for price distribution across cities or zip codes  
- **YoY Growth**: Year-over-year analysis of market value and transaction volumes  
- **Property Type Comparison**: Detached, semi-detached, condos, etc.  
- **Interactive Filters**: By region, year, property type, and price range  

---

### 🔍 Key Insights

- Consistent price growth observed in urban regions over the last 5 years  
- Certain suburbs show higher price volatility, indicating speculative activity  
- Condos and apartments have a lower average price but higher transaction volume  
- Peak buying seasons are often aligned with Q2 and Q3 across years  

---

### 📎 Usage

To explore the dashboard:

1. Open the `.pbix` file using **Power BI Desktop**  
2. Ensure your **Google BigQuery connection** is authenticated (or use a static extract if provided)  
3. Refresh the dataset or adjust filters to analyze specific regions or time periods  
4. Export visuals as PNG/PDF for reporting if needed  

---

### 📂 Dataset Source

The housing data was sourced from [insert source if applicable, e.g., Kaggle, Zillow public data, or internal database], and stored in **Google BigQuery** for high-performance querying.

---

