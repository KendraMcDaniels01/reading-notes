# class-01 Reading Notes

## Getting Started Notes

**1) How does HTTP send data between computers?**
  DNS server finds real address
  Browser sends a request via TCP/IP for a copy
  Server sends website files in small chunks
  Browser assembles the chunks

**2)How are HTML, css, and javascript parsed?**  
  * HTML is parsed first by the browser.
      It recognizes any <link> and <script> elements for CSS and JavaScript.
      It proceeds to request the corresponding CSS and JavaScript files specified in the <link> and <script> elements.
  * After the HTML parsing, the browser moves on to parse CSS.
      The browser constructs a CSS Object Model (CSSOM) structure based on the CSS rules found in the specified CSS files.
      The CSSOM represents the styles to be applied to the HTML elements.
  * Once CSS parsing is complete, the browser proceeds to parse JavaScript.
      The JavaScript code is compiled and executed by the browser's JavaScript engine.
      It can interact with the DOM (Document Object Model) and modify the CSSOM, adding dynamic functionality to the web page.
      Rendering and visual representation:
  * As the browser builds the DOM tree based on the parsed HTML and applies the CSSOM, it creates a visual representation of the web page on the screen.
  This visual representation, also known as the render tree, consists of the positioned and styled elements that form the webpage's layout.
  Users can see and interact with this visual representation, allowing them to navigate, click, input data, and perform other actions on the webpage.

**3)How can you find images to add to a website?**
  Use Google's license filter to reduce the liklihood og violating copyright/trademark
  
**4)How do you create a string vs. a number variable in javascript?**
  * To create a string variable, use either single or double quotes.
      Example: let stringVariable = "string";
      The value assigned to the variable should be enclosed in quotes, either single or double, to indicate that it is a string.
  * Creating a Number Variable:
      To create a number variable, no quotes are used.
      Example: let numberVariable = 62;
      The value assigned to the variable is a numerical value without any quotation marks.
      
**5)What are variables and why are they important?**
  variables act as containers for storing data in programming. Their 
  dynamic nature allows for flexibility, enabling developers to create 
  adaptable code that can respond to changing conditions. By utilizing 
  variables effectively, programmers can enhance code flexibility, improve
   code organization, and create efficient solutions
   
   
## Getting Started Notes

**1) What is an HTML attribute?**
  * Definition:
    HTML attributes provide additional information about HTML elements.
    They specify characteristics or properties related to the element's behavior, appearance, or functionality.
  * Structure:
    An attribute is placed within the opening tag of an HTML element.
    It consists of the attribute name, an equal (=) sign, and the attribute value enclosed in quotes.
    Attributes are separated by spaces if multiple attributes are present within a single opening tag.
  * Example:
    <tag attribute="attribute-name">content</tag>
    The opening tag of the HTML element contains the attribute, where "tag" represents the HTML tag, "attribute" is the attribute name, and "attribute-name" is the specific value assigned to the attribute.
    The attribute value is enclosed in quotes, either single or double quotes, to indicate the attribute's value.
    
**2) Anotomy of an element:**
  * Opening tag <>, content, closing tag </>
  * void elements do not have closing tags
    * used to insert or imbed

**3) What is the Difference between <article> and <section> element tags?**
  The <article> and <section> element tags serve different purposes in HTML.
  The <article> element represents self-contained, standalone content that can be independently distributed or syndicated.
  It typically represents a complete composition, such as a blog post, news article, or forum post.
  On the other hand, the <section> element is a generic sectioning element used to divide content into thematic groups.
  It should be used when there is no more specific semantic element available
  
**4) What element does a website typically have?**
  A head element

**5) How does metadata influence search engine optimization?**
  * Influence of Metadata on SEO:
    Metadata plays a crucial role in search engine optimization (SEO) by providing relevant information to search engines.
    Search engines analyze metadata to understand the content and relevance of a web page, which impacts its visibility in search results.

**6) How is the <meta> HTML tag used when specifying metadata?**
  The <meta> HTML tag is used to specify metadata for a web page.
  It is a void element, meaning it does not require a closing tag.
  The <meta> tag is placed within the <head> section of an HTML document.
  The name attribute specifies the type of metadata being defined, such as "author" or "description".
  The content attribute contains the actual value or content of the metadata.
  Example: <meta name="author" content="John Doe">
  By including relevant metadata, such as the author and page description, search engines and other applications can better understand and categorize the web page.
 

## Miscellaneous

### How to start to design a Website

**1) What is the first step to designing a webpage? 2) Most important question?**
  * Project Ideation: 
    The first step in designing a webpage involves project ideation and asking critical questions.
    The most important question to consider is: What do you want to accomplish with the website?
    This question helps clarify the purpose and goals of the webpage.
    It is crucial to understand how a website will help achieve those goals.
    Consider what needs to be done and in what order to ensure a structured approach to the design process.

### Semantics

**1) Why should you use an \<h1> element over a <span> element to display a top level heading?**
  When displaying a top-level heading on a webpage, it is recommended to use the <h1> element.
  The <h1> element is a semantic HTML element that assigns the role of a top-level heading to the content within it.
  Semantics refer to the meaning and structure of HTML elements, allowing search engines and assistive technologies to understand the purpose and hierarchy of the content.
  Although the visual appearance of <span> can be modified to resemble a header, it lacks the semantic significance provided by the <h1> element.
  Search engines and other readers of the code rely on semantic elements like <h1> to understand the structure and importance of the content.

**2) What are the benefits of using semantic tags in our HTML?**
  They provide a clear and meaningful representation of the code's purpose and intended functionality.
  Semantic tags improve the overall structure and organization of the HTML document.
  By using tags like <header> the layout and sections of the webpage become more evident.
  Semantic tags enhance accessibility to better interpret and navigate the content.
  Search engines also benefit from semantic tags, as they can understand the context and relevance of the webpage's content.
  
### What is JavaScript?

**1) Describe 2 things that require JavaScript in the Browser:**
  JavaScript in the browser empowers developers to create dynamic content 
  that updates in real-time and offers control over multimedia elements. 
  These capabilities enhance interactivity, user experience, and the 
  overall functionality of web applications.

**2) How can you add JavaScript to an HTML document?**
  * Using the <script> Element:
    JavaScript can be added to an HTML document using the <script> element.
    The <script> element is placed within the <head> or <body> section of the HTML document.
    It can be used to embed JavaScript code directly within the HTML file.
  * External JavaScript File:
    Alternatively, JavaScript code can be stored in an external file with the .js filename extension.
    To include an external JavaScript file, use the <script> element with the src attribute.
    The src attribute specifies the path to the external JavaScript file.
      Examples:
      Inline JavaScript within <script> tags:
      <script>
        // JavaScript code here
      </script>

      External JavaScript file inclusion:
      <script src="script.js"></script>

## Things I want to know more about
