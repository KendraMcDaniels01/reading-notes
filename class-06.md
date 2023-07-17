# class-06 Reading Notes

## JavaScript Object Basics

**1) How would you describe an object?**
  Objects are fundamental data structures in JavaScript, serving as a means to organize and manage data in a coherent manner.
  They consist of two primary components: Variables (also known as properties) and Functions (also known as methods).

**2) What are some advantages to creating object literals?**  
  Easy Structuring: Object literals provide a straightforward way to 
organize and structure related data items together. They allow us to 
group variables and functions that are relevant to a specific entity or 
concept in a single unit. They also allow for easy data transfer. 

**3) How do objects differ from arrays?**
  Objects composite data type that stores data in key-value pairs while arrays are a linear data structure that stores elements in a contiguous block. Accessing data in objects is done using the keys and is not solely reliant on index.
  
**4) Give an example for when you would need to use bracket notation to access an object’s property instead of dot notation.**
  When a property is held in a variable, dot notation will not work. Additionally, when the property has a name that can't be used with dot notation. 
  
**5) Evaluate the code below. What does the term this refer to and what is the advantage to using this?**
const dog = {
  name: 'Spot',
  age: 2,
  color: 'white with black spots',
  humanAge: function (){
    console.log(`${this.name} is ${this.age*7} in human years`);
  }
}
This is a keyword that refers to the current oject. It allows you to use the same functions for different objects. 
  
## Introduction To The DOM

**1) What is the DOM?**
  The document object model is the data representation of the objects taht comprise the structure and content of a document on the web.
    
**2) Briefly describe the relationship between the DOM and JavaScript.**
  The Dom representation allows the webpage to be manipulated via a script language like javascript.


   
## Things I want to know more about
