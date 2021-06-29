# FullStack Capstone Project -

## About Project -

In this final Project you have to create a clone of a [Shopify](https://www.shopify.com/).

Shopify is a commerce platform that allows anyone to set up an online store and sell their products.

You have to create a above project with combination of MERN (MongoDB, ExpressJS, ReactJS, NodeJS) stack.

## [Walkthrough Shopify](https://www.shopify.com/)

A demo video explaining the entire project and what needs to be done has been provided for deeper understanding.

<iframe
  src="https://youtu.be/Nnoq2JM4wfo"
  style="width:100%; height:300px;"
></iframe>

## [Instruction](#my-second-title) -

1. Fork this [repository](https://github.com/AltCampus/AC-FULLSTACK-capstone-1).

2. Visit shopify and play around with it. (Orders, Product, Customer, Analytic & Coupon)

3. There are multiple issues added on this project.

4. Create a dev branch from master and then create branch from dev for each issue.

5. Start from the first issue (create express application)

6. Once an issue is solved, merge it into dev branch.

## [Day-1]()

- Create a dev branch from master and then create branch from dev for each issue like `issue-1`.

- In `day-1` setup basic boilerplate for a project there is multiple way to setup a project.

  There are multiple ways, you can setup your node as well as react application.

  1. You can use a this [react-node-boilerplate](https://github.com/AltCampus/react-node-boilerplate) for creating full stack applications.

  OR

  2. You can create 2 separate applications i.e. one express server for serving APIs and another react application using create-react-app. Here, both applications will run on separate ports. you need to setup redux with react app on your own.

#### Setup Issue's

- [issue 1](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/1)

-  [issue 2](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/2)

-  [issue 3](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/3)

- [issue 4](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/4)

#### Add Product Category

- Create schema for product which should contain following things

```
title (required) - title of a product (e.g Macbook Pro) should be unique and lowercase.

slug - slug will be generated using title

description (required)- description of a product

media - image of a product (multiple). You can use cloudnary for upload of image

price (required)- This is a price on which you want to sell a product. (e.g 1,50,000)

compare price - This is a price which is compared with above price for a comparsion.

cost per item - The cost if item you are purchasing as a shopkeeper you get item at lower price and you sale for higher price for a profit

variant - The product can have a variant like color (Gray, silver) and storage(250GB SSD, 512 GB SSD, 1TB) in case of (macbook)

product type - The product can have type of product like electronic, clothes, toys etc.. if none is passed should have to default to `other`  type.

vendor - The product vendor which state the brand of a product

collection - The collection is a collection of multiple product e.g collection can be summer sale so we can add product to this collection and when we visit this collection we can see particular collection product. The collection will refer to Collection ID in a product.

tags - The product can have multiple tag which can be used for filter or search result on query.

status - The product status telling is  a product is active, draft

active: means the product is live for visibility in a store

draft: the product is created is not live on store but saved for now.

```

- Refer - [issue 5](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/5)

- Refer - [issue 6](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/6)

- For more detail of add product part refer [Add Product docs of shopify](https://help.shopify.com/en/manual/products/add-update-products)

> Add route in route folder and all logic regarding a route to a controller.

## [Day-2]()

- In Day-2 start working on client side creating a product form & have all the field that we are required to create a product in a db.

- Refer [issue 7](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/7)

- Refer [issue 8](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/8)

- Refer [issue 9](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/9)

- Refer [issue 10](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/10)

## [Day-3]()

- In Day-3 start working on a collection schema.

Collection Schema should contain following things

```txt
title (required) - title of collection e.g summer sale and should be lowercase and unique

slug - slug should be generated based on title

collection image - Can have single image for collection

collection type - we can add a product in a collection in one of following way

manual: where we wll select manually which product should be come to this collection.

automated: where the product will automatic will be added to a collection based on passed condition

the automated can be in one of following mode

all condition - which is kind of and operator

any condition - which is kind of or operator

condition name - price, tags, type, vendor
condition type -

price [equal to, greather than, less than , is not equal to]

tags [equal to]

type, vendor [equal to, is not equal to, starts with, ends with, contains, does not contains]

condition value - can be anything string or number in case of number

e.g tags - equal to - 'apple'

which will add all product with tag equal to 'apple' to this collection.

status - should be live on store or should be available this collection on a date kind of flipkart big billion day which happen in some date have selected item for a sale

products - which will shows all product fall in this collection
```

- [Refer Collection docs of shopify](https://help.shopify.com/en/manual/products/collections)

## [Day-4]()

- In Day-4 start working on client side creating a collection form & have all the field that we are required to create a collection in a db.

- Completed all collection operation create, read, update & delete by a client side.

## [Day-5]()

- Look the product and collection is communication properly with each other and working properly.

- Do the pending thing and fix patches.

## [Day-6]()

- Day 6 start working on backend and client side of customer which will list all customer a store have on admin side.

- Refer [issue 11](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/11)

## [Day-7]()

- Day 7 start working on backend and client side of orders which will list all orders a store received or draft on admin side.

- In order section you can mark a payment status like is received or incomplete.

- Also part order delivered status like order received, preparing of dispatch,  order shipped & delivered which can be control by admin side for a order.

## [Day-8]()

- Day 8 check the pending issue and fixes required from all days.

## [Day-9]()

- Day 9 start making user store

- Can store any UI

[DEMO STORE](https://themes.shopify.com/themes/expanse/styles/classic?surface_inter_position=1&surface_intra_position=8&surface_type=all)

#### Features

- Login Page & Sign Up Page (Add working)
- Home Page (Listing all product & slider)

## [Day-10]()

- Day 10 continue on user store

- Work on collection part of store

[Collection Live DEMO](https://themes.shopify.com/themes/expanse/styles/classic/preview?surface_inter_position=1&surface_intra_position=8&surface_type=all)

- Single Product showcase , Add to cart button, Buy Now Button (Add functionality too)

[Single Product with variant type DEMO](https://themes.shopify.com/themes/expanse/styles/classic/preview?surface_inter_position=1&surface_intra_position=8&surface_type=all)

## [Day-11]()

- Day 11 continue on user store

- Work checkout page, with taking input from customer address, contact details (Add client and backend functionality)

## [Day-12,13,14]()

- Start wrapping all the things leftover

## [Day-15]()

- Deploy the project live on digital ocean or other service and submit live link for a review
