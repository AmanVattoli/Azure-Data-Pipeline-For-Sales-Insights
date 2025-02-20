# **Azure Data Pipeline for Pizza Sales Insights**

## **Overview**
This project demonstrates an end-to-end data analytics pipeline for pizza sales using **Azure Data Factory**, **Azure Databricks**, and **Power BI**. The objective is to process raw sales data, transform it into actionable insights, and visualize key trends to aid decision-making.

The pipeline includes:
- Data ingestion from on-premises servers to **Azure Blob Storage** using **Azure Data Factory**.
  ![image](https://github.com/user-attachments/assets/f9e52b0d-fbd5-4fda-8f0e-fb8e941680e4)
  ![image](https://github.com/user-attachments/assets/bf899122-c15b-4a50-a534-2b19f421a5e2)



- Data transformation and cleaning using **PySpark** in **Azure Databricks**.
  ![image](https://github.com/user-attachments/assets/3bc7dd85-08ca-4ac5-a43b-3bbfe25af027)
  ![image](https://github.com/user-attachments/assets/75db39c9-d434-421f-84bc-617f2120ccd1)

- Interactive data visualization through a **Power BI dashboard**.

---

## **Dashboard**

![Sales Analysis Dashboard](https://github.com/user-attachments/assets/fafa4664-4297-4bb7-b6e7-866435600692)

The Power BI dashboard includes:
1. **Key Metrics**:
   - **Total Pizzas Sold**: 50,000+
   - **Total Orders**: 49,000+
   - **Total Sales Revenue**: $817.86K

2. **Insights**:
   - **Monthly Sales Trends**: Revenue remained steady at ~$70K/month, peaking at $73K in July.
   - **Sales Distribution**:
     - **Pizza Size**: Large pizzas contributed 45.8% of total revenue.
     - **Pizza Category**: "Classic" and "Supreme" pizzas were top sellers, contributing 26.9% and 25.5%, respectively.
   - **Day-wise Orders**: Friday saw the highest orders (8.1K), while Sunday had the lowest (5.9K).
   - **Top-Selling Pizzas by Revenue**:
     - The Thai Chicken Pizza led with $43.43K, followed by The Barbecue Chicken Pizza ($42.77K).

---

## **Findings**
1. **Customer Preferences**:
   - Large pizzas were the most popular size, contributing nearly half of the total revenue.
   - Chicken-based pizzas dominated the top-seller list.

2. **Seasonal Trends**:
   - Sales peaked in July and gradually declined toward the end of the year.

3. **Order Patterns**:
   - Fridays are the most active days for orders, suggesting a weekend sales surge.
