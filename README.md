# Supply-Chain-Management-Dashboard-Power-Bi-
# Author : Md Nadeem Ashraf Ansari

An end-to-end Supply Chain Management dashboard for the automotive sector using Power BI, MS SQL Server, and Python. The project covers data extraction, cleaning, modeling, and visualization of key metrics like inventory, sales, and supplier performance to enhance decision-making and efficiency.

# Project Title

**A brief description of what this project**

Supply Chain Management for Cars in Power BI provides a comprehensive overview of the entire supply chain process for automotive companies. This includes tracking the flow of materials, components, and finished products from suppliers to manufacturers, distributors, and ultimately to customers.

Using **Python, MS SQL SERVER, and Power BI**, companies can visualize key supply chain metrics such as inventory levels, production schedules, delivery performance, and supplier quality. They can also analyze historical data to identify trends, optimize operations, and make informed decisions to improve efficiency and reduce costs throughout the supply chain.

# Supply Chain Management Dashboard

### Dashboard Link : [Click here to view the dashboard](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/Supply_Chain_Project.pbix)

## Problem Statement

The automotive supply chain involves complex processes and a large number of suppliers, manufacturers, distributors and customers. Tracking and optimizing this supply chain is critical for automakers to reduce costs, improve efficiency and deliver vehicles to customers on time. However, many automakers struggle with siloed data, lack of visibility, and difficulty analyzing key supply chain metrics.

### Flow of the project 
1. Flow of the Project
2. Project Architecture
3. Project BRD or FRD Documents
4. Data Gathering
5. Data Cleaning / Data Transformation
6. Data Modeling
7. Mockup Preparation
8. DAX Functions (DAX Calculations)
9. Create Visuals (For Dashboard)
10. Add Navigation

### Project Architecture

![image](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/images/proj%20aarch.png)

### Summary for Steps followed 
1. **Data Gathering**
According to the BRD document, we have to connect the SQL Server database with Kaggle APIs and bring data automatically into database by writing some python code. After then from database to the Power BI Desktop using ‘Get Data’ option. First we will gather and manipulate data using Pandas library in python.

Firstly go to the Kaggle website dataset name, ‘Supply chain management for Car‘ you can access it here. For python code we are going to use Jupyter notebook. Install the below libraries first.

2. **Data Cleaning**
Let’s transform data on Power Query Editor, we need to remove some unnecessary attributes from the table and just keep the important columns which we can use for visualization. Below is the list of columns we are gonna work on, and rest of it has removed.

3. **Making Sure to See All Data:**
   
   Usually, Power BI shows details for only a limited number of responses. We wanted to see details of entire dataset, so we made sure to look at the information provided.

4. **Modeling In Power BI**
After creating the date master table, establish the relationship between these two tables using modelling. Go to the model view tab and create one-to-many relationship between date columns in both the tables. Also create a new measure for ‘Total Sales’ and keep all the new measures in separate table called ‘DAX Measures’.

![image](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/images/MODELLING%20IN%20PBI.png)

6. **Data Visualization**
   
In our dashboard project, we are gonna create four different pages and implement navigation between all these four dashboard pages. The dashboard pages are Home, Order, Sales, and Customer View.

# Report Snapshot (Power BI DESKTOP & Python Code)

**Python Code**
![image](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/images/python%20code.png)

**Power Bi Dashboard Reprot**

![image](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/images/scm_home.png)

![image](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/images/order%20detail.png)

![image](https://github.com/N-ansari1902/Supply-Chain-Management-Dashboard-Power-Bi/blob/main/images/sales%20detail.png)

**Contributing**

Contributions to this project are welcome! If you encounter any issues or have suggestions for improvements, please feel free to submit a pull request.

<br />


**Contact**

📧 Email: nansari1902@gmail.com 

🌐 LinkedIn: [linkedin.com/in/nansari1902](https://www.linkedin.com/in/nansari1902)




