# Seattle Airbnb Data Analysis

A Blog post for this project is on Medium. You can check here [A deep look into Seattle Airbnb business](https://medium.com/@ziyu1211/a-deep-look-into-seattle-airbnb-business-42c2e1b0e7ab).

### Description
This project is to analyse the '[Seattle Airbnb Open Data](https://www.kaggle.com/datasets/airbnb/seattle/data)" from kaggle. The analysis focused on 3 questions and I use both EDA and Modeling to find answers to 3 questions.
There are 3 parts in this project.

### 1.Data Exploration
In this part, I briefly check 3 datasets, the rows and columns in the datasets, and check if there are nulls or duplicates in rows or columns

### 2. Data wrangling
In this part,I clean up the 'listing' dataset,and prepare 3 sub-datasets for each of my questions. 


### 3. Data analysis
In this part,I answer my questions. For the first 2 questions, I use EDA to find the answer, and for question 3, I train a model and assessing its accuracy

### Questions and Findings
* **Question1: What kinds of property are the favorite type in airbnb?**
>From host side, they prefer to list 'entire home/apartment' as room type. House and apartment are their favorite listing property type.

>From customer side, they are more willing to write reviews for property type 'Cabin' and room type 'Private room'
* **Question2:Which neighborhood are most popular?**
>Based on the zipcode, 98122 area is the most popular neighborhood for listings.
* **Question3:How well can I predict the price(in airbnb) of a property based on the data?**
>Based on the model results, the best R-square for test data is 0.527. The best model use 19 out of 38 features as predictors.


#### References:
>Function name: `find_optimal_lm_mod(X, y, cutoffs, test_size = .30, random_state=42, plot=True)`
> 
>Lesson Title: `Putting It All Together - Solution.ipynb` 
> 
> Sources Code Name: `AllTogether.py`
> 
>Author: Udacity "Introduction to Data Science"
> 
>Date: 2022
> 
>Code version: N/A
> 
>Availability: [Udacity-Intro-to-data-secience](https://learn.udacity.com/nanodegrees/nd025/parts/cd0017/lessons/e630cd91-988b-46bb-ad6c-4a0737172630/concepts/1dd4a20f-c4ad-474a-ab56-14f7050affb9)
