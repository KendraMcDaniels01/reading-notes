# class-02 Reading Notes

## Basics of HTML, CSS & JS

**1) Why is it important to use semantic elements in our HTML??**
  They provide a clear and meaningful representation of the code's purpose and intended functionality.
  Semantic tags improve the overall structure and organization of the HTML document.
  By using tags like \<header> the layout and sections of the webpage become more evident.
  Semantic tags enhance accessibility to better interpret and navigate the content.
  Search engines also benefit from semantic tags, as they can understand the context and relevance of the webpage's content.

**2) How many levels of headings are there in HTML?**  
  6

**3) What are some uses for the \<sup> and \<sub> elements?**
  They are commonly used for dates or math expressions. 
      
**4) When using the \<abbr> element, what attribute must be added to provide the full expansion of the term?**
  When using the \<abbr> element in HTML, the "title" attribute must be added to provide the full expansion of the term.
  The "title" attribute specifies the full text or expansion of the abbreviated term.
  It allows users to view the complete meaning or description of the abbreviation when they hover over or interact with the element.
  Including the full expansion enhances accessibility and provides additional context for users who may be unfamiliar with the abbreviation.
   
   
## Learn CSS

**1) What are ways we can apply CSS to our HTML?**
  * CSS (Cascading Style Sheets) can be applied by using:
    * External Stylesheets: defined in an external .css file and linked to the HTML document using the \<link> element. This allows for the consistent application of styles across multiple web pages.
    * Internal Stylesheet: written within the \<style> tags in the \<head> section of an HTML document. This method is useful when applying specific styles to a single HTML file.
    * Inline Style: applied directly to individual HTML elements using the "style" attribute. This allows for immediate, element-specific styling, but can be less efficient for larger-scale applications.
    
**2) Why should we avoid using inline styles?**
  Mixing CSS rules within HTML markup can lead to cluttered code, reducing readability and making it challenging to identify and isolate styling information.
  Separating CSS into external or internal stylesheets allows for better code organization and improves maintainability.

**3) Review the block of code below:**
   h2 {
     color: black;
     padding: 5px;
   }
    1. What is representing the selector? h is the element that will have the CSS property applied; it is the subject of the selector
    2. Which components are the CSS declarations? A property paired with a value are called CSS declarations. 
    3. Which components are considered properties? In the example color and padding are the properties and the black and 5px are the values


### Learn JS

**1) What data type is a sequence of text enclosed in single quote marks?**
  a string

**2) List 4 types of JavaScript operators. 3) List 3 different types of comparison operators.**
  * addition (+), subtraction (-), multiplication (*), division (/)
  * (==), not equal to (!=), greater than (>), less than (<), greater 
    than or equal to (>=), and less than or equal to (<=)
                                                         
**3) Describe a real world Problem you could solve with a Function?**
  By calling this function whenever needed, you avoid duplicating the code and ensure consistency in the calculation process.
  Functions promote code modularity, readability, and maintainability, allowing you to solve real-world problems efficiently while reducing redundancy.
                                                     
### Making Decisions In Your Code – Conditionals.

**1) An if statement checks a** _a condition to check_ **and if it evaluates to** _be true_, **then the code block will execute.**

**2) What is the use of an else if?**
  the "else if" statement is useful for creating branching logic with multiple conditions. It allows for handling more than two possible 
  outcomes by chaining multiple "if" and "else if" statements together. 
  This construct provides flexibility in controlling program flow based on
  different scenarios and conditions.

**4) What is the difference between the logical operator && and ||?**
  * The logical operator && (AND) and || (OR) are used to evaluate conditions and return a Boolean value.
  * The && operator evaluates to true only if all of its operands (arguments) are true. It returns false if any of the operands are false.
  * The || operator evaluates to true if any of its operands are true. It returns false only if all operands are false.
  
  
## Things I want to know more about
