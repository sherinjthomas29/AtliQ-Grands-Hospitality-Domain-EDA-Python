# AtliQ Grands - Hospitality Revenue Analysis

💻 [Report](https://github.com/sherinjthomas29/AtliQ-Grands-Hospitality-Domain-EDA-Python/blob/main/Hospitality_Analysis.pdf)

## **📊 Project Overview**
Python-based data analytics project analyzing booking patterns and revenue trends for AtliQ Grands, a hotel chain operating across multiple Indian cities with brands including AtliQ Seasons, AtliQ Exotica, AtliQ Bay, and AtliQ Palace.
________________________________________

## **🎯 Project Description**

**Situation**

AtliQ Grands experienced declining revenue and market share in the competitive hospitality sector, lacking data-driven insights to understand booking patterns and optimize performance across properties and channels.

**Task**
Analyze booking data from official website and third-party platforms to identify revenue drivers, occupancy patterns, and performance gaps across cities, room categories, and time periods to support strategic decision-making.

**Action**

--> Performed comprehensive data exploration and cleaning on 134,590+ booking records
--> Removed outliers using statistical methods (mean ± 3*std) and handled missing data (57.9% ratings missing)
--> Analyzed occupancy rates across room categories, cities, and day types (weekday vs weekend)
--> Calculated revenue metrics by city, month, and property category
--> Created visualizations using Matplotlib for stakeholder presentation
--> Merged multiple datasets (bookings, hotels, rooms, dates) for holistic analysis

**Result**

Generated actionable insights revealing:

--> Occupancy patterns: Presidential rooms highest at 59.30%, Standard lowest at 58.22%
--> Revenue distribution: Identified top-performing cities and seasonal trends
--> Booking channel analysis: Direct vs third-party platform performance
--> Monthly revenue trends showing decline from May (₹347M) to July (₹330M)
________________________________________

## **🔍 Key Insights**
Occupancy Analysis

**Room Performance**: Presidential rooms lead with 59.30% occupancy, while all categories hover around 58-59%
**Day Type**: Weekend occupancy significantly higher than weekdays
**City Performance**: Occupancy rates vary significantly across Delhi, Mumbai, Bangalore, and Hyderabad

**Revenue Insights**

**Monthly Trend**: Revenue declined from ₹347M (May) → ₹324M (June) → ₹330M (July), indicating seasonal challenges
**City Contribution**: Certain cities dominate revenue generation, requiring targeted strategies for underperforming markets
**Booking Platforms**: Direct online bookings compete with third-party platforms (MakeYourTrip, LogTrip, Tripster, Journey)

**Data Quality**

Guest Records: Removed 12 records with invalid guest counts (≤0)
Outliers: Cleaned 5 extreme revenue outliers (>₹2.94 lakh) using 3-sigma rule
Missing Data: 57.9% of ratings not provided, indicating customer engagement opportunity

**Property Performance**

**Category Split**: Luxury vs Business properties across 4 major cities
**Room Distribution**: RT1 (Standard), RT2 (Elite), RT3 (Premium), RT4 (Presidential)
**Capacity Utilization**: Some properties show overbooking (>100% occupancy)
________________________________________

## **🛠️ Tools & Technologies**

Language: Python 3.x
Libraries:

Pandas (Data manipulation & analysis)
Matplotlib (Data visualization)
NumPy (Statistical operations)


IDE: Jupyter Notebook
Data Format: CSV files
________________________________________

## **💡 Recommendations**

Address Revenue Decline: Investigate 5% revenue drop from May to July and implement recovery strategies
Boost Weekday Occupancy: Create targeted promotions and business traveler packages for weekdays
Optimize Pricing Strategy: Presidential rooms show only 1% higher occupancy despite premium pricing
Improve Rating Collection: Only 42% of bookings have ratings - implement post-stay engagement campaigns
Balance Channel Mix: Analyze profitability of direct vs third-party platforms to optimize distribution
Focus on Low-Performing Cities: Develop city-specific strategies for markets with lower occupancy
________________________________________

## **🚀 Skills Demonstrated**

Exploratory Data Analysis (EDA)
Data cleaning and preprocessing
Statistical outlier detection
Multi-table data merging and transformation
Time-series analysis
Business metrics calculation (occupancy %, revenue)
Data visualization and storytelling
Python programming and Pandas proficiency
________________________________________

## **📊 Key Metrics Tracked**

Occupancy Rate: Successful bookings / Total capacity
Revenue Realized: Actual revenue after discounts and cancellations
Revenue Generated: Gross revenue before adjustments
Average Rating: Customer satisfaction metric
Booking Status: Success vs cancellation rates
