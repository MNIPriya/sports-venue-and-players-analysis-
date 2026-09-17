# 🏆 Sports Analytics & Venue Booking Analysis

## 📌 Project Overview

This project focuses on analyzing **sports venue booking data** to understand booking patterns, customer behavior, revenue generation, cancellations, and venue performance.

The project uses **Python, SQL, Excel, and Power BI** to perform an end-to-end data analytics workflow — from data cleaning and feature engineering to advanced analysis and interactive dashboard creation.

The goal is to transform raw sports booking data into meaningful business insights that can help sports facility and booking platforms improve **revenue, customer engagement, venue utilization, and operational efficiency**.

---

## 🎯 Objectives

* Analyze overall sports booking trends.
* Identify the most popular sports.
* Analyze revenue generated across different sports and venues.
* Identify peak booking days and time periods.
* Analyze customer booking behavior.
* Study booking cancellations and cancellation reasons.
* Compare venue and city performance.
* Analyze payment methods and booking sources.
* Identify high-performing venues.
* Create interactive dashboards for business decision-making.

---

## 📊 Dataset

The dataset contains sports venue booking information.

### Important Columns

| Column                | Description                               |
| --------------------- | ----------------------------------------- |
| `booking_id`          | Unique ID for each booking                |
| `user_id`             | Unique customer ID                        |
| `venue_id`            | Unique venue ID                           |
| `booking_date`        | Date of the booking                       |
| `booking_time`        | Time of the booking                       |
| `sport`               | Sport booked                              |
| `city`                | City where the venue is located           |
| `area`                | Area/location of the venue                |
| `venue_name`          | Name of the sports venue                  |
| `court_type`          | Type of court/facility                    |
| `duration_hours`      | Duration of the booking                   |
| `players_count`       | Number of players                         |
| `booking_amount`      | Original booking amount                   |
| `discount`            | Discount applied                          |
| `final_amount`        | Final amount paid                         |
| `payment_method`      | Payment method used                       |
| `booking_status`      | Status of the booking                     |
| `cancellation_reason` | Reason for cancellation                   |
| `booking_source`      | Source through which the booking was made |

---

# 🛠️ Tools & Technologies

### Python

* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook

### SQL

* Data querying
* Filtering
* Aggregations
* Joins
* Subqueries
* CTEs
* Window Functions
* CASE statements

### Excel

* Data cleaning
* Pivot Tables
* Pivot Charts
* Data analysis
* Interactive charts

### Power BI

* Data modeling
* DAX measures
* KPI cards
* Interactive visualizations
* Slicers
* Drill-down analysis
* Dashboard development

---

# 🔄 Project Workflow

```text
Raw Dataset
     ↓
Data Cleaning
     ↓
Exploratory Data Analysis
     ↓
Feature Engineering
     ↓
SQL Analysis
     ↓
Excel Analysis
     ↓
Power BI Data Modeling
     ↓
DAX Measures
     ↓
Interactive Dashboard
     ↓
Business Insights
```

---

# 🧹 Data Cleaning

The dataset was cleaned and prepared before analysis.

Major steps included:

* Checking missing values
* Checking duplicate records
* Correcting data types
* Standardizing column names
* Converting date and time columns
* Handling categorical variables
* Validating numerical columns
* Checking inconsistent values
* Preparing the dataset for analysis

---

# ⚙️ Feature Engineering

Additional features were created to improve the analysis.

Examples include:

* Day of Week
* Month
* Year
* Booking Hour
* Peak/Off-Peak Period
* Booking Duration Category
* Revenue-related features
* Discount-related features
* Cancellation indicators
* Customer booking frequency

These features helped identify **time-based booking patterns, customer behavior, and revenue trends**.

---

# 🗄️ SQL Analysis

Advanced SQL queries were used to analyze the booking data.

The analysis included:

* Total bookings
* Total revenue
* Revenue by sport
* Revenue by city
* Revenue by venue
* Bookings by day of week
* Monthly booking trends
* Cancellation analysis
* Customer booking frequency
* Top-performing venues
* Average booking value
* Payment method analysis
* Booking source analysis
* CTEs
* Window functions
* Ranking analysis
* Conditional aggregation

---

# 📗 Excel Analysis

Excel was used for exploratory analysis and summary reporting.

### Analysis performed:

* Pivot Tables
* Pivot Charts
* Revenue analysis
* Booking analysis
* Sport-wise analysis
* City-wise analysis
* Venue-wise analysis
* Cancellation analysis
* Customer behavior analysis
* Time-based booking analysis

---

# 📊 Power BI Dashboard

An interactive Power BI dashboard was developed to provide a comprehensive view of sports booking performance.

### Key KPIs

* **Total Bookings**
* **Total Revenue**
* **Total Users**
* **Total Venues**
* **Cancellation Rate**
* **Cancellation Bookings**

### Dashboard Analysis

The dashboard provides analysis of:

* 📈 Booking trends
* 💰 Revenue performance
* 🏏 Sports popularity
* 🏟️ Venue performance
* 📍 City and area analysis
* 📅 Day-of-week trends
* ⏰ Peak booking periods
* ❌ Cancellation behavior
* 💳 Payment methods
* 📱 Booking sources
* 👥 Customer behavior

Interactive slicers allow users to filter the analysis by relevant dimensions such as **sport, city, venue, booking status, and time period**.

---

# 🔍 Key Business Questions

The project answers questions such as:

1. What is the total number of bookings?
2. What is the total revenue generated?
3. Which sports receive the highest number of bookings?
4. Which sports generate the most revenue?
5. Which venues have the highest booking activity?
6. Which cities generate the highest revenue?
7. Which days have the highest number of bookings?
8. What are the peak booking periods?
9. What percentage of bookings are cancelled?
10. What are the major cancellation reasons?
11. Which payment methods are most frequently used?
12. Which booking sources generate the most bookings?
13. What is the average booking value?
14. How does booking duration affect revenue?
15. Which venues and sports show stronger booking performance?

---

# 💡 Business Insights

The analysis helps identify:

* Customer demand patterns across different sports.
* High-performing sports and venues.
* Revenue-generating locations.
* Peak booking periods.
* Cancellation patterns.
* Customer booking behavior.
* Payment preferences.
* Booking source performance.
* Opportunities to improve venue utilization and revenue.

---

# 📸 Dashboard

### Power BI Dashboard

Add screenshots of your Power BI dashboards below:

```markdown
![Sports Analytics Dashboard](images/dashboard1.png)
```

You can add multiple dashboard screenshots:

```markdown
![Overview Dashboard](images/dashboard1.png)

![Revenue Analysis](images/dashboard2.png)

![Booking Analysis](images/dashboard3.png)
```

---

# 📁 Project Structure

```text
Sports-Analytics/
│
├── data/
│   └── sports_booking_data.csv
│
├── python/
│   ├── data_cleaning.ipynb
│   ├── exploratory_data_analysis.ipynb
│   └── feature_engineering.ipynb
│
├── sql/
│   └── sports_analysis.sql
│
├── excel/
│   └── sports_analysis.xlsx
│
├── powerbi/
│   └── sports_analytics.pbix
│
├── images/
│   ├── dashboard1.png
│   ├── dashboard2.png
│   └── dashboard3.png
│
└── README.md
```

---

# 🚀 Skills Demonstrated

* Data Cleaning
* Exploratory Data Analysis
* Feature Engineering
* Python
* Pandas
* NumPy
* SQL
* Advanced SQL
* Excel
* Pivot Tables
* Data Visualization
* Power BI
* DAX
* Data Modeling
* KPI Development
* Business Intelligence
* Business Analysis
* Data Storytelling

---

# 👩‍💻 Author

**Priya Baradwaj**

Computer Science Engineering Student | Data Analytics | Python | SQL | Power BI

---

⭐ If you find this project useful, feel free to explore the repository.
