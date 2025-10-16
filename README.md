# Bus Trip Analytics

**Description:**  
Analyzing bus, location, and trip data to generate insights on bus registrations, trip patterns, and interstate trips.

---

## Project Structure

bus-trip-analytics/
│
├── data/
│ └── Bus-Trip-Data.xlsx # Excel file containing bus, location, and trip data
├── notebooks/
│ └── bus_trip_queries.ipynb # Jupyter notebook with all queries and analysis
├── README.md
└── .gitignore # Optional



---

## Notebook Overview

The notebook `bus_trip_queries.ipynb` contains:

1. **Import Libraries**  
   - pandas, numpy, datetime  

2. **Load Data**  
   - Load bus, location, and trip sheets from Excel file  

3. **Analysis Tasks**  
   - Q1: List states and city counts (only states with >4 cities)  
   - Q2: Display bus code and registration for AC or Sleeper buses registered last April  
   - Q3: Number of buses registered in each year (last 5 years)  
   - Q4: Find all trips in the current week starting from Bangalore  
   - Q5: Find trips where the destination is Mumbai  
   - Q6: Trips from Mysore to Chennai  
   - Q6 (Merged Table): Trip details including bus registration, starting & ending city/state  
   - Q7: Buses serving interstate trips in the current month  

4. **Conclusion**  
   - Summarizes insights about bus registrations, trip patterns, and interstate trips  

---

## How to Use

#### 1. Clone the repository:
```bash
git clone git@github.com:<your-username>/bus-trip-analytics.git
```
#### 2. Navigate to the repo:

`inline cd bus-trip-analytics `


#### 3. Open the notebook in Jupyter:

'inline jupyter notebook notebooks/bus_trip_queries.ipynb`


#### 4. Run all cells to view the results.

### Notes

- All results are displayed directly in the notebook; no CSV files are generated.

- Ensure Bus-Trip-Data.xlsx remains in the data/ folder for correct file paths.
