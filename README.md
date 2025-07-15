# Quantitative-Research-JP-Morgan-Job-Simulation-Virtual-internship
I recently completed the JPMC Quantitative Research job simulation in Forage. Here is what I learned in details and in simple terms.
The job simulation can be divided into **two main** projects with **4 tasks** in total, detailed promts are in each task folder.

**Task 1** - Take historic existing price data (monthly snapshot) and extarpolate for next year price estimation. Visualize and find patterns or seasonal trends for the factors that caused the variation. 

**What I did**: I can do np.polyfit (NumPy) or sklearn () or LSTM, For these datasets, i did the sklearn. I found that there appears to be a seasonal pattern, with higher prices occurring in the winter months (e.g., January, February, December) and lower prices in the summer months (e.g., June, July). This is likely due to increased demand for heating in the winter. 

However, in their sample answer, they did linear plus a seasinal trend which was an amazing idea. Learned something new! I am showing here what I did and what I submitted. Cannot provide the sample answer for obvious reason.

**Task 2** - price a commodity storage contract used VSCode and "Nat_Gas.xlsx"

**Task 3** - credit risk analysis used Jupyter Notebook (much easier) and "task 3 and task 4_Loan_Data.csv"

**Task 4** - bucket fico scores used Jupyter Notebook and "task 3 and task 4_Loan_Data.csv" somewhat confused on this task, however, tried to finish 

