# 🍽️ Zomato Bangalore Restaurant Analysis

## 📌 Project Overview
This project analyzes Zomato restaurant data from Bangalore to uncover patterns in restaurant distribution, pricing, ratings, and customer preferences. The goal is to derive actionable business insights using data cleaning, exploratory data analysis (EDA), and interactive dashboard visualization.

## 🛠️ Tools & Technologies
- **Python** (Pandas) – Data cleaning and preprocessing
- **Google Colab** – Development environment
- **Power BI** – Interactive dashboard and visualization

## 📊 Dataset
- **Source:** [Kaggle - Zomato Bangalore Restaurants](https://www.kaggle.com/datasets/himanshupoddar/zomato-bangalore-restaurants)
- **Size:** ~10,613 rows, 17 columns (after cleaning)
- **Fields:** Restaurant name, location, cuisines, rating, cost, online order availability, table booking, restaurant type, and more

## 🧹 Data Cleaning Steps
1. Cleaned the `rate` column (removed "/5" suffix, handled "NEW" and missing values)
2. Cleaned the `approx_cost` column (removed commas, converted to numeric)
3. Handled missing values using mean/median imputation and "Not Specified" placeholders
4. Removed unnecessary columns (url, phone, address, reviews_list, menu_item)
5. Removed duplicate rows

## 📈 Dashboard Features
The Power BI dashboard includes:
- Restaurant count by location
- Restaurant type distribution
- Average rating comparison (online order vs no online order)
- Average rating comparison (table booking vs no table booking)
- Top cuisines by restaurant count
- Cost vs rating relationship (scatter plot)
- Key metrics: Total restaurants, average cost, maximum rating

## 🔍 Key Insights
- **Location Distribution:** BTM has the highest number of restaurants (~950+), followed by Bannerghatta Road (~800), indicating high restaurant density and competition in these areas.
- **Restaurant Type:** Quick Bites is the most common restaurant type (36.8%), followed by Casual Dining, showing strong demand for fast and casual dining options in Bangalore.
- **Online Order & Rating:** Restaurants offering online ordering have a slightly higher average rating compared to those that don't.
- **Table Booking & Rating:** Restaurants offering table booking have a notably higher average rating, indicating premium/organized dining establishments receive better customer reviews.
- **Popular Cuisine:** North Indian cuisine is the most popular choice, followed by South Indian.
- **Cost vs Rating:** No strong correlation exists between cost and rating — higher-priced restaurants don't necessarily receive better ratings.

## 📁 Repository Contents
- `data_cleaning.ipynb` – Python code for data cleaning and EDA
- `Zomato_Restaurant_Dashboard.pbix` – Power BI dashboard file
- `README.md` – Project documentation

## 🚀 How to Use
1. Open `data_cleaning.ipynb` in Google Colab to view the data cleaning process
2. Open `Zomato_Restaurant_Dashboard.pbix` in Power BI Desktop to explore the interactive dashboard
