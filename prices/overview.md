---
pos: 1
title: Overview 
description: 
prev:
  path: /product/variants/
next:
  path: /prices/pricing-range/
---

In order to sell a product in a store we need to communicate its price. As products may come in different shape and size, each product variant may be priced differently. In this section we will describe the fundamentals of pricing products and how we can get most of the Saleor API.


Now we know how to fetch products from GraphQL API and how to add some of those products to a cart in order to initiate the checkout process. The next step is to understand the pricing. Products have prices, but it is also possible a product depending on its size or shape has some different prices. In that case we talk about the price range of a given product. 

The price for each product contains the tax (which may be also different for different countries). Saleor distinguishes between the net price, i.e. the prices without the tax, the gross price i.e. the price with the tax, and it can also the return just the tax amount for each product. 