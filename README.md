# FullStack Capstone Project -

## About Project -

In this final Project you have to create a clone of a [Shopify](https://www.shopify.com/).

Shopify is a commerce platform that allows anyone to set up an online store and sell their products.

You have to create a above project with combination of MERN (MongoDB, ExpressJS, ReactJS, NodeJS) stack.


## Table of Content -

1. [Walkthrough Shopify](#my-first-title)
2. [Instruction](#my-second-title)


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

- Create a `dev` branch and `day-1` branch.

- In `day-1` branch setup basic boilerplate for a project there is multiple way to setup a project.

  There are multiple ways, you can setup your node as well as react application.

  1. You can use a this [react-node-boilerplate](https://github.com/AltCampus/react-node-boilerplate) for creating full stack applications.

  OR

  2. You can create 2 separate applications i.e. one express server for serving APIs and another react application using create-react-app. Here, both applications will run on separate ports. you need to setup redux with react app on your own.

### Setup Issue's

- [issue 1](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/1)

-  [issue 2](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/2)

-  [issue 3](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/3)

- [issue 4](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/4)

### Add Product Category

- Create schema for product which should contain following things

**title** (required) - title of a product (e.g Macbook Pro) should be unique and lowercase.

**description** (required)- description of a product

**media** - image of a product (multiple). You can use cloudnary for upload of image

**price** (required)- This is a price on which you want to sell a product. (e.g 1,50,000)

**compare price** - This is a price which is compared with above price for a comparsion.

**cost per item** - The cost if item you are purchasing as a shopkeeper you get item at lower price and you sale for higher price for a profit

**variant** - The product can have a variant like color (Gray, silver) and storage(250GB SSD, 512 GB SSD, 1TB) in case of (macbook)

**product type** - The product can have type of product like electronic, clothes, toys etc.. if none is passed should have to default to `other`  type.

**tags** - The product can have multiple tag which can be used for filter or search result on query.

**status** - The product status telling is  a prouct is active, draft

_active_ means the product is live for visibility in a store

_draft_ the product is created is not live on store but saved for now

Refer - [issue 5](https://github.com/AltCampus/AC-FULLSTACK-capstone-1/issues/5)

For more detail of add product part refer [Add Product docs of shopify](https://help.shopify.com/en/manual/products/add-update-products)