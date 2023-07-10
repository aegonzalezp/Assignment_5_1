## Assignment 5_1 Summary

Dataset
This data comes to us from the UCI Machine Learning repository and was collected via a survey on 
Amazon Mechanical Turk. The survey describes different driving scenarios including the destination, 
current time, weather, passenger, etc., and then ask the person whether he will accept the coupon 
if he is the driver. Answers that the user will drive there ‘right away’ or ‘later before the coupon 
expires’ are labeled as ‘Y = 1’ and answers ‘no, I do not want the coupon’ are labeled as ‘Y = 0’. 
There are five different types of coupons -- less expensive restaurants (under $20), coffee houses, 
carry out & take away, bar, and more expensive restaurants ($20 - $50). 

## Summary of findings
The study so far focused on two types of coupons

1. Bar Coupon
2. Restaurants $20 to $50 Coupon

## Bar Coupon
### Hypothesize of drivers who accepted the bar coupons
We have calculated the proportion of drivers that accepted coupons using frequency, age, passenger, occupation, marital status, going to cheap restaurants, and income.
<br>
**The best criteria to determine bar coupon acceptance is bar frequency.  Drivers that go to bars 4 or more times per month accept the bar coupon at 76% of the times which is higher than any of the other evaluated combinations.**

## Restaurants $20 to $50 Coupon
### Hypothesize of drivers who accepted the Restaurant 20 to 50 coupons
Using various histograms we can quickly identify characteristics that will iincrease the acceptance of this coupon.  The overall acceptance of this coupon is 44%.  
<br>
The best criteria to determine Restaurant 20 to 50 coupon acceptance are
- Restaurant 20 to 50 more than 1
- Time of day 10am, 2pm (lunch) or 6pm (dinner)
- No urgent destination
- Driving with a Partner

**These characteristics almost double the base proportion of acceptance going from 44% to 80%**

### Notebook URL
https://github.com/aegonzalezp/Assignment_5_1/blob/main/5_1_AlvaroGonzalez.ipynb
