# Interactions

these functions' role is to implement entire user interactions
they will use the prompts, logic and renders to create a full user experience

you will call interaction functions from your UI using the `onclick` attribute

Here are some general rules for your interaction functions:

- they should not take any arguments
- they should not return any values
- they can use functions declared in logic.js, prompts.js and renders.js
- they can read and modify any data variables stored in data.js
