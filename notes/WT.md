---
sticker: 1f5a5-fe0f
---
**Unit III Java Servlets and XML**
- [x] Servlet:
    - [x] Servlet architecture overview
    - [x] A “Hello World” servlet
    - [x] Servlets generating dynamic content
    - [x] Servlet life cycle
    - [x] parameter data
    - [x] sessions
    - [x] cookies
    - [x] URL rewriting 
    - [ ] other Servlet capabilities
    - [ ] data storage
    - [ ] Servlets concurrency
    - [ ] databases (MySQL) and Java Servlets
- [x] XML:
    - [x] XML documents and vocabularies
    - [x] XML declaration
    - [x] XML Namespaces
    - [x] DOM based XML processing
    - [x] transforming XML documents
    - [x] DTD:
        - [x] Schema
        - [x] elements
        - [x] attributes
- [x] AJAX:
    - [x] Introduction
    - [x] Working of AJAX
  
Unit IV JSP and Web Services
- [ ] JSP:
    - [x] Introduction to Java Server Pages
    - [x] JSP and Servlets
    - [ ] running JSP applications
    - [x] Basic JSP
    - [ ] JavaBeans classes and JSP
    - [ ] Support for the Model-view-controller paradigm
    - [ ] JSP related technologies
- [ ] Web Services:
    - [ ] Web Service concepts
    - [ ] Writing a Java Web Service
    - [ ] Writing a Java web service client
    - [ ] Describing Web Services: WSDL
    - [ ] Communicating Object data: SOAP
- [ ] Struts:
    - [ ] Overview
    - [ ] architecture
    - [ ] configuration
    - [ ] actions
    - [ ] interceptors
    - [ ] result types
    - [ ] validations
    - [ ] localization
    - [ ] exception handling
    - [ ] annotations
  
Unit V Server Side Scripting Languages
- [ ] PHP:
    - [x] Introduction to PHP
    - [x] uses of PHP
    - [x] general syntactic characteristics
    - [x] Primitives
    - [x] operations and expressions
    - [x] output
    - [x] control statements
    - [x] arrays
    - [ ] functions
    - [ ] pattern matching
    - [x] form handling
    - [ ] files
    - [x] cookies
    - [x] session tracking
    - [x] using MySQL with PHP
    - [ ] WAP and WML
- [ ] Introduction to ASP.NET:
    - [ ] Overview of the .NET Framework
    - [ ] Overview of C#
    - [ ] Introduction to ASP.NET
    - [ ] ASP.NET Controls
    - [ ] Web Services
- [x] Overview of Node JS
  
Unit VI Ruby and Rails
- [ ] Introduction to Ruby:
    - [ ] Origins & uses of Ruby
    - [ ] scalar types and their operations
    - [ ] simple input and output
    - [ ] control statements
    - [ ] fundamentals of arrays
    - [ ] hashes
    - [ ] methods
    - [ ] classes
    - [ ] code blocks and iterators
    - [ ] pattern matching
- [ ] Introduction to Rails:
    - [ ] Overview of Rails
    - [ ] Document Requests
    - [ ] Processing Forms
    - [ ] Rails Applications and Databases
    - [ ] Layouts
    - [ ] Rails with Ajax
- [ ] Introduction to EJB

pyq
servlet lifecycle
hello world code servlet 
explain cookies & session 
xml schema 
internal external dtd
xslt example
diff xml & xslt
xml transforming 
client vs server 
dtd full topic
servlet architecture 
jsp architecture 
jsp lifecycle 
ajax
servlet vs jsp
jsp code
xmlhttp req object 
include directive
include actions
jsp implicit objs(atleast 5)
jsp all
webservices
uddi
soap
rest
MVC
struts 
struts.xml
web.xml
config files 
data tags struts 
interceptors 
localization 




### Compare `doGet()` and `doPost()` methods in servlet.

1. Purpose:
    
    - `doGet()`: This method is used to handle HTTP GET requests.
    - `doPost()`: This method is used to handle HTTP POST requests.
2. HTTP Verb:
    
    - `doGet()`: Corresponds to the HTTP GET verb.
    - `doPost()`: Corresponds to the HTTP POST verb.
3. Parameters:
    
    - `doGet()`: Parameters are part of the URL query string.
    - `doPost()`: Parameters are sent in the request body.
4. Data length:
    
    - `doGet()`: Limited by the maximum length of the URL.
    - `doPost()`: Not limited by the URL length, can handle larger data sets.
5. Security:
    
    - `doGet()`: Parameters are visible in the URL.
    - `doPost()`: Parameters are not visible in the URL, more secure for sensitive data.
6. Caching:
    
    - `doGet()`: GET requests can be cached by browsers or intermediate caching servers.
    - `doPost()`: POST requests are not cached by default.
7. Usage:
    
    - `doGet()`: Typically used for retrieving data or performing read-only operations.
    - `doPost()`: Typically used for submitting forms, creating new resources, or modifying data.

### Process of transforming XML document.

The process of transforming an XML document involves using an XML transformation language, such as XSLT, to convert the XML document into another format or structure. Here are the steps involved:

1. Define the Transformation Logic:
    
    - Create an XSLT stylesheet that defines the transformation rules.
2. Load the XML Document and XSLT Stylesheet:
    
    - Load the source XML document.
    - Load the XSLT stylesheet.
3. Create a Transformer:
    
    - Create an instance of a transformer object.
4. Set Transformation Parameters (Optional):
    
    - Set any required parameters on the transformer object.
5. Perform the Transformation:
    
    - Call the `transform()` method on the transformer object.
6. Handle the Transformed Output:
    
    - Save the transformed output to a file, send it as a response, or process it further.

### HTTP session

An HTTP session is a mechanism used to maintain stateful communication between a web server and a web client over a series of HTTP requests and responses. It allows the server to recognize and remember individual clients and their associated data.

Here's an overview of how an HTTP session works:

1. Session Creation:
    
    - When a client initiates a request, the server creates a unique session for that client.
    - The server generates a unique session identifier, typically stored in a cookie or URL.
2. Session Tracking:
    
    - The client includes the session ID in each request.
    - The server uses the session ID to track the client and retrieve session data.
3. Server-Side Data Storage:
    
    - The server maintains a data structure (session store) to store session-related data.
4. Accessing Session Data:
    
    - On each request, the server retrieves the session ID from the client.
    - The server accesses the corresponding session data from the session store.
5. Session Expiry and Inactivity Timeout:
    
    - Sessions have an expiration time or inactivity timeout.
    - Expired sessions are removed from the session store.
6. Session Termination:
    
    - The client can delete the session cookie or stop including the session ID.
    - The server can invalidate the session programmatically or based on certain conditions.

### Explain XML with respect to structure, declaration syntax, and namespace.

XML (eXtensible Markup Language) is a markup language designed to store and transport structured data. It provides a way to describe and organize data in a hierarchical format, making it suitable for a wide range of applications.

Structure:

- XML documents consist of text-based data organized hierarchically using elements.
- Elements are enclosed within start and end tags.
- Elements can contain other elements, forming a tree-like structure.
- Elements can have attributes associated with them.

Declaration Syntax:

- XML documents begin with an optional XML declaration.
- The declaration specifies the XML version and encoding.
- The declaration is enclosed within `<?xml ... ?>` tags.

Namespace:

- XML namespaces are used to avoid naming conflicts between elements and attributes.
- Namespaces are declared using a prefix and a URI.
- The prefix is a shorthand alias for the namespace.
- The namespace declaration is usually placed in the root element.

Example of an XML document with structure, declaration, and namespace:

```xml
<?xml version="1.0" encoding="UTF-8"?>
	<rootElement xmlns:prefix="http://www.example.com/namespace">
		<prefix:element attribute="value">
			<subElement>Text content</subElement>
		</prefix:element> 
	</rootElement>`
```


By leveraging XML's structure, declaration syntax, and namespace support, you can create well-organized and semantically meaningful documents for data exchange and processing.

### Explain the Struts architecture with a neat diagram and also explain the benefits of Struts.

![Struts Architecture Diagram](strut_architecture.jpg)


The Struts framework follows the Model-View-Controller (MVC) architectural pattern and provides a structured approach to application development. The key components of the Struts architecture are:

1. Controller (ActionServlet):
    
    - Central controller that receives and processes incoming HTTP requests.
    - Delegates requests to appropriate Action classes.
2. Action:
    
    - Encapsulates the business logic for processing requests.
    - Handles incoming requests, performs processing, and prepares data for the view.
3. ActionForm:
    
    - Represents the data submitted by the user or required for processing.
    - Validates user input and transfers data between the view and the Action.
4. Model (Business Logic):
    
    - Represents the business logic or services required for processing requests.
    - Performs data processing, calculations, and interacts with external systems.
5. View (JSP):
    
    - Renders the user interface and presents data to the user.
    - Typically uses JSP pages for generating dynamic content.
6. Struts Tag Library:
    
    - Provides custom tags for form handling, input validation, and data presentation.

Benefits of Struts:

1. MVC Architecture: Struts enforces separation of concerns and promotes code organization, modularity, and maintainability.
    
2. Reusability and Extensibility: Struts components can be easily extended or customized, promoting code reusability.
    
3. Simplified Form Handling: Struts simplifies form handling, automatically populating data, performing validation, and providing error handling.
    
4. Built-in Request Processing: Struts provides a request processing pipeline, handling parameter parsing and error handling.
    
5. Integration with Other Technologies: Struts integrates well with Hibernate, Spring, Tiles, and other technologies, leveraging their benefits.
    
6. Community and Ecosystem: Struts has a large community with extensive documentation and resources, providing support and knowledge sharing.
    

Overall, Struts offers a structured approach to web application development, promoting code organization, reusability, and maintainability. It simplifies development and provides a robust foundation for building applications.