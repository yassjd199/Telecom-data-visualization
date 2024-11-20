


# **Telecom Data Visualization Project**  

## **Overview**  
This project focuses on visualizing telecom-related data to uncover patterns in internet performance and its correlation with socioeconomic factors such as income, urbanization, and internet usage rates. As a hands-on exercise in Power BI, this project involved performing basic data transformations, linking datasets, and creating initial visualizations.

---

## **Project Objectives**  
- Perform basic transformations on datasets (e.g., handling null values, linking datasets).
- Create and experiment with data visualizations in Power BI.
- Explore data relationships and build a first interactive dashboard using Power BI.

---

## **Datasets**  
1. **Internet Performance Data**:  
   - Metrics: Broadband speeds (mb/s), Mobile speeds (mb/s), by country.  
2. **GapMinder Dataset**:  
   - Metrics: Income per person, Internet usage rate, Urban population rate, by country.  

Both datasets were linked using the `country` field to explore relationships between socioeconomic factors and internet performance.

---

## **Data Transformations**  
Basic transformations were performed to clean and prepare the data for visualization:  
- **Data type conversion**: Ensured consistency in numerical columns (e.g., broadband speeds, income).  
- **Removed rows with missing or null values**: Cleaned the dataset for accurate analysis.  
- **Linked datasets**: Combined the internet performance and socioeconomic data based on the `country` field.

---

## **Visualizations Created**  
In Power BI, the following visualizations were explored:  
1. **Internet Speeds by Country**: Visualized broadband and mobile speeds on a map by country.  
2. **Income vs. Internet Usage**: Scatter plot showing the relationship between income per person and internet usage rate.  
3. **Urbanization and Internet Access**: Line chart comparing urban population rate with internet usage.  
4. **Country Rankings**: Bar chart ranking countries based on broadband and mobile speeds.

These visualizations provide insights into how factors like income and urbanization impact internet connectivity.

---

## **Files Included**  
- **`data/`**: Cleaned datasets (CSV files).  
- **`reports/`**: Screenshots of key visualizations and the exported Power BI report.  

---

## **How to View the Dashboard**  
1. Download the `.pbix` file from the repository (if included).  
2. Open it in Power BI Desktop.  
3. Interact with the visualizations and explore the dashboard.  

---

## **Future Improvements**  
- Implement more advanced transformations or enrich the dataset with external data sources.  
- Enhance Power BI dashboards with advanced features (e.g., drill-downs, slicers).  
- Integrate real-time data from APIs to keep the analysis up-to-date.
