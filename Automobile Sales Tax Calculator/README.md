# AutoMobile Sales Tax Calculator
### Computes the sales tax for a collection of automobiles of different types. 
This program consists of four classes:
## 1. The Automobile class
### Contains the automobile’s make and model, and purchase price, which is specified in whole dollars. 
### Methods:
1. A **constructor** that allows the make and purchase price to be initialized.
2. A method named **salesTax** that returns the base sales tax computed as 5% of the sales price.
3. A **toString** method that returns a string containing the make and model of the automobile, the sales price, and the sales tax, appropriately labeled.
## 2. The Electric Class (subclass of Automobile). 
### Has an additional instance variable that contains its weight in pounds stored as an integer. 
### Methods:
1. A **constructor** that allows the automobile’s make and model, purchase price and weight to
be initialized.
2. An **overridden method salesTax** that returns the total sales tax. The sales tax for an
electric automobile consists of the base sales tax of 5% that applies to all automobiles
minus a discount. If the weight is less than 3000 pounds the discount is $200. Otherwise
it is $150.
3. An **overridden toString** method that returns a string containing the make and model of
the automobile, the sales price, sales tax and the weight, appropriately labeled.
## 3. The Hybrid Class (subclass of Automobile). 
### Has an additional instance variable that contains the number of miles per gallon stored as an integer. 
### Methods:
1. A **constructor** that allows the automobile’s make and model, purchase price and miles per
gallon to be initialized.
2. An **overridden method salesTax** that returns the total sales tax The sales tax for a hybrid
automobile consists of the base sales tax of 5% minus a discount. If the number of miles
per gallon is less than 40, the discount is $100. Otherwise there is an additional discount
of $2 for every mile per gallon in excess of 40.
3. An **overridden toString** method that returns a string containing the make and model of
the automobile, the sales price, sales tax and the number of miles per gallon,
appropriately labeled.
**No additional public methods should be included in any of the above three classes.**

## 4. The Project2 Class (with the main method)
### Generate the GUI shown below:
1. After entering the information about the make and model, its sales price and the type of the automobile, clicking the Compute Sales Tax button should display the sales tax in the text field to its right. In addition, the object should be stored in an array of type Automobile. That array should allow space for up to the last five automobiles entered.

2. If non integer values are entering in any of the fields that require integers, an error message should be displayed in a JOptionPane window.

3. Clicking the Clear Fields button should clear all text fields.

4. Clicking the Display Report button should produce a report on the console that includes the information about all the automobiles currently stored in the array. 
An example of the report that should be displayed is shown below:

Make and Model: Toyota Prius
Sales Price: 30000
Sales Tax: 1390.00
Hybrid Vehicle
MPG: 45
Make and Model: Ford Fusion
Sales Price: 21000
Sales Tax: 1050.00

*Be sure to follow good programming style*

#### Useful resources: 
1. [AWT Event Handling](https://www.tutorialspoint.com/awt/pdf/awt_event_handling.pdf)
2. [GUI Event Handling](http://www2.mta.ac.il/~urishamay/JavaResources/swingeventhandling.pdf)
3. [JavaFX Java GUI Tutorial ](https://www.youtube.com/watch?v=FLkOX4Eez6o)
