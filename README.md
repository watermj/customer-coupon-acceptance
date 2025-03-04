# customer-coupon-acceptance
Practical example from Berkeley Haas AI/ML 5.1

Author: Jason Waterman

Python notebook: [prompt.ipynb](https://github.com/watermj/customer-coupon-acceptance/edit/main/prompt.ipynb)

Dataset: [coupons.csv](https://github.com/watermj/customer-coupon-acceptance/edit/main/coupons.csv) 

### Problem 1:  
- Initial examination of dataset and data cleanning of dataset coupons.csv.

Results:
- Removed 'car' column as not enough data provided
- Fixed misspelling of column heading for passenger
- Overall usage of coupons is 57%. 

### Problem 2:
- Investigating the Bar coupon usage.

Results & Observations:
- Ratio of acceptance for customers that visit bars > 3 times per month is 77%.
- Age does not seem to be a determining factor for bar coupon usage.
- Rate of acceptance for customers who visit bars > 3 times per month had passengers that were not Kid(s), and occupations that were not Farming Fishing & Forestry =  43%
- There is a significant decrease in the acceptance of bar coupons from customers that did not travel with kids or work in Farming, Fishing, & Forestry.
- Usecase 1: Rate of acceptance for customers who visit bars > 3 times per month, had passengers that were not Kids, and were not widowed =  43%.
- Usecase 2: Rate of acceptance for customers who visit bars > 3 times per month, and are under 30 =  49%.
- Usecase 3: Rate of acceptance for customers who go to cheap restaurants > 4 times per month and have income less than $50k =  45%.
- The rate of coupon acceptance for customers for each of these use cases is about the same ~ 45%. Which is slightly lower than the overall acceptance rate of 57%.
- There is a high correlation between customers that accept bar coupons and frequently go to bars. That is the dominating factor independent of age, occupation, or income.

### Problem 3:
- Investigating the Expenseive Restuarant coupon usage.

Results & Observations:
- Overall usage rate of coupons to Expensive restuarants (>$50) is 44%. This is slightly lower than the overall coupon usage of 57%.
- Customer income does not seem to be a significant factor for usage of expensive restuarant coupons.
- Longer coupon expiration periods significantly increases the usage of expensive restuarant coupons.
- Customers who are single or have a partner but unmarried have a slightly higher usage rate for expensive restuarant coupons.
- Customer occupation has a significant influence on usage of expensive resturant coupons. The highest usage rates were for architecture & engineering, sales, computer & math, and office admin support.

### Next Steps and Recommendations
- There is a lot of opportunity to optimize acceptance rate of all coupons based on marital status, income level, and occupation.
- Exploration of the other coupon types: Inexpensive resturants (<$20), Carry out & Takeaway, and Coffee houses.
- Exploration of coupon usage based upon distance from location.
- Exploration of coupon usage based upon driving destination. 

