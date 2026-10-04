# 🏨 Hotel Booking Data Cleaning & Analysis

A data cleaning and exploratory data analysis (EDA) project built with Python and Pandas, focused on understanding what drives booking cancellations in a hotel booking dataset.

---

## 📌 Overview

This project walks through a practical, end-to-end data analysis workflow:

- Data cleaning and validation
- Missing value and duplicate checks
- Invalid value detection
- Outlier analysis
- Exploratory Data Analysis (EDA)
- Data visualization
- Business insights

---

## 📂 Dataset

The dataset contains hotel booking records with fields such as:

- Hotel type
- Cancellation status
- Lead time
- Arrival dates
- Customer type
- Market segment
- Deposit type
- ADR (Average Daily Rate)
- Special requests
- Reservation status

**After cleaning, the dataset contains 87,229 rows and 30 columns.**

---

## 🛠️ Tools & Technologies

- Python
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## 🧹 Data Cleaning

The cleaning process included:

- Checking for missing values
- Checking for duplicate records
- Reviewing data types
- Detecting invalid values
- Identifying potential outliers using the IQR method
- Reviewing suspicious values in the context of the data
- Removing invalid bookings with zero adults, children, and babies
- Removing negative ADR values

> Outliers were reviewed individually rather than being automatically removed.

---

## 📊 Exploratory Data Analysis

The analysis focused on booking cancellations and explored their relationship with:

- Hotel type
- Lead time
- ADR
- Market segment
- Deposit type
- Customer type
- Special requests
- Arrival month

A correlation analysis was also performed on the numerical variables.

---

## 💡 Key Insights

- **27.52%** of bookings were canceled.
- **City Hotel** had a higher cancellation rate than Resort Hotel.
- **Longer lead times** were associated with higher cancellation rates.
- **Online TA** had the highest cancellation rate among the major market segments.
- **Non Refund** bookings had a significantly higher cancellation rate.
- Cancellation rates generally **decreased as the number of special requests increased**.
- **August** had the most bookings (**11,242**) and also the highest cancellation rate (**32.22%**).
- **November** had the lowest cancellation rate (**21.15%**).

> ⚠️ These findings describe patterns and associations in the dataset and do not imply causation.

---

## 📈 Visualizations

The project includes the following charts:

- Overall cancellation distribution
- Cancellation rate by hotel type
- Cancellation rate by lead time
- Cancellation rate by ADR
- Cancellation rate by market segment
- Cancellation rate by deposit type
- Cancellation rate by customer type
- Cancellation rate by number of special requests
- Number of bookings by arrival month
- Cancellation rate by arrival month
- Numerical correlation heatmap

---

## 📁 Project Structure

```text
Hotel-Booking-Data-Cleaning-Analysis/
│
├──── hotel_bookings.csv
│
├──── hotel_booking_analysis.ipynb
│
└── README.md
```

---

## 🚀 How to Run

1. Clone the repository:
```bash
   git clone https://github.com/your-username/Hotel-Booking-Data-Cleaning-Analysis.git
```
2. Install the required libraries:
```bash
   pip install pandas numpy matplotlib seaborn jupyter
```
3. Open the notebook:
```bash
   jupyter notebook notebooks/hotel_booking_analysis.ipynb
```

---

## ✅ Conclusion

This project demonstrates a complete data cleaning and exploratory analysis workflow, transforming raw hotel booking data into a clean dataset and extracting meaningful insights through statistical analysis and visualization.
