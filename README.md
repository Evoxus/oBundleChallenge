# Preview code and URL
hjxdjoqao4


https://teststore363.mybigcommerce.com/?ctk=132f7eb8-4d27-494f-af31-4d35469a0016

## Thoughts/Progress
After spending as much time on this as I can this is where I am at with it all. 

The add and remove all from cart buttons are partially implemented. The functionality is mostly there but for some reason the cart fetch is not working correctly to get the cartId to make further requests work. Because of this road block I wasn't able to alert the user of success or failure correctly. I know that there has to be a better way to do this and I had initially seen some success implementing all this inside the category.js file. The issue there arose with my on click handler and `this` pointing to the button instead of any of the functions inside the category class.

I was able to show the signed in user info and complete the 2nd image on hover feature easily enough.

## Setup

- Sign up for a BigCommerce trial store, this will be valid for 15 days and will be needed to complete the test
- Install Stencil CLI for local development, you will be using the default Cornerstone Theme that comes standard with new BigCommerce stores


*Refer to the BigCommerce developer documentation for any questions you might have. It will contain all the info needed to complete the tasks below*

## Task

- Create a product called Special Item which will be assigned to a new category called Special Items. Be sure to add at least 2 images during the product creation
- The Special Item should be the only item which shows in this category
- Create a feature that will show the product's second image when it is hovered on.
- Add a button at the top of the category page labeled Add All To Cart. When clicked, the product will be added to the cart. Notify the user that the product has been added.
- If the cart has an item in it - show a button next to the Add All To Cart button which says Remove All Items. When clicked it should clear the cart and notify the user.
- Both buttons should utilize the Storefront API for completion.

#### *Bonus*

- If a customer is logged in - at the top of the category page show a banner that shows some customer details (i.e. name, email, phone, etc). This should utilize the data that is rendered via Handlebars on the Customer Object.

## Submission
- Create a GitHub repo for your codebase . In the Readme file remove the current data and add your own which describes a brief overview of your test.
- Be sure you include the Preview Code for the Bigcommerce Store, along with its URL, so we can view it. Then reply to this email with the Github repo link.