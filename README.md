Project Overview

This project was completed as part of the **British Airways Data Science Virtual Experience (Forage)**.
The goal was to use real-world data analysis and machine learning techniques to solve business problems in the aviation sector.

The project consisted of **two main tasks**:

1. **Lounge Demand Forecasting (Excel/BI)**

   * Forecasted lounge usage at Heathrow Terminal 3 based on passenger eligibility.
   * Designed lookup tables to group flights by haul type and time of day.
   * Used PivotTables and advanced Excel formulas to calculate lounge eligibility percentages for Tier 1, Tier 2, and Tier 3 passengers.
   * Delivered insights that can help British Airways plan lounge capacity more efficiently.

2. **Booking Prediction (Machine Learning in Python)**

   * Built a **Random Forest Classifier** to predict whether a customer would complete a holiday booking.
   * Dataset: **10,000+ booking records** with features including purchase lead time, number of passengers, add-ons, and flight details.
   * Performed **data cleaning, feature engineering, and one-hot encoding** to prepare data for modeling.
   * Model achieved **85% test accuracy** (mean CV accuracy 71.5%).
   * Top predictive features:

     * `purchase_lead` (days booked in advance)
     * `flight_hour`
     * `length_of_stay`
     * `flight_day`
     * `num_passengers`
   * Presented results in a summary slide, highlighting business insights and recommendations.

Tools & Technologies

* **Python**: Pandas, Scikit-learn, Matplotlib, Seaborn
* **Excel**: PivotTables, Advanced Formulas
* **Visualization**: Feature importance plots, summary slide deck
* **Version Control**: GitHub


Key Results

* Test Accuracy: **85%**
* Cross-validation Mean Accuracy: **71.5%**
* Precision (Bookers): **0.56**
* Recall (Bookers): **0.13**
* Insights: Customers who book earlier, travel with more passengers, and stay longer are more likely to complete bookings. to also generate a **short GIF of your feature importance plot** so you can include a visual in your GitHub README?
