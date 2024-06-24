# **Problem Statement**

You are working for a new-age insurance company that employs multiple outreach plans to sell term insurance to customers. Telephonic marketing campaigns remain one of the most effective ways to reach out to people, but they also incur a lot of cost. Therefore, it is important to identify customers who are most likely to convert beforehand so that they can be specifically targeted via calls. The goal of this project is to build a machine learning model that predicts whether a client will subscribe to the insurance.

#  **Features**
* age: (numeric)
* job: type of job
* marital: marital status
* educational_qual: education status
* call_type: contact communication type
* day: last contact day of the month (numeric)
* mon: last contact month of the year
* dur: last contact duration, in seconds (numeric)
* num_calls: number of contacts performed during this campaign and for this client
* prev_outcome: outcome of the previous marketing campaign (categorical: "unknown", "other", "failure", "success")
#  **Output Variable (Desired Target)**

y - has the client subscribed to the insurance?

#  **Minimum Requirements**

It is not sufficient to just fit a model; the model must be analyzed to find the important factors that contribute to the conversion rate. AUROC must be used as a metric to evaluate the performance of the models.

#  **Introduction**

This project was completed as part of the final project for the Master Data Science course by GUVI. The goal was to predict whether a client will subscribe to the insurance based on historical marketing data of the insurance company.

#  **Data Preprocessing**

The data was loaded and preprocessed, including handling missing values and encoding categorical features.

#  **Exploratory Data Analysis**

Data visualization and exploratory data analysis were performed to gain meaningful insights into the dataset.

#  **Model Building**

The initial model used was logistic regression, which achieved a good AUROC score. However, to build a more reliable model considering the domain context, a decent F1 score was required.


