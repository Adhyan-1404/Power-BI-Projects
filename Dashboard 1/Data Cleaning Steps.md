# Data Cleaning and Transformation before working on Dashboard

1. Deleting *Empty Columns* present in data named as **ind1** and **ind2**

‎ ![Image Alt](https://github.com/Adhyan-1404/Power-BI-Projects/blob/430fd5c2f0320e9fa2f096b7284af060bba3959f/Dashboard%201/Images/1%20(%20delete%20empty%20columns).jpg)

2. Replacing Values in **Returns** Column ( changing *#N/A* to *0* to maintain consistency as other option is *1* )

| Step 1 | Step 2 | Step 3 |
|---------|---------|---------|
| ![Image Alt](https://github.com/Adhyan-1404/Power-BI-Projects/blob/efce022082ebdb89940eb633f0cdf88f43d799a1/Dashboard%201/Images/2%20(replace%20na).jpg) | ![Image Alt](https://github.com/Adhyan-1404/Power-BI-Projects/blob/0687c505bf8908508cc05a321a097f8941f4a95a/Dashboard%201/Images/2.1.jpg) | ![Image Alt](https://github.com/Adhyan-1404/Power-BI-Projects/blob/0687c505bf8908508cc05a321a097f8941f4a95a/Dashboard%201/Images/2.2.jpg) |

3. Applied Steps

![Image Alt](https://github.com/Adhyan-1404/Power-BI-Projects/blob/bb311733a2ef7fb951c3ea175c765ac7c2eb4f97/Dashboard%201/Images/3.jpg)


# Dax Queries

1. Creating new column named **Avg-Delivery** to store the number if days between *Order Date* and *Ship Date*

   ![Image Alt](https://github.com/Adhyan-1404/Power-BI-Projects/blob/a4956d9de7132b842ba6c2c7b697dba8f344f37a/Dashboard%201/Images/4%20(%20new%20column%20using%20DAX%20).png)
