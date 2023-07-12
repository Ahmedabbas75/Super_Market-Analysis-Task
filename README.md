## 1- About the Dataset :
This dataset contains historical sales data from a supermarket company. The data includes records from three different branches over a three-month period.
____________________________________________________________________________
## 2- Data Description :
1. `Invoice ID`: Automatically generated identification number for sales slips.
2. `Branch`: Supercenter branch (identified as A, B, or C).
3. `City`: Location of the supercenters.
4. `Customer Type`: Type of customers, categorized as "Members" for those using a member card and "Normal" for those without.
5. `Gender`: Gender of the customer.
6. `Product Line`: Categorization of general items, including Electronic Accessories, Fashion Accessories, Food and Beverages, Health and Beauty, Home and Lifestyle, and Sports and Travel.
7. `Unit Price`: Price of each product in dollars ($).
8. `Quantity`: Number of products purchased by the customer.
9. `Tax`: 5% tax fee for customers.
10. `Total`: Total price including tax.
11. `Date`: Purchase date (Recorded from January 2019 to March 2019).
12. `Time`: Purchase time (from 10 AM to 9 PM).
13. `Payment`: Payment method used by the customer (Cash, Credit Card, or Ewallet).
14. `COGS`: Cost of goods sold.
15. `Gross Margin Percentage`: Gross margin percentage.
16. `Gross Income`: Gross income.
17. `Rating`: Customer satisfaction rating based on their overall shopping experience (rated on a scale of 1 to 10)
_________________________________________________________________________________
## 3- In Mind Questions
- General Questions related to the existence of
  - missing values?
  - wrong datatypes for columns?
  - complete duplicates in the data?
  - outliers in each column?

- Univariate Analysis
  1. Which `branch` has largest Sales numbers?
  2. Which `Gender` is greatly come to branches?
  3. What is the best-selling `product line` in the branches?
  4. Which `Payment` Customers preferred?
  5. Which `Customer type`comes to branches greater

- Bivariate Questions
  1. What is Relationship between `Gross income` and `Branches`?
  2. What is Relationship between `Branches` and `Product line`?
  3. What is Relationship between `Branches` and `Customer type`?
  4. What is Total Monthly transaction by `Gender`?
  5. What is `product line` generates most `income`?
______________________________________________________________________________________
## 4- Conclusion
- Reached Results from  Univariate Analysis
  - Branche `A` has largest Sales numbers
  - Most Gender Come to branches is `female`
  - Most sales in branches is `Fashion accessories`
  - Customers prefered to `Ewallet`,`cash` payments rather than `credit card`
  - Most Customers come to branches has `member card`

 - Reached Results from Bivariate Questions
   1. Branch `C` stands out slightly with higher income compared to Branch `A` and `B`. Despite Branch `A` having slightly higher sales, it is Branch `C`  that emerges as the most profitable branch in terms of gross income, there was no relationship between customer `ratings` and `gross income`
   2. `Fashion Accessories` and `Food and Beverages` were the most products. Therefore, must focus on these categories, with electronic accessories
   3. When `members` in Branch increased,Total of `gross income` increased
   4. When number of females increase, `Fashion accessories` Product line increase,  When number of male increase,`Health and beauty` Product line increase
   5. Gross income is highest in `food and beverages`



