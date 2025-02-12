# Electric Vehicles Market Size Analysis using Python

**Author:** Aman Kharwal  
**Date:** March 18, 2024  
**Category:** Machine Learning

## Overview
This project analyzes the market size of electric vehicles (EVs) in the United States. It explores how the EV market has grown over time and forecasts future trends. By studying various aspects like adoption over time, geographical distribution, EV types, manufacturer/model popularity, and electric range, the project provides insights into the potential growth of the EV industry.

## What I Did
1. **Data Collection & Cleaning**  
   - Loaded a dataset containing EV registration data (from 1997 to 2024) using Python's `pandas`.
   - Cleaned the data by removing rows with missing values to ensure accuracy.

2. **EV Adoption Analysis**  
   - Analyzed how many EVs were registered each year to understand the growth in adoption.
   - Visualized this trend with a bar chart to highlight a significant rise in registrations starting around 2016, with a peak in 2023.

3. **Geographical Distribution**  
   - Determined the top three counties with the highest number of EV registrations.
   - Visualized the distribution of EVs in major cities within these counties to see which areas lead in EV adoption.

4. **EV Types & Manufacturer/Model Analysis**  
   - Explored the breakdown of different EV types (such as Battery Electric Vehicles).
   - Analyzed which manufacturers and models are most popular, showing that brands like TESLA dominate the market.

5. **Electric Range Analysis**  
   - Examined the distribution of electric ranges across the vehicles.
   - Observed that while some EVs offer high ranges, most vehicles have a range below the average.

6. **Market Size Forecasting**  
   - Counted the number of EV registrations per year.
   - Used an exponential growth model (via SciPy's `curve_fit`) to forecast future EV registrations.
   - Predicted the total number of EVs for 2024 (with partial data) and estimated growth for the next five years.
   - Visualized actual versus forecasted data to show the expected market expansion.

## Technologies Used
- **Python** for analysis and forecasting.
- **Pandas & Numpy** for data manipulation.
- **Matplotlib & Seaborn** for data visualization.
- **SciPy** for curve fitting and forecasting.

## How to Run the Project
1. **Clone the Repository**  
   ```bash
   git clone <repository_url>
   ```
2. **Install the Required Libraries**  
   Make sure you have Python installed, then run:
   ```bash
   pip install pandas numpy matplotlib seaborn scipy
   ```
3. **Run the Analysis Script**  
   Navigate to the project folder and run:
   ```bash
   python ev_market_analysis.py
   ```

## Conclusion
The project shows that EV adoption in the United States has increased dramatically in recent years, with a sharp forecasted growth in the near future. This analysis indicates a promising outlook for the EV industry, suggesting opportunities for increased investments and business expansion.
