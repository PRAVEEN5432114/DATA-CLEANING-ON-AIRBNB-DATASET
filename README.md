

# 🧹 NYC Airbnb Data Cleaning Project

This project focuses on cleaning and preparing a real-world Airbnb dataset from New York City. The dataset was intentionally designed with missing values and inconsistencies to simulate real-world data challenges.

---

## 📌 Objective

To demonstrate my ability to:

* Handle missing and inconsistent data
* Perform basic exploratory steps after cleaning
* Prepare a clean, structured dataset ready for analysis or modeling

---

## 📂 Dataset Description

> 📎 **Dataset Source**: [**NYC Airbnb Open Data on Kaggle**](https://www.kaggle.com/datasets/arianazmoudeh/airbnbopendata)
> *(The dataset file is large, so please download it directly from the link above.)*

The dataset includes:

* **Listings**: Property details such as host ID, room type, location, and price
* **Calendar**: Availability and price per day
* **Reviews**: User reviews and feedback data

---

## 🧼 Cleaning Process Highlights

* ✅ Removed rows with critical missing fields (`host_id`, `neighbourhood`, etc.)
* ✅ Filled missing `reviews_per_month` using grouped medians by neighborhood
* ✅ Converted date columns to standard datetime format
* ✅ Handled outliers in `price` and `availability_365` columns
* ✅ Standardized inconsistent text values (e.g., neighborhood names, room types)

---

## 🔧 Tools Used

* **Python**: Data manipulation with Pandas and NumPy
* **Jupyter Notebook**: Documented step-by-step process
* **Matplotlib / Seaborn** (optional): For quick post-cleaning checks

---

## 📓 Notebook Included

| Notebook              | Description                                   |
| --------------------- | --------------------------------------------- |
| `data_cleaning.ipynb` | Main notebook with all cleaning steps applied |

---

## 🏁 Summary

The dataset is now clean, structured, and ready for:

* Further exploratory data analysis
* Dashboard reporting
* Machine learning modeling

This project demonstrates my practical data wrangling skills in a real-world scenario.

---

## 📄 License

This project is for educational and portfolio purposes only.


