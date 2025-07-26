# redbus-travel-demand-forecast-2025
Data-driven demand forecasting solution for redBus Data Decode Hackathon 2025 — predicting 15-day advance travel demand using real booking and search data.
This project was developed as part of the **redBus Data Decode Hackathon 2025**, aimed at solving one of the most challenging problems in the travel-tech industry — accurately forecasting the number of travelers for specific bus routes **15 days in advance**.

##  Problem Statement

In the bus transportation sector, only ~20% of bookings occur well in advance, leaving limited early signals for demand forecasting. This creates a complex challenge where traditional models struggle to predict future ridership effectively.

**Goal**: Build a robust, scalable, and data-centric solution to forecast daily travel demand using search logs, booking patterns, and route-level metadata.

---

##  Key Features & Methodology

-  **15-Day Advance Forecasting**  
  Custom time-series pipeline to predict route-level demand for each journey date.

-  **Feature Engineering**  
  - Temporal features: day-of-week, holidays, event proximity  
  - Route-based aggregation  
  - Lag and rolling-window features  
  - Search-to-booking conversion trends

-  **Models Used**
  - XGBoost & LightGBM  
  - Time-series ensemble with trend/seasonality handling  
  - Prophet (for benchmarking)  
  - Stacked models with meta-learners (optional)

-  **Evaluation Metrics**
  - SMAPE / RMSE on unseen dates
  - Route-specific error analysis for under- and over-predicted segments

---

##  Results & Outcomes

- Achieved significant improvement over baseline (benchmark model).
- Built explainable forecasting pipeline adaptable across routes and date windows.

---
##  Collaborators

- Akhilesh Dwivedi – Data Science & Modeling  

---

##  Contact

For queries or collaborations:  
📧 akhildwivedi933@gmail.com 
🔗 [LinkedIn](https://www.linkedin.com/in/akhileshdwivediworks/)  

