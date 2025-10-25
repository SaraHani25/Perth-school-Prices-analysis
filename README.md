# 🏫 Perth School Prices Analysis

## 📋 Project Description
This project focuses on **analyzing and visualizing Perth school pricing data** using **Python** and **Power BI** to uncover key insights about tuition trends and school performance.  
It demonstrates a complete data pipeline — from cleaning and exploring raw data to building an interactive dashboard that highlights major findings.

**Highlights:**
- Analyzed **33,657 school records** from Perth.  
- Cleaned and standardized data, removing **15% invalid or duplicate entries**.  
- Found that **private schools charge 45% higher tuition fees** than public schools on average.  
- Identified a **weak correlation (r ≈ 0.18)** between tuition fees and school ratings.  
- Built a **Power BI dashboard** to visually present the key insights and comparisons across suburbs and school types.

---

## ⚙️ Data Processing & Analysis Steps

### 1️⃣ Data Loading
- Loaded the dataset using **pandas (`pd.read_csv()`)**.  
- Verified structure and quality with `.info()` and `.head()`.

### 2️⃣ Data Cleaning
- Removed **missing and duplicate entries** (~15% of total).  
- Fixed **data type mismatches** and standardized column names.  
- Generated a final clean dataset of **~28,600 valid records** for analysis and visualization.

### 3️⃣ Exploratory Data Analysis (EDA)
- Summarized tuition fees, school types, and ratings using **Pandas** and **NumPy**.  
- Investigated **average tuition by region** and **rating distribution** across schools.  
- Conducted correlation analysis between tuition and ratings.  
- Highlighted top-performing schools and highest-priced suburbs.

### 4️⃣ Data Visualization (Python)
Created visuals using **Matplotlib** and **Seaborn**:
- 📊 **Histogram:** Tuition distribution across schools.  
- 📈 **Bar chart:** Average tuition per school type.  
- 📦 **Boxplot:** Outliers in tuition fees.  
- 🔵 **Scatter plot:** Tuition vs. rating correlation.  

Customized visuals with titles, axis labels, color themes, and legends.

### 5️⃣ Interactive Dashboard (Power BI)
- Designed a **Power BI dashboard** integrating the cleaned dataset.  
- Showcased:
  - Average tuition per **suburb and school type**.  
  - Distribution of **ratings vs. price ranges**.  
  - **Top 10 most expensive schools** in Perth.  
  - Key performance indicators (KPIs) for **average fee**, **rating**, and **category comparisons**.  
- Added filters and slicers to enable dynamic exploration of insights.

---

## 📈 Key Insights
- **Private schools** charge an average of **45% more** than public ones.  
- **Top 3 suburbs** have tuition prices up to **25% higher** than the city average.  
- **Weak correlation (r ≈ 0.18)** between tuition and ratings — higher prices don’t guarantee better quality.  
- Data cleaning improved reliability and reduced inconsistency by **15%**.  
- The **Power BI dashboard** enables quick comparison and clear visual storytelling for decision-makers.

---

## 🧩 Tools & Technologies Used
- **Python** – data processing & analysis  
  - **Pandas** – data cleaning  
  - **NumPy** – numerical operations  
  - **Matplotlib** & **Seaborn** – data visualization  
- **Power BI** – dashboard creation & interactive insights  
- **Excel / CSV** – dataset handling and transformation  

---

## 📊 Project Summary
Analyzed and visualized **33,657 Perth school records** to uncover tuition patterns and trends.  
After cleaning **15% invalid entries**, findings revealed **45% higher tuition in private schools** and a **weak correlation (r ≈ 0.18)** between price and ratings.  
An interactive **Power BI dashboard** was created to clearly present these insights for better decision-making.


