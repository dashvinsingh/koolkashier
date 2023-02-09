# koolkashier
KoolKashier is a solution that came out of problem I saw in a small business. A lot of small businesses in South East Asia still resort to old fashion methods of "retailing". Receipts, accounting, and inventory management have all been on paper. As a computer science student at that time, I saw the opportunity to make an impact in the community. The lack of data collection mechanisms and technology usage in small businesses lead me to develop an iPad Based Point of Sale and Business Management platform for small retail businesses.  

This project has been in production for a local business since July 2017; since then, the business has been able to track their customers, make business decisions based on sales data collected and not to mention, they've gone from an all paper business to paper-only-when-required business(i.e. printing thermal receipts). 


# Technical Specs
There are two components to this solution, the front-end (iPad application and Web Dashboard) and the back-end (Database and RESTful API).
## Front-end
  - Swift (iPad)
  - HTML, CSS, and Javascript (Dashboard)
 
## Back-end
  - NodeJS with Express (API)
  - MySQL (Relational Database)

# Snapshots
## iPad Application

#### Login and Main Page
Users login to the application using a passcode. Depending on the passcode they may enter employee or owner mode. 

The main page is where all the action happens. Users would select a product from the list on the right and supply additional information relating to the product before it gets added to the list of products on the left. The list of products can be modified on the web dashboard component of the product.  

<span><img src=./login.png width=400><img src=./main-page.png width=400></span>

#### New Product and Discount
Once a product is selected, users are required to fill information regarding the product. The information collected was as per the requirements of the small business.  

A discount can also be placed on the subtotal amount. This feature is an initial attempt to support discounts. Currently the user can apply a discount by amount or percentage. Supplying promo codes is the next step in supporting discounts.  

<span><img src=./new.png width=400> <img src=./discount.png width=400></span>


#### View Invoice
After a sale is created, the user can view all invoices of the day. They can even search old invoices by invoice ID, date, or customer phone number. This allows the owner to easily access historical data when customers shop in the store. In case an incorrect sale was made, the owner can void the sale and restart the process.

The owner can also **print receipts** at the point of sale or any time. This applies to any invoice that shows up in the invoice page. Wirelessly printing receipts in the store is one of the most important feature for the POS system. Check it out in the demo!

<img src=./invoice-mobile.png width=400>

## Web Application
The web application has extended feature such as: adding products, viewing sale reports, modifying receipts, adding customer phone numbers, applying discounts. If the store owner is not at the store, thanks to the dashboard, they can view their sales happen live during the day. 

#### Dashboard and Reports.
This dashboard lists all sales and stats of the day. Users can also go back and view the dashboard of a previous day. In addition to the "day" dashboard, the user can view monthly and annualy reports. This is a cruicial page to track how the retail store was doing during different times of the year and if there are external events and factors that affect the operatoins of the store. 

<span><img src=./dashboard.png width=400><img src=./reports.png width=400></span>

#### Invoice
Just like the iPad application, the web application also provides the invoice view for each sale.

<img src=./invoice.png width=400>

#### Customer Dashboard
One of the key plus points for this business is their ability to track how much each customer has spent at the store. This allowed the business owner to create promotions targeting each customer differently depending on the amount of money spent.  

<img src=./customer.png width=400>

## Next Steps
This product was a solution to an underlying problem and we are looking to improve and add additional features to enhance the business operations.  

If you're interested in checking out the demo, please reach out to me at **singh.dashvin [@] gmail.com**



