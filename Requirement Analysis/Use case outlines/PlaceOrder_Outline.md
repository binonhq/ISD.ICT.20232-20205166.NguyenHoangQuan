Use case "Place order":
Basis flow:

Step 1: Customer navigates to cart
Step 2: The system displays cart information
Step 3: Customer reviews, updates the cart
Step 4: Customer requests to place an order
Step 5: The system checks availablility of products
Step 6: The system shows delivery form
Step 7: Customer sets up delivery information and submit
Step 8: The system checks delivery information
Step 9: The system shows invoice
Step 10: Customer selects payment method
Step 11: Customer confirms the order
Step 9: The system makes the cart empty

Alternative flow:
At step 5: If there are any unmet product, the system shows the inventory quantity for each unmet product then return step 3
At step 9: If customer chooses rush order delivery and at least one product is not support this, the system announce and return step 7
