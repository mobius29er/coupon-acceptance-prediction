# Coupon Acceptance Prediction

## 🧠 Project Overview

This project explores the question: **"Will a customer accept the coupon?"**

Using data collected via survey on Amazon Mechanical Turk and sourced from the UCI Machine Learning Repository, I performed **exploratory data analysis (EDA)** and created **visualizations** to understand which factors influence whether a customer accepts a coupon offer while driving.

This project is part of my machine learning coursework and is a practical demonstration of my skills in data analysis, visualization, and statistical reasoning.

---

## 📊 Dataset Summary

The dataset includes responses to driving-related coupon offers with features such as:

- Destination
- Weather
- Time of day
- Presence of passengers
- Type of coupon offered (e.g., restaurant, coffee shop, bar)
- User response:
  - `Y = 1` (Accepted: "Right away" or "Later")
  - `Y = 0` (Rejected: "No")

---

## 📌 Key Findings

- **Time of Day** and **Destination** significantly influence acceptance.
- **Less expensive restaurants** and **coffee house coupons** were more likely to be accepted.
- Coupons offered when **passengers are present** tend to be accepted more often.
- Weather and driving direction showed minimal impact on decision-making.

---

## 📈 Visualizations

- Bar plots for categorical comparisons (e.g., coupon type vs. acceptance rate)
- KDE plots and histograms for continuous features
- Subplots to compare variable effects across different coupon types

All visualizations include:
- Clear axis labels and descriptive titles
- Scaled and styled for readability

---

## 🛠 Tools Used

- Python
- Pandas
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## ✅ Recommendations

- Target **less expensive coupons** during **lunchtime** when drivers are heading to common destinations.
- Focus offers when **passengers are present**, increasing social motivation to accept.
- Avoid sending coupons during poor weather, though minimal statistical significance was observed.

---

## 📎 Files

- `coupon_acceptance_analysis.ipynb`: Full notebook with code, analysis, and plots
- `coupon_data.csv`: Cleaned dataset
- `README.md`: This summary report

---

## 🔗 View the Notebook

👉 [View the full notebook on GitHub](./coupon_acceptance_analysis.ipynb)

---

## 📬 Contact

For questions or collaborations, feel free to reach out via [LinkedIn](https://www.linkedin.com/in/jeremyfoxx/) or check out more projects at [jeremyfoxx.com](https://www.jeremyfoxx.com/).
