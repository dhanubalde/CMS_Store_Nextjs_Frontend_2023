
  <p align="center">A progressive <a href="http://nextjs.org" target="_blank">Next.js</a> framework for building efficient and scalable both server-side & client side applications.</p>
    <p align="center">
<a href="" target="_blank"><img src="https://img.shields.io/npm/v/@nestjs/core.svg" alt="NPM Version" /></a>
<a href="" target="_blank"><img src="https://img.shields.io/npm/l/@nestjs/core.svg" alt="Package License" /></a>
<a href="" target="_blank"><img src="https://img.shields.io/npm/dm/@nestjs/common.svg" alt="NPM Downloads" /></a>
<a href="" target="_blank"><img src="https://img.shields.io/circleci/build/github/nestjs/nest/master" alt="CircleCI" /></a>
<a href="" target="_blank"><img src="https://coveralls.io/repos/github/nestjs/nest/badge.svg?branch=master#9" alt="Coverage" /></a>
<a href="" target="_blank"><img src="https://img.shields.io/badge/discord-online-brightgreen.svg" alt="Discord"/></a>
<a href="" target="_blank"><img src="https://opencollective.com/nest/backers/badge.svg" alt="Backers on Open Collective" /></a>
<a href="" target="_blank"><img src="https://opencollective.com/nest/sponsors/badge.svg" alt="Sponsors on Open Collective" /></a>
<a href="" target="_blank"><img src="https://img.shields.io/badge/Donate-PayPal-ff3f59.svg"/></a>
<a href=""  target="_blank"><img src="https://img.shields.io/badge/Support%20us-Open%20Collective-41B883.svg" alt="Support us"></a>
</p>
  <!--[![Backers on Open Collective](https://opencollective.com/nest/backers/badge.svg)](https://opencollective.com/nest#backer)
  [![Sponsors on Open Collective](https://opencollective.com/nest/sponsors/badge.svg)](https://opencollective.com/nest#sponsor)-->





# Full Stack E-Commerce + Store  & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL, 2023

### Front-end Store
<img src="./resources/store.png"/>

For DEMO, use [Stripe Testing Cards](https://stripe.com/docs/testing)

This is a repository for a Full Stack E-Commerce + Dashboard & CMS: Next.js 13 App Router, React, Tailwind, Prisma, MySQL


Key Features:

#### Shadcn UI for the Admin: 
- You're planning to use Shadcn UI for the admin interface, which is likely a UI framework or library for creating the user interface.

#### Admin Dashboard as CMS, Admin, and API: 
- The admin dashboard will have multiple roles, serving as a content management system (CMS), an admin interface for managing the application, and also as an API for interacting with the application's data.

#### Control Multiple Vendors/Stores: 
- The system will support multiple vendors or stores. Each store might have its own unique content, such as products and categories.

##### Categories Management: 
- You can create, update, and delete categories. Categories help organize and classify products.

#### Products Management: 
- You can create, update, and delete products. Products are the items that vendors sell through your platform.

#### Multiple Product Images: 
- The system allows for uploading multiple images for products and changing them as needed. This feature enhances the product presentation.

#### Filters (e.g., Color and Size): 
- You can create, update, and delete filters like "Color" and "Size" and associate them with products. Filters help customers narrow down their product searches.

#### Billboards Management: 
- You can create, update, and delete billboards. Billboards are prominent text or promotional banners that can be attached to categories or used independently.

#### Search and Pagination: 
- Users can search through categories, products, sizes, colors, and billboards, with pagination for navigating search results efficiently.

#### Featured Products: 
- You can mark certain products as "featured" so that they are prominently displayed on the homepage or other relevant sections of the website.

#### Order and Sales Management: 
- The system allows you to track and manage orders and sales, providing valuable data and functionality for monitoring business operations.

#### Revenue Graphs: 
- Graphs and charts are available to visualize revenue and other performance metrics, helping you analyze the business's financial health.

#### Clerk Authentication: 
- Clerk is likely an authentication and authorization service, ensuring secure access to the admin dashboard and other parts of the system.

#### Order Creation: 
- This feature enables the creation of orders, likely for customers purchasing products from the vendors.

#### Stripe Checkout: 
- Integration with Stripe for processing payments, which is a common payment gateway solution.

#### Stripe Webhooks: 
- Stripe webhooks provide real-time notifications about events related to payments and transactions.

#### Database and ORM: 
- The technology stack includes MySQL as the database, Prisma as the Object-Relational Mapping (ORM) tool, and PlanetScale, which might be used for database scaling and management.


### Prerequisites

### **Node version 14.x**


# Getting Started
First, run the development server:
```
npm run dev
```
```
yarn dev
```
```
pnpm dev
```
```
bun dev
```
Open http://localhost:3000 with your browser to see the result.

You can start editing the page by modifying app/page.tsx. The page auto-updates as you edit the file.

This project uses next/font to automatically optimize and load Inter, a custom Google Font.

# Learn More
To learn more about Next.js, take a look at the following resources:

Next.js Documentation - learn about Next.js features and API.
Learn Next.js - an interactive Next.js tutorial.
You can check out the Next.js GitHub repository - your feedback and contributions are welcome!

# Deploy on Vercel
The easiest way to deploy your Next.js app is to use the Vercel Platform from the creators of Next.js.

Check out our Next.js deployment documentation for more details.

###Next.js
# Install and configure Next.js.
# Create Project
Start by creating a new Next.js project using create-next-app:
npx create-next-app@latest my-app --typescript --tailwind --eslint
Create shadcn-ui init command to setup your project:
```
npx shadcn-ui@latest init
```
### Install packages

```shell
npm i
```

### Setup .env file

```shell
NEXT_PUBLIC_API_URL=
```


### Start the app

```shell
npm run dev
```

