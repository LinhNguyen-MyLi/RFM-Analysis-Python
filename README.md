# RFM-Analysis-Python

## **Task project:**<br />
Using Quintitle and Python to make RFM analysis model for behavior based customer segmentation of a Superstore dataset

## **Introduction:**<br />
1. Why RFM?<br />
   - RFM (Recency, Frequency, Monetary) analysis is a marketing model using customer segmentation based on their transaction history.<br />
   - This model could be very useful, especially for small and medium-sized enterprises (SMEs) with limited marketing resources, helping them focus on the potentially right customer segments to increase ROI, reduce churn, reduce cost, improve customer relationship, and a lot more.<br />

2. How?<br />
   - In RFM analysis, customers are scored based on three factors (Recency - how recently, Frequency - how often, Monetary - how much), then labeled based on the combination of RFM scores.<br />

3. Reference:<br />
    https://www.putler.com/rfm-analysis


## **Dataset:**
It include 06 sheets: 
- Orders: store all information related to orders from 2014 to 2017. Ex: order date, product ID, sales, quantity, unit cost...
- Product: info of all purchased products. Ex: name product, product ID...
- Location: location of buyers or ship address
- Customer: infor of purchased customers. Ex: name, customerID
- Return: collection of all orders that have been returned
- Segmentation: classification for behavior of customer. Ex: loyal, at risk, lost customers....

## **Guildeine:**
1. Prepare data set suitable for RFM model.
2. Determine how to calculate and calculate the R, F, M score of each customer.
Note: The calculation date of the R index is December 31, 2017 "
3. Provide a calculation method with a score corresponding to a scale of 1 to 5.
Hint: use the quintile method of Statistics."
4. Based on the classification table to group for each customer
5. Visualize the number of segment sets with data dimensions - Dimension
6. Analyze the current situation of the company and give suggestions to the Marketing team (answer below)
7. Suggestions to the Marketing and Sales team with the retail model of Superstore company, which index should be most interested in in the 3 R, F, and M indexes? (answer below)

## **Definition and recommended action for each customer segment:**

| **Segment**     | **Characteristics**   | **Recommendation**   | 
| ------------- | ------------- | ------------- | 
| Champions |	Bought recently, buy often and spend the most! | Reward them. Can be early adopters for new products. Will promote your brand. |
| Loyal |	Spend good money with us often. Responsive to promotions. |	Upsell higher value products. Ask for reviews. Engage them.
| Potential Loyalist | Recent customers, but spent a good amount and bought more than once. |	Offer membership / loyalty program, recommend other products.
| New customers |	Bought most recently, but not often. | Provide on-boarding support, give them early success, start building relationship.
| Promising |	Recent shoppers, but haven’t spent much. |	Create brand awareness, offer free trials
| Need attention |	Above average recency, frequency and monetary values. May not have bought very recently though. |	Make limited time offers, Recommend based on past purchases. Reactivate them.
| About to sleep |	Below average recency, frequency and monetary values. Will lose them if not reactivated. | Share valuable resources, recommend popular products / renewals at discount, reconnect with them.
| At risk |	Spent big money and purchased often. But long time ago. Need to bring them back! | Send personalized emails to reconnect, offer renewals, provide helpful resources.
| Cannot lose them |	Made biggest purchases, and often. But haven’t returned for a long time. | Win them back via renewals or newer products, don’t lose them to competition, talk to them.
| Hibernating customers |	Last purchase was long back, low spenders and low number of orders. |	Offer other relevant products and special discounts. Recreate brand value.
| Lost customers | Lowest recency, frequency and monetary scores. | Revive interest with reach out campaign, ignore otherwise.



