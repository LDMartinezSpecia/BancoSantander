# Santander Bank Product Data Exploration 
## Project Description <a name="installation"></a>
To view full commentary on project and the results, visit my Medium page [here](https://medium.com/@luisdm/credit-cards-and-crisp-dm-96a73b07e3e2). 
This project is intended to be an introduction into the data science process. In it, I pose some business questions, then take a set of data and answer those questions using visualization and an exploratory model. Although there is much potential to continue the analysis of this data set in many ways, this project gives the foundation for how to approach a data science project. 
The business questions that guide the analysis are the following:
1) What are the most common products used by our bank customers?
2) Do customers with longer bank tenure use credit cards more frequently?
3) Do value segments differ in the amount of products that they use?
4) What customer attributes are most predictive of credit card usage?
## Data Description <a></a>
Full data and Kaggle project for which it was made available can be found [here](https://www.kaggle.com/c/santander-product-recommendation/data).  
Data is comprised of customer descriptive attributes as well as binary indicators for each available product. The full data includes many records per customer as it has a time series component. For this project, I have used only the last available record for each customer with the products that they held at that time.
## File Descriptions <a></a>
The analysis is presented in three files: 

**santander_data_prep** – cleans and prepares the data for analysis. The output of this will be two separate files one of which is the source for the visualization and the other which is the source for the modeling. The input file for this file (train_ver2) comes from the training file available in the Kaggle link above. 

**santander_visualization** – in this file, I visualize the data to answer some of the business questions that are posed in the [article](https://medium.com/@luisdm/credit-cards-and-crisp-dm-96a73b07e3e2). 

**santander_model** – here, the data is further prepared for modeling by imputing missing values and coding categorical variables as numeric. Then a decision tree is trained and visualized to see which of the attributes in the data might be most predictive of customers who use credit cards.  
## Installation <a></a>
Some common data science packages are used in the notebooks, including numpy, pandas, matplotlib,  seaborn, and sklearn. I also use graphviz to visualize the final decision tree. 
