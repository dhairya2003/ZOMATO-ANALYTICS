# 🍴 Zomato Analytics

## 📌 Project Description

**Zomato Analytics** is an end-to-end data analytics and business intelligence project built to analyze restaurant data and uncover meaningful insights about restaurant distribution, ratings, pricing, cuisines, customer votes, online delivery, table booking, and restaurant opening trends.

The project analyzes **9,551 restaurants across 141 cities and 15 countries** and presents the findings through dashboards created using **Tableau, Power BI, and Excel**, supported by **SQL/MySQL** for data exploration and database analysis.

The objective is to transform raw restaurant data into clear, interactive, and business-focused visual insights that can support decision-making and demonstrate practical data analytics skills.

---

## 🎯 Project Objectives

- Analyze restaurant distribution across cities and countries.
- Identify top-rated restaurants.
- Analyze restaurant pricing and cost categories.
- Identify the most expensive restaurants.
- Analyze popular cuisines and customer votes.
- Compare restaurants offering online delivery.
- Analyze table booking availability.
- Study restaurant openings by year and quarter.
- Build interactive dashboards using multiple BI tools.
- Use SQL for structured data analysis and business questions.

---

## 📊 Key Project Metrics

| KPI | Value |
|---|---:|
| Total Restaurants | **9,551** |
| Total Cities | **141** |
| Total Countries | **15** |
| Average Rating | **2.89** |
| Average Cost | **$10.09** |
| Online Delivery Available | **25.66%** |
| Table Booking Available | **12.12%** |

---

# 📈 1. Tableau Dashboard

The Tableau dashboard provides an interactive executive-level view of the Zomato restaurant dataset.

### Dashboard Highlights

- Total Restaurants
- Total Cities
- Total Countries
- Average Rating
- Average Cost
- Restaurant opening by quarter
- Table booking analysis
- Online delivery analysis
- Most expensive restaurants
- Top cuisines
- Top 10 rated restaurants

### Interactive Filters

- Rating
- Country
- Year of Opening
- City
- Online Delivery
- Table Booking

### Tableau Dashboard Screenshot

![Zomato Tableau Analytics Dashboard](Dashboard_Images/01_tableau_dashboard.png)

---

# 📊 2. Power BI Dashboard

The Power BI dashboard provides an interactive business intelligence view of the restaurant dataset.

### Dashboard Highlights

- Total Restaurants
- Total Cities Covered
- Restaurants by price category
- Top-rated restaurants
- Online delivery analysis
- Most expensive restaurants
- Votes by cuisine
- Interactive country and city filters
- Rating filtering
- Year and quarter analysis

### Power BI Features

- Interactive slicers
- KPI cards
- Cross-filtering
- Business-focused visualizations
- Restaurant and cuisine analysis
- Pricing analysis
- Delivery analysis

### Power BI Dashboard Screenshot

![Zomato Power BI Analytics Dashboard](Dashboard_Images/02_powerbi_dashboard.png)

---

# 📊 3. Excel Dashboard

The Excel dashboard provides an additional interactive analysis of the Zomato dataset.

### Dashboard Highlights

- Total Restaurants
- Total Cities Covered
- Top-rated restaurants
- Restaurants by price category
- Online delivery analysis
- Table booking analysis
- Most expensive restaurants
- Popular cuisines by votes

### Interactive Filters

- Country
- City
- Rating
- Year
- Quarter

### Excel Dashboard Screenshot

![Zomato Excel Analytics Dashboard](Dashboard_Images/03_excel_dashboard.png)

---

# 🗃️ 4. SQL / MySQL Analysis

SQL was used to explore and analyze the restaurant data before and alongside dashboard development.

### SQL Analysis Includes

- Restaurant count analysis
- City-wise restaurant analysis
- Country-wise restaurant analysis
- Average rating analysis
- Cuisine analysis
- Pricing analysis
- Online delivery analysis
- Table booking analysis
- Vote analysis
- Top-rated restaurant analysis

### Example SQL Queries

#### Total Restaurants

```sql
SELECT COUNT(*) AS total_restaurants
FROM restaurants;
```

#### Average Rating

```sql
SELECT AVG(Rating) AS average_rating
FROM restaurants;
```

#### Restaurants by City

```sql
SELECT City,
       COUNT(*) AS restaurant_count
FROM restaurants
GROUP BY City
ORDER BY restaurant_count DESC;
```

#### Restaurants by Country

```sql
SELECT Countryname,
       COUNT(*) AS restaurant_count
FROM restaurants
GROUP BY Countryname
ORDER BY restaurant_count DESC;
```

#### Restaurants by Cuisine

```sql
SELECT Cuisines,
       COUNT(*) AS restaurant_count
FROM restaurants
GROUP BY Cuisines
ORDER BY restaurant_count DESC;
```

#### Online Delivery Analysis

```sql
SELECT Has_Online_delivery,
       COUNT(*) AS restaurant_count
FROM restaurants
GROUP BY Has_Online_delivery;
```

#### Table Booking Analysis

```sql
SELECT Has_Table_booking,
       COUNT(*) AS restaurant_count
FROM restaurants
GROUP BY Has_Table_booking;
```

> Column names may need to be adjusted according to the actual SQL table schema.

---

# 🔍 Key Business Questions

The project focuses on answering the following business questions:

1. How many restaurants are present in the dataset?
2. How many cities and countries are covered?
3. What is the average restaurant rating?
4. What is the average restaurant cost?
5. Which restaurants are the most expensive?
6. Which restaurants have the highest ratings?
7. Which cuisines are the most popular?
8. Which cuisines receive the highest number of votes?
9. What percentage of restaurants provide online delivery?
10. What percentage of restaurants provide table booking?
11. How are restaurants distributed across price categories?
12. How many restaurants opened in each year?
13. Which quarter has the highest number of restaurant openings?
14. How does restaurant performance vary by city and country?

---

# 💡 Key Insights

- The dataset contains **9,551 restaurants**.
- The restaurants are distributed across **141 cities**.
- The dataset covers **15 countries**.
- The average restaurant rating is **2.89**.
- The average cost shown in the Tableau dashboard is **$10.09**.
- **25.66%** of restaurants provide online delivery.
- **12.12%** of restaurants provide table booking.
- Restaurant pricing is concentrated in the lower price categories.
- Cuisine-level analysis shows differences in restaurant presence and customer votes.
- Restaurant openings can be analyzed by year and quarter.
- Top-rated and high-cost restaurants can be identified through interactive dashboards.

---

# 🛠️ Tools & Technologies

| Tool | Purpose |
|---|---|
| **SQL / MySQL** | Data querying, aggregation and analysis |
| **Microsoft Excel** | Data analysis and dashboard development |
| **Tableau** | Interactive data visualization |
| **Power BI** | Business intelligence and interactive dashboards |
| **GitHub** | Project version control and portfolio presentation |

---

# 📁 Recommended Repository Structure

```text
Zomato-Analytics/
│
├── README.md
│
├── Dataset/
│   └── Zomato_Raw_Dataset.xlsx
│
├── Tableau/
│   └── Zomato_Analytics_Dashboard.twbx
│
├── PowerBI/
│   └── Zomato_Analytics_Dashboard.pbix
│
├── Excel/
│   └── Zomato_Analytics_Dashboard.xlsx
│
├── SQL/
│   └── restaurant_db_dump.sql
│
├── Dashboard_Images/
│   ├── 01_tableau_dashboard.png
│   ├── 02_powerbi_dashboard.png
│   └── 03_excel_dashboard.png
│
└── Documentation/
    └── Zomato_Questionnaire.txt
```

---

# 🚀 Skills Demonstrated

- Data Cleaning
- Data Preparation
- Exploratory Data Analysis
- SQL
- MySQL
- Microsoft Excel
- Tableau
- Power BI
- DAX
- Data Visualization
- Dashboard Development
- KPI Development
- Business Intelligence
- Interactive Filtering
- Business Analysis
- Data Interpretation

---

# 📌 Project Outcome

This project demonstrates an end-to-end analytics workflow:

**Raw Data → SQL Analysis → Excel Analysis → Tableau Dashboard → Power BI Dashboard → Business Insights**

The final dashboards convert restaurant data into interactive visual insights that make it easier to understand restaurant performance, pricing, ratings, cuisines, customer votes, service availability, locations, and opening trends.

---

# 👨‍💻 Author

**Dhairya Yadav**

Data Analytics Enthusiast

### Areas of Interest

- Data Analytics
- Business Intelligence
- SQL
- Excel
- Tableau
- Power BI
- Data Visualization

---

## ⭐ Project Highlights

**9,551 Restaurants | 141 Cities | 15 Countries | SQL + Excel + Tableau + Power BI**

