## Exercise: Shopping Cart

#### Objective:

Practice using HashMap to create a simple shopping cart.

#### Description:

Create a program that simulates a basic shopping cart using a HashMap. The program should allow users to add items to the cart along with their quantities, display the cart's contents, calculate the total price, and exit the program.

#### Guidelines:

- Create a HashMap to store item names as keys and their corresponding quantities as values.
- Create another HashMap to store item names as keys and their corresponding prices as values.
- Implement a loop that displays a menu with the following options:
    - Add item to cart
    - Display cart contents
    - Calculate total price
    - Exit

Depending on the selected option, perform the following tasks:

1.	To add an item, take input from the user for the item's name and quantity, and add it to the cart HashMap.
2.	To display cart contents, iterate through the cart and print each item's name and quantity.
3.	To calculate the total price, iterate through the cart, retrieve item prices from the price HashMap, and calculate the total.
4.	To exit, terminate the program.
