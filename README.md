## Data Analyst Portfolio
### About me
I am Mechanical Engineering graduated. Although I graduated from different field I have always wanted to try new path and explore for new opportunity, that is when i have an interests on data sciences. Ready to learn new things and experiences. I am very adaptable person and can work coordinately within team environment. I have fundamental in various skills and eager to use for objectives to be done benefitting the organization.

### Technical Skills
- SQL
- Python (_Basic_)
- Tableau 
- Microsoft Offices 

### Soft Skills 
- Problem Solving, Adaptabily, Creativity

## Education
Mechanical Engineering | Kasetsart University (_2023_)

### Work Experience
Intern at 

## Projects 
### 1.) Online Shopping Analysis
#### Introduction
This project is about online shopping analytic with insight of consumers' patterns, tendencies, decisions and particular preferences. With the data that provide variety of information such consumer's location, purchases history, product purchased preferences and their purchase frequency. This collection of data will further put in to analytic process to determine cosumers' shopping patterns and habits.

#### Objectives and Context
This project will mainly analyse on comsumer behavior and shopping habits, with the range of variable in the dataset can lead to multiple answers to these questions:
- What is the most purchase castegory?
- Does the gender affect how frequent consumer purchase a product?
- What state in United States purchase the most across all the region?
- What are the most trending item in every season of the year?

And put answer to the questions by developing a concise and coherent dashboard.

#### About the dataset
- The dataset in this project is from [Kaggles](https://www.kaggle.com/datasets/zeesolver/consumer-behavior-and-shopping-habits-dataset) formed by merge data 
- the dataset contain 18 columns in total: Customer ID, Age, Gender, Item Purchased, Category, Purchase Amount (USD), Location, Size, Color, Season, Review Rating, Subscription Status, Shipping Type, Discount Applied,
  Promo Code Used, Previous Purchases, Payment Method, Frequency of Purchases.
- The dataset is clean and no date-time value. The Frequency of Purchases is a reference to date-time value.

#### Tools Used
- Microsoft Excel, MySQL, Tableau

#### Approachs

#### 1. Data Gathering and Data Summary
Download the dataset from Kaggles. Use Excel the to summarize all the data, the data is already clean which means that the data have no NULL(blank row) and no duplicates. The column name has blank space, so it replaces with underscore for later usage in data manipulation. 

![1](https://github.com/user-attachments/assets/bf01def0-d8ba-488d-9667-b467794f700b)
**<p align="center">Fig. 1</p>**
#### 2. Data Exploratory 
Firstly, begin by reviewing all the data and columns. The dataset consist of 18 columns in total.After a thorough review. i decided to utilize only eight columns: age, category, purchase amount, location, previous purchase, frequency of purchases, season and review rating.

![image](https://github.com/user-attachments/assets/b444912d-25f8-4343-ad52-b48f6b11b919)

![image](https://github.com/user-attachments/assets/01fbf644-0de5-457d-8c96-e2ec912a042d) 

**<p align="center">Fig. 2</p>**

These columns will be determined for the main objective for this project. Since the primary objective of this project is to analyze consumer behavior and online shopping habits, I have determined that identifying the top-selling product categories across all purchases is a crucial factor in enhancing sales performance for each category.

![image](https://github.com/user-attachments/assets/6067c789-f575-4bbc-88df-938bde27705d) ![image](https://github.com/user-attachments/assets/c8fd4a09-fd00-4d13-9707-c55f0e5d58cf)

**<p align="center">Fig. 3</p>**

This also come along with a curiosity to which items in those category standout the most by evaluating the customer feedback through the rating review columns as shown in fig. 4.

![image](https://github.com/user-attachments/assets/ad83a317-a80c-4e67-9325-999142510e23)
**<p align="center">Fig. 4</p>**


At this stage, one factors become relevant. I have decided to put season as new factor for analyzing the product sales.
The term "season" refers to a specific period within a year, defined by time and date. In this context, it can be useful for developing a trend diagram. However, its applicability is limited to a one-year duration, as the dataset lacks precise date and time values (Fig. 5).

**<p align="center">Fig. 5</p>**

The dataset provide previous purchase and frequency in refer to rate of purchasing product of customer. As shown in fig (5) to fig(7) frequency and previous purchase number can be analyze as multiple variable together with other variable. For example in fig(5), gender is used as a grouping varible to differentiate the rate of purchase to the product.

fig 5
fig 6
fig 7

Lastly in this section, we explore more on a wide perspective. In this part we observe on the sales across all the region to later utilize for comparsion diagram, the data is as shown in fig 8. 

#### 3. Worksheet Build

In this project will consist of total of 5 worksheets that will answer all the questions state in the project objective. Begin with connect to the dataset table for particular worksheet. Worksheet 1 will present about the total purchases in which grouped by product category. Worksheet 1 uses pie chart to visulize the majority of the number toward the category as shown in fig 8.

fig 8

Worksheet 2 will visualize in frequency of purchase seperated by certain preiod of time and grouped by gender . In this worksheet, using barchart can easily show the grouped population while maintaining the comparison of the data as shown in fig 9

fig9


Worksheet 3 will visualize seasonal trends of an item.The trend chart can be shown in various chart but in this porject i decided to use sunbrust chart to focus the majority of number in both season ans item variable. the chart is as shown in fig 10.

fig 10

worksheet 4 wil focus on customer's feedback on a certain product. This fourth worksheet visualize on the overall item rating, worksheet shows both item that have the most rating within its own category. The rating is in the table as shown in fig 11.

fig 11


Lastly, the worksheet 5 will visualize the sales across all USA region but in this scenario Alaska is excluded. The grion comparison is as shown in fig 12.


fig 12





#### 4. Dashboard Build


#### 5. Conclusion

