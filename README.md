# Indian-real-estate-market-analytics
# Indian Real Estate Market Analytics

## 📌 Project Overview

This project analyzes Indian real estate property data to identify patterns and insights related to property prices, locations, property types, BHK, furnishing, amenities, RERA registration, and other property characteristics.

The project uses Python for data cleaning and exploratory data analysis (EDA), and Power BI for interactive dashboard visualization.

## 🎯 Objectives

- Analyze property prices across different Indian cities
- Compare prices across different property types
- Analyze property prices by BHK and bathrooms
- Study furnishing and parking patterns
- Analyze RERA registration status
- Understand property age and year-built distribution
- Analyze price ranges
- Calculate and compare price per square foot
- Build an interactive Power BI dashboard

## 🛠️ Technologies Used

- Python
- Pandas
- NumPy
- Matplotlib
- Jupyter Notebook
- Power BI

## 📊 Dataset

The dataset contains Indian real estate property listings with information such as:

- City
- Locality
- Property Type
- BHK
- Bathrooms
- Balconies
- Furnishing
- Super Built-up Area
- Built-up Area
- Building Type
- Year Built
- Property Age
- Facing
- Amenities
- RERA Registration
- Latitude and Longitude
- Property Price

The dataset was cleaned and prepared before performing the analysis.

## 🧹 Data Cleaning

The following data-cleaning steps were performed:

- Checked missing values
- Checked duplicate records
- Handled missing city values using locality information
- Handled missing categorical values
- Filled numerical missing values using appropriate statistical methods
- Preserved missing RERA IDs where properties were not RERA registered
- Checked the final dataset after cleaning

## 📈 Exploratory Data Analysis

The project includes analysis of:

- Average property price by city
- Number of properties by city
- Average price by property type
- Property count by property type
- Average price by BHK
- City and property-type price comparison
- Furnishing-wise average price
- RERA registration distribution
- Price-range distribution
- Year-built distribution
- Property-age distribution
- Bathroom-wise average price
- Parking distribution
- Facing distribution
- Amenities distribution
- Building-type distribution
- Average area by property type
- RERA registration by city
- Average price per square foot by city

## 📊 Power BI Dashboard

An interactive Power BI dashboard was created to visualize the major findings from the analysis.

### Dashboard Preview

![Indian Real Estate Dashboard](dashboard.png)

The dashboard includes:

- Average Property Price by City
- Average Property Price by Property Type
- Average Property Price by Furnishing
- Property Type Distribution
- Number of Properties by City
- City filter
- Property Type filter
- Furnishing filter
- Bathroom filter
- Price range filter

## 📁 Project Structure

```text
indian-real-estate-market-analytics/
│
├── Indian_Real_Estate_Cleaned.csv
├── Real_Estate_Analysis.ipynb
├── project.pbix
├── dashboard.png
└── README.md
