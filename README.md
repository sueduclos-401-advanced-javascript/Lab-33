# Lab-33 - Class 33

Code 401 Class 33 Virtual Store Phase 3 - Redux Additional Topics

## Project Name - Virtual Store app

Virtual Store Phase 4: Complete work on the Virtual Store by adding detail pages for individual products as well as the the cart checkout page

In phase 4, we will be completing work on our Virtual Store by adding a two full page views to the application: Product Details and Checkout

The user stories from Phases 1, 2 and 3 remain unchanged. For this phase, we are now adding the following new user stories to meet the new requirements.

* As a user, I want to see a full detail view of a product so that I can make a more informed choice about purchasing it.
* As a user, I want to view my full cart and initiate the checkout process so that I can purchase my items and have them delivered

## Technical Requirements / Notes

* Add routing to the application
* Link every product to a page that displays the full product details
Link the “Cart” summary in the header to a full shopping cart page with shipping/payment forms
Additionally, we will be swapping out our Redux store and replacing it with a store built using Redux Toolkit

## Application Architecture

* Add <BrowserRouter /> to your application
* Create a new page component: <ProductDetails />
  * Alter each product on the listing screen to have a new “Product Details” button
  * When clicked, <Link to...> /products/## where ## is the product ID
  * On this page, show an expanded view of the product, including placeholders for additional information such as reviews, suggestions, etc

* Create a new page component: <ShoppingCart />
  * Link to this page from the Cart (x) in the header, on the /cart route
  * On this page, show:
    * A summary of items in tabular format
    * A final order total
    * A form allowing the user to enter their billing/shipping address and credit card information
    * On submit, simply draw an alert that says “Thank you for your purchase”
      * We will not be processing transactions or storing orders just yet

### Author: Sue Duclos

### Links and Resources

- [CodeSandox Link](https://codesandbox.io/s/sduclos-401n16-lab33-phase-4-0qky3)
- [Netlify Deployment](www.abc.com)
