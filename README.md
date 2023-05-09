# Telcom-Churn-EDA-and-Modelling
![What Is a Good Customer Churn Rate? | ChartMogul](https://chartmogul.com/blog/wp-content/uploads/2022/02/blogWhat_s-a-good-Customer-Churn-Rate-1200x500.jpeg)

II have taken the Telcom Churn Dataset and tried to do an EDA (Exploratory Data Analysis) to and visualize them and fitted a Decision Tree Classifier which predicts the weather the customers have churned or not.

## Exploratory Data Analysis and Decision Tree Classifier on Telecom Churn Dataset

Telcom dataset that you described. The dataset contains information on customers of a telecom company, including their demographic information such as gender and age, as well as their account information such as the services they subscribe to, their tenure with the company, and their billing information. The target variable in the dataset is "Churn," which indicates whether a customer has terminated their service with the company.

**This project covers the EDA of the Telecom Churn dataset through which i suggested the business how to reduce churn by observing the insights i got from the analysis. After the EDA i have also fitted a Decision Tree Classifier which will predict weather the customer churn  is "Yes" or "No".**

## Telecom Churn Data
Here are the details about each variable in the Telecom dataset:
-   `customerID`: A unique identifier for each customer.
-   `gender`: The gender of the customer (either "Male" or "Female").
-   `SeniorCitizen`: Indicates whether the customer is a senior citizen (1) or not (0).
-   `Partner`: Indicates whether the customer has a partner or not (Yes or No).
-   `Dependents`: Indicates whether the customer has dependents or not (Yes or No).
-   `tenure`: The number of months the customer has been with the company.
-   `PhoneService`: Indicates whether the customer has a phone service or not (Yes or No).
-   `MultipleLines`: Indicates whether the customer has multiple lines or not (Yes, No, or No phone service).
-   `InternetService`: Indicates the type of internet service the customer has (DSL, Fiber optic, or No).
-   `OnlineSecurity`: Indicates whether the customer has online security or not (Yes, No, or No internet service).
-   `OnlineBackup`: Indicates whether the customer has online backup or not (Yes, No, or No internet service).
-   `DeviceProtection`: Indicates whether the customer has device protection or not (Yes, No, or No internet service).
-   `TechSupport`: Indicates whether the customer has tech support or not (Yes, No, or No internet service).
-   `StreamingTV`: Indicates whether the customer has streaming TV or not (Yes, No, or No internet service).
-   `StreamingMovies`: Indicates whether the customer has streaming movies or not (Yes, No, or No internet service).
-   `Contract`: The type of contract the customer has (Month-to-month, One year, or Two year).
-   `PaperlessBilling`: Indicates whether the customer has paperless billing or not (Yes or No).
-   `PaymentMethod`: The payment method the customer uses (Electronic check, Mailed check, Bank transfer (automatic), or Credit card (automatic)).
-   `MonthlyCharges`: The amount charged to the customer monthly.
-   `TotalCharges`: The total amount charged to the customer since they joined the company.
-   `Churn`: Indicates whether the customer has churned (i.e. cancelled their service) or not (Yes or No).

## We will structure the code as follows

1.  Loading the data
    
2.  Preparing the data
    
3.  Exploratory Data Analysis
    
4.  Building the model and accuracy analysis
    
5.  Final Analysis of the model
    

## These are some of the insights

![Premium Vector | Business concept chart flat illustration](https://img.freepik.com/premium-vector/business-concept-chart-flat-illustration_9041-226.jpg?w=2000)

- Both male and female customers, but there are slightly more male customers in the company.
-   A significant number of customers are senior citizens.
    
-  About half of the customers have a partner, and a similar number have dependents.

-  The average tenure of customers is approximately 32 months.
-   The average monthly charge is $70, which is higher than the mean, indicating that the distribution is slightly skewed towards lower values.

- The tenure of customers varies widely, with some customers having been with the company for only a few months and others having been with the company for several years.
    
- Most customers have a phone service, and a significant number have multiple lines.
    
- Fiber optic is the most common type of internet service, followed by DSL.
    
 -  A significant number of customers do not have online security, online backup, device protection, or tech support.
    
  -  Streaming TV and streaming movies are relatively popular services among customers.
  -  Month-to-month contracts are the most common type of contract.
    
-  A majority of customers have paperless billing.
    
-  Electronic check is the most popular payment method.
    
-  Monthly charges vary widely, with some customers paying as little as $18 per month and others paying over $118 per month.
    
-  Total charges are positively correlated with tenure and monthly charges.
    
-  About 27% of customers have churned (i.e. cancelled their service).

## Decision Tree Classifier
![Introducing TensorFlow Decision Forests — The TensorFlow Blog](https://1.bp.blogspot.com/-Ax59WK4DE8w/YK6o9bt_9jI/AAAAAAAAEQA/9KbBf9cdL6kOFkJnU39aUn4m8ydThPenwCLcBGAsYHQ/s0/Random%2BForest%2B03.gif)

After fitting the  **Decision Tree Classifier**  model on our data and comparing the results of the Training and the Testing data we were able to observe that our model predicted the Churn with an accuracy of 78% which can vary depending on the data and the fitting of the model.

To take a look at the models, feel free to look at the  `ipnyb`  file to explore more.

![10,100 Thank You Videos and HD Footage - Getty Images](https://media.gettyimages.com/id/1308979937/video/thank-you-animated-retro-banner-video-overlay-in-black.jpg?s=640x640&k=20&c=GCGI-SRNWcljUkuavrPD3DUO29KsYycGp-b8qqaqGFQ=)

