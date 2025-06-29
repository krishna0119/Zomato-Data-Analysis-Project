# 🍽️ Zomato Data Analysis Project

This project analyzes Zomato restaurant data to uncover patterns in customer preferences, ratings, restaurant types, online order behavior, and spending habits. The project includes data cleaning, visualization, and insights generation using Python.

---

## 📂 Dataset

- **File:** `Zomato data .csv`
- **Description:** The dataset contains information about restaurants including name, order type, table booking, ratings, votes, average cost for two, and restaurant category.

---

## 🧰 Tools & Libraries

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🔍 Workflow

### ✅ Step 1: Load Dataset
- Imported CSV using `pandas.read_csv()`.
- Displayed first few rows to understand structure.

### ✅ Step 2: Data Cleaning
- Cleaned `rate` column by removing "/5" and converting it to `float`.
- Checked and confirmed appropriate data types.
- Removed rows with null values.

### ✅ Step 3: Exploratory Data Analysis (EDA)

#### 🔹 1. Restaurant Types
- **Tool:** Count plot
- **Insight:** Dining and Buffet are among the most common types.

#### 🔹 2. Votes by Restaurant Type
- **Tool:** Bar chart
- **Insight:** Casual Dining receives the most votes overall.

#### 🔹 3. Ratings Distribution
- **Tool:** Histogram
- **Insight:** Most restaurants are rated between **3.5 to 4.0**.

#### 🔹 4. Restaurant Cost for Couples
- **Tool:** Count plot
- **Insight:** ₹300–₹800 is the most common spending range for two.

#### 🔹 5. Online vs. Offline Ratings
- **Tool:** Box plot
- **Insight:** Online orders generally receive slightly higher ratings.

#### 🔹 6. Online Orders by Restaurant Type
- **Tool:** Pivot table + Heatmap
- **Insight:** Cafes tend to receive more online orders, while Fine Dining is mostly offline.

---

## 📊 Key Insights

1. **Most Common Restaurant Type:** Buffet and Casual Dining
2. **Restaurant Type with Most Votes:** Casual Dining
3. **Rating Range:** Majority of ratings fall between **3.5 to 4.0**
4. **Couples Spending:** Most couples spend ₹300–₹800 per order
5. **Higher Rated Mode:** Online orders have slightly higher ratings
6. **Offline Preference:** Fine Dining receives more offline orders

---

## 📁 Files Included

- `Zomato data analysis project.ipynb` – Jupyter notebook with all code and visuals
- `Zomato data .csv` – Raw data file
- `README.md` – Project summary and documentation

---

## 🚀 How to Run

1. Clone or download the repo.
2. Install dependencies:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```
3. Open the notebook:
    ```bash
    jupyter notebook "Zomato data analysis project.ipynb"
    ```
4. Run the cells sequentially to perform data cleaning, visualization, and analysis.

---

## 📬 Contact

Created by **Krishna Nakrani**  
For collaboration or queries, feel free to reach out via [LinkedIn](https://www.linkedin.com).

