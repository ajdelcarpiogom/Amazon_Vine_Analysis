# Amazon_Vine_Analysis

## Analysis Overview

The purpose of this project is to analyze the Amazon Vine program and determine whether there is a bias toward favorable reviews from Vine members.
For this analysis I used PySpark in order to perform the ETL process to extract the dataset, manipulate the data, connect to the AWS RDS instance, load data into pgAdmin4 and visualize part of the dataset.
We focused on the US reviews for sports.

## Results

After filtering the data in order to find our answers, here are the questions we can answer:
 - How many Vine reviews and non-Vine reviews were there?
![image](https://user-images.githubusercontent.com/57331058/148879152-2cb3a124-5aa7-4b13-8417-e526d38fb855.png)
![image](https://user-images.githubusercontent.com/57331058/148879197-185b2a5a-f521-4c82-8416-1a1218ae30ce.png)

 - We can see above that we had 61,948 reviews in total. We had 334 paid reviews and 61,614 unpaid reviews.

  - How many Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/57331058/148879431-94be36f0-ed58-448d-ac67-bdff467ad16a.png)

  - 139

  - How many non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/57331058/148885482-72453289-3268-410a-baee-e1315895fc02.png)
  - 32,665
  
  - What percentage of Vine reviews were 5 stars? 
![image](https://user-images.githubusercontent.com/57331058/148886382-8af875c7-6497-4264-97e7-8c233bd3ae33.png)

  - 41.62%
  
  - What percentage of non-Vine reviews were 5 stars?
![image](https://user-images.githubusercontent.com/57331058/148886450-03f2451a-1091-459b-b270-f45e7a79a4d9.png)

  - 53.02%

## Summary

After looking at the data, we can see that 41.62% of the Vine program were 5 star reviews and the non-Vine reviews were 53.02%. Due to this information, we cannot conclude that there's a positivity bias for reviews in the Vine program.
Other statistics we can look at in order to make a better informed decision would be looking at the mean, mode, and standard deviation of both Vine and non-Vine reviews and that could help us see a bigger picture of whether there could be a positivity bias for reviews in the Vine program.
