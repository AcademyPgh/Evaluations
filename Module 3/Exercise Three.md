## Shopping cart

Build a shopping cart to calculate the total cost of an array of items. The app will need to support buy-one-get-one sales.

Use a function that takes an array of strings and returns the cost as a decimal: `checkout(string[]):decimal`

Items that can be in the list:

| item    | cost |
|---------|------|
| apples  | .35  |
| oranges | .60  |
| bananas | .50  |

### Example run
```
Please add items to your cart. O=Orange, A=Apple, B=Banana
B
You have 1 item in your cart would you like to Checkout [C] or continue shopping [Shop]?
Shop
Please add items to your cart. O=Orange, A=Apple, B=Banana
A
You have 2 items in your cart would you like to Checkout [C] or continue shopping [Shop]?
C
Your total is $0.91!
```

### Stretch Goal
Support these promotions:
* Apples are buy 1 get 1 free
* Oranges are buy 2 get 1 free
