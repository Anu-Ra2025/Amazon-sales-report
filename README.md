#                      Amazon Sales Report

This dataset is having the data of 1K+ Amazon Product's Ratings and Reviews as per their details listed on the official website of Amazon
## Features:-
*	product_id
*	product_name
*	category	
*	discounted_price	
*	actual_price	
*	discount_percentage	
*	rating	
*	rating_count	
*	about_product	
*	user_id	
*	user_name	
*	review_id	
*	review_title	
*	review_content	
*	img_link	
*	product_link

## Import Libraries:-
*	Pandas: - Data manipulation and analysis
*  Numpy :- Numerical calculation
*	Matplotlib :- Visualized the Data


![image](https://github.com/user-attachments/assets/2b2c6311-c0b8-4461-b69c-0c00e5d3eff1)

# Data manipulation and analysis

## Load a CSV file then creating a dataframe

![image](https://github.com/user-attachments/assets/c93320e7-f5ae-4a7f-8816-4fcfb0844828)

Noiced taht the dataframe created with 1465 entries  with 16 columns.

## Let's see the column names

![image](https://github.com/user-attachments/assets/3cc9d25c-3594-4b81-b950-e61044716af1)

## Examine the columns along with their data types in detail by utilizing the info() function.

![image](https://github.com/user-attachments/assets/8fda046a-12c5-4ab1-8749-4bbce082a561)

![image](https://github.com/user-attachments/assets/1aad3e2c-1d88-4ff2-9ab5-be4770ae7063)

* Observation

1. There are 1465 rows and 16 columns in the dataset.

2. The data type of all columns is object.

3. The columns in the datasets are:
('product_id', 'product_name', 'category', 'discounted_price',
'actual_price', 'discount_percentage', 'rating', 'rating_count',
'about_product', 'user_id', 'user_name', 'review_id''review_title',
'review_content', 'img_link', 'product_link')

4. There are a few missing values in the dataset.

* Changing Data Types of Columns from object to float

![image](https://github.com/user-attachments/assets/5e1d5b05-6387-4873-8512-97fd5bbd278c)

5. Replace the missing values in the rating_count column with '000'

![image](https://github.com/user-attachments/assets/0a2e5a1d-101f-447a-af7e-8b479f9c198d)

![image](https://github.com/user-attachments/assets/a60671d9-4d38-4fe3-acb8-097faa181dce)

 
6. Drop duplicates product id  and Identify duplicate entries within the DataFrame.

![image](https://github.com/user-attachments/assets/8b166a96-958e-4331-b76b-699bde4c7a04)

![image](https://github.com/user-attachments/assets/3877e65c-8625-405e-ad79-1c729bdd8bab)

Data farme changed into 1351 enties * 16 columns.

7. Split user name, user ID, review ID and review_title.
  ![image](https://github.com/user-attachments/assets/3b4031f3-24f1-42d4-b02f-f52f0cc922de)
  ![image](https://github.com/user-attachments/assets/725e5307-a4f4-492d-b61f-5fd18ec36c3e)
  ![image](https://github.com/user-attachments/assets/b5e9e536-865f-4653-9e0f-7bfc63d52008)
data frame change into 7693 enties * 16 colomus 








