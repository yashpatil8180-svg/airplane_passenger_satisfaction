✈️ Airline Passenger Satisfaction Analysis
📌 Project Overview
The Airline Passenger Satisfaction Analysis project explores passenger feedback to understand satisfaction levels, travel-class preferences, customer types, seat-comfort ratings, gender distribution, and flight-distance categories.

The project uses data analysis and visualization to turn passenger records into meaningful insights that can help airlines identify service strengths and opportunities for improvement.

🎯 Objectives
- Analyze passenger satisfaction across travel classes.
- Compare satisfaction between loyal and disloyal customers.
- Explore satisfaction patterns by gender.
- Understand the distribution of passengers by customer type.
- Examine seat-comfort ratings.
- Analyze passenger distribution across flight-distance categories.
- Present the findings through an interactive-style dashboard
- .
🛠️ Tools & Technologies
- Microsoft Excel — data cleaning, PivotTables, charts, and dashboard creation
- Power BI — data visualization and dashboard reporting
- Python — data analysis in Jupyter Notebook
- Pandas & NumPy — data manipulation and numerical analysis
- Matplotlib & Seaborn — charts and visualization
- 
📊 Dashboard Overview
The dashboard presents six main visualizations:
1. Satisfaction by Travel Class — compares neutral/dissatisfied and satisfied passengers across Eco, Business, and Eco Plus.
2. Satisfaction by Customer Type — compares satisfaction counts for disloyal and loyal customers.
3. Satisfaction by Gender — displays satisfaction categories for male and female passengers.
4. Passenger Distribution by Customer Type — shows the proportion of loyal and disloyal passengers.
5. Seat Comfort Rating Distribution — displays the number of responses for ratings from 1 to 5.
6. Passengers by Flight Distance — compares long-, medium-, and short-distance passenger groups.
   
🔍 Key Insights
Based on the dashboard values shown:
- 250 passenger records are represented in the dashboard.
- Business class has the highest satisfied count among the three travel classes shown: 54, compared with 42 for Eco and 30 for Eco Plus.
- For customer type, the dashboard shows 67 satisfied disloyal customers and 59 satisfied loyal customers. Satisfaction should also be compared using percentages, because the groups may have different sizes.
- The customer-type distribution is approximately 52% disloyal and 48% loyal.
- Seat-comfort rating 5 has the highest response count (64), while rating 4 has 42 responses in the displayed chart.
- Long-distance passengers form the largest flight-distance group, with 146 passengers (58.4%), followed by medium distance with 74 (29.6%) and short distance with 30 (12%).
Note: These findings describe the 250 records displayed in the dashboard. Validate the figures against the final cleaned dataset before using them in a formal report. Counts alone do not establish the satisfaction rate; percentages provide a fairer comparison between groups.

🚀 How to Use the Project
1. Download or clone this repository.
2. Open the Excel workbook to explore the PivotTables and dashboard.
3. Open the .pbix file in Power BI Desktop to explore the report.
4. Open the Jupyter Notebook and run the analysis cells in order.
5. If running the Python analysis locally, install the required packages:
   pip install pandas numpy matplotlib seaborn jupyter
6. Update file paths in the notebook if your dataset is stored in a different location.
📈 Possible Future Improvements
- Add interactive slicers or filters for travel class, gender, and customer type.
- Compare satisfaction percentages, not only raw counts.
- Investigate the relationship between delays, service ratings, and satisfaction if those fields are available in the dataset.
- Add recommendations supported by the full dataset.
- Refresh the dashboard when new passenger feedback becomes available.
💡 Conclusion
This project demonstrates how Excel, Power BI, and Python can be used together to analyze passenger feedback and communicate findings visually. The dashboard highlights differences across travel classes, customer groups, seat-comfort ratings, and flight-distance categories, helping identify areas for further investigation and service improvement.
👤 Author
Yash Patil
