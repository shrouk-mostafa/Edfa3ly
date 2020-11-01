Challenge Description:
================================================================================

This is a program that can price a cart of products, accept multiple products, combine offers, and display a total detailed bill in different currencies "based on user selection".

Available catalog products and their price in USD:

1- T-shirt $10.99
2- Pants $14.99
3- Jacket $19.99
4- Shoes $24.99

The program can handle some special offers, which affect the pricing.

Available offers:

Shoes are on 10% off.
Buy two t-shirts and get a jacket half its price.

The program accepts a list of products, outputs the detailed bill of the subtotal, tax, and discounts and bill can be displayed in various currencies.

There is a 14% tax (before discounts) applied to all products.

Examples:
================================================================================

Example-1 in USD:
------------------

The products:

T-shirt
T-shirt
Shoes
Jacket

Outputs the following bill, the user selected the USD bill:

Subtotal: $66.96
Taxes: $9.37
Discounts:
	10% off shoes: -$2.499
	50% off jacket: -$9.995
Total: $63.8404

Example-2 in EGP with no offers are eligible:
---------------------------------------------

The products:
T-shirt
Pants

Outputs the following bill:

Subtotal: 409 e£
Taxes: 57 e£
Total: 467 e£


Installation:
================================================================================

You can run this command if you want to calculate or get the bill.

"php index.php --bill-currency=EGP T-shirt T-shirt Shoes Jacket"

 where the first parameter is bill currency and the second parameter is products.

Dependencies:
================================================================================
1- php 7 or more.
