# Coupon_Acceptance
**Will a customer accept the coupon?**

Please find the code here - (https://github.com/meenamurali2m/Coupon_Acceptance/blob/main/prompt_MM.ipynb)

**Overview**
In this assignment we seek to answer the question, “Will a customer accept the coupon?” We use various visualizations and probability distributions to distinguish between customers who accepted a driving coupon versus those who did not. 

**Data**
This data is from the UCI Machine Learning Repository and was collected via a survey on Amazon Mechanical Turk. The survey describes different driving scenarios, including the destination, current time, weather, and passenger, and then asks people whether they will accept the coupon if they are the driver. There are three possible answers people can choose from:

“Right away”
“Later, before the coupon expires”
“No, I do not want the coupon”
The first two responses are labeled as “Y = 1,” and the third is labeled as “Y = 0.” There are five different types of coupons: Less expensive restaurants (under $20), coffee houses, carryout and takeaway, bars, and more expensive restaurants ($20–$50).

**Exploration and Analysis based on the drivers who will accept Bar coupons**
Based on the analysis, 

****First Observation ****
Acceptance rate between drivers who go to bars more than once a month and had passengers that were not a kid and had occupations other than farming, fishing, or forestry. AND
Acceptance rates between those drivers who go to bars more than once a month, had passengers that were not a kid, and were not widowed **are same**

**Second Observation**
Acceptance rate between drivers who go to a bar more than once a month and are over the age of 25 to the all others - All others **is the least**

**Third Observation**
Acceptance rate by drivers whose Income <50k is less
followed by
Drivers that go to bars more than once a month and are under the age of 30

**Final Observation**
Drivers that didnt have a kid as a passenger tend to accept the coupons at the bar more.

**Independent Investigation**
Analyzed the drivers that will accept the 'Coffee House' coupons. 

The approach was to explore coffee house coupons with other factors like Age, Destination, Marital Status and Passanger.

**Observation from the Independent Investigation**
1. Drivers aged 21 and 26 tend to accept Coffee House Coupons more compared to other age groups
2. Drivers that dont have to go anywhere urgently tend to accept Coffee House Coupons more compared to others
3. Drivers that are driving single or with a married partner tend to accept Coffee House Coupons more compared to others
4. Drivers that are driving Alone or with friend(s) tend to accept Coffee House Coupons more compared to others
