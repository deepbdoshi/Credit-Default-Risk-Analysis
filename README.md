## Credit Default Risk Analysis


#### Problem Statement

This project addresses the challenge of determining creditworthiness for a leading platform offering customized loan products to customers.

Focused on underwriting for personal loans, the goal was to develop and deploy a data-driven model to decide whether to extend a credit line and define its terms, leveraging insights from salaried professionals and MSMEs' data.


Data Source - **Confidential**.


#### Features
* Employment Details.
* Public Records.
* Credit Info.
* Current Loan Request Info.


#### Dependencies
**Tech Stack** - Pandas, Scikit-learn, Matplotlib, LogisticRegression, Supervised Learning, Regression metrics and ROC-AUC curves.

#### Project Workflow

* **Overview** - Developed a predictive model to estimate potential loan defaulter based on factors such as employement, house ownership, and public records.<br>
* **Utility Functions** - Designed some utility functions for assisstance in data visualization analysis of the given features, feature engineering and data cleaning.
* **Data Preprocessing** -
    * **Data Anslysis and Transformation** - Performed data transformation to uncover outliers and fill in the missing values and encode various features for better model trainings.
    * **Data Visualization** - Performed data visualization to understand data distribution across various categories of various features.
    * **Feature Engineering** - Conducted feature engineering by extracting the relevant address info from the customer's entire address.
* **Model Training** - Implemented and optimized LogisticRegression model by implementing metrics like precision, recall and F1 Score to enhance robustness of the model.
* **Best Model** - **LogisticRegression** performed well on all metrics of **Precision, Recall and F1 Score**.


#### Usage
Install the Jupyter Notebook and access the data mentioned in the link in Data Source and execute the cells one by one.


#### Results
The model was able to process the customer details and predict the potential credit defaulters with an **$Accuracy$ of 98.5 %**.


#### Final Notes
This is a great project to learn:-
* Feature Engineering.
* Data Analysis.
* Data Transformation and Encoding.
* F1 SCore, Precision and Recall metrics.
* ROC - AUC curve for model comparison.
