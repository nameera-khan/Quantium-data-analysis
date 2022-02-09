# Quantium-data-analysis

- Exploratory data analysis of market dataset

The analysis consists of fields with customer transaction details in a separate dataframe and customer behaviour in another (initially). The first task involves exploratory data analysis of the dataset which includes the following steps:
- Importing necessary modules 
- Summary statistics 
- Data visualisation for customer insights
- Data mining using apriori algorithm to dive deep into customer segmentation by merging the transactions and customer behaviour dataset. 
- Following data mining, affinity analysis of the brands with customer categories. 
- Deep diving into trends set by the transactions on monthly basis. 

The peculiarities of apriori algorithm are that it uses the items and quantity purchased to calculate support, confidence and lift. However, in this situation, the analysis depends only on chip purchases, 
hence, providing no other product in the customer basket. Thus, only the likelihood of the customer purchasing a brand was calculated (support) and not the rest. 

- Task 2 - Experimentation and uplift test 
This task involves choosing a null-hypothesis against 3 trial stores that have been selected by the client. 
- The control stores have been chosen based on the scores calculated using correlation and magnitude difference for total sales and number of customers in each store. The store with a final score that is close to the trial store with a miniscule difference was chosen as the control store. 
- The three trial stores chosen by the client were : 77,86 and 88. 
- The assessments for these stores were done against the control stores to generate the sales during a trial period of 2019-02 and 2019-04. 
