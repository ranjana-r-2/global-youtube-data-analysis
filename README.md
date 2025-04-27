# 📊 Global YouTube Statistics Analysis

This project performs an exploratory data analysis (EDA) on a dataset containing global YouTube channel statistics. It uncovers key insights about subscribers, earnings, uploads, and demographic factors influencing YouTube channel growth and revenue.

## 📁 Dataset

- **File:** `Global_YouTube_Statistics.csv`
- **Encoding:** ISO-8859-1
- **Description:** Contains data about YouTube channels worldwide including country, category, subscribers, video views, uploads, earnings, population demographics, etc.

## 🛠️ Libraries Used

- **Pandas** - Data manipulation and analysis
- **NumPy** - Numerical operations
- **Matplotlib** - Data visualization
- **Seaborn** - Advanced visualization
- **Jupyter Notebook** - Code execution and visualization (`%matplotlib inline`)

---

## 📝 Analysis Performed

1. **Data Cleaning**
   - Checked for missing values and duplicates
   - Dropped irrelevant or incomplete features
   - Handled missing data by dropping rows

2. **Feature Engineering**
   - Created `avg_yearly_earning` feature as the average of `lowest_yearly_earnings` and `highest_yearly_earnings`
   - Created `revenue_per_subscriber` feature

3. **Exploratory Data Analysis (EDA)**
   - **Correlation Heatmap** between numerical features
   - **Scatter Plots**:
     - Subscribers vs Average Yearly Earnings (log-log scale)
     - Urban Population vs Uploads
     - Unemployment Rate vs Recent Subscriber Growth
     - Population vs Subscribers
     - Education Enrollment vs Average Yearly Earnings
   - **Top 10 Rankings**:
     - YouTubers with the highest recent subscriber growth
     - Countries with the highest number of YouTubers
     - YouTubers with highest revenue efficiency (revenue per subscriber)
     - Countries with highest revenue per subscriber
   - **Category Analysis**:
     - Average yearly earnings by content category

---

## 📈 Visualizations

- Correlation Matrix
- Bar Charts (Top Countries, Categories)
- Scatter Plots (Growth Trends, Revenue Trends)
- Regression Lines for relationships
- Log Scaled Axes for better visualization where needed

---

## 📈 Key Findings

- Strong correlation between subscribers and views.
- "Shows" category earns significantly higher than others.
- Revenue per subscriber varies notably by country.
- Upload frequency has limited impact on success compared to content quality.
- Macroeconomic indicators (like unemployment, education) show weak influence on YouTube growth.

---

## 🎯 Recommendations

- Focus on high-earning content categories like "Shows" and "Comedy."
- Maintain consistent short-term activity to drive earnings.
- Prioritize quality content over quantity of uploads.
- Explore regional markets with higher monetization rates.
- Study outliers for unique growth strategies beyond general trends.
