# Dynamic Pricing Strategy using Python

This project shows how to build a **dynamic pricing strategy** for a ride-sharing company using Python and Machine Learning.

We use data like:
- Number of Riders (demand)
- Number of Drivers (supply)
- Vehicle Type
- Expected Ride Duration

The goal is to adjust ride prices based on real-time demand and supply to improve profits.

---

## Tools Used
- Python
- Pandas, NumPy
- Plotly (for graphs)
- scikit-learn (for machine learning)
- Jupyter Notebook

---

## Steps Done
1. **Data Cleaning**  
   Missing values and outliers were handled.

2. **Dynamic Pricing Logic**  
   Ride cost was updated using demand and supply multipliers.

3. **Profit Analysis**  
   Calculated how many rides became profitable.

4. **Model Training**  
   Used Random Forest Regressor to predict ride prices.

5. **Accuracy**  
   Achieved R² score: **86.7%**

---

## Files Included
- `dynamic_pricing_analysis.ipynb` – Jupyter Notebook
- `dynamic_pricing.csv` – Dataset
- `README.md`
