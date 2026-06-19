# Data Analyst Internship - Task 3: Interactive Dashboard Design

## 🎯 Objective
The objective of this task is to design an interactive dashboard for business stakeholders using a Sales/Financial dataset to derive actionable insights and inform business decisions.

## 🛠️ Tools Used
* **Development Environment:** Google Colab (Python)
* **Libraries:** Pandas (Data Manipulation), Plotly Express & Graph Objects (Interactive Visualizations)
* **Documentation & Summary:** Microsoft PowerPoint & GitHub Markdown

---

## 📊 Key KPIs & Insights Addressed
1.  **Total Sales & Total Profit:** Displayed using summary metrics to give stakeholders an immediate health check of the business.
2.  **Time-Series Analysis:** A dynamic Line Chart showing sales trends over time to identify seasonal peaks or drops.
3.  **Category Performance:** A Bar Chart breaking down sales by product categories to pinpoint top revenue generators.
4.  **Regional Distribution:** A Donut/Pie Chart representing profit distribution across different regions.

---

## 💻 How to Run the Code
1. Open the `Sales_Dashboard_Task3.ipynb` file in Google Colab.
2. Upload your own sales CSV file or use the provided dataset.
3. Run all cells sequentially to generate the interactive Plotly charts.

---

## ❓ Technical Interview Questions & Answers

### Q1. What are the key elements of a dashboard?
**Answer:** The core elements include KPI cards for summary metrics, visual charts (line, bar, pie) for trends and comparisons, slicers/filters for interactivity, a consistent layout/color scheme, and clear navigation for the user.

### Q2. What is a KPI?
**Answer:** KPI stands for Key Performance Indicator. It is a measurable value that demonstrates how effectively a company is achieving its key business objectives (e.g., Total Revenue, Net Profit Margin).

### Q3. What are slicers in Power BI?
**Answer:** Slicers are on-canvas visual filters in Power BI that allow users to filter the data displayed in all other dashboard visuals by specific categories, dates, or regions.

### Q4. Difference between Power BI and Tableau?
**Answer:** * **Power BI:** Developed by Microsoft, tightly integrated with Excel, has a free desktop version, uses DAX, and is highly user-friendly.
* **Tableau:** Known for powerful data visualization capabilities, handles massive datasets seamlessly, but has a steeper learning curve and higher licensing costs.

### Q5. How do you make a dashboard interactive?
**Answer:** Interactivity is achieved through the use of slicers, cross-filtering (clicking one chart filters others), drill-down features, tooltips on hover, and custom buttons/bookmarks.

### Q6. How do you deal with large datasets in dashboards?
**Answer:** To handle large datasets, we use data aggregation (summarizing data before loading), optimize data models (like Star Schema), choose the correct storage mode (DirectQuery vs. Import), and remove unnecessary columns.

### Q7. What chart types do you use for trend analysis?
**Answer:** Line charts and Area charts are the industry standard for trend analysis as they clearly show progression, patterns, and cycles over time.
