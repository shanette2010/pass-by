# PASS BY EXPLANATIONS #

# Pass by Copy/Value: #
When you pass a variable to a function, a copy of the variable's value is made and passed to the function. 
Any changes made to the variable within the function do not affect the original variable outside of the function. 
This is common in languages like C and Python for primitive data types like integers, floats, and booleans.

# Pass by Reference: #
Passing a copy of the variable's value, a reference to the variable itself is passed to the function. 
This means that any changes made to the variable within the function will affect the original variable outside of the function. 
Languages like JavaScript typically pass objects and arrays by reference.

# How I feel: #
How do I feel about all of this? Well, these concepts are like the foundation of a building. 
They might not always be the most exciting part, but without them, everything else would collapse. 
They're crucial for understanding how data is handled in programming languages, which ultimately affects how we write and debug our code.

# Explaning this to someone else: #
  * Pass by Copy/Value -Imagine you have a recipe book and you make a copy of a recipe to share with a friend. 
If your friend decides to scribble some notes on their copy, it doesn't affect your original recipe. Each of you has your own independent version.


  * Pass by Reference- Think of a library where books are stored. When you lend a book to a friend, you're not giving them a copy, you're giving them access to the actual book.
If they decide to doodle in the margins or add sticky notes, those changes are reflected in the original book because you're both referring to the same physical object.
