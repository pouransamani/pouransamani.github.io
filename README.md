# Data Scientist-Project Management Portfolio

## About me
  I have over a decade of experience in project management and geology and now transitioning into data analysis and business intelligence. With expertise in SQL, Python, ML, and Power BI and project management methodologies like Agile and Waterfall, I specialize in transforming complex data into actionable insights. My background in managing multidisciplinary geological projects, optimizing resource allocation, and leveraging data-driven decision-making allows me to bring efficiency and innovation to any team. I'm passionate about using analytics to solve real-world problems, and I’m excited to apply my skills in a role that combines data, strategy, and impact. I'd love to connect and explore how my experience can contribute to your team!
  
#### Techincal Skills: Python, ML, SQL, Tableau, Excel, MS Project, ERP(Oracle) 

## Projects
 - #### House Price Prediction
   - A home buyer describe his dream house. He might focus on the number of bedrooms or the beautiful yard. However, as it will discover in this project, many factors can influence a home's price beyond just its visible features. With a dataset containing 79 variables that describe nearly every aspect of residential properties in Ames, Iowa, the challenge will be to predict the final sale price for each home.
     
  - #### Objective 
The goal is to develop a predictive model applying regression problem by implementing and tuning algorithms such as Lasso, Random Forest, and Gradient Boosting to accurately estimate SalePrice for homes in the test dataset. Specifically, for each Id in the test set, the model should generate a corresponding SalePrice prediction.

Following the pipeline for doing this project
  ![image](https://github.com/user-attachments/assets/2bb38bfa-ea31-4122-978d-1b2822739318)

   - #### **Preprocessing and data cleaning**
     This step was performed by first checking for duplicate values. The metadata was carefully analyzed to better handle missing values. Therefore, three stages were applied: (1) NA values were replaced with None in the Garage, Pool, Basement, and Alley variables, (2) numerical features were imputed with the median, while categorical features were imputed with the mode, and (3) one feature was dropped.
   ![image](https://github.com/user-attachments/assets/9adfc931-0b74-41b8-bcea-71eb559bd296)


     - Outlier Detection
Scatter plot showed two extreme house price comparing with the rest of the data, I dropped these tow datapoints. 
![image](https://github.com/user-attachments/assets/7f730850-64b1-4a4d-8b13-c4a5f2978b9d)

     - Standardization and normalization
The numerical features were scaled to ensure they’re on a similar scale to improve model performance and reduce bias from large numbers. The SalePrice has a right-skewed distribution, normalization, especially using log transformation, makes the distribution more normal, improving regression results. 

     - Features engineering
Numerical features with senses of categorical were converted to categorical ones
Year related features were transformed to Age related features
Porch, Basement, Bath were Converted to total Square feet

      - Encoding
features with quality order were transformed via ordinal labeling
the rest categorical-nominals using dummy encoding were transformed

   - ### **Exploratory Data Analysis (EDA)**
     - To understand data, first exploratory data analysis was performed. This will provide insights that will be useful in building prediction models. the goal is: 
        - Investigate the relationship between each variables and house price and identify any patterns. For example, between the year of construction of a house and its price change. 
        - Analyze relationships between the features. This may reveal that certain features are redundant, and this would help the subsequent analysis.
    - Through this stage, histograms, correlation charts, regression scatter plots and bar graphs were creaated and they provided insightful understanding of the features.
![image](https://github.com/user-attachments/assets/84a3bdaa-3ab2-4920-81f6-dac0ba0ae3f9)

   - ### **Machine learning models with evaluation metrics**
For modeling one baseline model (Linear Regression) and four advanced models (Lasso, Ridge, Random Forest, and Gradient Boosting) were used. the resulit shows;
        - Lasso performs worse than the Base Model, as shown by its higher RMSE and lower R².
        - Ridge performs slightly better than Lasso but still worse than the Base Model.
        - Random Forest outperforms both Lasso and Ridge but still underperforms compared to the Base Model.
        - XGBoost performs significantly better than Lasso, Ridge, and Random Forest in terms of both RMSE and R², making it the best non-linear model. However, it still underperforms compared to the Base Model.      

![image](https://github.com/user-attachments/assets/766ce17e-2279-4a41-988e-d0a0e05dc3d2)



## Work Experience
- Project Coordinator @ WSP, Montreal 
  - Foster seamless collaboration among stakeholders, and assist in the development of project plans, timelines, and schedules
  - Maintain and organize project documentation, including contracts, approvals, meeting minutes, monthly status reports, third party contracts schedules, reports, and project files
  - Track project progress and budget (CPI & SPI indicators), invoices & expenditures to ensure alignment with overall portfolio processes, standards, methods, and tools
  -	Final review and ensure all project documentation is complete and stored appropriately
  - Achievements: Successfully optimizing resource allocation for engineering-mining projects, ensuring smooth project execution and alignment with objectives, monitoring project financial health leading to increased efficiency in budget and resource tracking through effective collaboration.
    
- Administrative Agent @ CIUSSS of South-Central Montreal, Verdun Hospital
  -	Schedule appointments, meetings, and other events
  -	Communicate by answering phone calls, responding to emails, and interacting with patients, nurses, and doctors
  -	Achievements: Streamlining patient reception processes, coordinating over 200 patient appointments weekly; and managing 100 patient calls daily, improving response time and increasing patient satisfaction by 10%.

 - Exploration Core Geologist @ Osisko Mining, Val d'Or, Quebec
   - Describe the drilling cores and create DHL logs, lithological description, core sampling
   - Write weekly drilling reports, compile analysis data and manage the drilling field database
   - Draw and interpret drill holes in section
  
 - Technical Geology Project manager @ Research Institute of Petroleum Industry (RIPI), Iran
   - Directed geological tasks, managing personnel, and allocated resources effectively to meet project requirements
   - Delivered oral presentations to stakeholders, providing clear and concise updates on project status and results
   - Achievements: Successfully led 12 geology-focused projects, improving overall project performance by 25% through effective resource coordination, planning, and timely execution, delivering quality results that met client expectations and project objectives, besides published 3 English articles related to geology and 3 conference presentations. 


## Education
  - AEC in Data Science @ Montreal College of Information Technology
  - Project Management Certificate @ HEC Montreal
  - Master’s degree in Petroleum Geology @ Shahid Chamran University-Iran (Comparative Evaluation, QC)
  -	Bachelor’s Degree in Geology @ Isfahan University-Iran (Comparative Evaluation, QC)
    
## Volunteering
  -	Customer Service, CIUSSS of South-Central Montreal @ Verdun Hospital
  - L'île des Soeurs Elementary School Activities @ Montreal
  - Child Care Board Member @ RIPI-Iran
  - Polio Eradication (giving polio drops to children) @ Saman-Iran
