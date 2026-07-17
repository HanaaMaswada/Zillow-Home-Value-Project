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


referances
* [Google Colab Code Snippets](https://colab.research.google.com/notebooks/io.ipynb)
* [Pandas read_csv Documentation](https://pandas.pydata.org/docs/reference/api/pandas.read_csv.html)
* [Pandas DataFrame.shape](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.shape.html)
* [Pandas DataFrame.head](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.head.html)
* [Pandas melt Documentation](https://pandas.pydata.org/docs/reference/api/pandas.melt.html)
* [Pandas to_datetime](https://pandas.pydata.org/docs/reference/api/pandas.to_datetime.html)
* [Pandas DataFrame.set_index](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.set_index.html)
* [Pandas DataFrame.sort_index](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.sort_index.html)
* [Pandas DataFrame.isin](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.isin.html)
* [Pandas DataFrame.copy](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.copy.html)
* [Pandas DataFrame.to_csv](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.to_csv.html)
* [Pandas DataFrame.groupby](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.groupby.html)
* [Pandas DataFrame.resample](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.resample.html)
* [Pandas DataFrame.unstack](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.unstack.html)
* [Python os.makedirs Documentation](https://docs.python.org/3/library/os.html#os.makedirs)
* [Pandas DataFrame.plot](https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.plot.html)
* [Matplotlib Axes Documentation](https://matplotlib.org/stable/api/axes_api.html)
* [Matplotlib Legend Guide](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.legend.html)
* [Matplotlib ax.grid](https://matplotlib.org/stable/api/_as_gen/matplotlib.axes.Axes.grid.html)
* [Matplotlib tight_layout](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.tight_layout.html)
* [Matplotlib plt.show](https://matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.show.html)
* [Tableau Desktop Help and Documentation](https://help.tableau.com/current/desktopdeploy/en-us/desktop_deploy_guide.htm)
* [Tableau Data Prep and Formatting Best Practices](https://help.tableau.com/current/pro/desktop/en-us/data_structure_for_tableau.htm)
* [Tableau Visual Analytics Guide](https://help.tableau.com/current/blueprint/en-us/bp_visual_analytics.htm)
