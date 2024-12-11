In this project, the objective was to analyze the factors influencing loan approval and to develop predictive models to better understand this process. The project began with an exploratory data analysis (EDA), where different categories of variables were studied, including demographic factors (age, education level, marital status), loan characteristics (loan amount, duration, interest rate), and variables related to creditworthiness (annual income, monthly debt payments). This step allowed to identify initial trends and insights, such as the potential relationships between certain variables and loan approval.

Next, statistical tests were performed to explore the relationships between categorical and quantitative variables. For example, chi-square tests and T-tests were used to confirm whether the differences observed between groups were statistically significant.

In the second phase, machine learning models were developed to predict loan approval. Two types of models were created:

A model based on loan characteristics.
A model based on solvency variables.
For these models, advanced techniques were used to deal with data imbalance, including the use of SMOTE (Synthetic Minority Oversampling Technique) and undersampling. Several algorithms were tested, including XGBoost, to identify the best performing model.
The performance of the models was evaluated using indicators such as precision, recall, F1 score, and the ROC curve. The final results demonstrated that the model based on solvency variables performed well, with balanced metrics between the two categories (approved and unapproved loans).

Finally, the project concluded with the creation of an interactive dashboard in Tableau that summarizes the exploratory data analysis. This dashboard includes visualizations of key variables, allowing users to quickly understand the main drivers and trends in the dataset.

[Tableau dashboard](https://public.tableau.com/views/Classeur1_17192156001680/LoanApprovalDashboard?:language=en-US&publish=yes&:sid=&:redirect=auth&:display_count=n&:origin=viz_share_link)

[Dataset](https://www.kaggle.com/datasets/lorenzozoppelletto/financial-risk-for-loan-approval/data)
