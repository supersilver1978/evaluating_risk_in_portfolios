# evaluating_risk_in_portfolios
Our firm is utilizing pandas and jupyter labs to evaluate different funds investment potential based on key risk-management metrics: the daily returns, standard deviations, Sharpe ratios, and betas. We are evaluating the funds over roughly a 6- year period from late 2014 to late 2020.

---

## *Technologies*

- **Programming Language:** Python
- **Libraries:** Pandas, Pathlib, Matplotlib, NumPy
- **Framework:** JupyterLab, can also use VS Code
- **Operating Systems:** Microsoft Windows

---

## *Installation Guide*

****
- **1:** Install Jupyter Labs and run it from the terminal. Make sure that you make sure you have an up-to-date version of Python
 [Install and run JupyterLab:](https://jupyter.org/install)
- **2:** Copy URL of this repo
- **3:** Clone folder to this repo and open in jupyter labs
- **4:** Ensure that you have the imports correctly identified to download
- **5:** Check the resources folder that you have access to the whale_navs.csv
---

## *Usage*

- Running the code can be done in one of two ways:
    1. You can click the "play" button at the very top of the notebook.
    2. You can click shift + enter on each block of code to run each batch of code as you go through it. 
<img width="350" alt="run preview" src=https://github.com/supersilver1978/bitcoin_arbitrage/blob/main/Resources/run.png>

  ### *5 Important Steps*
  Our goal is ultimately to answer the following two questions:
    1. Which of the two portfolios seem more sensitive to movements in the S&P 500?
    2. Which of the two portfolios do you recommend for inclusion in your firm’s suite of fund offerings?
  
  -**Step 1: Importing Data** 
      - Import required libraries and dependancies
      - Import paths to read the csv
      - Create a daily returns dataframe and preview the data
      
  **Step 2: Analyzing the Performance** 
      - Plot the daily returns and cumulative returns over the 6 years of the whales and S&P 500

  **Step 3: Analyzing the Volatility** 
      - Box plot of cumulative returns gives a nice visual of the variance
      - Dropping S&P and creating a box plot of just the whales gives a better perspective of their relative behavior      

  **Step 4: Analyzing the Risk** 
      - Plotting line graphs of the 21-day rolling average of standard deviation of returns is a good visual to evaluate risk.
      - The S&P500 index operates on a much d
      ifferent scale so you will need to remove it from the list and plot the whales to visualize the comparative risk.
    
  **Step 5: Analyzing Risk to Reward Ratios** 
      - Average annual returns and sharpe ratios are great tools for analyzing risk to reward ratios. 
      - This excercise clearly demonstrates that a high sharpe ratio can also yield low returns (ie. Tiger) so a thorough analysis is always key.
      
**Step 6: Diversification** 
      - Evaluating covariance and beta of the whales is important for understanding the diversification of a portfolio.
    
    
## *Contributor*

- Michelle Silver
- supersilver1978@hotmail.com

---

## *License*

This software is licensed under GNU General Public License v3.0. See the [LICENSE](https://github.com/djohnst914/Loan_Qualifier_New_Feature/blob/main/LICENSE) file for details. 
