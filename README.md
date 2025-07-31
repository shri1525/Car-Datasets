# 🚗 Cars Data Analysis Project

This repository contains a comprehensive data analysis project based on a dataset of 10,000 cars. The primary objective is to explore, clean, and analyze the dataset to extract meaningful insights about car features, pricing, popularity, and more. Visualizations and statistical techniques are used throughout to support the findings.

## 📁 Files Included

* `cars_data_10K.csv` – The original dataset containing information on various car models.
* `Assignment_01.pdf` – A compiled report (R Markdown output) of the analysis.
* R Script / Notebook (to be added optionally if you wish to upload your `.Rmd` or `.R` file).

## 🔍 Project Overview

### ✅ Objectives:

* Clean and preprocess the dataset
* Handle missing values and outliers
* Perform exploratory data analysis (EDA)
* Analyze car prices and their distribution
* Understand relationships between key variables
* Segment vehicles based on price and style
* Identify the most influential factors for MSRP

---

## 🧹 Data Cleaning

* **Missing Values:** Removed using `na.omit()`
* **Outliers in MSRP:** Identified using z-scores and removed (threshold: ±3)
* **Data Types:** Converted relevant columns (e.g., `Vehicle.Size` as factor, `MSRP` as numeric)

---

## 📊 Exploratory Data Analysis (EDA)

### 📌 Summary Statistics
* Number of observations after cleaning: **9,715**
* Variables analyzed: Year, Engine Power, Cylinders, Doors, MPG (city & highway), Popularity, MSRP, etc.

### 📈 Visualizations
* **Pie Chart** of Vehicle Sizes
* **Bar Chart** of Vehicle Styles
* **Histogram** of Engine Horsepower
* **Scatter Plot**: Highway MPG vs. City MPG
* **Histogram** of MSRP (Price)
* **Boxplot** of MSRP by Vehicle Style

---

## 💡 Key Insights

### 🔹 Price Grouping

Cars were grouped into three categories:

* **Low Price:** MSRP < \$10,000
* **Medium Price:** \$10,000 ≤ MSRP ≤ \$20,000
* **High Price:** MSRP > \$20,000

### 🔹 Brand Influence

* **Luxury Brands** (e.g., BMW, Audi) → Higher price due to premium features.
* **Mass-Market Brands** (e.g., Toyota, Honda) → Popular for reliability and value.
* **Innovative Brands** (e.g., Tesla) → High prices due to technology-driven appeal.

---

## 🛠️ Tools & Technologies Used

* **Language:** R
* **Libraries:** `outliers`, `tinytex`, `knitr`
* **Visualization:** Base R plotting (pie, bar, histogram, scatter, boxplot)
* **Environment:** RStudio / R Markdown

---

## 📌 How to Reproduce

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/cars-data-analysis.git
   cd cars-data-analysis
   ```

2. Open the `.Rmd` file in RStudio (if included), or refer to the `Assignment_01.pdf`.

3. Install required packages (if not installed already):

   ```r
   install.packages("outliers")
   install.packages("tinytex")
   ```

4. Run the script chunk by chunk or knit the R Markdown file.

---

## 📄 License

This project is for academic and learning purposes. If reused or modified, please attribute appropriately.

---

## 🙋‍♂️ Author

**Shrikunj**
📅 March 23, 2025
🎓 Master's in BDA – Assignment 1



