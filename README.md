# Zillow-Home-Value-Project
Zillow Home Value Project


# Zillow Home Value Analysis Project

This project provides a comprehensive data analysis and interactive visualization of home value trends across multiple states between 2010 and 2020. The workflow combines data preprocessing using Python in Google Colab and interactive storytelling using Tableau Public.

## 🔗 Project Links
* **Interactive Tableau Story:** [View Interactive Dashboard](https://public.tableau.com/views/ZillowHomeValueProject/ZillowHomeValueProject?:language=en-US&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)
* **Google Colab Notebook:** [View Python Code](https://colab.research.google.com/drive/1byevZwCcjBPBA0QAUK4gm15dNUa276Z3?usp=sharing)

---

## 📊 Key Insights & Deliverables

### 📍 Story Point 1: Most Expensive Zip Codes
* A structured bar graph showing the **Median Home Value by Location** (including State, County Name, and Zip Code).
* The visualization is filtered to isolate only the most expensive zip codes, with bars color-coded dynamically by **County Name** for immediate distinction.

### 📈 Story Point 2: Percentage Change (2010 - 2020)
* A line graph tracking the historical change in home values over a decade, color-coded by **State**.
* Implemented a Table Calculation to compute the percentage difference in the median home value relative to the starting date.
* **Key Finding (Annotated):** **Nevada (NV)** recorded the largest percentage increase in home values between 2010 and 2020.

### 🗂️ Story Point 3: Top 20 Highlight Table
* An interactive **Highlight Table** displaying the Top 20 most expensive zip codes.
* Includes distinct breakdown metrics: State, County Name, City, Zip Code, and Median Home Value.
* Filtered specifically by Month/Year with **December 2020** set as the default, presented through a clean, single-value slider filter.

### 🗺️ Story Point 4: Geographic Distribution Map
* A geographical map utilizing a tailored **Dark Mode** map style layers to plot out real estate values across regions.
* Styled with a color gradient representing the median housing values to spot high-value clusters instantly.

---

## 🛠️ Tech Stack & Tools
* **Data Cleansing & Aggregation:** Python (Pandas, NumPy) via **Google Colab**
* **Data Visualization & BI:** **Tableau Public**
