This small project is to assess a Shopify engineering candidate's procifiency with Shopify theme development, Javascript and CSS. The goal is to show product upsells on the cart page and create a recently viewed products section on the product detail page time permits.

## Requirements

Please complete the following features:

- Display product upsells from the 'upsell' collection on the cart page
  - Create a new section that can be enabled/disabled in theme settings
  - Display a grid of 2 products from the 'upsell' collection that link to each product page
  - Write styles to match the design below
  - Send a Google Analytics event when product is clicked
 - Track and display recently viewed products on product detail page
   - Keep track of viewed products using a localstorage or a cookie
   - Create a new section that can be enabled/disabled in theme settings
   - Displays a grid of 1-4 recently viewed products that link to each product page
   - Write styles to match the design below
   - Send a Google Analytics event when product is clicked

  
## Getting Started

Be sure to install the [Shopify CLI](https://shopify.dev/themes/tools/cli).

* In a new directory pull the live theme: `shopify theme pull --store=fake-barstool`
* Serve your development theme and start building: `shopify theme dev`

## Design

### Desktop design
<img width="1130" alt="Screen Shot 2022-12-21 at 10 46 48 AM" src="https://user-images.githubusercontent.com/9220514/208945939-36936ad3-ce65-4f03-aacf-cb30dbb2d8de.png">

### Mobile design
<img width="571" alt="Screen Shot 2022-12-21 at 10 48 07 AM" src="https://user-images.githubusercontent.com/9220514/208946022-0fadcef5-e183-46d2-9e8a-d96531f0d49f.png">

