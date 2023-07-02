# Lending Club Case Study
The company is the largest online loan marketplace, facilitating personal loans, business loans, and financing of medical procedures. Borrowers can easily access lower interest rate loans through a fast online interface.
 
The company wants to understand the driving factors (or driver variables) behind loan default, i.e., the variables which are strong indicators of default.  The company can utilise this knowledge for its portfolio and risk assessment.

## Steps Involved in the process
- Data Cleaning
- Outlier analysis
- Univariate analysis
- Segmented Univariate analysis
- Bi-variate analysis

## Observations of Uni-variate analysis (Driving Factors for Default)
- Higher Interest Rates
- Low annual income
- Higher or riskier grade or subgrade
- Higher Credit Utilization
- High debt to income ratio

## Observations of Bi-Variate analysis (Driving Factors for default)
- Interest rate is inversely proportional to the annual income. Lower annual income and High interest rates result in defaults. Higher annual income, lower interest rates can repay the loan.
- Higher interest rates on customers with riskier grades or sub-grades can lead to a high proportion of defaults.
- Most small businesses are not able to repay the loans when interest is more than 10.75%.
- Very high interest rates for educational and house loans that are greater than 14.96% have a very high rate of defaults.
- For a low-income range less than 49000 dollars, when term is 60 months, there is a fair percentage of people that default.
- For renewable energy when income < 36000 dollars, there are a fair percentage of values that have defaulted.
- For small business when income < 49000 dollars, there are a fair percentage of people that have defaulted.
- People with low income and high credit utilization have a default rate and people with high income and low credit utilization have a low default rate. These 2 variables are inversely proportional.
- A low income with high debt-to-income ratio reflects financial instability and can lead to defaults.
- People with housing loans with a high credit utilization have a very high default ratio.
- Educational and Small business loans have a very high default ratio when the term given to fulfill the loan is 60 months.
- People with housing loans with a high credit utilization have a very high default ratio.
- For education loans, a high dti can cause a higher default ratio


## Technologies Used
- Seaborn
- Numpy
- Pandas
- Matplotlib

## By
Created by damodar avadhani, mallikarjuna
