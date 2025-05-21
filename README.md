# 🏠 Airbnb Python Project - New York 2024

This project presents a complete exploratory data analysis (EDA) on Airbnb listings in New York for the year 2024. Using Python and its powerful libraries, the analysis dives into pricing trends, room types, neighborhood popularity, and geographical distribution.

---

## 📂 Dataset Overview

- **Source**: `new_york_listings_2024.csv`
- **Total Records**: 20,770
- **Columns**: 22
- **Includes**:
  - Listing details (name, host, location)
  - Room types and prices
  - Number of reviews
  - Availability and rating
  - Bedrooms, beds, and bathrooms

---

## 📊 Project Workflow

1. **Importing Dependencies**
   - `Pandas`, `NumPy`, `Matplotlib`, `Seaborn`

2. **Loading & Exploring Data**
   - Initial inspection using `.head()`, `.info()`, `.describe()`

3. **Data Cleaning**
   - Removed nulls & duplicates
   - Data type conversion for IDs and other relevant fields

4. **Univariate Analysis**
   - Price distribution
   - Availability across listings
   - Outlier removal for cleaner insights

5. **Feature Engineering**
   - Created a new feature: `price per bed` for better comparative analysis

6. **Bivariate Analysis**
   - Price vs. Room type across boroughs
   - Price vs. Number of reviews
   - Neighborhood vs. average price

7. **Geographical & Correlation Analysis**
   - Heatmap for correlation matrix
   - Latitude/Longitude scatterplot of listing locations

---

## 📈 Key Visualizations

- Box plot and histogram for price distribution
- Bar plots for average prices across neighborhoods
- Scatterplots for price vs. reviews and availability
- Pairplot of numeric variables
- Heatmap of correlation matrix
- Geographic mapping of listings by room type

---

## 🧠 Insights Extracted

- 🏙️ **Manhattan** has the highest average price per bed.
- 🛏️ Private rooms are more affordable across all boroughs.
- 📍 Most listings are concentrated in Manhattan and Brooklyn.
- 🔍 Outliers affect pricing distributions and were filtered.
- 💬 No direct strong correlation between price and number of reviews.

---

## 🛠 Technologies Used

- **Python 3**
- **Pandas** for data cleaning and transformation
- **Seaborn** and **Matplotlib** for visualizations
- **Jupyter Notebook** for analysis and code execution

---

## 🚀 How to Run This Project

1. Clone this repository:
   ```bash
   git clone https://github.com/Analyst-Rajat333/AirBnb-Python-Project.git
