# Amazon Vine Analysis

## Overview

Use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. 

### Purpose

To analyze Amazon reviews written by members of the paid Amazon Vine program. 

## Results

![Screen Shot 2021-12-01 at 6 51 57 PM](https://user-images.githubusercontent.com/88747464/144335617-075dcbdc-16f2-43ba-851e-04fdc0e788e9.png)

![Screen Shot 2021-12-01 at 6 52 11 PM](https://user-images.githubusercontent.com/88747464/144335634-64483fce-57a1-4bd0-99ff-c6395d1843b5.png)

- Total Reviews: 49 in Vine and 151400 in non_Vine.

![Screen Shot 2021-12-01 at 6 54 52 PM](https://user-images.githubusercontent.com/88747464/144335658-dfc4f076-3adc-42e0-bd1c-9abf0be3f6de.png)

- Five-stars Reviews : 9 in Vine and 78061 in non-Vine.

![Screen Shot 2021-12-01 at 6 55 02 PM](https://user-images.githubusercontent.com/88747464/144335681-c77cac97-0de5-4fee-888f-8a676ee8c40f.png)

- Percentage: 18.4% in Vine and 51.5 in non-Vine

## Summary

I think there’s no positivity bias for reviews in the Vine program since the percentage of five-star reviews is only 18% in the Vine program compared to 51% in the non-Vine program. 

We can perform calculations on the percentage of the one-star reviews each for the Vine and non-Vine programs. Then we can analyze and determine if there are any other biases.
