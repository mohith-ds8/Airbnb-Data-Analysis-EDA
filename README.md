# Airbnb-Data-Analysis-EDA
![airbnb](https://user-images.githubusercontent.com/119489207/205582931-4a73dba0-8b62-49c2-8e5c-7901204ebd2a.png)

Airbnb is an online marketplace focused on short-term homestays and experiences. The company acts as a broker and charges a commission from each booking. It is based in San Francisco, California. <br> 
An Airbnb Dataset of 48895 entries and 16 variables was given to perform Exploratory Data Analysis (EDA)to find solutions for a particular business objective. <br>
The business objective was to provide the managment with insights that would help them break into hotel business in New York City under the brand name **Airbnb Stay**. <br>

The first step was to understand the data. Before that, the necessary libraries such as **Numpy, Pandas, Matplotlib & Seaborn** were imported. The data was loaded under the variable name *df* and first 5 rows were viewed to comprehend the data.
<br>
To understand each variable, all unique values were checked for each variable.

Upon inspection, it was found that some values were null. These null values in the Dataset were taken cared by replacing it with values best suited.
The columns also had ambigous values such as zero, which was taken cared by replacing those values by mean values of that particular subgroup and then the dataset was ready for EDA. 

Here are the list of EDAs performed on th dataset:
* A bar plot comparing the number of Airbnb units by neighbourhood group.
* A bar chart for neighbourhood group wise mean price and a box plot for all the price details.
* A bar polt showing top 10 neighbourhoods by unit count.
* A bar plot showing top 10 cheapest neighbourhoods by average price.
* A Countplot showing the count of room type by neighbourhood group.
* A bar plot showing top 10 hosts on Airbnb.
* A Scatter plot showing Airbnb unit availability vs their price.
* A Scatter plot to check how pricing affects number of reviews.

**After the EDA, we saw how each analysis contributed positively for the business objective to be achieved, and the same suggestions were made. They are:**

1. It is safer to stick with either of the top 2 neighbourhood group: Brooklyn / Manhattan.

2. As all the tourist attractions in NYC are present mostly in Manhattan & Brooklyn, guests prefer to stay close to this proximity, which in-turn allows hosts to charge higher prices.
Hence Airbnb should look at investing in any of these 2 neighbourhood groups.

3. It would be the best for Airbnb to locate their hotel in any one of the top 10 neighbourhoods within Brooklyn & Manhattan.

4. If Airbnb is thinking of starting off with a small investment, the provided 10 neighbourhoods would be best suited as they have low land price, and therefore will be able to charge customers in range of USD 50-60

5. If Airbnb has narrowed their choices to Brooklyn & Manhattan, it is best to invest in an entire home if they're going with Manhattan / invest in a single room if they're going with Brooklyn.

6. The top 10 people know the game better than anybody else, therefore Airbnb can get any one of them as a consultant at least for their first investment.

7. If Airbnb is targeting the luxury segment, they have to make sure to be available 365 days a year. These properties are empty most of the year & make their money back in short amount of time due to high pricing.

8. If Airbnb is planning in the luxury niche, they have to be on point as there's not much reviews and they've got to make sure every review they get is positive.

Outside of these results, I also mentioned that Airbnb as a platfrom had people's trust which it had earned all these years & they would have no problem with initial business.

But, as this property would be exclusively from Airbnb, the expectation would be at a much higher level compared to the elegance of the platform. And hence, the future of the hotel unit depends upon the reviews of the initial guests. Airbnb should go out of their way to serve these initial guests to get a good ratinh on their property which build momentum and drives business.
