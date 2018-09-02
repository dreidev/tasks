# Local Cart

Implement [the deisgn](https://www.figma.com/file/YdHvYic4a8F0Hu7l6YQnDhvr/CartTask?node-id=0%3A1)

## Restrictions

- You may use a framework of your choosing.
- Vanilla JS is better, jQuery is worse.
- Please don't use any extra libraries if you can. (no bootstrap)
- You should use ES6+ Javascript Features, all modern browsers support ES Modules and async/await
- create a repo for the project and publish github page or on now.sh
- use this backend API `https://faker-api-yczfsfkfcd.now.sh/api/products` endpoint to load the products
    - You may save and load the data locally if it's more suitable
- You must create a cart.js file that manages your cart state futhur explained bellow

#### cart.js

`cart.js` should contain you app logic and should be designed to work with any framework or pure JS

Your cart.js file contains
- the state of the cart 
- methods for adding removing incrementing and decrementing items
- a way to get the state of the car directly
- implements an EventEmitter exposing a subscribe method that allows you to pass a function that is triggered whenever the cart's state changes

## Extra resources

You are judged on the cleanliness of your code [here's a summary of Clean Code for JS](https://github.com/ryanmcdermott/clean-code-javascript)



