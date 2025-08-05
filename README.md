# Data Scientist Portfolio

#### Resume: [My Data Scientist Resume](https://2d7974f8-5fa5-4136-aaa2-354b07c4877e.filesusr.com/ugd/a966b5_9b5ee692db00467f9b11ba99d706aee5.pdf)
#### Proficiency: Python, R, Tableau  
#### Familiarities: SQL, Jes, Power BI  
#### Tech Stack: pandas, NumPy, SciPy, seaborn, matplotlib, statsmodels, tidyverse, Git, Jupyter, Quarto, Excel

---

## Education

- **M.D.S., Data Science** – University of Pittsburgh *(Aug 2025 – Present)*  
- **B.G.S., Mathematics** – Ball State University *(Aug 2020 – May 2024)*  
- **A.A., Computer Science** – Ball State University *(Aug 2020 – May 2022)*

---

## Work Experience

### Lead Analyst – Iconic Care Inc *(June 2025 – Present)*
- Created financial forecasts identifying **$75,000+** in projected savings using data modeling and visualization.
- Deployed predictive models with **90%** accuracy and automated workflows to accelerate product readiness/improve decision-making.
- Automated ordering processes, reducing operational time by **50%**.
- Designed dashboards that increased procurement efficiency by **37%**.
- Uncovered **$30,000+** in unpaid CGM patient balances using `Python`.
- Conducted trend analysis on **100+** diabetic supplies/solutions to identify new revenue channels.

### Billing/Revenue Specialist – Iconic Care Inc *(May 2025 – June 2025)*
- Developed pricing tables and consignment structures that increased billing success by **65%**.
- Integrated `eVendor` and drop-shipping into `Brightree`, cutting delivery costs by **30%**.
- Built product "kits" to reduce cycle time by **25%** and improve profit margins.

### CEO / Data Scientist – Palmer Projects *(May 2023 – Present)*
- Collaborate with nonprofit and commercial teams to improve decisions through custom data tools.
- Build and deploy predictive models aligned with business strategy.
- Share findings through a public website blog to support the Data Science community.

---

## Projects

### MyCaddy | Physics-Based Golf Shot Calculator  
[Repository](https://github.com/CanyenPalmer/MyCaddy)  
[Launch the Web App](https://mycaddy.onrender.com)

**About:**  
Multi-interface, physics-based shot distance calculator that adjusts carry based on wind, temperature, lie, and weather drag.  
**`Python` · `Flask` · `Data Modeling` · `Web App` & `Desktop GUI`**

#### Overview
Simulates environmental effects on golf shots. Built for both beginners and professionals to make data-informed club selections.

#### Key Techniques
- Vector-based wind modeling  
- Temperature-density scaling (±0.3% per °F from 70°F)  
- Weather drag (e.g., rain: −4%)  
- Lie severity carry distance penalties (up to 40%)  
- Flyer lie simulation (88–95% confidence)

#### Tech Stack
- **Backend**: `Python`, `Flask`, `Gunicorn`  
- **Frontend**: `Jinja2`, `CSS`, `tkinter`  
- **Hosting**: `Render`

#### Impact
- Improved carry prediction by **20–30%** in rough lies  
- Reduced wind-related shot error by **7–12 yards**  
- Corrected temperature-based carry by **up to 5 yards**  
- Increased club choice accuracy by **up to 15%**

![MyCaddy](/assets/img/rangefinder.jpg)

---

### Google Capstone: Salifort Motors | Employee Attrition Prediction  
[Repository](https://github.com/CanyenPalmer/Logistic-Regression-and-Tree-based-Machine-Learning)  
[View Certification](https://www.coursera.org/account/accomplishments/professional-cert/certificate/GLIO99TYNKY8)

**About:**  
End-to-end machine learning project to help predict and prevent employee turnover using HR data.  
**`Python` · `scikit-learn` · `pandas` · `XGBoost` · `EDA`**

#### Overview
Analyzed *15,000 records* to build classifiers that predict whether an employee will leave. Generated HR-ready insights to support retention initiatives.

#### Key Techniques
- `EDA` for trends, correlations, and outliers  
- Logistic Regression (baseline)  
- Tree-based models (`Random Forest`, `XGBoost`)  
- Performance evaluation (accuracy, recall, F1, ROC)  
- Feature importance analysis

#### Tech Stack
- **Data Handling**: `pandas`, `NumPy`  
- **Modeling**: `scikit-learn`, `XGBoost`  
- **Visualization**: `seaborn`, `matplotlib`  
- **Environment**: `Jupyter Notebook`

#### Impact
- Achieved **94%** accuracy using `XGBoost`  
- Top predictors included: **satisfaction level**, **evaluation score**, and **number of projects**  
- Delivered actionable insights to reduce turnover risk  
- Built a scalable retention modeling framework

![Google Capstone](/assets/img/google.jpg)

---

### CGM Billing Analytics | Python Excel Automation  
[Repository](https://github.com/CanyenPalmer/CGM-Patient-Analytics)

**Tools:** `Python`, `pandas`, `Excel`, `OpenPyXL`

#### Overview
Script automates billing insights saving **200+** hours by filtering `HCPCS` codes and calculating patient responsibility from Excel exports.

#### Features
- Filters for codes `A4239` and `E2103`  
- Computes responsibility as (Allowed – Payments)  
- Generates dynamic summaries and Excel sheets  
- Consolidates financial trends for billing teams

#### Impact
- Identified **$317,000** in unpaid patient responsibility  
- Found **44%** of CGM patients had unpaid balances, saving the company *thousands* 
- Highlighted **$245,000** still uncollected  
- Diagnosed a **56:100** payment success ratio

![CGM Patients](/assets/img/cgm.jpg)

---

### Real Estate Price Modeling | Ames, TX  
[Repository](https://github.com/CanyenPalmer/R-Coding---Real-estate-Conditions-Comparrison)

**Tools:** `R`, `tidyverse`, `GLM`, `yardstick`, `ggplot2`

#### Overview
Used *2,300+ observations* and *60+ variables* to build a predictive model of home sale prices in Ames, TX.

#### Key Techniques
- Data wrangling with `tidyverse`  
- Log-transformation to normalize skew  
- Predictive modeling via `GLM`  
- Evaluation using `yardstick::rmse_vec()`

#### Impact
- Explained over **88%** of the variance in housing prices using a `Generalized Linear Model (GLM)` applied to the Ames Housing dataset, demonstrating strong model fit and predictive reliability.
- Identified *above-ground living area* and *neighborhood* as the top two drivers of sale price, contributing to more than **60%** of total model influence, enabling targeted pricing strategies for real estate professionals.
- Revealed that a finished basement adds **~$10K–$20K** in value on average, providing actionable insights for investors prioritizing renovations.
- Empowers *non-technical* stakeholders with interpretable visualizations (coefficient plots, residual diagnostics), bridging statistical output and business decision-making.

![Real-Estate](/assets/img/real_estate.jpg)

