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

Results / Observations:
- Ratio of acceptance for customers that visit bars > 3 times per month is 77%.
- Age does not seem to be a determining factor for bar coupon usage.
- Rate of acceptance for customers who visit bars > 3 times per month had passengers that were not Kid(s), and occupations that were not Farming Fishing & Forestry =  43%
- There is a significant decrease in the acceptance of bar coupons from customers that did not travel with kids or work in Farming, Fishing, & Forestry.
- Usecase 1: Rate of acceptance for customers who visit bars > 3 times per month, had passengers that were not Kids, and were not widowed =  43%.
- Usecase 2: Rate of acceptance for customers who visit bars > 3 times per month, and are under 30 =  49%.
- Usecase 3: Rate of acceptance for customers who go to cheap restaurants > 4 times per month and have income less than $50k =  45%.
- The rate of coupon acceptance for customers for each of these use cases is about the same ~ 45%. Which is slightly lower than the overall acceptance rate of 57%.

### Problem 3:
- Investigating the Expenseive Restuarant coupon usage.

