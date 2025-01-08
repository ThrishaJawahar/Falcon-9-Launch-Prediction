**Falcon 9 Launch Prediction Capstone Project**


This project aims to analyze and predict Falcon 9 launch outcomes using machine learning techniques. The data includes various features related to Falcon 9 launches, including payload mass, launch site, mission outcomes, and more. The project involves cleaning the data, transforming it, performing exploratory data analysis (EDA), and building several machine learning models, such as Logistic Regression, Support Vector Machine (SVM), Decision Tree, and K-Nearest Neighbors (KNN). The models are then fine-tuned using hyperparameter optimization and evaluated based on their accuracy. The final goal is to identify the best-performing model to predict the launch success rate.

The steps performed in this project include:
- Data Collection and Web Scraping
- Data Preprocessing and Feature Engineering
- Exploratory Data Analysis and Visualization
- Model Building and Hyperparameter Tuning
- Model Evaluation and Comparison

---

### **Tasks List**:

#### **1. Data Collection and Web Scraping**
- Request the Falcon 9 Launch Wiki page from its URL
- Create a BeautifulSoup object from the HTML response and print the page title
- Extract all column/variable names from the HTML table header

#### **2. Data Preprocessing**
- Filter the Falcon 9 launch records from a dataset
- Handle missing values for the PayloadMass column and replace NaN values with the mean
- Handle missing values for the "Booster landing" column
- Filter Falcon 9 launches
- Data Transformation
- Data Merging and Joining
- Data Grouping and Aggregation
- Handling Categorical Data
- Time Series Analysis

#### **3. Data Analysis and Aggregation**
- Analyzing the number of launches at each site
- Calculate the number of launches for each orbit
- Calculate the number of occurrences of each mission outcome
- Create a list for landing_class based on whether the outcome is in bad_outcomes or not
- Calculating the mean of the success rate
- Count the number of launches from each launch site
- Define the set of landing outcomes that represent a complete failure to land
- Retrieve Unique Launch Sites
- Query to select 5 records where the launch site begins with 'CCA'
- Calculate Total Payload Mass for NASA (CRS)
- Query to calculate the average payload mass for booster version F9 v1.1
- Query to get the date of the first successful landing outcome on the ground pad (True RTLS)
- Query to list the names of the boosters that have successful drone ship landing and payload mass between 4000 and 6000
- Query to count the total number of successful and failed mission outcomes
- Find the Booster Version with Maximum Payload Mass
- Retrieve Launch Data for Failures on Drone Ship in 2015, Grouped by Month
- Count and Group Landing Outcomes between Specific Date Range

#### **4. Data Visualization**
- Visualize Flight Number vs Launch Site with hue='Class'
- Visualize Payload Mass vs Launch Site with hue='Class'
- Calculate success rate for each orbit type
- Create a scatter plot for FlightNumber vs Orbit
- Create a scatter plot for Payload Mass vs Orbit
- Yearly Trend of Launch Success Rate

#### **5. Feature Engineering and Model Preparation**
- Selecting the features required for prediction
- Standardize the Feature Data (X) after One-Hot Encoding
- Extract and Convert the 'Class' Column to a NumPy Array
- Split the Data into Training and Test Sets

#### **6. Model Building and Hyperparameter Tuning**
- Perform Grid Search for Logistic Regression Hyperparameter Tuning
- Perform Grid Search for Support Vector Machine (SVM) Hyperparameter Tuning
- Perform Grid Search for Decision Tree Hyperparameter Tuning
- Perform Grid Search for K-Nearest Neighbors Hyperparameter Tuning

#### **7. Model Evaluation and Performance Comparison**
- Calculate accuracy on the test data for Logistic Regression
- Calculate the accuracy on the test data using the best model from GridSearchCV for SVM
- Calculate the accuracy of the best model on the test data for Decision Tree
- Calculate the accuracy of the KNN model on the test data using the score method
- Compare Model Performance and Identify the Best Model Based on Accuracy

#### **8. Final Output and Conclusion**
- Visualize Launch Sites and Outcomes on a Map with Distance Calculation
- Find the number of records in the test sample
- Display the best performing model
- Display the best parameters and scores from each GridSearchCV run

#### **9. Additional Information**
- Query to select 5 records where the launch site begins with 'CCA'
- Query to count the total number of successful and failed mission outcomes
- Find the Booster Version with Maximum Payload Mass

---


