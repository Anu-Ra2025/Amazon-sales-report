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

8. Value of rating 
![image](https://github.com/user-attachments/assets/9a8d57d1-c721-488c-842a-f5720f6c4daa)
Most common rating: 4.1, appearing 1,261 times.

Other frequent ratings: 4.3 (1,151 times) and 4.2 (1,109 times).

Less common ratings: 2.3 (4 times) and 2.0 (2 times).

Unexpected symbol "|" appears 5 times, which might indicate data issues.

9. I got this product rating on Amazon by searching the provided product_id on their official website (amazon.in)

The rating is 3.9. So, I am going to give the item rating a 3.9 as well.

![image](https://github.com/user-attachments/assets/02ab3980-a3f9-4f90-bbd9-6f95e9ee8dc9)

![image](https://github.com/user-attachments/assets/49270744-ae7c-454c-bf33-225f13f5a30e)

10.  Change type of reating

![image](https://github.com/user-attachments/assets/64c79ddd-7a34-4242-8f54-0c097d832b14)

11. Top products by frequency

![image](https://github.com/user-attachments/assets/c001db27-3fa1-4ca6-8f20-86768dcc7ec8)

12.Top products by rating count

![image](https://github.com/user-attachments/assets/dcfd16e0-67fb-4f90-88fd-a6064014204c)

13. Average rating by category

![image](https://github.com/user-attachments/assets/34cecf30-b925-4f54-b1d6-c4589e413306)

14.  Correlation analysis and visualization

![image](https://github.com/user-attachments/assets/9ae0c6c4-6c56-48d9-ba45-e6f58e0fae91)


# # Based on the analysis:

1. Most Important Products (by frequency):
Top 10 Most Frequent Products:

![image](https://github.com/user-attachments/assets/7170ee92-3eb2-4ec6-9d1b-f2dcc31320b3)

![image](https://github.com/user-attachments/assets/307e5c56-0ef5-454b-bed9-e392eb0eb249)

Most Popular: Firestick Remote (16 mentions), suggesting frequent replacements or high sales.

Tech Dominance: Items like Acer TVs, HDMI cables, and USB chargers appear repeatedly, indicating high consumer interest in affordable electronics.

Household Needs: Products such as Activa Nutri Mixer and Lint Roller suggest practical everyday purchases.

Miscellaneous Essentials: Samsung Type-C Cable, KENT Water Filter, and various charging accessories highlight a need for reliability in gadgets.


2. Top Products by Rating Count:
Top 10 Products by Rating Count:

![image](https://github.com/user-attachments/assets/664c808c-22b6-403a-8059-7a2e2b378160)

![image](https://github.com/user-attachments/assets/1e1ede78-b555-420a-b24e-128102383aac)

Most Rated Product: AmazonBasics HDMI Cable leads with 426,973 ratings, showing high demand for connectivity accessories.

Tech & Audio Dominance: boAt earphones and JBL headphones rank high, signaling strong interest in affordable, quality audio gear.

Popular Electronics: Redmi 9 Activ Smartphone shows a significant rating count, suggesting a well-received budget-friendly phone.

Storage Essentials: SanDisk USB drives and SD cards appear multiple times, proving their necessity for data storage.

Household Utility: Pigeon Handy Chopper enters the mix, showing strong demand for compact kitchen tools.


3. Average Rating by Category:
Top 10 Categories by Average Rating:

![image](https://github.com/user-attachments/assets/27b61446-29fb-495b-8a38-e15fde18d57a)

![image](https://github.com/user-attachments/assets/5b71bd00-867b-4500-aa00-c6afb1661d3d)

Most Rated: AmazonBasics HDMI Cable dominates with 426,973 ratings, showing strong demand for affordable, reliable connectivity accessories.

Tech & Audio: boAt earphones and JBL headphones rank high, reflecting interest in budget-friendly, quality sound.

Electronics: Redmi 9 Activ Smartphone stands out as a popular, well-received choice for budget-conscious buyers.

Storage: SanDisk USB drives & SD cards appear frequently, reinforcing their necessity for data management.

Household Utility: Pigeon Handy Chopper shows significant interest in compact kitchen tools.


4. Correlation analysis and visualization

![image](https://github.com/user-attachments/assets/81bbe12a-470c-4fd3-8190-94d87b45ce9c)

![image](https://github.com/user-attachments/assets/2b1dec02-6a1b-432a-8725-093289183808)

The actual_price or discounted_price columns contain NaN (missing values).

The data might be stored as objects (strings) instead of numeric values.

There are inconsistencies, such as empty cells or non-numeric characters.





















