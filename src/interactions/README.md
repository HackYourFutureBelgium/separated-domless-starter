# Interactions

these functions' role is to implement entire user interactions.
they will use the _prompts_ and _renders_ to interact with the user, and _logic_ to process user data.

you will call interaction functions from your UI using the `onclick` attribute.

Here are some general rules for your interaction functions:

- they should not take any arguments
- they should not return any values
- they can use functions declared in `/logic`, `/prompts` and `/renders`
- they can read and modify data variables stored in data.js
