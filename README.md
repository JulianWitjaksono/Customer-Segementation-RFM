# Customer-Segementation-RFM
# Context
This is a collection of sales transaction data for NichoaChocolate, based in Magelang, for more than one year. This Magelang-based shop has been selling a wide variety of quality chocolate products since 2018. Their customers come from all major cities in Indonesia and usually make direct purchases as well as through e-commerce.
# use case

# Objective Statement:
- Get insight about revenue Every Year & Month.
- Get insight about profit Every Year & Month.
- Get insight about the platforms that customers often use to buy chocolate.
- Get insight about the price of chocolate that is often purchased by customers.
- - Find out best top 5 selling chocolate bar.
- Get business insight about top 5 product sold every segment
- Increase Marketing Efficiency about chocolate bar using Segment RFM,and EDA.

# Challenges:
- Data Have Missing at june 2021.
- Data have a lot Outlier at quantity column.
- Choose specific customer data that buys chocolate bar.
- Remove customers who didnt pay for chocolate bar.
- Methodology / Analytic Technique:
- Descriptive analysis.
- Graph analysis.
- Segment Analysis using RFM Analysis.

# Business Benefit:
- Knowing how to treat customer with specific criteria.
- Knowing sales performance every month so, it can be a reference for future decision making.
- Knowing revenue every Year & Month.
- Knowing profit every Year & Month.
- Knowing about the price of chocolate that is often purchased by customers.
- Knowing best top 5 selling chocolate bar.
- Knowing about the platforms that customers often use to buy chocolate.

# Expected Outcome:
- Find out how much revenue per year and per month.
- Find out sales performance every month.
- Find out revenue every Year & Month.
- Find out profit every Year & Month.
- Find out the platforms that customers often use to buy chocolate.
- Find out the price of chocolate that is often purchased by customers.
- Find out best top 5 selling chocolate bar.
- Know customer segmentation analysis.
- Business Understanding
- How many product sold every month?
- How much revenue every month?
- How much revenue every year?
- How much profit every month?
- How much profit every year?
- What platforms customers often buy chocolate?
- What chocolates are most frequently purchased by customers?
- What is the price of chocolate that customers often buy?

# Data Understanding
Data of Nichoa Customer with 21 columns and 1616 rows

This data from 02/01/2021 to 24/02/2022

# Data dictionary :
- order no : Order Number.
- order time : the day and time the customer ordered chocolate.
- brand : Brand is the name of a specific product.
- brand comission rate : commision rate each product
- brand comission amount : commission amount for each product
- item group : The product group represents the shape and type of product.
- item name : Product Name
- item sku : Stock Keeping Units are differentiator types of goods or services sold.
- qty : Quantity of the product
- currency : currency type for payment
- price : product price
- add-on price : additional price of the product
- discount percent : discount percentage of the product
- discount amount : the discount amount of each product
- amount : product price/ product amount
- tax amount : tax amount of product
- cost perunit : valuable calculations to make sure their cost is lower than the selling price of a single unit.
- total cost : is the amount of money spent by a company to produce a product in a specific time frame.
- profit : the company's net income, or the amount of money you make from sales in a certain period after deducting COGS and expenses. It can also be said as "net income" or "net income."
- paid to brand : the amount to be paid to the brand
- payment type : payment type to buy products (the type of payment through the bank is an order via whatsapp)

# Data preparation
Code Used :
- Python Version: 3.7.6 / Google Colaboration and Jupyter Notebook
- Packages: Pandas, Numpy, Matplotlib, Seaborn, Sklearn, and Feature Engine
