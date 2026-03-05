This README provides a detailed overview of the **IMDb Movies Data Analysis** project, based on the provided Jupyter Notebook.

---

# IMDb Movies Data Analysis

## 📌 Project Overview

This project performs an in-depth exploratory data analysis (EDA) of a curated dataset containing 100 top-performing movies. By applying data cleaning, feature engineering, and visualization techniques, the analysis aims to uncover what makes a movie successful in terms of profitability, popularity, and critical acclaim.

## 🗂️ Project Structure

* **IMDB_movies.ipynb**: The primary Jupyter Notebook containing the Python code, statistical analysis, and visualizations.
* **Data Source**: The analysis is built on a movie dataset (originally named `Movie+Assignment+Data.csv`) featuring 62 attributes for each entry.

## 🛠️ Technologies Used

* **Python**: Core programming language.
* **Pandas & NumPy**: For data manipulation and complex calculations.
* **Matplotlib & Seaborn**: For creating insightful static visualizations.

## 📊 Key Features & Analysis

### 1. Data Cleaning & Preparation

* **Currency Standardization**: Converted `budget` and `Gross` revenue columns into "millions of dollars" to improve readability and analysis accuracy.
* **Handling Nulls**: Identified and managed missing values in metadata such as actor likes and genre tags.

### 2. Financial Performance

* **Profit Analysis**: Engineered a `profit` feature to identify the top 10 most profitable movies.
* **Budget vs. Profit Correlation**: Visualized the relationship between a movie's financial backing and its eventual return on investment.

### 3. Critical & Audience Reception

* **Hybrid Rating System**: Created an `Avg_rating` metric by normalizing and averaging MetaCritic and IMDb scores.
* **Demographic Insights**: Analyzed voting patterns specifically for R-rated movies among younger audiences (Under 18).

### 4. Popularity & Cast Analysis

* **Star Power Index**: Calculated a `Popularity` score for each movie by aggregating the Facebook following of the top three lead actors.
* **Trio Ranking**: Identified the top 5 most "popular" cast trios based on social media presence.

### 5. Genre & Runtime Distribution

* **Genre Trends**: Analyzed the top 10 most frequent genres and their average audience vote counts.
* **Runtime Profiling**: Generated distribution plots to understand the standard length of high-performing films.

## 📈 Summary of Findings

* **Profitability**: Identified the specific films that achieved the highest net profit.
* **Rating Leaders**: Ranked movies based on a balanced metric of professional critic reviews and fan ratings.
* **Cast Impact**: Verified if a high social media following for lead actors correlates with movie popularity.

## 📖 How to Use

1. **Clone** this repository to your local machine.
2. Install the required dependencies: `pip install pandas numpy seaborn matplotlib`.
3. Ensure the dataset file is in the correct directory as specified in the notebook.
4. Open `IMDB_movies.ipynb` in **Jupyter Notebook**, **VS Code**, or **Google Colab** to view the full analysis.

---

*This analysis was developed as part of a Data Science portfolio to demonstrate proficiency in Python-based EDA.*
