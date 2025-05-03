# Python_RFM_Analysis: Customer Segmentation
## I. Introduction
### 1. Business question
- AdventureWorks is a global retail brand that operates across multiple regions and offers a wide range of products. As the holiday season approaches, the Marketing Team plans to launch targeted campaigns during Christmas and New Year to reward loyal customers and convert potential buyers into repeat customers.
- To enhance customer targeting, the Marketing Director has suggested leveraging the RFM (Recency, Frequency, Monetary) model using Python. This model will help segment the customer base based on their purchasing behavior, allowing the marketing team to tailor personalized messages and offers. An analysis of the current customer base will support the development of an effective campaign strategy.
- Considering the business model of AdventureWorks, which of the three RFM indicators should the company prioritize to increase customer retention and maximize return on investment?
### 2. Dataset
Dataset includes 4 different related tables, including: transaction information, product information, returned orders of customers purchasing products from 2014 to 2017 and RFM classification
- Transaction information dataframe
![image](https://github.com/user-attachments/assets/68aebb58-138f-4d5a-a95e-84b0d78133eb)
- Product information dataframe
![image](https://github.com/user-attachments/assets/3fc9d91e-8fee-4ea4-aa80-16324ded38e7)
- RFM_rank information dataframe
![image](https://github.com/user-attachments/assets/fa45e52e-8c0f-4f58-b93f-5ebb58de2db9)

### 3. RFM Model
RFM is a technique used to assess customer value, widely applied in database and direct marketing, especially within the retail and professional services sectors. In an RFM analysis, customers are assigned numerical scores for each of these three dimensions, typically ranging from 1 to 5, where higher scores indicate stronger performance. Customers with the highest scores across all categories are considered the most valuable. The acronym RFM stands for:
- **Recency** – When was the customer's most recent purchase?
- **Frequency** – How regularly does the customer make purchases?
- **Monetary Value** – How much does the customer typically spend?

## II. Data Visualization with Python
![image](https://github.com/user-attachments/assets/ea1a2d7a-ed9f-4ba0-bae4-5fee4651f95f)
![image](https://github.com/user-attachments/assets/519113bb-2062-4978-9c66-f6e8a9b21c36)
![image](https://github.com/user-attachments/assets/e9ae60ce-fbf3-4060-be43-2bdd4474f320)
![image](https://github.com/user-attachments/assets/19434065-6ebe-4c1f-acd9-89fce1c729cd)
![image](https://github.com/user-attachments/assets/43bc748a-8852-4091-bb71-87d88aa9899d)

## III. Insights
- Champions are the most valuable customers. They purchase frequently, recently, and spend the most. This is the segment with the highest ROI potential and lowest churn risk.
- These Loyal customers are satisfied and return to purchase, but aren’t spending at the level of Champions yet.
- At Risk contributed significantly to revenue in the past but hasn’t been active recently. There's a high risk of churn if not addressed.
- Potential Loyalist is a newer or infrequent buyer. They show signs of future loyalty but haven't yet contributed much monetarily.
- Can Not Lose Them are high-spending, high-value customers who haven’t returned in a while. You’re on the verge of losing them.
- Need Attention recently purchased, but only once or rarely. They need guidance toward becoming more engaged.
## IV. Summary Recommendations
### 1. Champion
- VIP Loyalty Programs: Offer early access to new products, exclusive discounts, or personalized thank-you gifts.
- Referral Incentives: Encourage them to refer others by offering attractive rewards.
- Premium Tier Services: Upsell premium services or products—they are likely to respond positively.
- Collect Testimonials: Use their satisfaction for social proof in marketing.

### 2. Loyal Customers
- Cross-sell and Upsell: Recommend related or higher-value products.
- Personalized Content: Use their history to offer tailored promotions.
- Engagement Campaigns: Keep them warm with newsletters, sneak peeks, and community engagement.

### 3. At Risk
- Reactivation Campaigns: Send limited-time offers, personalized “we miss you” emails, or exclusive return discounts.
- Surveys: Ask for feedback to understand drop-off reasons.
- Retargeting Ads: Launch Facebook/Google ads tailored to their past purchases.

### 4.  Potential Loyalists
- Onboarding Journey: Educate them post-purchase with email series or product tips.
- Incentivize Repeat Purchases: Offer discounts for a second or third purchase.
- Membership Programs: Highlight the benefits of becoming a loyal customer.

### 5. Cannot Lose Them
- Personalized Outreach: A phone call or VIP email offering a major benefit to return.
- Urgency Offers: Create a "final chance" campaign with a compelling reason to act.
- Customer Service Touchpoint: Check if there was an issue in the last purchase or experience.
### 6. Need Attention
- Nurture Sequences: Educational or storytelling campaigns to create emotional attachment.
- Intro Bundles: Offer small bundles at attractive prices to increase frequency.
- Product Reviews or Feedback Requests: This builds interaction and trust.
