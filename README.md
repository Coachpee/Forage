# TATA GROUP JOB SIMULATION

### Project Outline :

- [Project Title](Project-Title)

- [Project Overview](Project-Overview)

- [Dataset](Dataset)

- [Tools Used](Tools-Used)

- [Analysis Steps](Analysis-Steps)

- [Key Findings](Key-Findings)

- [Recommendations](Recommendations)

- [Conclusion](Conclusion)

  ----------------

### Project Title : Sales Performance Analysis for an Online Retail Store

----------

### 📊 Project Overview

This project analyzes the sales performance of an online retail store and seeks to uncover key insights such as top performing customers, regional performance in terms of sales and revenue generation and monthly sales trends. The goal is to produce an interactive Power BI dashboard that highlights these findings. By analyzing the various parameters in the data received,we seek to gather insights enough to make reasonable decisions which then enables me to tell a compelling story around our data.

---------------

### 📂 Dataset

The dataset used in this project contains sales transactions in 2010 and 2011. It includes the following fields:
- #### Invoice Number
- #### Stock code
- #### Description
- #### Quantity
- #### Invoice Date
- #### Unit Price
- #### Customer ID
- #### Country

### 🧰 Tools Used

- **Power BI:** For data cleaning and building of interactive dashboards and visualizations

- ---------
### 🔍 Analysis Steps

#### 1. Data Loading
Through the 'Get Data' ribbon on the **Home tab** of my PowerBI, I was able to load the data which was supplied as an xls file into PowerBI then I proceeded to cleaning the data.

#### 2. Data Cleaning

- Ensured there were no duplicate records and missing values

- Ensured removal of negative quantity values and unit prices less than 1

- Ensured that the columns were fixed at the right data type

#### 3. Analysis

On PowerBI, I was able to create a **Revenue column**  using the **Custom Column** ribbon by multiplying the **Unit Price** with the **Quantity**.

#### 4. Visualization

 Created interactive dashboards to visualize:

  - Monthly Sales Trend for 2011
    
  - Top-performing Countries in terms fo Revenue generation excluding UK
 
  - Top-performing Customers

  - A Map showing countries with respect to sales demand

------------------------
### 💡 Key Findings

- #### Monthly Sales Trend for 2011

The analysis showed that the month of November had the higest revenue of 1.51M in 2011. We can also observe an increase in sales in the later part of the year from the month of August to November from 0.76M to 1.51M. There was no sales in the month of December in Australia,Japan and Switzerland and also for the month of January and August in Japan.
  
![Forage1](https://github.com/user-attachments/assets/6df4d2ac-5829-420a-8c79-ba862684b77e)
![japan](https://github.com/user-attachments/assets/780183e6-e5a9-42e1-a306-bb800d5525a8)
![switz](https://github.com/user-attachments/assets/5cab6e5b-30bf-422b-b37f-bdc881acdb5d)
![Australia](https://github.com/user-attachments/assets/5bd9f037-5cbf-44da-875a-8a2c86ffaa55)

 - #### Top-performing Countries in terms fo Revenue generation excluding UK

The analysis showed tha Netherlands had the highest revenue of 285,402, closely followed by EIRE with a revenue of 283,490, Germany, 228,833, france, 209,639, Australia,138,527, then Spain, Switzerland, Belgium, Sweden and Japan following at the tail end of the chart.
Among the top 10, Germany and France had the most customers, 9040 and 8341 respectively

![Forage2](https://github.com/user-attachments/assets/885a7dfc-8d26-4bf1-82c5-be0dd0ce27a1)
![france](https://github.com/user-attachments/assets/e68fb286-cbab-4d42-99bd-17d5135386cb)
![germany](https://github.com/user-attachments/assets/aae3b972-1497-4e91-82ff-7303568e4cfb)
![table](https://github.com/user-attachments/assets/7048fb1b-e3d3-4e27-9a28-c1f09a11077f)

 - #### Top-performing Customers

The highest performing customer from our analysis is customer with ID 14646, having a total revenue of 280,169. with the use of slicers as shown below, I was able to deiscover that the top-most performing customer is from Netherlands. Out of a total of 2359 customers in Netherlands,only one customer generated 280,169 revenue out of the total of 285,402 revenue generated in Netherlands. 

![Forage3](https://github.com/user-attachments/assets/ead59324-13dc-49ee-9e05-001594293f77)
![Forage5](https://github.com/user-attachments/assets/4ca1cf4c-fa00-4e50-b264-cf853f991005)

 - #### A Map showing countries with respect to sales demand

As seen on the map below, using the size of the bubble as a reference to the level of demand of products, aside UK, Netherlands had the highest demand of products and this is followed by the other top-performing countries in the same order.
![Forage4](https://github.com/user-attachments/assets/a2c26182-3313-477d-8b18-cfc769d6952b)

### 🔦 Recommendations:

Based on these findings, I would suggest that we consider driving growth in top performing revenue generating countries like France and Germany as they have most customer base with more high paying loyal customers compared to other countries.
More marketing investments should be made in countries like Australia, Netherlands, Spain, Switzerland, Belgium, Sweden and Japan as these countries had fewer customers.
Strategies like customer loaylty programs that could help with increased loyalty of cutomers can be applied in countries like Netherlands,EIRE,Australia and Japan. Such strategies can also be applied to retain our high paying customers.
Lastly, it is also important to ensure adequate stock of items towards the end of the following year in order to have good sales in these regions. It is also important to look into the possible reasons why there was no sales in the month of December in Australia,Japan and Switzerland and also for the month of January and August in Japan and also avoinding them in the following year.

### 📘 Conclusion:

The sales analysis provided valuable insights into the performance of different product. By examining key metrics such as total revenue, product demand and Monthly trends, we could identify the best-performing customers and regions, as well as opportunities for improvement, growth and expansion.
