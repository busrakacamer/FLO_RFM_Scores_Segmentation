# RFM 

 ### What is RFM (recency, frequency, monetary) analysis?

RFM analysis is a marketing technique used to quantitatively rank and group customers based on the recency, frequency and monetary total of their recent transactions to identify the best customers and perform targeted marketing campaigns. The system assigns each customer numerical scores based on these factors to provide an objective analysis. RFM analysis is based on the marketing adage that "80% of your business comes from 20% of your customers."

#### RFM analysis ranks each customer on the following factors:

##### Recency: How recent was the customer's last purchase? Customers who recently made a purchase will still have the product on their mind and are more likely to purchase or use the product again. Businesses often measure recency in days. But, depending on the product, they may measure it in years, weeks or even hours.

This refers to the amount of time since a customer’s last interaction with a brand, which can include their last purchase, a visit to a website, use of a mobile app, a “like” on social media and more. Recency is a key metric because customers who have interacted with your brand more recently are more likely to respond to new marketing efforts.

##### Frequency: How often did this customer make a purchase in a given period? Customers who purchased once are often are more likely to purchase again. Additionally, first time customers may be good targets for follow-up advertising to convert them into more frequent customers.

This refers to the number of times a customer has made a purchase or otherwise interacted with your brand during a particular period of time. Frequency is a key metric because it shows how deeply a customer is engaged with your brand. Greater frequency indicates a higher degree of customer loyalty.

##### Monetary: How much money did the customer spend in a given period? Customers who spend a lot of money are more likely to spend money in the future and have a high value to a business.

This refers to the total amount a customer has spent purchasing products and services from your brand over a particular period of time. Monetary value is a key metric because the customers who have spent the most in the past are more likely to spend more in the future.

![Ekran görüntüsü 2023-03-08 170505](https://user-images.githubusercontent.com/121626776/223761877-14744e8b-f341-4354-be7e-d6ba8061490f.png)


### Segmentation of RFM Score:

After analyzing these three metrics, these values are scored between 1 and 5. Scores are ranked from 5 to 1 as from best to worst.

For the recency metric, the lowest value indicates the best score, while for other metrics, the highest value indicates the best score.

If you are a domestic appliance seller, frequency is not an important metric for your customer analysis. So it would be best if you focused on RM criteria to optimize your sales. Another common model is the RF Model, especially if you are analyzing a single product. You can see the segments prepared by the RF criterion by looking at the picture below.

### RF Model

Only the recency and frequency metrics are used for this model.


![Ekran görüntüsü 2023-03-08 165842](https://user-images.githubusercontent.com/121626776/223761957-aecbebc3-1e11-49a0-842e-59ae5b9cacd2.png)

### Business Problem

FLO, which is an online shoe store, wants to divide its customers into segments and determine marketing strategies according to these segments. 

#### Features of Dataset

Total Features : 12

Total Row : 19.945

#### Inputs:

master_id: Unique customer number

order_channel: Which channel of the shopping platform used (Android, iOS, desktop, mobile)

last_order_channel: Channel where the last shopping was made

first_order_date: Customer's first shopping date

last_order_date: Customer's latest shopping date

last_order_date_online: Customer's latest shopping date on the online platform

last_order_date_offline: Customer's latest shopping date on offline platform

order_num_total_ever_online: Customer's total number of shopping on the online platform

order_num_total_ever_offline: Customer's total number of shopping on the offline platform

customer_value_total_ever_offline: Total fee paid by the customer in offline shopping

customer_value_total_ever_online: Total fee paid by the customer in online shopping

interested_in_categories_12: List of categories where the customer shopping in the last 12 months


###### Sources:
https://www.techtarget.com/searchdatamanagement/definition/RFM-analysis

https://enhencer.com/articles/advantages-and-inefficacies-of-rfm-segmentation/

https://www.actioniq.com/blog/what-is-rfm-analysis/
