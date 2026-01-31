# Movie Ratings Analysis using Exploratory Data Analysis

## Internship Mini Project  
*Organization:* Hex Softwares Pvt Ltd  
*Project Type:* Data Science Internship Project  
*Difficulty Level:* Intermediate  
*Target Dataset:* TMDB 5000 Movies Dataset  

---

## Project Overview
This project focuses on analyzing movie ratings data from *The Movie Database (TMDB)*.  
The objective is to extract meaningful insights about *rating distributions, genre performance, temporal trends, and budget correlations* using real-world movie data through comprehensive exploratory data analysis.

The project follows an **industry-level data pipeline**, covering:
- Data Collection & Merging
- Data Cleaning & Preprocessing
- Exploratory Data Analysis (EDA)
- Data Visualization
- Dashboard Creation
- Documentation & Reporting

---

## Data Source & Ethical Compliance
- *Dataset:* TMDB 5000 Movie Dataset (Public Domain)
- *Source:* Kaggle - The Movie Database
- *Usage Type:* Educational (Non-commercial)

### Data Privacy & Compliance Measures
- ✔️ Used publicly available dataset from Kaggle
- ✔️ No personal/private data accessed
- ✔️ Data used strictly for educational purposes
- ✔️ All analysis and visualizations created from scratch
- ✔️ Original data sources properly credited

This ensures compliance with data privacy standards and Hex Softwares internship guidelines.

---

## Tools & Technologies
- Python 3.8+
- pandas, numpy
- matplotlib, seaborn
- plotly (for interactive dashboards)
- Google Colab (Primary Development Environment)
- Jupyter Notebook

---

## 🔄 Project Workflow

### 1. Data Collection & Preparation
- Downloaded TMDB 5000 Movies and Credits datasets
- Merged two datasets using movie IDs
- Verified data integrity and completeness
- Created structured dataset for analysis

### 2. Data Cleaning & Preprocessing
- Handled missing values (ratings, budgets, release years)
- Standardized data formats and types
- Created derived features (decade, rating categories, ROI)
- Removed inconsistencies and outliers
- Generated analysis-ready dataset

### 3. Exploratory Data Analysis (EDA)
- Statistical analysis of ratings (mean, median, mode, distribution)
- Genre-wise performance analysis
- Temporal trend analysis (ratings over decades)
- Budget vs Rating correlation study
- Vote count distribution analysis

### 4. Data Visualization
- Rating distribution histograms and density plots
- Time series visualizations (ratings over years)
- Genre performance bar charts
- Budget-Rating correlation scatter plots
- Interactive dashboards with multiple visualizations

### 5. Dashboard Creation
- Built interactive HTML dashboard using Plotly
- Created 9-panel comprehensive dashboard
- Developed simplified 4-panel dashboard for quick insights
- Implemented hover interactions and tooltips

### 6. Documentation & Reporting
- Well-structured project documentation
- Clear and commented code
- Professional reporting of findings and insights
- Complete methodology documentation

---

## 📊 Key Insights
- Average movie rating: **6.09/10** with median at 6.20
- **Documentary and History** genres have highest average ratings (6.8+)
- Movie ratings have remained relatively stable over decades
- Weak positive correlation (**+0.12**) between budget and ratings
- **Drama and Comedy** are the most common movie genres
- Movies with ≥1000 votes show more reliable rating patterns

---

## ⚠️ Limitations
- Dataset limited to ~4,800 movies from TMDB
- Historical data (mostly up to 2017)
- Budget and revenue data incomplete for many movies
- Genre information in JSON format requires parsing
- No real-time or streaming platform data included

---

## 👤 Individual Contribution
- **Complete Project:** Md Haris Asad (Solo Project)
- **Data Processing:** Data cleaning, merging, feature engineering
- **Analysis & Visualization:** Statistical analysis, plot creation
- **Dashboard Development:** Interactive HTML dashboard building
- **Documentation:** Complete project documentation and reporting

---

## 📝 Compliance Statement
This project strictly follows ethical data analysis practices and Hex Softwares internship guidelines.  
All data used is publicly available with proper attribution. No proprietary or restricted data was accessed.

---

## 📉 Data Limitations & Biases
The dataset is sourced exclusively from **TMDB**, and therefore:
- Represents only movies available in TMDB database
- May have selection bias towards English-language movies
- User rating patterns may differ from general audience
- Historical data may not reflect current trends
- Budget/revenue data may be estimates rather than actual figures

These limitations are clearly acknowledged in the analysis and reporting.

---

**Hex Softwares Pvt Ltd**  

*Data Science Internship – Task 2* 

## 📁 Project Structure

```text
HexSoftwares_Movie_Ratings_Analysis/
│
├── notebooks/
│   └── HexSoftwares_Movie_Ratings_Analysis.ipynb  # Complete Jupyter notebook
│
├── dashboards/
│   ├── movie_ratings_dashboard.html   # Main interactive dashboard
|   ├── movie_dashboard_simple.html    # Simplified dashboard
