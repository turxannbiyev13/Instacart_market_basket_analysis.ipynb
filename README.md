# 📊 Instacart Market Basket Data Analysis

An end-to-end data analytics project focused on exploring customer purchasing behavior, order distribution habits, and product reorder dynamics using Python and advanced data manipulation techniques.

## 📌 Project Overview
This project tackles real-world retail and e-commerce challenges by uncovering critical business insights from large-scale transactional datasets. The analysis transitions from basic data distributions to complex user-level and product-level aggregations.

## 🛠️ Tech Stack & Tools
* **Language:** Python
* **Environment:** Google Colab
* **Libraries:** Pandas, NumPy, Matplotlib, Seaborn

## 📂 Dataset
The original dataset used in this project is hosted externally due to file size constraints. You can access the data files here:

[Download Instacart Dataset from Google Drive](https://drive.google.com/drive/folders/1-P3jBC0Vnm4Hu5gdkAVxTVki4c61vnfR?usp=sharing)

## 🔍 Key Insights Discovered
* **Peak Ordering Windows:** Core traffic is highly concentrated between **10:00 AM and 4:00 PM**. Weekday traffic peaks sharply in the morning, while weekend (Saturday) traffic forms a sustained afternoon plateau.
* **Customer Purchasing Cycles:** The data reveals strong behavioral patterns with massive spikes at the **7-day (weekly routine)** and **30-day (monthly subscription/lapsed users)** marks.
* **Cart Dynamics & User Intent:** Fresh organic produce serves as the primary engine for the platform. These items are predominantly the **first-to-cart** choices, driving the intent behind entire shopping sessions.
* **Product Stickiness:** High reorder ratios among specific staples indicate deep-rooted household habits, showcasing prime opportunities for automated restock subscription models.

## 📈 Methodology & Tasks
The codebase is structured into progressive complexity tiers:
1. **Basic Exploratory Analysis (Tier A):** Reviewing peak hours, minimum/maximum reorder days, and data types.
2. **Comparative Analysis (Tier B):** Investigating workday vs. weekend hour distributions and plotting overlapping histograms.
3. **Advanced Data Merging & Aggregations (Tier C - Hard):** Calculating product reorder ratios, individual user-level reorder proportions, and uncovering the top items placed first in carts.

## 🚀 How to Run the Notebook
1. Clone this repository.
2. Open the `.ipynb` file in Google Colab or Jupyter Notebook.
3. Ensure the dataset path is correctly pointed to your environment.
4. Run all cells to generate the visualizations and metrics.
