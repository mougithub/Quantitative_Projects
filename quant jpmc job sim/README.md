# Quantitative-Research-JP-Morgan-Job-Simulation-Virtual-internship
I recently completed the JPMC Quantitative Research job simulation in Forage. Here is what I learned in details and in simple terms.
Tools used: 
The job simulation can be divided into **two main** projects with **4 tasks** in total, detailed promts are in each project folder.
In first project(Task 1 and Task 2) I was given a natural gas price data and told to 

**Task 1** - Take historic existing price data (monthly snapshot) and extarpolate for next year price estimation. Visualize and find patterns or seasonal trends for the factors that caused the variation. 

**What I did**: 

**Task 2** - Build a pricing model so they can buy gas in summer to store and sell in winter in order to take advantage of the resulting increase in gas prices. There are a lot of parameters that should be taken into account for pricing like injection/withdrawal cost, storage costs, the prices at which the commodity can be purchased/sold on those dates etc.

In second project(Task 3 and Task 4) I was given a loan data and told to

**Task 3** - credit risk analysis used Jupyter Notebook (much easier) and "task 3 and task 4_Loan_Data.csv"

**Task 4** - bucket fico scores used Jupyter Notebook and "task 3 and task 4_Loan_Data.csv" somewhat confused on this task, however, tried to finish 

# Quantitative-Research-JP-Morgan-Job-Simulation-Virtual-Internship

I recently completed the **JPMC Quantitative Research Job Simulation** on Forage. Below is a brief overview of the projects and tasks I completed.  

**Tools used:** Python, Pandas, NumPy, Matplotlib, Statsmodels, Scikit-learn, XGBoost  

The simulation consisted of **two projects with four tasks**:

---

### **Project 1: Natural Gas Price Analysis**
- **Task 1 – Time Series Forecasting**  
  Used historical monthly natural gas prices to identify trends and seasonality, then forecasted future prices using a **SARIMA model**. Visualized patterns and built a function to retrieve predicted or historical prices for any date.  

- **Task 2 – Storage Contract Valuation**  
  Developed a **pricing model** for gas storage contracts to optimize buying and selling based on forecasted prices. Considered injection/withdrawal rates, storage costs, and max volume constraints to calculate potential contract value.

---

### **Project 2: Credit Risk Analysis**
- **Task 3 – Probability of Default & Expected Loss**  
  Modeled credit risk using loan data. Trained **Logistic Regression, Random Forest, and XGBoost** models, calibrated probabilities, and computed expected losses for individual borrowers.  

- **Task 4 – FICO Score Bucketing**  
  Bucketed FICO scores using a combination of **K-Means clustering and Decision Process**, estimated probability of default per bucket, and visualized the results.  

---

**Summary:**  
This simulation strengthened my skills in **time series forecasting, financial modeling, supervised learning, risk assessment, and data visualization**, while giving hands-on experience in applying quantitative techniques to real-world energy and finance problems.
