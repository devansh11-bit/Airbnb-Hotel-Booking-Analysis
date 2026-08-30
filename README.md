# Airbnb Hotel Booking Analysis

## 📌 Project Overview

This project analyzes Airbnb Open Data to identify meaningful patterns and insights related to room types, neighbourhoods, pricing, hosts, reviews, service fees, cancellation policies and availability.

The analysis was performed using Python, Pandas, Matplotlib and Jupyter Notebook.

## 🎯 Objectives

The project aims to answer the following questions:

1. What are the different property/room types in the dataset?
2. Which neighbourhood group has the highest number of listings?
3. In which neighbourhoods are the highest number of rooms available for Airbnb listings?
4. Is there a relationship between the construction year of a property and its price?
5. Who are the top 10 hosts by evaluated host listings count?
6. Are hosts with verified identities more likely to receive positive reviews?
7. Is there a correlation between the price of a listing and its service fee?
8. What is the average review rate, and does it vary by neighbourhood group and room type?
9. Does cancellation policy affect yearly availability?

## 🛠️ Tools & Technologies

* Python
* Pandas
* Matplotlib
* Jupyter Notebook
* Excel Dataset

## 🧹 Data Cleaning

The dataset was examined for:

* Missing values
* Duplicate records
* Invalid minimum-night values
* Inconsistent neighbourhood names
* Numerical data quality

Duplicate records were removed, and invalid minimum-night values were handled using the median of valid observations.

## 📊 Key Findings

* Manhattan has the highest number of listings among neighbourhood groups.
* Bedford-Stuyvesant has the highest number of listings among individual neighbourhoods.
* Entire home/apt and Private room are the most common room types.
* Construction year does not show a clear relationship with price.
* Blueground has the highest calculated host listing count with 332 listings.
* Verified hosts have only a slightly higher average review rating than unconfirmed hosts.
* Price and service fee have an extremely strong positive correlation.
* The overall average review rating is approximately 3.28 out of 5.
* Cancellation policy shows only a small difference in average yearly availability.

## 📁 Project Structure

```text
Airbnb-Hotel-Booking-Analysis/
│
├── Airbnb_Hotel_Booking_Analysis.ipynb
├── README.md
└── Airbnb_Open_Data.xlsx
```

## 📌 Conclusion

The analysis provides insights into Airbnb listing patterns, pricing, host activity, customer reviews and availability. The results demonstrate how Python-based exploratory data analysis can be used to understand patterns in a real-world hospitality dataset and support data-driven decision making.
