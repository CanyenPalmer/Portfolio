# Data Scientist

#### Resume: [(https://2d7974f8-5fa5-4136-aaa2-354b07c4877e.filesusr.com/ugd/a966b5_d8e418714fc148a69ee20224d2504475.pdf)](https://2d7974f8-5fa5-4136-aaa2-354b07c4877e.filesusr.com/ugd/a966b5_d8e418714fc148a69ee20224d2504475.pdf)
#### Proficiency: Python, R, Tableau
#### Familiarities: SQL, Jes, Power BI
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

### MyCaddy | Physics-Based Golf Shot Calculator
[Publication][(https://github.com/CanyenPalmer/MyCaddy)](https://github.com/CanyenPalmer/MyCaddy)
#### Live Demo
[Launch the Web App][(https://my-caddy-distance.onrender.com)](https://mycaddy.onrender.com/)

*About Us:*
- Multi-interface, physics-based shot distance calculator developed to help golfers make data-driven club selections by modeling the true impact of environmental and surface conditions. It dynamically adjusts shot carry distances based on lie severity, temperature, wind direction and speed, and weather-related drag—all through an intuitive web or desktop interface.
**Python · Flask · Data Modeling · Web App & Desktop GUI**

#### Overview  
**MyCaddy** addresses the demand for an affordable, accurate tool to model real-world shot conditions—empowering beginners to build confidence and professionals to refine strategy. It simulates the impact of wind, temperature, weather, and lie severity on carry distance using physics-based calculations and vector math. The platform is available in both web and desktop formats.

#### Key Techniques  
- Vector-based wind modeling (shot direction vs. wind angle)  
- Temperature-density scaling (±0.3% per °F from 70°F)  
- Weather drag adjustments (e.g., rain: −4%, snow: −8%)  
- Lie severity carry penalties (up to 40%)  
- Flyer lie simulation with 88–95% confidence intervals

#### Tech Stack  
- **Backend**: Python, Flask, Gunicorn  
- **Frontend**: Jinja2, CSS (responsive UI), tkinter (desktop GUI)  
- **Hosting**: Render

#### Impact  
- Improved carry prediction by **20–30%** in rough lies  
- Reduced wind-related shot error by **7–12 yards**  
- Adjusted temperature-influenced carry by **up to 5 yards**  
- Increased club selection accuracy by **up to 15%**

#### License

- MyCaddy empowers modern golfers to integrate performance science into every round through adaptable, analytical, and user-focused design.
- © 2025 Palmer Projects. All rights reserved. Created and led by Canyen Palmer, CEO of Palmer Projects.


![MyCaddy](/assets/img/rangefinder.jpg)


### Google Advanced Data Analytics Capstone: Salifort Motors | Employee Attrition Prediction
[Publication][(https://github.com/CanyenPalmer/Logistic-Regression-and-Tree-based-Machine-Learning)](https://github.com/CanyenPalmer/Logistic-Regression-and-Tree-based-Machine-Learning)

#### Certification  
[View Certification][(https://www.coursera.org/account/accomplishments/professional-cert/certificate/GLIO99TYNKY8)](https://www.coursera.org/account/accomplishments/professional-cert/certificate/GLIO99TYNKY8)

*Project Design:*  
- End-to-end machine learning pipeline designed to help Salifort Motors identify employees at risk of leaving the company. This project enables the HR department to take proactive, data-informed actions to improve retention and workplace satisfaction.  
**Python · scikit-learn · pandas · EDA · Logistic Regression · Tree-Based Classification**

#### Tech Stack  
- **Data Handling**: pandas, NumPy  
- **Modeling**: scikit-learn, XGBoost  
- **Visualization**: seaborn, matplotlib  
- **Development Environment**: Jupyter Notebook

#### Overview  
This capstone project addresses a real business problem: predicting employee attrition using HR data. With 15,000 employee records from a public dataset, the objective was to determine the key drivers of employee turnover and construct classification models to predict who is likely to leave the company. This helps Salifort Motors reduce costly turnover and better understand employee engagement factors.

#### Key Techniques  
- Exploratory data analysis (EDA) for trends, correlations, and class imbalance  
- Feature selection and preprocessing of numeric and categorical variables  
- Logistic Regression as a baseline model  
- Decision Tree, Random Forest, and XGBoost classifiers for performance comparison  
- Model evaluation via accuracy, precision, recall, F1 score, confusion matrix, and ROC curve  
- Feature importance analysis to interpret predictors of attrition

#### Tech Stack  
- **Data Handling**: pandas, NumPy  
- **Modeling**: scikit-learn, XGBoost  
- **Visualization**: seaborn, matplotlib  
- **Development Environment**: Jupyter Notebook

#### Impact  
- Achieved classification accuracy of up to **94%** using XGBoost  
- Identified key predictors of attrition including **satisfaction level**, **evaluation score**, and **number of projects**  
- Provided HR with interpretable and actionable insights to reduce employee turnover  
- Delivered a replicable framework for ongoing internal workforce analysis

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

#### Broader Impact:
This project bridges statistical theory with real-world business intelligence. The predictive modeling framework developed here can be extended to:

- Valuation models for residential and commercial real estate.
- Feature selection in complex, multi-variable environments.
- Price optimization and trend forecasting in dynamic markets.


![Real-Estate](/assets/img/real_estate.jpg)
