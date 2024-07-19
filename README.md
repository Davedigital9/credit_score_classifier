# **Credit Score Classification with Machine Learning**

## **Overview**
This project focuses on building a machine-learning model to classify credit scores. Credit score classification is crucial for financial institutions to determine the creditworthiness of individuals. By using machine learning techniques, we can automate and improve the accuracy of credit score assessments. There are three credit scores that banks and credit card companies use to label their customers:
1. Good
2. Standard
3. Poor

The classification will be done in consideration of several factors represented by the columns in the dataset. Some of these factors include annual salary, number of bank accounts, number of credit cards, etc. These factors can influence how high or low your credit will be and the category it falls into. The algorithm works with a combination of the analysis of these factors together to give accurate results.

Box plots (also known as Box and Whisker plots) will be used to represent the visualization of the analysis. It is a way to display data and the spread of the data. It shows a 5-key point description of the data. That is the Minimum value, the first Quartile, the Median (2nd Quartile), the third quartile, and the Maximum value. 

![1_boxplots](https://github.com/user-attachments/assets/3a94d8df-51fa-422e-9c8f-927a542abc5c)

For more information on Box plots: 
- https://youtu.be/nV8jR8M8C74?si=lbtOiee5CQ_0VogK
- https://youtu.be/vQ0L-gSUyvc?si=4W75YBA-JGLZAH60                                  

## **Purpose**
The primary purpose of this project is to develop a reliable and efficient model to classify credit scores based on various features. This classification helps in predicting the risk associated with lending to a particular individual. 

## **Features**
- Data Preprocessing: Handling missing values, encoding categorical variables, and scaling numerical features.
- Model Training: Using machine learning algorithms to train the classification model.
- Model Evaluation: Assessing the performance of the model using metrics like accuracy, precision, recall, and F1-score.
- Prediction: Using the trained model to predict credit scores on new data.

## **Technologies Used**
- Python: Programming language used for developing the project.
- Pandas: Library for data manipulation and analysis.
- Scikit-Learn: Machine learning library for model building and evaluation.
- Matplotlib & Seaborn: Libraries for data visualization.
- Jupyter Notebook: Interactive environment for running the code and visualizing results.

## **Data Exploration**
The dataset has many features that can train a Machine Learning model for credit score classification. This features refer to the factors that can affect the credit score. The box plot of these features will be displayed as well as their effect on the model.

### Occupation
![occuption_plot](https://github.com/user-attachments/assets/fbf60aa7-bd25-40c4-a26d-c95526726b12)

There’s not much difference in the credit scores of all occupations mentioned in the data.

### Annual Income
![annual_income_plot](https://github.com/user-attachments/assets/2aa456d5-1b81-41ec-9bbc-6a05b8388b35)

According to the above visualization, the more you earn annually, the better your credit score is.

### Monthly Inhand Salary
![salary_inhand_monthly_plot](https://github.com/user-attachments/assets/b9c5d800-eb3f-4c86-8a92-7636fa4af637)

Like annual income, the more monthly in-hand salary you earn, the better your credit score will become.

### Number of Bnak Accounts
![no_bank_accounts_plot](https://github.com/user-attachments/assets/fabfe84b-55d1-4a30-8de1-133ef4dacd22)

Having over five accounts is bad to a healthy credit score. It is advisable for an individual to maintain only 2 – 3 bank accounts. Therefore, having multiple bank accounts does not enhance credit scores positively.

### Number of Credit Cards
![number_of_credit_cards](https://github.com/user-attachments/assets/0d600e22-14d6-4ed0-9a61-4a6161b824ad)

Similar to the number of bank accounts, having additional credit cards will not enhance your credit ratings. Maintaining 3 – 5 credit cards is beneficial for your credit score.

### Average Interest Rates
![avg_interest_rates](https://github.com/user-attachments/assets/694d6bc8-7070-479c-802e-1b52aad89bce)

If the mean interest rate ranges from 4 to 11%, the credit rating is considered favorable. However, having an average interest rate exceeding 15% negatively impacts your credit scores.

### Number of Loans Taken By the person
![no_of_loans_taken](https://github.com/user-attachments/assets/b4eeab69-5d9a-4f08-bfd6-6dc019757d10)

To maintain a favorable credit rating, it is advisable not to acquire more than 1 – 3 loans simultaneously. Exceeding three loans concurrently will have adverse effects on your credit scores.

### Average Number of Days Delayed for Credit card Payments
![no_of_days_delayed_on_credit_card_pay](https://github.com/user-attachments/assets/318da2d9-b7c0-4b22-a84a-c3c4d5eaa3c9)

You can delay your credit card payment 5 – 14 days from the due date. Extending your payments beyong 17 days from the due date will impact your credit scores negatively.

### Number of Delayed Payments
![no_of_delayed_payments](https://github.com/user-attachments/assets/0c58f71a-0a0d-4aa1-9e5c-a021b74d46c0)

Delaying payments by 4 – 12 months from the deadline won't impact your credit ratings. However, delaying payments by more than 12 months from the deadline will have a negative effect on your credit scores.

### Outstanding Debt
![outstanding_debts](https://github.com/user-attachments/assets/b430e135-1303-45f9-af6f-4f522b60d642)

A debt ranginf from $380 – $1150 will not affect your credit scores. However, consistently owing over $1338 will have a negative effect on your credit scores.

### Credit Utilization Ratio
![credit_utilization_ratio](https://github.com/user-attachments/assets/93443d26-697d-422f-9246-c5c64a51fc0b)

Credit utilization ratio means your total debt divided by your total available credit. Following the above figure, your credit utilization ratio doesn’t affect your credit scores.

### Credit History Age
![credit_history_age](https://github.com/user-attachments/assets/0f8af24d-49b2-41ee-b030-1d8195378349)

Having a long credit history results in better credit scores.

### Total Number of EMIs per months
![total_no_of_EMIs_monthly](https://github.com/user-attachments/assets/09b797ad-2ecb-49f2-a1ac-b2bfd59c7bee)

The number of EMIs you are paying in a month doesn’t affect much on credit scores. EMI stands for Equated Monthly Installment.

### Amount Invested Monthly
![monthly_investment](https://github.com/user-attachments/assets/d9a867e6-4439-49e6-a8d9-f76946c4bf87)

The amount of money you invest monthly doesn’t affect your credit scores a lot.

### Monthly Balance left
![monthly_balance_left](https://github.com/user-attachments/assets/3e68ccb8-40fc-45bb-8d4a-dad849738ea0)

Having a high monthly balance in your account at the end of the month is good for your credit scores. A monthly balance of less than $250 is bad for credit scores.

## **Installation**
To run this project locally, follow these steps: 
**Clone the repository:** git clone https://github.com/Davedigital9/credit-score-classification.git 
**Navigate to the project directory:** cd credit-score-classification
**Install the required dependencies:** pip install -r requirements.txt

## **Usage**
**Open the Jupyter Notebook:** Jupyter notebook
Run the notebook cells to preprocess the data, train the model, and evaluate its performance.

## **Results**
The model's performance is evaluated based on various metrics, and the results are visualized using plots. The accuracy of the model and other evaluation metrics will be displayed in the notebook.

**Contributing**
Contributions are welcome! If you have any suggestions or improvements, please create a pull request or open an issue.

**Contact**
For any questions or inquiries, feel free to contact me at d909dave@gmail.com
