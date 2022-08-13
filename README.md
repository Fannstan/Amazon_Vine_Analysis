# Amazon_Vine_Analysis

## Overview of Analysis:
The purpose of this project is to analyze Amazon reviews written by members of the Amazon Vine program. The Amazon Vine program charges a fee to companies to obtain reviews for their products from paid Amazon Vine members, who are paid to publish reviews of these products.  This analysis will extract a dataset of pet products reviewed by Vine(paid) and non-Vine(un-paid) members.  The dataset will be transformed, so that the data is cleaned up and categorized into separate tables. The dataset will then be loaded into pgAdmin for Companies like SellBy to use in their own analyses. 

## Results:
- Dataset loaded into Spark DataFrame:
![Spark_DataFrame](https://user-images.githubusercontent.com/103215123/184510896-e757d479-4103-4379-9077-7c52191cecfd.png)

### 4 DataFrames created from Pet-Products Dataset: 
1. customers_df
![customers_df](https://user-images.githubusercontent.com/103215123/184512708-f18648f4-2eb8-4385-8456-f140b5d4bb03.png)

2. products_df
![products_df](https://user-images.githubusercontent.com/103215123/184513357-fb9b3970-76f3-4c88-81dc-929385bcecd5.png)

3. review_id_df
![review_id_df](https://user-images.githubusercontent.com/103215123/184513741-2d6dd444-db9a-46a6-9dc8-9d065b405d91.png)

4. vine_df
![vine_df](https://user-images.githubusercontent.com/103215123/184514249-b485e2d6-18b9-4f1c-b99c-ae4bc7a81b24.png)

### Deliverable 2 
In the 2nd project Deliverable, the bias of Vine Reviews was analyzed to determine if paying for a Vine review made a difference in the percentage of 5-Star product reviews. The vine_df DataFrame was further transformed in the following ways:
- Filtered total vote count to those products that have a vote count that is greater than or equal to 20 votes
- Filtered to show all rows where the number of helpful votes divided by total votes is greater than or equal to 50%

The reviews were then separated by paid and unpaid reviews and put into the DataFrame below:
![ratings_df](https://user-images.githubusercontent.com/103215123/184515327-f1e3d28b-fc45-41a9-a83d-3d9a07ae8291.png)

- There are 170 ne reviews and 37,840 non-Vine reviews of pet products
- There are 

- 





