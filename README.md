📊 Electric Vehicle Data Analysis — Python Project
📝 Overview

This project analyzes 53 Electric Vehicles to understand battery performance, WLTP range, efficiency, consumption trends, and brand-level differences.
The full analysis is performed in a Jupyter Notebook, supported by visualizations and a recommendation system.

🧩 Business Problem

The EV market is expanding, but comparing vehicles across battery size, range, energy consumption, price, and performance is challenging.

This project answers key questions:

Which EVs are the most efficient?

How do major brands compare?

Are any vehicles unusually high or low in consumption?

Which EVs are best for specific budgets and range needs?

How can we simplify EV selection for customers?

A Top-3 EV Recommendation System is included to enhance decision-making.

📁 Dataset Information

The dataset includes 53 EVs with 25 attributes, embedded directly inside the notebook.

Key Columns

Car Details: Name, Make, Model

Performance: Engine power, Torque, Acceleration, Top speed

Battery & Range: Battery capacity (kWh), WLTP range (km), Energy consumption

Dimensions: Length, Width, Height, Wheelbase

Weight & Capacity: Empty weight, Gross weight, Boot capacity

Other: Price, Drive type, Braking type, Tire size, Seats, Doors, DC charging power

🧰 Tools & Technologies

Python, Jupyter Notebook

Pandas, NumPy

Matplotlib, Seaborn

SciPy (statistical tests)

OOP (Recommendation Class)

📂 Project Structure
```plaintext
EV-Data-Analysis/
│
├── Documentation/
│   └── EV_project_pdf.pdf
│
├── Notebook/
│   └── EV_project.ipynb
│
└── README.md

🔬 Methods

Data cleaning and imputation

Summary statistics & descriptive analysis

Outlier detection using IQR

Scatter plots, box plots, histogram distributions

Tesla vs Audi hypothesis testing (t-test)

Custom OOP EV recommendation engine

🔍 Key Insights
1. Budget + Range Filtering

Only 12 EVs satisfy Range ≥ 400 km and Price ≤ 350,000 PLN.

These belong to Audi, BMW, Hyundai, Kia, Mercedes-Benz, Tesla, Volkswagen.

Strong competition exists in the mid-range EV category.

Tesla & Volkswagen deliver excellent range at competitive pricing.

2. Battery Capacity vs Efficiency

Premium brands have higher battery capacities but lower range efficiency.

Tesla & Volkswagen achieve high range with smaller batteries → strong design efficiency.

3. Energy Consumption Analysis

No outliers detected in consumption values (14–25 kWh/100km common range).

Energy consumption across EVs is consistent and realistic.

4. Battery Capacity vs WLTP Range

Strong positive correlation — larger batteries yield longer range.

Variation among similar battery sizes shows the influence of design, efficiency, and aerodynamics.

5. EV Recommendation System

Prioritizes range first, price second.

Example recommendations for budget ≤300k PLN, range ≥400 km, battery ≥60 kWh:

Tesla Model 3 Long Range

Tesla Model 3 Performance

Volkswagen ID.3 Pro S

6. Tesla vs Audi Engine Power

Hypothesis testing shows no significant difference in average engine power.

Both brands have comparable motor performance.

✅ Final Recommendations

Improve efficiency, not just battery size — some EVs underperform despite large batteries.

Reassess pricing for EVs offering lower value (high price, low performance).

Prioritize mid-range EVs (430–550 km) due to strong consumer demand.

Focus on charging speed and efficiency, not just motor power.

Build customer-facing tools, such as dashboards or web apps, using the recommendation system.

Enhance range efficiency by improving aerodynamics and drivetrain optimization.

▶️ How to Run This Project
1. Clone the repository
   git clone https://github.com/your-username/EV-Data-Analysis-Python.git
2. Install dependencies
   pip install pandas numpy matplotlib seaborn scipy
3. Open the notebook
   jupyter notebook Notebook/EV_project.ipynb
👤 Author & Contact

Name: Abhishek Tandle
Email: abhishektandle1507@gmail.com

LinkedIn: https://linkedin.com/in/abhishek-tandle-a10b70260

GitHub: https://github.com/abhishekt1507

Portfolio: https://abhi-shek.my.canva.site
