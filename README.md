# Data Scientist Portfolio
### Techincal Skills: Python, ML, SQL, Tableau, Excel, MS Project, ERP(Oracle) 
### Projects
 - House Price Prediction
   - A home buyer describe his dream house. He might focus on the number of bedrooms or the beautiful yard. However, as it will discover in this project, many factors can influence a home's price beyond just its visible features. With a dataset containing 79 variables that describe nearly every aspect of residential properties in Ames, Iowa, the challenge will be to predict the final sale price of each home.
  - This project will give hands-on experience in:
    - Creative Feature Engineering: Identifying and creating new features that could improve model’s performance.
    - Advanced Regression Techniques: Implementing and tuning models such as Random Forests and Gradient Boosting to make accurate predictions.
- #### Loading libraries and reading the data
    - This section loads the train and test datasets using pandas.  
      - The train_test column created to differentiate between training and test data.
      - The test data does not include the actual SalePrice column in the test dataset, it is set to NaN because this is what we need to predict. Adding this column ensures consistency in the structure of both datasets, making them easier to combine.  
      - Both datasets concatenated into a single dataframe for `consistent preprocessing`.
      - There are 1460 instances of train data and 1459 of test data. Total number of attributes equals 81, from which 36 is quantitative, 43 categorical + Id and SalePrice.
- #### Preprocessing and data cleaning
     - Handling Duplicat
     - Handling missing values
       
     ![image](https://github.com/user-attachments/assets/04f6ea8a-d91a-4ab9-a472-5d4ba6a9fbd6)
  
 - **Insights from missing data**
     - According to the bar chart: 35 features have missing values, 6 features are 50% and above, 23 features are below 5% and 6 features are between (5-20)%.
     - Missing data was computed according to median and mode methods.
     - To fix the 35 predictors that contains missing values. When I go through each feature having NAs there are multiple variables that relate to Pool, Garage, and Basement, so I deal with them as a group referring to meta data which shows definiton of variables and make it clear that NA in that feature doesn't mean missed value, it means that house dosn't have Pool, Garage, or Basement, so it will be replaced with NONE.





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


### Education
  - AEC in Data Science @ Montreal College of Information Technology
  - Project Management Certificate @ HEC Montreal
  - Master’s degree in Petroleum Geology @ Shahid Chamran University-Iran (Comparative Evaluation, QC)
  -	Bachelor’s Degree in Geology @ Isfahan University-Iran (Comparative Evaluation, QC)
    
### Volunteering
  -	Customer Service, CIUSSS of South-Central Montreal @ Verdun Hospital
  - L'île des Soeurs Elementary School Activities @ Montreal
  - Child Care Board Member @ RIPI-Iran
  - Polio Eradication (giving polio drops to children) @ Saman-Iran
