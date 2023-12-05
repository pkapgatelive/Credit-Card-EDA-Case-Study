## Credit_Card_EDA

### **Problem Statement I**
- This case study is designed to illustrate the practical application of Exploratory Data Analysis (EDA) in a business context. Through the exploration of EDA techniques, participants will gain insights into risk analytics within the banking and financial services sector. The study emphasizes the utilization of data to mitigate the risk associated with lending, providing a comprehensive understanding of strategies employed to minimize financial losses in customer transactions.

#### **Business Understanding:**
- Loan providers face challenges in extending loans to individuals with insufficient or non-existent credit histories, as some consumers exploit this situation by defaulting on loans. As an employee of a consumer finance company specializing in lending various types of loans to urban customers, your role involves utilizing Exploratory Data Analysis (EDA) to analyze patterns in the data. The objective is to ensure that loan applicants capable of repaying are not unjustly rejected.

When evaluating loan applications, the company must make decisions based on the applicant's profile, considering two associated risks:

*	Approving a loan for a capable applicant ensures business for the company.
*	Approving a loan for a high-risk applicant may lead to financial losses if the applicant defaults.

The provided data includes information about loan applications at the time of submission and encompasses two scenarios:

- **Clients with payment difficulties:** Those who had late payments exceeding X days on at least one of the first Y installments.

- **All other cases:** Instances where payments were made on time.

Four types of decisions can be made by the client or company during the loan application process:

1.	Approved: The company approves the loan application.
2.	Cancelled: The client cancels the application, either due to a change of mind or, in some cases, due to receiving unfavorable terms.
3.	Refused: The company rejects the loan application based on non-compliance with requirements.
4.	Unused offer: The client cancels the loan at various stages of the process.

This case study employs EDA to discern how consumer attributes and loan characteristics influence the likelihood of default.

#### **Business Objectives:**

- The primary goal of this case study is to identify patterns that serve as indicators of a client's difficulty in paying installments. The insights derived from these patterns can inform strategic actions, such as denying the loan, reducing loan amounts, or lending to riskier applicants at higher interest rates. The overarching objective is to ensure that consumers capable of repaying the loan are not unfairly rejected. The focus of this case study is on using Exploratory Data Analysis (EDA) to identify such applicants.

- In essence, the company aims to comprehend the driving factors, or driver variables, behind loan defaults—those variables that strongly indicate a likelihood of default. The knowledge gained from this analysis can be leveraged for portfolio management and risk assessment within the company.

- As part of developing a comprehensive understanding of the domain, participants are encouraged to conduct independent research on risk analytics. This research should encompass an exploration of the types of variables involved and their significance in the context of risk assessment.

#### **Data Understanding:**

The dataset for this analysis comprises three files:

- **application_data.csv:**  This file encompasses comprehensive information about the client at the time of loan application. It specifically focuses on whether the client faces payment difficulties.

- **previous_application.csv:**  This file provides insights into the client's previous loan data, detailing whether the prior application was approved, cancelled, refused, or if it resulted in an unused offer.

- **columns_description.csv:**  Serving as a data dictionary, this file elucidates the meaning of the variables present in the dataset, offering a reference guide for understanding the information contained in the other files.


 
### **Problem Statement II**
In the pursuit of extracting meaningful insights from our dataset, the anticipated results encapsulate a comprehensive understanding of various facets crucial to our analysis. As we embark on this exploration, we aim to present a clear overview of our analytical approach, addressing key elements such as handling missing data, identifying outliers, and analyzing potential data imbalances.

Our objective is to not only provide a structured presentation of our findings but to also translate these results into actionable business insights. Through a meticulous examination of the data, we anticipate unveiling patterns, correlations, and anomalies that will contribute to a robust comprehension of the underlying dynamics within the dataset.

This section will guide you through the expected outcomes of our analysis, encompassing the identification and resolution of missing data, insights into potential outliers, a nuanced understanding of data imbalances, and a comprehensive interpretation of analysis results in terms of their business implications. Each expected result is aligned with the overarching goal of extracting knowledge that is not only statistically significant but also strategically valuable in the context of our problem statement.

1.	Overall Approach Presentation: Provide a brief overview of the problem statement and the analysis approach.
2.	Handling Missing Data:
    - Identify missing data in the dataset.
    - Utilize an appropriate method to address missing values, whether through removal of columns or replacement with suitable values.
    - Clearly articulate the rationale behind the chosen approach.
3.	Outlier Identification:
    - Identify outliers in the dataset.
    - Provide an explanation for why each identified point is considered an outlier.
    - Emphasize that, for this exercise, removal of data points is not necessary.
4.	Data Imbalance Analysis:
    - Assess data imbalance in the 'Target variable' (clients with payment difficulties and all other cases).
    - Calculate the ratio of data imbalance.
    - Employ a mix of univariate and bivariate analysis, considering different scales for graphs if necessary.

5.	Explaining Analysis Results:
    - Interpret the results of univariate, segmented univariate, and bivariate analyses in business terms.
    - Utilize loops for appropriate columns to extract insights.

6.	Top 10 Correlations:
    - Identify the top 10 correlations for clients with payment difficulties and all other cases.
    - Segment the data frame with respect to the target variable.
    - Correlate variables within each segment, excluding the target variable as it is categorical.

7.	Visualizations and Summarization:
    - Include relevant visualizations to explain numerical/categorical variables.
    - Summarize the most important results, providing insights into why specific variables are crucial for distinguishing clients with payment difficulties from all other cases.
