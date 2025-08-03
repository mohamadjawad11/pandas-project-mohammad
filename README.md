# 🛍️ Retail Sales Analysis with Pandas

This project explores and analyzes real-life retail bike store sales using the Pandas library in Python. 

## 📊 Dataset

The dataset includes over 113,000 transactions with fields like:
- Date of purchase
- Customer demographics
- Product categories
- Order quantity, cost, price, revenue, and profit

## 🔍 Key Analysis

- Distribution and stats of unit costs
- Revenue and profit by age group
- Histograms, KDE plots, and boxplots for numerical features
- Correlation matrix
- Custom feature engineering:
  - Revenue per Age
  - Calculated Cost & Revenue
  - Unit price after tax
- Country-level filtering (e.g., France, United States, Kentucky)

## 🧰 Tech Used

- Python
- Pandas
- Matplotlib
- Jupyter Notebooks

## 🧠 Skills Demonstrated

- Data cleaning and transformation
- Feature engineering
- Exploratory Data Analysis (EDA)
- Visualization with Matplotlib
- Advanced Pandas filtering and logic

## 📁 How to Run

1. Clone this repo:git clone https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
2. Install requirements: pip install pandas matplotlib jupyter
3. you can run

============================================================================================================================================

Project2 readme:

# 🎬 Sakila Video Rental Analysis

A full exploratory data analysis of the Sakila movie rental database using SQL, Pandas, and Matplotlib.


## 🔍 Project Highlights

- Connected to `sakila.db` using `sqlite3`
- Queried relational tables (rentals, customers, inventory, films, stores)
- Analyzed:
  - Film rental rates vs replacement costs
  - City-wise rental volume
  - Customer behavior and frequency
  - Film ratings and revenue implications
- Created custom metrics:
  - `rental_gain_return = (rental_rate / replacement_cost) * 100`
  - Number of rentals to break even

## 🧪 Tools Used

- Python (Pandas, Matplotlib, SQLite)
- SQL (via `pd.read_sql`)
- Jupyter Notebook

## 📈 Sample Graphs

![Density Plot](https://user-images.githubusercontent.com/7065401/52071924-c003ad80-2562-11e9-8297-1c6595f8a7ff.png)

## 📁 How to Run

1. Clone the repo
2. Make sure `sakila.db` is in a `/data` folder
3. Run `sakila(project2).ipynb` in Jupyter

```bash
pip install pandas matplotlib jupyter
jupyter notebook


   
