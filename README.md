# job-market-analysis
U.S. Job market analysis: Ranking cities by job growth, salaries, and employment trends

**Overview**
This project analyzes employment trends, salary distributions, and job market growth across major U.S. cities using real data from the Bureau of Labor Statistics (BLS). It ranks cities based on a custom Job Market Index (JMI) score, normalizes salaries for cost-of-living adjustments, and visualizes insights through clear, well-structured charts.
Features
•	Real-world BLS Data - Extracted, cleaned, and analyzed without requiring an API key.
•	Custom JMI score - Weighted scoring method ranks cities based on employment, salaries, job openings, and growth.
•	Cost-of-living adjusted salaries - Provides a realistic comparison of purchasing power in different cities.
•	Correlation analysis - Examines relationships between job growth and median salaries.
•	Seaborn & Matplotlib visuals - formatted charts with proper labels and insights.
📂 Structure
├── 📁 data/
│   └── 📄 bls_job_market_data.csv    # Cleaned dataset used for analysis
├── 📁 notebooks/
│   └── 📄 job_market_analysis.ipynb  # Jupyter notebook for data analysis and visualization
├── 📁 visualizations/
│   ├── 📊 job_market_index.png       # Bar chart of job market index scores
│   ├── 📊 job_growth_rate.png        # Job growth rate comparison
│   ├── 📊 median_salary.png          # Median salary comparison
│   ├── 📊 adjusted_salary.png        # Cost-of-living adjusted salary comparison
│   ├── 📊 job_growth_vs_salary.png   # Scatter plot of job growth vs. salary
├── 📁 app/
│   ├── 📄 app.py                     # Optional: Interactive web app for insights (Dash/Streamlit)
│   └── 📁 static/
│       └── 🎨 style.css              # Optional: Custom CSS styling
├── 📄 README.md                      # Project documentation
└── 📄 requirements.txt               # Python dependencies

**📊 Visualizations**
•	Job market index Score - Ranking of cities based on multiple employment factors.
•	Job growth rate comparison - Identifies fast-growing job markets.
•	Median salary estimate by City - Shows income disparities across locations.
•	Adjusted salary comparison - Evaluates salary differences after accounting for cost-of-living.
•	Job growth vs. Salary scatter plot - Identifies trends in job market expansion vs. compensation.

**Pre-processing/analysis**
1.	Data collection: Downloaded BLS job market data for multiple U.S. cities.
2.	Data cleaning & processing: Filtered key employment factors (salaries, job growth, employment levels).
3.	Normalization & scoring: Used Min-Max scaling and weighted scores to compute the Job Market Index (JMI).
4.	Cost-of-living adjustment: Adjusted salaries based on estimated city cost-of-living indexes.
5.	Data visualization: Created detailed Seaborn & Matplotlib charts to present insights.
6.	Project structuring: Organized files into data, notebooks, visualizations, and app directories for clear maintainability.

**🛠️ Requirements**
To run the analysis, install the dependencies:
pip install -r requirements.txt

**Instructions**
1.	Clone the repository:
git clone https://github.com/yourusername/job-market-analysis.git
2.	Navigate into the project directory:
cd job-market-analysis
3.	Run the Jupyter Notebook to analyze data:
jupyter notebook notebooks/job_market_analysis.ipynb

**Conclusion**
This project provides valuable insights into the U.S. job market, demonstrating data analysis, visualization, and economic interpretation skills. It is a great portfolio piece showcasing expertise in real-world data analytics.
