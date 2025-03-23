# E-COMMERCE-BUSINESS-INSIGHTS
## Project Overview: 
This project involves performing Exploratory Data Analysis (EDA) on an e-commerce store’s past data to uncover trends and patterns in customer behavior, sales performance, and business efficiency. The goal is to derive meaningful insights that will help the business optimize its operations, improve customer satisfaction, and increase profitability.
The analysis will focus on several key areas, including customer demographics, purchase behavior, loyalty, pricing strategies, marketing effectiveness, and return rates. By exploring these aspects, I aim to provide data-driven recommendations that will enhance decision-making and business growth.

## Problem Statement: 
The e-commerce store faces challenges in understanding customer behavior, product preferences, and the impact of discounts and marketing strategies on sales performance. Additionally, high return rates and inconsistent brand loyalty raise concerns about product quality and customer satisfaction.

To address these challenges, this project aims to answer the following questions:
1.	Which customer age group (young vs. old) spends more, and how do their preferences differ?
2.	What factors influence customer retention and return rates?
3.	Do discounts effectively increase spending, and how do they impact return rates?
4.	How do purchase categories relate to shipping preferences and peak shopping times?
5.	What role does social media play in purchase decisions and product ratings?
6.	Are products with lower ratings returned more frequently, and which categories experience the highest return rates?

By analyzing this data, I will uncover trends that help the business improve its marketing efforts, optimize pricing strategies, reduce return rates, and enhance overall customer satisfaction

## Data Source:
The dataset I used for this analysis was provided as a CSV file by InternPulse as part of an internship task.

## Tools and Methodology:
**Tools Used:** EXCEL, Pivot table, Excel Functions, Charts

**Data Cleaning and Preparation:** I grouped the Customer age into two groups, young (below 35 years) and Old (above 36 years) using the IF Function, then I grouped the brand loyalty into High loyalty, Moderate loyalty and Low loyalty using Nested IF Function.

I also grouped the Customer’s Satisfaction to either very satisfied, satisfied, neutral, dissatisfied, or very dissatisfied, then I went further to extract the day of the week from the data of purchase using the TEXT Function.

Moreover, I needed to use the hour of purchase for my analysis, but since it wasn’t made available, I used the formula =Date of Purchase + [Time to Decision(hours) + Time Spent on Product Research(hours)] /24 to extract the exact hour of purchase which was used to depict the peak shopping hours in the business.

**Data Analysis and Insight Finding:** Pivot table was used to analyze and summarize my data to derive the necessary insights.

**Data Visualization:** I created an Excel interactive dashboard containing relevant charts and graphs to properly present my data in a visually appealing manner.

## Key Insights:
* Young customers spend slightly more than old customers, with a total of **$138,866** on purchased items while old customers spend **$136,198**. 
* Young customers spend the most on **Sports & Outdoors ($7,669)**, while old customers spend the most on **Jewelry & Accessories ($8,958)**. 
* There is a moderate return rate, with many customers making at least one return.
*	Customer satisfaction does impact brand loyalty, but dissatisfaction does not necessarily mean lost customers.
*	Discount sensitive customers spends more when products are discounted with a purchase of over $96,500, while the Not-sensitive customers spend $88,536.
*	The discount used does not really affect the return rate because customers that used discounts has a higher percent of return rate **(52%)** while does that didn’t use the discount has a lesser percentage **(48%)**
*	Customers with high income level are more interested in discounts than those of middle income.
*	Purchase category affects shipping preference because a large number of customers that purchase home appliances and those that purchase Jewelry & Accessories prefer to use the Standard shipping.
*	Customers that purchase Sports & Outdoors has no shipping preference at all.
*	The peak shopping days of the week are **Tuesdays and Thursdays** with a total sale of **$44,241 & $42,329** respectively.
*	The peak shopping hour is at **2:00pm** with about **88** customers making their purchase at that time and a total of **$25,440** sales.
*	Customers with high social media influence **purchase more** products with a purchase sum of $76,193, while those that has no influence on social media has the **least purchase** amount of $64,911.
*	Product with high rating of 5 has the highest return rate of over 210 returns, this suggests that customer expectations may not be aligning with reality for highly rated products.

## RECOMMENDATIONS:

**1.	TARGET PRODUCT PROMOTIONS BASED ON CUSTOMER AGE:** Since young customers spend slightly more than older customers and have different category preferences (Sports & Outdoors vs. Jewelry & Accessories), the business can refine its marketing and product strategies to increase sales from both groups.
*	For young customers, focus marketing campaigns on Sports & Outdoors, using social media ads and influencer collaborations.
*	Promote products during sports seasons and fitness trends.
*	For old customers, emphasize luxury and exclusivity in Jewelry & Accessories.
*	Offer personalized jewelry recommendations (e.g., anniversary gifts).

**2.	IMPROVE CUSTOMER SATISFACTION TO STRENGTHEN LOYALTY:** While dissatisfied customers still shop, their loyalty may not be long-term.
*	Implement a customer feedback loop to understand their pain points and improve products/services.
*	Neutral customers exhibit high loyalty, making them a key target for brand retention efforts.

**3.	 MANAGING HIGH RETURN RATES ON DISCOUNTED PURCHASES:** Since customers who use discounts return items more frequently than those who don’t. The business should focus on strategies to reduce return rates without discouraging discount-driven sales. 
*	Implement Smarter Discount Policies by offering discounts mainly on low-return-rate products to protect profit margins.
*	Minimize return risks by improving product descriptions and customer decision-making.

**4.	OPTIMIZE STANDARD SHIPPING FOR HIGH-DEMAND CATEGORIES:**
*	Since Home Appliances and Jewelry & Accessories customers prefer Standard Shipping, ensure that this mode remains efficient, cost-effective, and reliable.
*	Consider negotiating better shipping rates with carriers to improve profit margins on these high-volume shipments.

**5.	LEVERAGE PEAK SHOPPING DAYS & HOURS:**
*	Targeted Promotions: Implement flash sales, discounts, or free shipping offers specifically for Tuesdays and Sundays.
*	Inventory & Staffing: Ensure sufficient stock levels and staff availability to handle increased order volumes on these peak days.

**6.	IMPLEMENT INFLUENCER-EXCLUSIVE DISCOUNTS & PARTNERSHIP:**
*	Partner with high-social-media-influence customers by offering exclusive referral discounts to their followers.
*	Enable direct shopping via social media platforms (Instagram, TikTok, Facebook) where influencers promote products.
*	Create ambassador programs where top influencers get commission-based incentives for driving sales.
*	Invest in social media ads targeting followers of high-influence customers to drive conversion.

**7.	IMPROVE PRODUCT DESCRIPTIONS & SET REALISTIC EXPECTATIONS:**
*	Ensure detailed and accurate product descriptions to reduce mismatch in customer expectations.
*	Use 360-degree product images and videos to give a better preview before purchase.
*	Implement conditional returns (e.g., stricter policies for frequently returned products).

## CONCLUSION:

In conclusion, by aligning product promotions with customer demographics, enhancing satisfaction to foster loyalty, managing returns on discounted purchases, optimizing shipping for high-demand items, leveraging peak shopping periods, partnering with influencers, and improving product descriptions, the business can drive higher sales, reduce costs, and increase customer retention. Implementing these strategies will create a more efficient, customer-centric, and profitable e-commerce operation.
