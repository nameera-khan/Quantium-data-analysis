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
