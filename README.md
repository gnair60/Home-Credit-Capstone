# Home-Credit-Default-Risk
## Introduction

Home Credit is an international consumer finance provider which operates in 9 countries. It provides point of sales loans, cash loans and revolving loans to underserved borrowers. The term undeserved borrower here refers to those who earn regular income from their job or businesses, but have little or no credit history and find it difficult to get credits from other traditional lending organizations. They believe that the credit history should not be a barrier for a borrower to fulfill their dreams. The goal of the project is to leverage the accumulated borrower behavioral data to develop predictive models. These models will enable Home Credit to efficiently analyze the risk associated with a given client and estimate the safe credit amount to be lent, even for underserved borrowers with little or no credit history. Ultimately, the aim is to provide financial assistance to customers and fulfill their dreams while ensuring responsible lending practices.

## Business Problem

Home Credit is facing a substantial barrier in providing loans to individuals with insufficient or non-existent credit histories. This challenge hampers the company's mission of broadening financial inclusion and exposes this demographic to exploitation by untrustworthy lenders.

## Analytics Approach

This is a predictive analytics project, and the analytics approach for solving the problem will involve a supervised learning methodology. A classification algorithm will be utilized to predict whether a loan applicant is likely to repay or not. We will make use of a variety of alternative data (including telco and transactional information) to create the model. The target variable for the supervised classification model will be binary, indicating whether the applicant is classified as capable of repayment or not.

## Scope

The project entails developing a predictive analytics model through supervised learning and a classification algorithm for loan repayment prediction. Utilizing diverse alternative data, including telco and transactional information, the scope encompasses model development, validation, and integration. Excluded from the scope are detailed loan decline analyses and specific loan term considerations. Potential future additions involve refining the model with extra data sources or incorporating real-time updates.

## Project Objective

The main aim of this project is to create a predictive analytics solution using supervised learning techniques to evaluate the creditworthiness of loan applicants. The objective is to employ a classification algorithm to predict whether an applicant is likely to fulfill their loan obligations or default.  The target variable for the supervised classification model will be binary, indicating whether the applicant is deemed capable of repayment or not. This project seeks to offer a dependable tool for financial institutions to make well-informed lending decisions, with the ultimate goal of reducing default risks and optimizing their loan portfolios.

## Solution 

These notebooks will delve into the exploration of Home Credit default risk data, encompassing data cleaning, exploratory analysis, hypothesis testing, and visualization.

In our exploratory data analysis (EDA), we'll leverage both the application dataset and the bureau dataset to conduct hypothesis testing and perform data cleansing. This includes scrutinizing transactional data from the Bureau dataset. Throughout our analysis, we'll delve into several hypothesis questions, investigating aspects like the relationship between gender and default rates, the influence of age and gender on defaults, and how factors such as occupation affect default rates.

Following the EDA, we'll construct predictive models using the cleaned data to evaluate credit default risk. Our focus will be on the target variable, employing diverse machine learning models and assessing their performance using metrics such as accuracy and ROC values.

Our objective is to identify the optimal model based on Kaggle scores. We'll commence our analysis with logistic regression and then evaluate the performance of additional models, including Random Forest, XGBoost, and LightGBM, to determine their effectiveness in predicting credit default risk.


## Contributution

My contributions to the project primarily focused on two key areas: data exploration and modeling using the Random Forest algorithm. I conducted thorough analysis of the datasets, uncovering intricate insights related to credit default risk through meticulous examination of patterns and correlations. 
Through meticulous examination, I identified key patterns, correlations, and potential predictors that could significantly influence the predictive outcomes. Following the exploratory phase, I transitioned into the modeling realm, where I spearheaded the implementation of the Random Forest algorithm. Leveraging its ensemble learning capabilities, I constructed a predictive model tailored to discerning credit default probabilities. This involved meticulous parameterization and fine-tuning to optimize model performance, ensuring its ability to effectively capture the underlying complexities within the data.

## Business Value

The model's ability to predict default rates enables Home Credit to proactively identify customers at risk of defaulting on their loans. Through the utilization of Explainable AI (XAI), the model elucidates which predictors exert the most influence on the likelihood of default, providing valuable insights for risk management strategies.

Modeling plays a pivotal role in mitigating the risk of non-performing assets, consequently bolstering the company's bottom line by minimizing losses attributed to defaults. Moreover, extending loans to underserved customers lacking credit history expands Home Credit's customer base and revenue streams, fostering inclusive growth and financial empowerment.

Embracing technology and machine learning in the financial sector not only drives business growth but also streamlines operations, enhancing efficiency and customer service. Through the optimized loan portfolio facilitated by the solution, Home Credit strategically allocates resources to applications with the highest expected returns relative to their associated risks, thereby maximizing profitability while maintaining a prudent risk profile.

Furthermore, enhanced profitability is achieved through improved risk assessment and portfolio optimization, enabling Home Credit to approve loans with favorable Risk-Adjusted Return on Capital (RAROC) values. This results in increased revenue generation while mitigating the adverse effects of defaults.

## Challenges

**Missing values**:- Handling missing values poses a challenge, as determining whether to impute them with measures like mean, median, or mode, or treat them as a distinct category like 'None', requires careful consideration for each column containing missing data.

**Model selection**:- The challenge in model selection arises from high correlations between predictors and the risk of multicollinearity. Careful consideration is needed to choose models that can handle these challenges effectively.

**Prioritizing Features**:- One of the primary challenges our team faced was managing the large volume of data resulting from numerous data files. This presented obstacles during the feature engineering stage, complicating the process of determining which features to incorporate into our predictive model.

**Resource Constraints**:- Resource constraints, such as limited computational power, presented challenges in scaling our analysis and implementing modeling techniques. Streamlining model training times and effectively utilizing available resources proved to be a time-consuming endeavor.

**Hyperparameter tuning**:- Fine-tuning hyperparameters for the models is essential to ensure a good fit with the dataset and yield optimal results. This process entails adjusting parameters to attain the best possible fit, and the challenge lies in identifying the most suitable combination for each model to achieve optimal predictive accuracy.


## Lessons Learned

Understanding Hypotheses through Visualizations:- Deciphering hypotheses through visualizations was a key aspect of our analysis, aiding in interpreting patterns and relationships within the data. The integration of disparate datasets allowed for a holistic examination of the problem, enabling comprehensive analysis and exploration of potential solutions.

Model Optimization:- Overcoming class imbalance issues, particularly the majority class problem, necessitated employing under-sampling methods to balance the class distribution. Additionally, model selection and hyperparameter tuning were instrumental in optimizing performance and achieving the best results.

Feature Engineering:- Navigating through extensive datasets underscored the significance of feature engineering in extracting meaningful insights and enhancing model performance, prompting exploration of diverse feature selection and extraction techniques.

Model Development and Performance Evaluation:- From implementing machine learning algorithms like LG Boost to fine-tuning parameters and evaluating performance metrics, I honed my skills in model development and assessment, enabling informed decision-making based on results interpretation.

