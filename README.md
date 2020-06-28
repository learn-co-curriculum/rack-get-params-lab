# Rack Routes and GET Params

We've provided the code for a basic list of items. Now it's your turn to extend it.
Do your work in `app/application.rb`.

## Vocabulary Word: "Route"

In applications built on Rack, we use the noun "route" to to refer to a path
that the application has a special response to.

Thus the `/shoes` "route" shows information about shoes. The `/profile` "route"
shows information about the logged-in user. The `/logout` route does something
to delete some information that let the server know the user was logged in.

## Instructions

  1. Create a new class array called `@@cart` to hold any items in your cart
  2. Create a new route called `/cart` to show the items in your cart
  3. Create a new route called `/add` that takes in a `GET` param with the key `item`. This should check to see if that item is in `@@items` and then add it to the cart if it is. Otherwise give an error
