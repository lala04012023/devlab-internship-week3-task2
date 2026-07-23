# devlab-internship-week3-task2
# Hotel Booking Analysis

## Project Overview

This project analyzes hotel booking data to uncover customer behavior, booking trends, and cancellation patterns. The analysis includes data cleaning, feature engineering, exploratory data analysis (EDA), and visualizations that provide actionable insights for hotel revenue management.

---

## Dataset

https://www.kaggle.com/datasets/jessemostipak/hotel-booking-demand

---

## Project Tasks

### 1. Data Cleaning

* Loaded the `hotel_bookings.csv` dataset.
* Checked for missing values.
* Filled missing values:

  * `country` → **"Unknown"**
  * `agent` → **0**
  * `company` → **0**

### 2. Feature Engineering

* Created a new **arrival_date** column by combining:

  * `arrival_date_year`
  * `arrival_date_month`
  * `arrival_date_day_of_month`

### 3. Pivot Table Analysis

* Built a pivot table with:

  * **Rows:** Arrival Month
  * **Columns:** Hotel Type
  * **Values:** Booking Count

### 4. Cancellation Analysis

* Calculated the monthly cancellation rate for each hotel type.
* Compared the average **lead_time** for:

  * Cancelled bookings
  * Non-cancelled bookings

### 5. Country Analysis

* Identified the **Top 10 countries** by total bookings.
* Calculated the cancellation rate for each country.

### 6. Market Segment Analysis

* Analyzed booking demand across different market segments such as:

  * Online TA
  * Offline TA/TO
  * Direct
  * Corporate
  * Groups
  * Complementary
  * Aviation

---

## Visualizations

The project includes the following visualizations:

* Heatmap of booking counts (Arrival Month × Hotel Type)
* Monthly cancellation rate line chart
* Top 10 countries by bookings (Bar Chart)
* Market segment distribution (Pie Chart)

---

## Business Insights

* Online Travel Agencies (Online TA) generate the highest booking demand, making them an important sales channel.
* Longer lead times are generally associated with higher cancellation rates.
* Cancellation rates vary across hotel types and months, indicating seasonal booking behavior.
* Focusing marketing efforts on countries and market segments with lower cancellation rates can improve occupancy and increase revenue stability.

---

## Technologies Used

* Python
* Pandas
* NumPy
* Matplotlib
* Seaborn
* Jupyter Notebook




---

## Conclusion

This project demonstrates how data analysis can help hotels better understand booking behavior, reduce cancellations, optimize pricing strategies, and support more effective revenue management decisions.
