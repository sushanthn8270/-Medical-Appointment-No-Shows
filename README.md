# 🧹 Data Cleaning and Preprocessing Project

### 📘 Overview
This project focuses on **data cleaning and preprocessing** of a raw dataset using Python (Pandas).  
The goal is to prepare the data for further analysis by handling missing values, fixing inconsistent formats, and ensuring the dataset is clean, structured, and analysis-ready.

---

### 🗂️ Dataset Used
**Dataset Name:** Netflix Movies and TV Shows  
**Source:** [Kaggle – Netflix Movies and TV Shows](https://www.kaggle.com/datasets/shivamb/netflix-shows)

**Description:**  
This dataset contains information about movies and TV shows available on Netflix, including titles, directors, release years, countries, and the date they were added to Netflix (`date_added` column).

---

### 🧠 Objectives
- Identify and handle missing or null values.  
- Remove duplicate records.  
- Standardize inconsistent text formats (e.g., country names, ratings, etc.).  
- Convert date columns into a consistent datetime format.  
- Rename columns for uniformity and readability.  
- Check and correct incorrect data types.

---

### 🧰 Tools & Libraries
- **Python 3.x**
- **Pandas**
- **NumPy**
- **Matplotlib / Seaborn** (optional for data visualization)
- **Jupyter Notebook / Google Colab**

---

### ⚙️ Data Cleaning Steps
1. Renamed all column headers to lowercase and replaced spaces with underscores.  
2. Removed duplicate rows using `drop_duplicates()`.  
3. Checked for missing values using `.isnull()` and handled them appropriately.  
4. Standardized text entries (e.g., normalized country and rating names).  
5. Converted the `date_added` column into proper datetime format (`YYYY-MM-DD`).  
6. Verified column data types and converted where needed.  
7. Exported the cleaned dataset as **`netflix_cleaned.csv`**.

---

### 📊 Output
- Cleaned and consistent dataset ready for analysis or visualization.
- File: `netflix_cleaned.csv`
- Notebook/Script: `data_cleaning.ipynb` or `data_cleaning.py`

---

### 📈 Example Insights (Optional)
After cleaning, you can perform analyses such as:
- Number of shows added per year or month.
- Top genres or countries with most Netflix content.
- Trend of movie vs. TV show additions over time.

---

### 👨‍💻 Author
**Sushanth N**  
*Master’s Student – Data Analytics / Machine Learning*  
📧 *[Your Email or LinkedIn link here]*  

---

### 🏷️ License
This project is released under the [MIT License](LICENSE).  
Dataset © Kaggle / Original Authors.
