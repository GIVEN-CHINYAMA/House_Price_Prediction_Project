# 🚴 Cyclistic Bike-Share: Marketing Strategy Case Study

![Data Analysis](https://img.shields.io) ![SQL](https://img.shields.io) ![Python](https://img.shields.io)

## 📌 Business Scenario
Cyclistic is a successful bike-share program in Chicago. The director of marketing believes the company’s future success depends on maximizing the number of annual memberships. 

**Goal:** Analyze how annual members and casual riders use Cyclistic bikes differently to design a new marketing strategy to convert casual riders into annual members.

## 🛠️ The Data Process (Ask, Prepare, Process, Analyze, Share, Act)
1.  **Data Source:** 12 months of Cyclistic’s historical trip data (5.6M+ records).
2.  **Processing:** Cleaned data using **Python (Pandas)** to handle null values, remove duplicate entries, and calculate trip duration.
3.  **Feature Engineering:** 
    - Created `ride_length` (trip duration in minutes).
    - Extracted `day_of_week` and `month` to identify seasonal and weekly patterns.
    - Filtered out "test" rides and maintenance trips.

## 💡 Key Business Insights
*   **The Weekend Warrior:** Casual riders use bikes primarily on weekends (Sat/Sun) for leisure, with average trip durations **2.5x longer** than members.
*   **The Commuter:** Annual members have highly predictable peaks at **8 AM and 5 PM** on weekdays, suggesting they use Cyclistic for daily work transit.
*   **Seasonal Trends:** Ride volume for both groups drops by **75% in Winter (Dec-Feb)**, but casual ridership drops more drastically than member ridership.
*   **Station Popularity:** Casual riders congregate near tourist landmarks and waterfronts, while members use inland stations near office hubs.

## 🎯 Final Recommendations (Marketing Strategy)
1.  **Seasonal Campaigns:** Launch "Early Bird" membership discounts in late February to capture casual riders as the weather warms up.
2.  **Weekend Membership:** Introduce a "Weekend-Only" or "Leisure Pass" to transition high-volume casual riders into a recurring subscription model.
3.  **Digital Targeting:** Use location-based digital ads at the top 10 "Casual" stations (tourist hubs) promoting the cost-savings of annual memberships for long trips.

## 📊 Visualizations
*Check the `visuals/` folder for high-resolution charts showing:*
- Average Trip Duration by User Type.
- Total Rides per Month (Casual vs. Member).
- Peak Usage Hours (Heatmap).

## 🚀 How to Run
```bash
git clone https://github.com
# Data cleaning and analysis performed in Jupyter Notebook
jupyter notebook Cyclistic_Analysis.ipynb


## 📬 Contact
[LinkedIn](https://linkedin.com) | [Email](mailto:givenchinyama@gmail.com)
