# Lending Club Case Study
> This case study focuses on applying Exploratory Data Analysis (EDA) techniques to understand the risk associated with lending for the consumer finance company.

## Group Details
UpGrad and IIITB Machine Learnig and AI Program July 2024 - ML C67
Group Facilitator: Umesh Goyal (umeshg1981@gmail.com)
Group Member: Krishna Kumar.S (urkrishna@gmail.com)

## Table of Contents
* [General Info](#general-information)
* [Analysis Steps](#analysis-steps)
* [Technologies Used](#technologies-used)
* [Conclusions](#conclusions)
* [Acknowledgements](#acknowledgements)

<!-- You can include any other section that is pertinent to your problem -->

## General Information
The consumer finance company must balance two key risks when making loan approval decisions: rejecting applicants who would repay the loan, thus losing potential business, and approving applicants who are likely to default, which could lead to significant financial losses. The objective is to analyze a dataset of past loan applicants to identify patterns and factors that influence the likelihood of loan defaults. The consumer finance company at the center of this analysis is interested in minimizing financial losses by improving its decision-making process in loan approvals. By identifying key indicators of default, the company aims to manage its risk exposure and reduce credit loss.

The goal of this analysis is to use EDA to uncover the factors that can predict loan default, allowing the company to better assess the risk profile of applicants. This knowledge will enable the company to make data-driven decisions to either reject, modify, or accept loan applications, ultimately reducing credit loss and improving financial performance.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->

## Analysis Steps
* Reading Data
* Data wrangling
  * Handle missing rows
  * Handle missing data from column prespective
  * Check for Duplicates
  * Remove single-valued columns
  * Filter data
  * Select columns based of business knowledge
  * Cleaning columns and correcting data types
  * Handle Outliers
* Univariate Analysis
  * Define functions
    * Define Univariate Analysis FUnction
    * Define Function for Segmentation
    * Define Function for Segmented Univariate Analysis
  * Analyse Categorical Variables
    * Univariate Analysis
  * Analyse Numeric Variables
    * Univariate Analysis
    * Segmented Univariate Analysis
* Bivariate Analysis
  * Define functions
    * Define function for Bivariate Categorical Variable analysis
    * Define function for segmentation
    * Define function for Bivariate analysis of Numeric Variables
  * Analyse Categorical attributes
    * Bivariate analysis
  * Analyse Numeric Attributes
    * Bivariate analysis
    * Bivariate analysis after binning
* Correlation and heat map
* Multivariate Analysis
  * Investigate defaults for loans issued around holidays

## Conclusions
**Driving Factors for Loan Default.**

Basis analysis done, below are the variables that are driving factors for Loan default.
The variables are listed in decreasing weightage of impact they have have. i.e. highest impact driving factor is listed first.
1. Grade
2. Sub Grade
3. Interest Rate
4. Revolving Credit Utilization
5. Installment to Monthly Income Ratio
6. Term
7. Delinquency Count
8. Issue Month
9. Installment
10. Annual Income
11. Combination of Interest Ratea nd Revolving Credit Utilization can be a farily good predictor of Loan Default.

**Recomendations**
-  Even when source verification or full verification is conducted, default rates are not reduced to the same level as for customers who do not require verification. Review the verification process and enhance its accuracy by incorporating additional verification attributes.
-  Loans issued during the holiday season (November-December) and long weekends is a strong driving factor for defaults. Setup additional processing rules around these.
-  The internal proceses within the company is not able to keep pace with the rapid expansion and scaling. Reivew, optimize and enhance loan risk assessment processes within the comapny to be in sync with the expansion and scaling goals.
-  Loan defaults are influenced by both seasonal factors and loan purpose. The vacation season (May-June) appears to be a particularly risky period for Vacation loans. Add additional verification steps for Vacation loans during this period.
-  Create stricter approval processes for high-risk loan purposes such as debt consolidation.
-  Implement predictive models that weigh interest rate, loan term, and borrower income heavily to improve default prediction.
-  Introduce more flexible loan repayment plans, especially around the holiday season to reduce defaults.

<!-- You don't have to answer all the questions - just the ones relevant to your project. -->


## Technologies Used
- Numpy
- Pandas
- Matplotlib
- Seaborn

<!-- As the libraries versions keep on changing, it is recommended to mention the version of library used in this project -->

## Acknowledgements
- Live session on EDA conducted by upGrad.
- Live session on Case Study conducted by upGrad.
- Resposnes provided in Daily Doubt Resolution sessions conducted by upGrad.
- Cource content in upGrad Course 1 - Module 4 - Exploratory Data Analysis.


## Contact
Created by [@kk20krishna](https://github.com/kk20krishna) and [@umeshg1981](https://github.com/umeshg1981) - feel free to contact us!


<!-- Optional -->
<!-- ## License -->
<!-- This project is open source and available under the [... License](). -->

<!-- You don't have to include all sections - just the one's relevant to your project -->
