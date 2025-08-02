# Data Scientist

#### Resume: [(https://2d7974f8-5fa5-4136-aaa2-354b07c4877e.filesusr.com/ugd/a966b5_c4bc33c5a0f94ea8987f1c6a68e671e9.pdf)](https://2d7974f8-5fa5-4136-aaa2-354b07c4877e.filesusr.com/ugd/a966b5_c4bc33c5a0f94ea8987f1c6a68e671e9.pdf)
#### Proficiency: Python, R, Tableau
#### Familiarities: ARM Assembly, Jes, SQL, Power BI, AI
#### Tech Stack: Pandas/NumPy, Scipy, seaborn, Matplotlib, statsmodels, Tidyverse, Git, Jupyter, CSV/Excel, Quarto(.qmd)

## Education
- M.D.S, Data Science | The University of Pittsburgh (_Aug 2025 - Present_)								       		
- B.G.S, Mathematics	| Ball State University (_Aug 2020 - May 2024_)	 			        		
- A.A, Computer Science | Ball State University (_Aug 2020 - May 2022_)

## Work Experience
**Lead Analyst @ Iconic Care Inc (_June 2025 - Present_)**
- Created different financial forecasts that uncovered $75,000+ in projected savings for 2025 through data extraction, analysis, modeling, and visualization.
- Deployed predictive models and analytical workflows to improve decision-making and accelerate product readiness.
- Automated key stages of the ordering cycle, reducing operational time by 50%.
- Designed interactive dashboards that increased order cycle efficiency by 37%, enabling real-time insight across departments.
- Researched marketing trends and applied data analysis to identify new revenue opportunities.
- Discovered $30,000+ in unpaid patient responsibility for CGM equipment using data modeling/manipulation in Python

**Billing/Revenue Specialist @ Iconic Care Inc (_May 2025 - June 2025_)**
- Created consignment structures and pricing tables that improved billing success rates by 65%.
- Integrated eVendor and drop-shipping systems into Brightree, lowering delivery expenses by 30%.
- Developed "kits" in Brightree, reducing processing time within the ordering cycle and increasing overall profit margins.

**CEO/Data Scientist @ Palmer Projects (_May 2023 - Present_)**
- Work with volunteer services to create better patient outcomes through data 
- Engineer data models for small businesses/large corporations baised on their current inititaves
- Showcase my findings throughout a 'blog' like website to contribute back to the community of data science

## Projects

### MyCaddy | Elemental Factoring for Yardage Calculations
[Publication][(https://github.com/CanyenPalmer/MyCaddy)](https://github.com/CanyenPalmer/MyCaddy)

**My Caddy Distance** is a precision golf shot calculator that models real-world conditions to deliver highly accurate carry distance estimates. Built for all levels of golfers—from beginners learning club confidence to professionals fine-tuning for competitive rounds—this tool helps players understand how environmental factors affect each shot.

#### What It Does

My Caddy Distance takes in player-defined inputs such as:

- Distance to the flag
- Lie condition (e.g., fairway, rough, buried)
- Temperature (°F)
- Weather (sunny, cloudy, rain, snow)
- Wind direction and speed
- Shot direction
- Optional flyer lie (adds a projected distance range)

Based on these values, it calculates an **adjusted carry distance** using aerodynamic formulas, environmental physics, and lie-based modifiers.

#### Key Features

- Fully interactive **web application** built with Python (`Flask`)
- Packages: `math` and `tkinker`
- **Themed UI** styled to reflect clarity and professionalism
- Core logic extracted to a standalone module (`my_caddy_core.py`)
- Using `calculations.py` only and running will allow local hosting for desktop application
- Support for “flyer lies” with projected low/high yardage range
- Accessible for golfers of all experience levels
- Hosted publicly via Render

#### How It Works

The program simulates how temperature, wind, and lie conditions affect the effective carry distance of a golf ball using simplified aerodynamic principles. It applies:

- Temperature adjustments (~0.3% per °F deviation from 70°F)
- Wind impact based on angle and speed
- Carry reduction for different lie conditions (0–100%)
- Realistic flyer range adjustments (+5% to +12%)

#### Live Demo

[Launch the Web App][(https://my-caddy-distance.onrender.com)](https://mycaddy.onrender.com/)


#### License

This project is released under the rights of @PalmerProjects, all copyright ownership belongs to Canyen Palmer

![MyCaddy](/assets/img/rangefinder.jpg)


### Capstone: Google Advanced Data Analytics
[Publication][(https://github.com/CanyenPalmer/Logistic-Regression-and-Tree-based-Machine-Learning)](https://github.com/CanyenPalmer/Logistic-Regression-and-Tree-based-Machine-Learning)

#### Skills and Techniques: 
Statistical Hypothesis Testing, Feature Engineering, Machine Learning, Object Oriented Programming (OOP), Tableau Software, Data Visualization, Sampling (Statistics), Statistical Analysis, Regression Analysis, Exploratory Data Analysis

**Logistic Regression:**
- The logistic regression model achieved a precision of 80%, recall of 83%, f1-score of 80% (all weighted averages), and an accuracy of 83%, on the test set.

**Tree-based Machine Learning**
- After conducting feature engineering, the decision tree model achieved AUC of 93.8%, precision of 87.0%, recall of 90.4%, f1-score of 88.7%, and an accuracy of 96.2% on the test set. The random forest modestly outperformed the decision tree model.

![Google Capstone](/assets/img/google.jpg)

### Patient Responsibility & Billing Analytics Automation
[Publication][(https://github.com/CanyenPalmer/CGM-Patient-Analytics)](https://github.com/CanyenPalmer/CGM-Patient-Analytics)

Tools: `Python`, `Pandas`, `Excel`, `OpenPyXL`

Developed a Python-based analytics solution to streamline billing insights for CGM-related procedures. The script extracts and processes data from an Excel file to identify patient responsibility by filtering for HCPCS codes **A4239** and **E2103**. Using `pandas`, it cleans financial fields, calculates patient responsibility (Allowed Amount – Payments), and organizes key billing data into a structured report. Additionally, the script generates a dynamic monthly summary that groups patient responsibility by individual and service date. Outputs include:

- Detailed Report with sortable, patient-level billing rows and a total summary
- Pivoted Monthly Responsibility Report showing trends over time

Both reports are exported to a formatted Excel workbook with separate sheets, enhancing visibility for finance and care teams. Using `OpenPyXL`, I was able to produce the outputs in a consolidated Excel file. This project demonstrates proficiency in healthcare data analysis, Excel automation, and building reproducible reporting tools that reduce manual effort and improve billing transparency.

#### Conclusions
It was discovered that the company still awaits payment for **over 50% ($317,000)** of their expected funds in `Patient Responsibility` assets alone. Out of all **CGM patients**, the company needs **44% ($245,000)** of payments to be recieved even after the patient has been billed.

This can occur from billing errors, patients not making payments, waiting transfer balances, and/or more.
That means currently, the company's successful payment ratio is roughly = **'56:100'**

**55%** of all invoices issued in the *United States are paid late*, with **22%** of business owners not expecting late payment incidents to cease in the near future.
This can dampen financial stability and can create permanently lost funds over time (more expenses = more profit lost)

**Calculated Totals:**

- Patient Responsibility Total = 317k
- Invoice Detail Charge Total = 602k
- Invoice Detail Allow Total = 562k
- Invoice Detail Payments = 245k
- Invoice Detail Balance = 201k

![CGM Patients](/assets/img/cgm.jpg)

### R coding | Real-estate Conditions Comparison: Real Estate Price Modeling in Ames, TX
[Publication][(https://github.com/CanyenPalmer/R-Coding---Real-estate-Conditions-Comparrison)](https://github.com/CanyenPalmer/R-Coding---Real-estate-Conditions-Comparrison)

As part of a recent applied statistics and modeling project, I developed a predictive model to analyze housing market conditions in Ames, Texas. Using a rich dataset with over **2,300 observations** and **60+ features**, this project focused on identifying the most significant predictors of **home sale prices** through exploratory data analysis and regression modeling.

Key Techniques and Tools:

#### R Programming: 
- Leveraged the `tidyverse` for data wrangling and visualization.
- **Generalized Linear Models (GLM)**:
- Applied **log-transformation** to normalize skewed response variables and improve linear model fit.
-  **Model Selection**: 
- Assessed multiple predictors including `foundation`, `condition_1`, `condition_2`, and `sale_condition` using linear regression.
- **Model Evaluation**: 
- Used `yardstick::rmse_vec()` to compare prediction accuracy via **Root Mean Square Error (RMSE)**.

#### Data Handling: 
Interpreted over 60 numeric and categorical predictors, including physical features, zoning codes, and home attributes.

#### Why It Matters:
This project bridges statistical theory with real-world business intelligence. The predictive modeling framework developed here can be extended to:

- Valuation models for residential and commercial real estate.
- Feature selection in complex, multi-variable environments.
- Price optimization and trend forecasting in dynamic markets.

#### Broader Impact:
This hands-on experience reinforces my ability to:

- Transform raw data into actionable insights.
- Build and validate interpretable machine learning models.
- Communicate technical results to drive decision-making—skills that are vital in any data science or analytics role

![Real-Estate](/assets/img/real_estate.jpg)
