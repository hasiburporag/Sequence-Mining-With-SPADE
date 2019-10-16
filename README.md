<div align="center">  
<h1>Sequence Mining With SPADE</h1>
<img src="http://cab.spbu.ru/wp-content/uploads/2016/04/SPAdes_transparent_background.png" height="150">
<p>Subscriber purchase pattern analysis to ensure repeat purchase and cross-sales.<b> (Market Basket Analysis)</b> </p>
  
</div>

### Overview
Market basket analysis is a data mining technique used by retailers
to increase sales by better understanding customer purchasing patterns.
It involves analyzing large data sets, such as purchase history, to reveal
product groupings, as well as products that are likely to be purchased together. In our
case, we are trying to find out the order in which a customer buy the products 
of a retail shop frequently.

### Issues to be resolved
- A retail shop needs to track its own customers to ensure they visit the shop repeatedly and don’t move to competitor retail shops.
- Also retail shop needs to understand what else a customer probably will buy. The shop should then try to sell those to the customer to maximize revenue from the customer.
- The retail shop thus needs to understand its customers purchase pattern when he is supposed to do repeat purchase and what are his potential needs. 


### Data Collection
The data provides customer and date level transactions for few years.
It also provides customer_id, transaction date and Amount of purchase.  
https://www.kaggle.com/regivm/retailtransactiondata


### Prerequisites
- Python version 3 or greater is required
- Pycspade. This is a python wrapper for the C++ implementation of C-SPADE algorithm by the author, Mohammed J. Zaki. 
Link: https://pypi.org/project/pycspade/
