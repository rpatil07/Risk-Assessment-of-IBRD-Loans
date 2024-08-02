# Risk-Assessment-of-IBRD-Loans

This project includes analyzing and modeling data from "The International Bank for Reconstruction and Development" about the loans provided to various countries. The major purpose is investigating loan distribution, identifying patterns, and evaluating loan risks. The dataset contains detailed loan information, including loan amounts, statuses, and repayment details.

**IBRD**: It stands for "International Bank for Reconstruction and Development" and is a financial institute that along with the "International Development Association(IDA)" makes up the World Bank. Set up in 1944, IBRD aims to help developing countries reduce poverty and build shared prosperity. IBRD loans are made to, or guaranteed by, countries that are members of IBRD. IBRD may also make loans to "International Finance Corporation(IFC)". IBRD lends at market rates. The World Bank complies with all sanctions applicable to World Bank transactions.

**Dataset**: The dataset contains 1.3M rows of data with 33 columns providing various information about the country, region, the loan amount, the loan status, and the dates at which the loan was sanctioned, approved, repaid, etc. More information on each column can be found on the jupyter notebook.

**Data Preprocessing**: The stage involved handling missing data, converting the values into appropriate types, using encoding to categorize the "loan status" column for the machine learning algorithm, and calculating two new columns "Loan Duration" and "Remaining Principal" to analyze how long a country takes to repay its loans. 

**Exploratory Data Analysis**: Set up different visualizations to analyze the distribution of loans per region, the loan statuses of each region, the top 10 countries with the highest time taken to repay loans, and the countries with the highest amount due to IBRD.

**Model Selection**: Developing a risk model to predict the likelihood of loans being high-risk based on loan status and other relevant features. Used a RandomForest classifier and binary classification to to identify loans with high-risk characteristics. A classification report and confusion matrix are also done to visualize the accuracy of the model.
