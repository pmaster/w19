---
layout: lab
num: lab09
ready: true
desc: "Practicing what we learned"
assigned: 2019-03-12 8:00:00.00-7
due: 2019-03-15 8:00:00.00-7
---

<div markdown="1">

## Goals for this lab

In preparation for the final exam, practice writing code for the following concepts:

* Flow control if-else statements
* While loops
* For loops
* Evaluating expressions
* Data representation
* Data types and declarations
* Arrays
* Passing parameters to functions
* Passing arrays to functions and returning arrays from functions
* Pointers
* Structs
* Pointers and structs
* Pointers and arrays
* Arrays of structs
* Dynamic Memory Allocation
* Linked-lists
* Strings
* Iteration through lists
* Recursion on linked lists and strings

## Log in and create a local directory

* Under your **cs16** directory, create a new directory named **lab09** (refer to lab00 for instructions if you have forgotten how to do this)

There is no starter code: you get to create it from scratch.


## Create a repo on github in our class organization

As usual, start by creating a repo _in the **ucsb-cs16-w19** organization_. 

Make sure that when you create a repo, the **Owner** is the **ucsb-cs16-w19** organization (**NOT** your personal account).


## Create Products and Carts

Imagine that you were hired by an online mega-seller Zonamaze. 
They put you in charge of creating their inventory and allowing users to purchase various items that are currently in stock.

* How many structs do you need to create?
* What are the member variables of each struct? What are their types?


Dynamically create an inventory list that contains three different products; for each product, record its title, manufacturer, quantity, and price.

Allow the user to add those items to their cart. If the inventory has 0 items of that type, the user should get a message that this item is out of stock.
Let the user remove the items.

Test your functions:

* Dynamically add three items to the user's cart.
* Output the contents of the cart, showing the items.
* Update the quanity of items (not exceeding the inventory's capacity)
* Output the contents of the cart, making sure the quanity was updated.
* Remove the second item that was added; print the contents of the cart, then remove the first item;
* Delete user's cart (making sure to delete the items that were in it first)
* Add another item to the inventory
* Show all items in the inventory that are out of stock


## Submit your code on Gradescope<a name="submit"></a>

Once you are satisfied that **your programs are correct**, then it's time to submit them. 

Log into your account on [https://www.gradescope.com/](https://www.gradescope.com/) and navigate to our course site. Select this assignment. Then click on the "Submit" button on the bottom right corner to make a submission. You will be given the option of  uploading files from your local machine or submitting the code that is in a Github repo. _Select the second option and select your Github repo for this assignment._ You should receive full credit for submitting at least some attempt on this lab.



## Log Out!<a name="done"></a>

You are now done with this assignment!
If you are in the Phelps lab or in CSIL, make sure to log out of the machine before you leave. Also, make sure to close all open programs before you log out. Some programs will not work next time if they are not closed. Remember to save all your open files before you close your text editor.

If you are logged in remotely, you can log out using the `exit` command:

`$ exit`


## Grading rubric

In addition to the points given by gradescope, our staff may be manually grading your code for style. Code style, includes but is not limited to the following:

1. Code can be easily understood by humans familiar with C++ (including both the author(s) of the code, and non-authors of the code.)
2. Code is neatly indented and formatted, following standard code indentation practices for C++ as illustrated in either the textbook, or example code given in lectures and labs
3. Variable names choices are reasonable
4. Code is reasonably "DRY" (as in "don't repeat yourself")&mdash;where appropriate, common code is factored out into functions
5. Code is not unnecessarily or unreasonably complex when a simpler solution is available



</div>

