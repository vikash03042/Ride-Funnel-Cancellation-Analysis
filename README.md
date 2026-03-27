📊 Ride-Hailing Funnel Optimization & Cancellation Analysis
(Namma Yatri Datathon Case Study)


🚀 Project Overview

This project is an end-to-end data analytics case study based on a ride-hailing platform inspired by Namma Yatri.

The goal is to analyze the user journey across key funnel stages —
Search → Quote → Booking → Ride Completion — and identify critical drop-offs and cancellation patterns affecting overall platform efficiency.

🎯 Objectives
Analyze conversion funnel performance
Identify major drop-off stages
Study booking cancellations (driver vs rider)
Perform root cause analysis using clustering & trends
Provide data-driven business recommendations


📂 Dataset Description

The dataset consists of multiple CSV files representing different stages of the ride lifecycle:

search_data.csv → User search requests
quote_data.csv → Driver quotes for rides
booking_data.csv → Booking details & ride status
booking_cancellation_data.csv → Cancellation reasons


🧠 Key Analysis Performed
🔹 1. Conversion Funnel Analysis
Computed conversion rates:
Search → Quote
Quote → Booking
Booking → Completion
Identified maximum drop-off stage
Segmented analysis by:
Time of day (Morning, Day, Evening, Night)
Trip type (Short, Medium, Long)

🔹 2. Cancellation Analysis
Calculated overall cancellation rate
Compared:
Driver vs Rider cancellations
Identified:
Top cancellation reasons
Analyzed relationships:
Driver rating vs cancellations
Pickup distance vs cancellations

🔹 3. Root Cause Analysis
Identified critical funnel stage
Applied clustering techniques to segment drivers:
High-quote, low-booking drivers
Low-rated, high-cancellation drivers
Performed time-series analysis to detect trends & seasonality

🔹 4. Data Visualization & Storytelling
Built interactive funnel charts using Plotly
Created:
Bar charts
Time-series graphs
Highlighted key insights using visual storytelling

📊 Key Insights
Significant drop observed in Quote → Booking stage
Higher pickup distance leads to more cancellations
Low-rated drivers tend to cancel more frequently
Certain time segments (e.g., Evening/Night) show lower conversion rates


💡 Business Recommendations
Optimize driver allocation to reduce pickup distance
Incentivize high-rated drivers
Introduce penalties for frequent cancellations
Improve pricing strategies for long-distance trips
Enhance matching algorithms for better ride acceptance


🛠️ Tech Stack
Python
Pandas, NumPy
Matplotlib, Seaborn
Plotly (for interactive visualizations)
Jupyter Notebook



📈 Project Structure
Namma_Yatri_Analysis/
│
├── data/
├── notebooks/
│   └── analysis.ipynb
├── output/
│   ├── charts/
├── README.md


📌 How to Run
Clone the repository
git clone https://github.com/your-username/project-name.git
Install dependencies
pip install pandas numpy matplotlib seaborn plotly
Open Jupyter Notebook
jupyter notebook
Run analysis.ipynb


🎯 Skills Demonstrated
Exploratory Data Analysis (EDA)
Funnel & Conversion Analysis
Data Cleaning & Feature Engineering
Clustering (Machine Learning Basics)
Data Visualization & Storytelling
Business Insight Generation


🏁 Conclusion

This project demonstrates how data can be used to analyze user behavior, identify bottlenecks, and improve product performance in a ride-hailing ecosystem.

It showcases strong capabilities in data analysis, business thinking, and problem-solving, making it highly relevant for Data Analyst and Business Analyst roles.


🙌 Author

Vikash Kumar
B.Tech CSE | Data Analytics Enthusiast
