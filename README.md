# amazon_vine_analysis

## Overview of the analysis:
- In this project I have picked a data set from amazon reviews regarding video games and used Pyspark to perform the ETL process by extracting the data, transforming the data, and connecting to the database that was generated for me through the AWS webserver. With the reviews, my goal is to try and determine if there is favorable review bias from the Vine members of our data set.

## Results: 

## How many Vine reviews and non-Vine reviews were there?
- There were a total of of 94 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset. Which gives us a total of 40,565

![Screen Shot 2021-07-04 at 20 22 20](https://user-images.githubusercontent.com/79731109/124406210-4d382700-dd06-11eb-930d-2c1915881f68.png)


## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
- In the data set, there were a total of 48 5-star vine reviews
- In the data set, there were a total of 15,663 5-star non-vine reviews

![Screen Shot 2021-07-04 at 20 23 08](https://user-images.githubusercontent.com/79731109/124406223-532e0800-dd06-11eb-902e-6a16d212153b.png)


## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
- 51.06% of the five_star reviews were vine
- 38.70% of the five_star reviews were non-vine

<img width="991" alt="Screen Shot 2021-07-04 at 20 23 40" src="https://user-images.githubusercontent.com/79731109/124406576-5b3a7780-dd07-11eb-8043-f24c106a3865.png">



## Summary: 
51% of the reviews in the Vine program were 5 stars reviews whereas the percentage in the non-Vine reviews is only 39%. This describes a positivity bias for reviews in the Vine program.
Additionally we could analyse the statistical distribution (mean, median and mode) of the star rating for the Vine and non-Vine reviews.
