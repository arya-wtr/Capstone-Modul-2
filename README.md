Amazon Web Service - SaaS Sales Data Analysis

Background
Amazon Web Services (AWS) is a comprehensive cloud computing platform launched by Amazon in 2006. It provides a wide range of on-demand services, including computing power, storage, and databases, as well as machine learning, analytics, and Internet of Things (IoT) capabilities. AWS was developed to meet the growing need for scalable, reliable, and cost-effective infrastructure solutions, initially catering to Amazon's own internal requirements for e-commerce and later expanding to serve a diverse global customer base. With data centers located across multiple geographic regions, AWS ensures high availability and fault tolerance, enabling businesses to deploy applications quickly and efficiently.

Over the years, AWS has consistently innovated, introducing a vast array of services that support various use cases, from startups to large enterprises. Today, AWS is recognized as a leader in the cloud computing industry, transforming the way organizations operate by enabling them to focus on innovation while outsourcing their infrastructure needs.

AWS approaches Software-as-a-Service (SaaS) as a business and software delivery model that enables organizations to provide their offering to customers in a low-friction and service-centric manner. Software-as-a-Service (SaaS) is a way of delivering applications remotely over the internet instead of locally on machines (known as “on-premise” software). AWS works with organizations to build a SaaS model that establishes agility and operational efficiency as pillars of their business strategy—promoting growth, reach, and innovation.

Business Problem
Amazon Web Services as one of leader in cloud computing industry, now focus on transaction of SaaS selling sales and marketing software to other companies (B2B). In B2B business, there are many challenges that somehow we encountered along the way. The most significant is decrease in profit.

Profit Loss can be caused by :
1. Sales Performance (e.g. declining in sales growth, poor pricing product),
2. Target Market Issues (e.g. customer segmentation, market saturation),
3. Marketing Strategy (e.g. discount strategies, selling strategies)

Therefore, a comprehensive analysis are needed.

Goals
Finding the key-factor of things that related to profit.
Enhance Profit.

## **Data**
This dataset contains transaction data from SaaS company selling sales and marketing software to other companies (B2B). In the dataset, each row represents a single transaction/order (9,994 transactions), and the columns include: 

Dataset from [here](https://www.kaggle.com/datasets/nnthanh101/aws-saas-sales/data). 

### **Features**
**Original Dataset :**


| No. | **Attribute**    | **Description**                                          |
|-----| ---------------- | -------------------------------------------------------- |
| 1.  | **Row ID**       | A unique identifier for each transaction.                |
| 2.  | **Order ID**     | A unique identifier for each order.                      |
| 3.  | **Order Date**   | The date when the order was placed.                      |
| 4.  | **Date Key**     | A numerical representation of the order date (YYYYMMDD). |
| 5.  | **Contact Name** | The name of the person who placed the order.             |
| 6.  | **Country**      | The country where the order was placed.                  |
| 7.  | **City**         | The city where the order was placed.                     |
| 8.  | **Region**       | The region where the order was placed.                   |
| 9.  | **Subregion**    | The subregion where the order was placed.                |
| 10.  | **Customer**     | The name of the company that placed the order.           |
| 11.  | **Customer ID**  | A unique identifier for each customer.                   |
| 12.  | **Industry**     | The industry the customer belongs to.                    |
| 13.  | **Segment**      | The customer segment (SMB, Strategic, Enterprise, etc.). |
| 14.  | **Product**      | The product was ordered.                                 |
| 15.  | **License**      | The license key for the product                          |
| 16.  | **Sales**        | The total sales amount for the transaction.              |
| 17.  | **Quantity**     | The total number of items in the transaction             |
| 18.  | **Discount**     | The discount applied to the transaction.                 |
| 19.  | **Profit**       | The profit from the transaction.                         |
