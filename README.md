# Rack Routes and GET Params

In this lab, we'll create a shopping cart application. We've provided you the code for a basic list of items as well as the path for those items and how to search for items. Now it's your turn to extend it.

## Instructions

  1. Create a new class array called `@@cart` to hold any items in your cart.
  2. Create a new route, or path, called `/cart` to show the items in your cart.
  3. Create a new route, or path, called `/add` that takes in a `GET` param with the key `item`. This should check to see if      that item is in `@@items` and then add it to the cart if it is. Otherwise give an error message. 

