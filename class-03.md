# class-03 Reading Notes

## Ordered and Unordered lists

**1) When should you use an unordered list in your HTML document? 3) When should you use an ordered one?**
  * Unordered lists in HTML are used when the order of the list items is not important, typically for creating bullet point lists.
  * In contrast, an ordered list should be used when the order of items holds significance, such as step-by-step instructions or a ranking system.

**2) How do you change the bullet style of unordered list items?**  
  by tabbing with in the code

**4) Describe two ways you can change the numbers on list items provided by an ordered list?**
  the "reversed" attribute in the \<ol> element reverses the numbering of list items in an ordered list, while the "start" attribute in an individual \<li> element allows you to start numbering from a custom value. 
      
     
## The Box Model

**1) Describe the CSS properties of margin and padding. 2) List and describe the four parts of an HTML elements box as referred to by the box model.**
  * Content:
    The content area is where the actual content, such as text or images, is displayed.
    It is influenced by the width and height properties.
  * Padding:
    Padding sits around the content area, providing space between the content and the border.
    It can be adjusted using the "padding" CSS property.
  * Border:
    The border encloses the content and padding, creating a visible boundary.
    It can be customized in terms of style, color, and width using the "border" CSS property.
  * Margin:
    The margin is the outermost layer of the box model, wrapping the content, padding, and border.
    It provides space between the element and other neighboring elements.
    The margin can be adjusted using the "margin" CSS property.
    

### Arrays.Operators and Expressions.Conditionals.Loops.

**1) What data types can you store inside of an Array?**
  Arrays can store various data types, and they also allow mixing different data types within the same array, including other arrays.

**2) Is the people array a valid JavaScript array?  If so, how can I access the values stored? 
If not, why? const people = [['pete', 32, 'librarian', null], ['Smith', 40, 'accountant', 'fishing: hiking:rock_climbing'], ['bill', null, 'artist', null]];**
  Yes, it is a proper array. The values of an array can be accessed via their index number with the first value in the array having an index of 0.
                                                         
**3) List five shorthand operators for assignment in javascript and describe what they do.**
  x += f() addition assignment
  x -= f() subtraction assignment
  x \*= f() multiplication assignment
  x \*\*= f() exponent assignment
  x /= f() division assignment
                                                    
**4) Read the code below and evaluate the last expression and explain what the result would be and why.
 let a = 10;
 let b = 'dog';
 let c = false;
 (a + c) + b;**
 * (a + c) = 10: 
  * The variable a has a value of 10, which is a number.
  * The variable c has a value of false, which is a boolean which will have a value o 0 when added to 10
* (a + c) + b = '10dog'
  * 10 is converted to a string and then concatenated with 'dog'.

**2) Describe a real world example of when a conditional statement should be used in a JavaScript program.**
  When code should only be executed when specific conditions are met.

**4) Give an example of when a Loop is useful in JavaScript.**
  Loops are good for executing the same code repeatedly often with slight variates ecah time. One use case for this would be printing out the values in an array.
  
  
## Things I want to know more about
