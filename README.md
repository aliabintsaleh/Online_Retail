 This project aims to analyst an Online retail data set using RFM module.
 An RFM model is built using recency(how recently a customer has transacted with a brand), 
 frequency (how frequently they’ve engaged with a brand ) 
 and monetary (how frequently they’ve engaged with a brand. 
 It is a method of using data and segmenting customers based on recency, frequency, and value spent based on current customer behavior to predict the behavior of new customers in the future 
 also It helps to know the size of clients, estimate their value to the business, and create an appropriate marketing strategy.

  <img width="648" alt="image" src="https://github.com/aliabintsaleh/Online_Retail/assets/159874711/e244ab95-3f03-4e3b-b827-858eac1704ff">

 This Online Retail data set contains all the transactions occurring for a UK-based and registered, non-store online retail between 01/12/2009 and 09/12/2011.The company mainly sells unique all-occasion gift-ware. Many customers of the company are wholesalers.
Attribute Information:
InvoiceNo: Invoice number. Nominal. A 6-digit integral number uniquely assigned to each transaction. If this code starts with the letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal. A 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice date and time. Numeric. The day and time when a transaction was generated.
UnitPrice: Unit price. Numeric. Product price per unit in sterling (Â£).
CustomerID: Customer number. Nominal. A 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal. The name of the country where a customer resides.

Data cleaning and preparation  for analysis :
Checking if there is missing data 
1.there is a missing values in description column and Customer Id
2. Since the missing values in the description are less than 5%, so I dropped them 
3.the missing values in the Customer id are 25% but because there is no other column that can identify the customer , so I dropped them.
4-Quantity column is numeric ,so I  checked if there is  outlier values and dropped them
5-delet the records with  0.00 values in unit price column 
6-checking the inconsistency in Country, description column 
7-add profit, hour, day and month column 
