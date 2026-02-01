# Snapdeal_Men-s_Sports_shoes
Snapdeal-Mens-Sports-Shoes-Analysis/
│
├── scraping/
│   └── snapdeal_scraper.py
│
├── data/
│   ├── raw/
│   │   └── snapdeal_raw_data.csv
│   └── cleaned/
│       └── snapdeal_cleaned_data.csv
│
├── powerbi/
│   └── Snapdeal_Shoes_Analysis.pbix
│
├── images/
   └── dashboard_preview.png

   📌 Project Overview

This project focuses on analyzing men’s sports footwear products available on Snapdeal to uncover insights related to pricing, discounts, savings, ratings, and brand-wise performance. The objective of this analysis is to understand how different brands compete in terms of product availability, customer perception (ratings & reviews), and discount strategies, and to present these insights through an interactive and user-friendly Power BI dashboard.

The project demonstrates an end-to-end data analytics workflow, starting from data collection via web scraping, followed by data cleaning and transformation, and finally visualization and insight generation.

🌐 Data Collection (Web Scraping)

The data used in this project was scraped directly from the Snapdeal website using Python-based web scraping techniques. Relevant product-level information was extracted, including:

Product Name
Brand
Original Price
Discounted Price
Price Savings
Discount Percentage
Product Rating
Number of Reviews

The scraped data was compiled into a structured dataset (CSV format), which served as the raw input for further analysis. This step highlights practical experience in handling real-world, unstructured web data and converting it into an analyzable format.

🧹 Data Cleaning & Transformation

After scraping, the raw dataset was imported into Power BI, where data cleaning and preprocessing were performed. This included:

Handling missing and inconsistent values
Standardizing price and discount-related columns
Creating calculated fields such as savings and discount percentage
Ensuring correct data types for numerical analysis
Filtering irrelevant or incomplete records
The cleaned dataset ensured accuracy, consistency, and reliability of the insights presented in the dashboard.

📈 Dashboard & Analysis

An interactive Power BI dashboard was developed to visualize key metrics and trends related to men’s sports footwear on Snapdeal. The dashboard provides both high-level KPIs and brand-level comparisons, enabling quick decision-making and exploratory analysis.

Key Metrics Displayed:

Total Products: 20
Average Rating: 3.10
Total Reviews: 178
Average Savings: 1.15K

Key Visual Insights:

Brand-wise Product Count highlights market presence of each brand
Total and Average Savings by Brand reveals discount strategies
Original Price vs Discounted Price comparison shows pricing competitiveness
Discount Percentage by Brand identifies brands offering higher relative discounts
Interactive Filters allow users to slice data by brand and rating

🔍 Key Insights:

Some brands dominate in terms of product availability, while others focus on higher discounts to attract customers.

Higher discounts do not always correlate with higher ratings, indicating that price is not the only factor influencing customer satisfaction.

Certain brands offer better average savings, making them more attractive to price-sensitive customers.

The dashboard enables quick identification of value-for-money brands based on combined price, discount, and rating analysis.

🛠 Tools & Technologies Used:

Python – Web scraping and dataset creation
Power BI – Data cleaning, transformation, and dashboard creation
CSV Dataset – Intermediate data storage

Attach the snapshot of dashbaord_link:- https://github.com/HimanshiAgrawal27/Snapdeal_Men-s_Sports_shoes/blob/main/snapshot_men'sfootware_dashboard.png

