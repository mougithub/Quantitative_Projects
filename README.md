# Quantitative-Research-JP-Morgan-Job-Simulation-Virtual-internship
I recently completed the JPMC Quantitative Research job simulation in Forage. Here is what I learned in details and in simple terms.
Tools used: 
The job simulation can be divided into **two main** projects with **4 tasks** in total, detailed promts are in each project folder.
In first project(Task 1 and Task 2) I was given a natural gas price data and told to 

**Task 1** - Take historic existing price data (monthly snapshot) and extarpolate for next year price estimation. Visualize and find patterns or seasonal trends for the factors that caused the variation. 

**What I did**: It can be done by np.polyfit (NumPy) or sklearn (scikit-learn) or even LSTM. For this dataset, I did the sklearn regression. I found that there appears to be a seasonal pattern, with higher prices occurring in the winter months (e.g., January, February, December) and lower prices in the summer months (e.g., June, July). This is likely due to increased demand for heating in the winter. 
While degree 3 polynomial model evaluation was improved and good enough to predict prices for any given date, it does miss the seasonality.
However, in their sample answer, they did linear plus a sinusoidal seasonal trend combined which was an amazing idea. Learned something new!
Inspired by the example answer, I also tried for a seasonality model using only numpy and np.polyfit. Improved R-squared: 0.9139 and Mean Squared Error: 0.0484. I am happy with the second method. Although the estimated price prediction did not change that much from the sklearn polynomial regression model.
I am showing here what I did and what I submitted. Cannot provide the sample answer for obvious reason.

**Task 2** - Build a pricing model so they can buy gas in summer to store and sell in winter in order to take advantage of the resulting increase in gas prices. There are a lot of parameters that should be taken into account for pricing like injection/withdrawal cost, storage costs, the prices at which the commodity can be purchased/sold on those dates etc.

In second project(Task 3 and Task 4) I was given a loan data and told to

**Task 3** - credit risk analysis used Jupyter Notebook (much easier) and "task 3 and task 4_Loan_Data.csv"

**Task 4** - bucket fico scores used Jupyter Notebook and "task 3 and task 4_Loan_Data.csv" somewhat confused on this task, however, tried to finish 

