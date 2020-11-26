<!-- BEGIN TITLE -->
# DOCS
<!-- END TITLE -->

<!-- BEGIN TOC -->
- [data.js](#srcdatajs)
- [interactions](#interactions)
- [logic](#logic)
- [prompts](#prompts)
- [renders](#renders)
<!-- END TOC -->



<!-- BEGIN DOCS -->

---

# [./src/data.js](./src/data.js)



---

# Interactions

these functions' role is to implement entire user interactions.
they will use the _prompts_ and _renders_ to interact with the user, and _logic_ to process user data.

you will call interaction functions from your UI using the `onclick` attribute.

Here are some general rules for your interaction functions:

- they should not take any arguments
- they should not return any values
- they can use functions declared in `/logic`, `/prompts` and `/renders`
- they can read and modify data variables stored in data.js


[TOP](#DOCS)

---


---

# Logic

these functions' role is to process and transform data. these are the traditional "coding challenge"/algorithm functions

Here are some general rules for your logic functions:

- they always need at least one argument
- they will always return a value
- they only use console.log
- they cannot use prompt, alert, or confirm


[TOP](#DOCS)

---


---

# Prompts

these functions' role is to gather and validate user input
we'll call these functions "prompts".

Here are some general rules for your prompt functions:

- they don't always need an argument
- they will always return a value
- they must use at least one prompt() or confirm()
- they can also use alert & console.log


[TOP](#DOCS)

---


---

# Renders

these functions' role is to format data so it's nice for users to read

Here are some general rules for your render functions:

- they always need at least one argument (you need some data to display!)
- they will return a formatted version of your data
- they can only use console.log
- they cannot use prompt, alert or confirm (you will alert the return value)


[TOP](#DOCS)

---
<!-- END DOCS -->