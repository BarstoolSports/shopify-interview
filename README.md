This small project is to assess a Shopify engineering candidate's procifiency with Shopify theme development, Javascript and CSS. The goal is to create a recently viewed products section on the product detail page.

## Requirements

Please complete the following features:

 - Track and display recently viewed products on product detail page
  - Keep track of viewed products using a localstorage or a cookie
  - Create a new section that can be enabled/disabled in theme settings
  - Displays a grid of 1-4 recently viewed products that link to each product page
  - Write styles to match the design below
  - Send a Google Analytics event when product is clicked
- Display product upsells from the 'upsell' collection on the cart page
  - Create a new section that can be enabled/disabled in theme settings
  - Display a grid of 2 products from the 'upsell' collection that link to each product page
  - Write styles to match the design below
  - Send a Google Analytics event when product is clicked
  
## Getting Started

Be sure to install the [Shopify CLI](https://shopify.dev/themes/tools/cli).

* First, log in: `shopify login --store=fake-barstool`
* In a new directory pull the live theme: `shopify theme pull`
* Serve your development theme and start building: `shopify theme serve`

## Design

### Desktop design
<img width="1239" alt="Screen Shot 2022-03-23 at 8 22 09 AM" src="https://user-images.githubusercontent.com/9220514/159698452-220aa9ed-f4c3-4057-8f05-a43a90e13be2.png">


### Mobile design
<img width="645" alt="Screen Shot 2022-03-23 at 8 22 50 AM" src="https://user-images.githubusercontent.com/9220514/159698483-ffeb0800-368b-4439-89de-4f0bbfa5db79.png">
