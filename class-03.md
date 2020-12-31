# Class03

## HTML
-	
-	***The ordered(ol)*** list is created with the element. Each item in the list is placed between an opening and a closing tag.
Ordered lists use numbers.

-	***The unordered(ul)*** list is created with the element. Each item in the list is placed between an opening and a closing tag.
Unordered lists use bullets.

-	***The definition (dl)*** list is created with the element and usually consists of a series of terms and their definitions. Inside the element you will usually see pairs (dt) for the beginning of the definition  and (dd) the definition .
Definition lists are used to define terminology


-	You can put a ***second list*** in the (li) tag.

## CSS

By default a box is sized just big enough to hold its contents.To set your own dimensions for a box you can use the height and width properties.

Some page designs expand and shrink to fit the size of the user's screen. In such designs, the min-width property specifies the smallest size a box can be displayed at when the browser window is narrow, and the max-width property indicates the maximum width a box can stretch to when the browser window is wide.

In the same way that you might want to limit the width of a box on a page, you may also want to limit the height of it. This is achieved using the min-height and max-height properties.

The overflow property tells the browser what to do if the content contained within a box is larger than the box itself. It can have one of two values:

-	** hidden** This property simply hides any extra content that does not fit in the box.

-	**scroll** This property adds a scrollbar to the box so that users can scroll to see the missing content.

Border, Margin & Padding Every box has three available properties that can be adjusted to control its appearance. Style, color and margin

Centring content by:
1.	Text-alin:center;
2.	Controlling margin

Display:
1.	Inline
2.	Block
3.	Inline-block
4.	None

The visibility property allows you to hide boxes from users but It leaves a space where the element would have been. This property can take two values: 
1.	hidden This hides the element.
2.	visible This shows the element.

*	We can make border for images. 
*	We can do shadow for boxes.
*	We can do elliptical shapes.

## JavaScript 

***Array***
-	You create an array and give it a name just like you would any other variable (using the var keyword followed by the name of the array).
-	Values in an array are accessed as if they are in a numbered list. It is important to know that the numbering of this list starts at zero (not one).
-	You can change the value of an item an array by selecting it and assigning it a new value just as you would any other variable (using the equals sign and the new value for that item).

***IF..ELSE statements***
*	It check a condition if its true it will run if false it will run else.
*	Note that the statements inside an if statement should be followed by a semicolon, but there is no need to place one after the closing curly brace of the code blocks.

***Switch statement***
*	A switch statement starts with a variable called the switch value. Each case indicates a possible value for this variable and the code that should run if the variable matches that value.
*	u have a default option that is run if none of the cases match.
*	If a match is found, that code is run; then the break statement stops the rest of the switch statement running (providing better performance than multiple i f statements).

*** truthy and falsy values***
*	Falsy values are treated as if they are fa 1 se. The table to the left shows a hi ghScore variable with a series of values, all of which are falsy. Falsy values can also be treated as the number 0 .
*	Truthy values are treated as if they are true. Almost everything that is not in the falsy table can be treated as if it were true. Truthy values can also be treated as the number 1.

***check equality and existence***
*	Because the presence of an object or array can be considered truthy, it is often used to check for the existence of an element within a page.
*	A unary operator returns a result with just one operand. Here you can see an if statement checking for the presence of an element. If the element is found, the result is truthy, so the first set of code is run. If it is not found, the second set is run instead.
*	Because of type coercion, the strict equality operators ===and ! == result in fewer unexpected values than ==and ! = do.

***short circuit values***
*	Logical operators are processed left to right. They short-circuit (stop) as soon as they have a result - but they return the value that stopped the processing (not necessarily true or false).
*	Logical operators will not always return true or false.
*	As soon as a truthy value is found, the remaining options are not checked.

***loops***

*	we use this operators in **loops** if the condition is **true** then the loop can run
*	the loop keep running till the codition is ***false***


*	there is 3 types of loops:
1.	**FOR**
2.	**WHILE**
3.	**DO WHILE**.


*	if we want to loop for specific nubmer we use for
*	if we want to loop for non-specific number we use while -and we use do while as we use while but do while will run the code one time before checking the condition is true or false.


