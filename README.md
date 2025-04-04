# Data-Driven Customer Churn Insights Project | Power BI • SQL • Machine Learning
Customer churn is one of the most significant challenges facing modern businesses. As markets become increasingly saturated, understanding why customers leave—and more importantly, how to retain them—has never been more critical. Churn analysis provides a data-driven approach to tackling this issue by uncovering behavioural trends and service-related factors that influence customer decisions. By integrating predictive modelling and actionable insights, organizations can shift from reactive responses to proactive engagement, ensuring stronger customer relationships and improved business outcomes.

## Relevant Sectors & Stakeholders
Understanding customer attrition is vital across industries. This project, initially designed for the telecom sector, provides a scalable framework for churn analysis applicable to finance, retail, and healthcare. By leveraging data analytics and predictive modeling, businesses can proactively address churn, optimize retention strategies, and enhance customer lifetime value.
 
## Project Overview
This project focuses on Customer Churn Analysis for a telecom firm, utilizes SQL for ETL, leveraging Power BI for data visualization and Machine Learning (Random Forest) to identify churn patterns, predict future churners, and provide actionable insights. While the project is specific to telecom, its methodologies can be applied across industries such as retail, finance, and healthcare to enhance customer retention strategies.
 
## Data resources used
- Dataset
  - <a href="https://github.com/Shakeel-Data/Churn-prediction-Dashboard/blob/main/Customer%20data.csv">csv</a>
  - <a href="https://github.com/Shakeel-Data/Churn-prediction-Dashboard/blob/main/Prediction%20data.xlsx">xlsx</a>
- Queries
  - <a href="https://github.com/Shakeel-Data/Churn-prediction-Dashboard/blob/main/SQL%20queries.docx">queries</a>
- Power query
  - <a href="https://github.com/Shakeel-Data/Churn-prediction-Dashboard/blob/main/Power%20Query%20Transformation%20and%20Measures">DAX</a>
- Python
  - <a href="https://github.com/Shakeel-Data/Churn-prediction-Dashboard/blob/main/Python%20Codes%20for%20Machine%20learning%20-%20Random%20Forest.docx">codes</a>

# Dashboard
![Dashboard overview ](https://github.com/user-attachments/assets/6f467caa-e353-479c-a5b3-85beb3499fa3)
![Dashboard overview 2](https://github.com/user-attachments/assets/8de9bb5e-a779-4fe7-96a3-54215076590e)

## Project Goals
- **Visualizing and Analyzing Customer Data at different levels**:
  -	Demographic (Age, Gender, Marital Status)
  -	Geographic (State-wise churn rates)
  -	Payment & Account Information (Contract Type, Payment Method)
  -	Services Used (Internet, Security, Billing, etc.)

-  **Identifying Churner Profiles** and areas for marketing interventions.
   
-  **Predicting Customer Churn** using **Machine Learning (Random Forest)**.

## Key Metrics Used
   -	**Total Customers**
   -	**Total Churn & Churn Rate**
   -	**New Joiners**
   -	**Churn Rate by Demographics, Payment Method, Tenure, and Contract Type**

## Project Workflow
1. ETL Process in SQL Server
   -	Created a **database and imported CSV files** into SQL Server using the Import Wizard.
   -	Performed **data exploration** to check distinct values and nulls.
   -	Cleaned data by **removing null values** and inserted it into the **production table**.
   -	Created **views in SQL Server** to integrate with Power BI.

2. Power BI Data Transformation
   -  Added new calculated columns in **prod_Churn**.
   -	Created reference tables for:
      -	**Age Group Mapping**
      -	**Tenure Group Mapping**
      -	**Service Categories**

3. Power BI Measures & Visualization
   -	Developed **DAX measures** for key performance indicators (KPIs).
   -	Designed interactive dashboards to **analyze churn patterns** across various segments

4. Customer Churn Prediction Using Machine Learning (Random Forest)
   -	**Data Preparation** for the ML model.
   -	Installed necessary **Python libraries**.
   -	Imported data and performed **preprocessing**.
   -	Trained a **Random Forest Model** to predict churn.
   -	Used the model to **predict future churners**.
  
5. Power BI Visualization of Predicted Data
   -	Imported **predicted churn data** into SQL Server and Power BI.
   -	Created additional **DAX measures** to analyze predicted results.
   -	Designed a Churn Prediction Dashboard to visualize potential **churners and customer risk factors**.

## Business Impact
   -	Proactive Customer Retention : Identifying high-risk customers allows businesses to take preventive measures to reduce churn.
   -	Data-Driven Decision Making  : Visualization and predictive analytics help tailor marketing strategies.
   -	Improved Revenue Management  : Understanding churn trends can enhance customer loyalty programs and pricing models.

## Software & Frameworks
   *	SQL Server (Database & ETL)
   *  DAX (Power BI Calculations)
   *	Power BI (Data Transformation & Visualization)
   *	Python (Pandas, NumPy, Matplotlib) 
   *	Machine Learning algorithm (RANDOM FOREST)

## Conclusion & Next Steps
This Churn Analysis Dashboard provides a data-driven foundation for understanding customer attrition and its underlying causes. The insights reveal critical risk factors related to demographics, service preferences, contract types, and regional trends. Addressing these challenges through proactive retention strategies, service enhancements, and personalized engagement can significantly improve customer loyalty and reduce churn. By integrating SQL, Power BI, and Machine Learning, it provides a comprehensive solution for customer retention strategies.The methodology and tools used here can be extended to various industries to drive data-driven decisions and enhance customer experience.

This project underscores the value of data-driven decision-making in driving business growth. Future developments may focus on:
  -	Implement personalized retention offers for high-risk customers.
  -	Improve contract structures to encourage long-term commitments.
  -	Deploy real-time monitoring and alerts for early churn indicators.






   






