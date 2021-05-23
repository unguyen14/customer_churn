# Telecom Customer Churn Analysis and Prediction

## Project Overview
This is an analysis about customer attention for a Telecommunication Company, based on the details about its customers' interactions with the services. The dataset is available on [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn), and the analysis is done on [Google Colab](https://colab.research.google.com/drive/14OyWXkSN-rphrcBmQ2g2C4G8jZahgmYr?usp=sharing).

## Main methods:
- Data Wrangling with pandas
- EDA with seaborn
- Feature Selection with SelectFromModel and SelectFromKBest
- Sample Balancing with RandomOverSampler
- Classification with Machine Learning algorithms, Ensemble Methods, and Multilayer Perception Neural Network   

## Dataset:
As mention above, the dataset is available on [Kaggle](https://www.kaggle.com/blastchar/telco-customer-churn). The dataset contains 7043 customers' records, with 21 recorded features.

| Variable | Description | Type |
| --- | ---  | --- |
| customerID | Customer ID | object | 
| gender | Whether the customer is a male or a female | object | 
| SeniorCitizen | Whether the customer is a senior citizen (1) or not (0) | int64 |  
| Partner | Whether the customer has a partner or not (Yes, No) | object |
| Dependents | Whether the customer has dependents or not (Yes, No) | object |
| tenure | Number of months the customer has stayed with the company | int64 |
| PhoneService | Whether the customer has a phone service or not (Yes, No) | object |
| MultipleLines | Whether the customer has multiple lines or not (Yes, No, No phone service) | object |
| InternetService | Customer’s internet service provider (DSL, Fiber optic, No) | object |
| OnlineSecurity | Whether the customer has online security or not (Yes, No, No internet service) | object |
| OnlineBackup | Whether the customer has online backup or not (Yes, No, No internet service) | object |
| DeviceProtection | Whether the customer has device protection or not (Yes, No, No internet service) | object |
| TechSupport | Whether the customer has tech support or not (Yes, No, No internet service) | object |
| StreamingTV | Whether the customer has streaming TV or not (Yes, No, No internet service) | object |
| StreamingMovies | Whether the customer has streaming movies or not (Yes, No, No internet service) | object |
| Contract | The contract term of the customer (Month-to-month, One year, Two year) | object |
| PaperlessBilling | Whether the customer has paperless billing or not (Yes, No) | object |
| PaymentMethod | The customer’s payment method (Electronic check, Mailed check, Bank transfer (automatic), Credit card (automatic)) | object |
| MonthlyCharges | The amount charged to the customer monthly | float64 |
| TotalCharges | The total amount charged to the customer | object |
| Churn | Whether the customer churned or not (Yes or No) | object |

## Project Directory:
```
| - customer_churn                                        
|   -- dataset                                              Contains the raw dataset 
|     --- WA_Fn-UseC_-Telco-Customer-Churn.csv
|   -- src                                                  Contains the source codes
|     --- Telco_Customer_Churn.ipynb
|   -- README.md                                            Project Overview
|   -- LICENSE                                              MIT License
```

## Future Considerations:
This analysis can be better visualized with additional tools like Tableau to make an easy-to-digest dashboad.
