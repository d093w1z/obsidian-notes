## Unit 1 - Web Essentials and Mark-up language

**1. What are the different website design issues?**
1. Slow Page Loading Speed
2. Not Optimized for Mobile
3. Poor UI/UX Design
4. Poor SEO and Content
5. Broken Pages and Links
6. Too Much Clutter
7. Hidden Basic Information
8. Lack of Human Element
9. Security and Certification Issues

**3a. internet vs www**
| S.No. | INTERNET                                                                                  | WWW                                                                                     |
| ----- | ----------------------------------------------------------------------------------------- | --------------------------------------------------------------------------------------- |
| 1     |  a global network of networks.                                                 | WWW stands for World wide Web.                                                          |
| 2     |  a means of connecting a computer to any other computer anywhere in the world. | World Wide Web which is a collection of information which is accessed via the Internet. |
| 3     |  infrastructure.                                                               | WWW is service on top of that infrastructure.                                           |
| 4     | Internet can be viewed as a big book-store.                                               | Web can be viewed as collection of books on that store.                                 |
| 5     | At some advanced level, to understand we can think of the Internet as hardware.           | At some advanced level, to understand we can think of the WWW as software.              |
| 6     |  primarily hardware-based.                                                     | WWW is more software-oriented as compared to the Internet.                              |
| 7     | It is originated sometimes in late 1960s.                                                 | English scientist Tim Berners-Lee invented the World Wide Web in 1989.                  |
| 8     |  superset of WWW.                                                              | WWW is a subset of the Internet.                                                        |
| 9     | The first version of the Internet was known as ARPANET.                                   | In the beginning WWW was known as NSFNET.                                               |
| 10    | Internet uses IP address.                                                                 | WWW uses HTTP.                                                                          |



**4. Differentiate HTML Vs HTML5**
| **Parameter**         | **HTML**                  | **HTML5**                 |
| --------------------- | ------------------------- | ------------------------- |
| Memory sotrage        | cookies                   | db for webpage            |
| browser compatibility | old                       | new & old                 |
| Mobile friendliness   | no                        | yes                       |
| Multimedia support    | external plugins required | tags \<audio\\>, \<video\\> |
| location support      | not accesible             | js geolocation api        |
| js support            | not allowed directly      | js webworker api          |
| syntax complexity     | complex and long          | short and simple          |
| semantic tags         | does not contain          | contains                  |

**5. Write and explain text formatting tags in HTML.**
| **Element name** | **Description**                                                                         |
| ---------------- | --------------------------------------------------------------------------------------- |
|  <b\>              | This is a physical tag, which is used to bold the text written between it.              |
|  <strong\>         | This is a logical tag, which tells the browser that the text is important.              |
|  <i\>              | This is a physical tag which is used to make text italic.                               |
|  <em\>             | This is a logical tag which is used to display content in italic.                       |
|  <mark\>           | This tag is used to highlight text.                                                     |
|  <u\>              | This tag is used to underline text written between it.                                  |
|  <tt\>             | This tag is used to appear a text in teletype. (not supported in HTML5)                 |
|  <strike\>         | This tag is used to draw a strikethrough on a section of text. (Not supported in HTML5) |
|  <sup\>            | It displays the content slightly above the normal line.                                 |
|  <sub\>            | It displays the content slightly below the normal line.                                 |
|  <del\>            | This tag is used to display the deleted content.                                        |
|  <ins\>            | This tag displays the content which is added                                            |
|  <big\>            | This tag is used to increase the font size by one conventional unit.                    |
| <small\>          | This tag is used to decrease the font size by one unit from base font size.             |

**7. Write the HTML code with example to explain internal and external CSS**

-   **Internal or embedded** ⁠— add **<style\>** tag in the **<head\>** section of HTML document
-   **External** ⁠— link the HTML sheet to a separate **.css** file
-   **Inline** ⁠— apply CSS rules for specific elements.

```html
<!DOCTYPE html>
<html>
<head>
<!-- External CSS -->
<link rel="stylesheet" type="text/css" href="style.css" /> 
<!-- Internal CSS -->
<style>
body {
    background-color: blue;
}
h1 {
    color: red;
    padding: 60px;
} 
</style>
</head>
<!-- Inline CSS -->
<body style="background-color:black;">
<h1 style="color:white;padding:30px;">Hostinger Tutorials</h1>
<p style="color:white;">Something usefull here.</p>

</body>
</html>
```

**8. Write and explain text related CSS properties.**
| Property | Description | Values |
|----|----|-----|
|color|Sets the color of a text|RGB, hex, keyword|
|line-height|Sets the distance between lines|normal, _number, length, %_|
|letter-spacing|Increase or decrease the space between characters|normal, _length_|text-align|Aligns the text in an element|left, right, center, justify|
|text-decoration|Adds decoration to text|none, underline, overline, line-through|
|text-indent|Indents the first line of text in an element|length, %|
|text-transform|Controls the letters in an element|none, capitalize, uppercase, lowercase|

## Unit 2 - Client Side Technologies: JavaScript and DOM

**20. Explain the concept of DOM. What is intrinsic event handling in DOM?**

### DOM (Document Object Model)

The Document Object Model (DOM) is a _**programming interface**_ for **HTML(HyperText Markup Language)** and **XML**(Extensible markup language) documents. It defines the **logical structure** of documents and the way a document is accessed and manipulated.
DOM is a way to represent the webpage in a structured hierarchical way so that it will become easier for programmers and users to glide through the document. With DOM, we can easily access and manipulate tags, IDs, classes, Attributes, or Elements of HTML using commands or methods provided by the Document object. Using DOM, the JavaScript gets access to HTML as well as CSS of the web page and can also add behavior to the HTML elements. so basically **Document Object Model is an API that represents and interacts with HTML or XML documents.**

### **THE DOM EVENT HANDLING**

One of the keys to creating dynamic web pages is the use of event handlers. These allow you to execute specific script code in response to user or system initiated actions.Most events relate to the browser GUI, such as mouse movements, button or key clicks and updates to form inputs. These are usually tied to a specific page element. Others relate to browser actions such as when a document or image completes loading.Some objects have default actions defined for certain events, such as clicking on a hypertext link. The browser's normal action in that event is to load the URL associated with the link.

In any case, all events follow the same model. The DOM provides methods for capturing events so you can perform your own actions in response to them. It also provides an Event object which contains information specific to a given event that can be used by your event processing code

**21. Explain the concept of jQuery with example.**
## What is jQuery?

jQuery is a lightweight, "write less, do more", JavaScript library.

The purpose of jQuery is to make it much easier to use JavaScript on your website.

jQuery takes a lot of common tasks that require many lines of JavaScript code to accomplish, and wraps them into methods that you can call with a single line of code.

jQuery also simplifies a lot of the complicated things from JavaScript, like AJAX calls and DOM manipulation.

Points:
-   jQuery is a small, fast and lightweight JavaScript library.
-   jQuery is platform-independent.
-   jQuery means "write less do more".
-   jQuery simplifies AJAX call and DOM manipulation.

The jQuery library contains the following features:

-   HTML/DOM manipulation
-   CSS manipulation
-   HTML event methods
-   Effects and animations
-   AJAX
-   Utilities

```html 
<!DOCTYPE html>  
<html>  
<head>  
 <title>First jQuery Example</title>  
 <script type="text/javascript" src="https://ajax.googleapis.com/ajax/libs/jquery/2.1.3/jquery.min.js">  
 </script>  
 <script type="text/javascript" language="javascript">  
 $(document).ready(function() {  
 $("p").css("background-color", "cyan");  
 });  
 </script>  
 </head>  
<body>  
<p>The first paragraph is selected.</p>  
<p>The second paragraph is selected.</p>  
</body>  
</html>  
```

**23. Explain the different jQuery selector with example for each.**
| Selector     | Example                  | Description                                                         |
| ------------ | ------------------------ | ------------------------------------------------------------------- |
| \*            | $("\*")                   | It is used to select all elements.                                  |
| \#id          | $("#firstname")          | It will select the element with id="firstname"                      |
| .class       | $(".primary")            | It will select all elements with class="primary"                    |
| class,.class | $(".primary,.secondary") | It will select all elements with the class "primary" or "secondary" |
| element      | $("p")                   | It will select all p elements.                                      |
| el1,el2,el3  | $("h1,div,p")            | It will select all h1, div, and p elements.                         |
