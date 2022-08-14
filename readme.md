# What Is JavaScript
JavaScript (Js) is a light-weight object-oriented programming language which is used by several websites for scripting the webpages. It is an interpreted, full-fledged programming language that enables dynamic interactivity on websites when applied to an HTML document. It was introduced in the year 1995 for adding programs to the webpages in the Netscape Navigator browser. Since then, it has been adopted by all other graphical web browsers. With JavaScript, users can build modern web applications to interact directly without reloading the page every time. The traditional website uses js to provide several forms of interactivity and simplicity.
Although, JavaScript has no connectivity with Java programming language. The name was suggested and provided in the times when Java was gaining popularity in the market. In addition to web browsers, databases such as CouchDB and MongoDB uses JavaScript as their scripting and query language.

# Features of JavaScript
There are following features of JavaScript:

1. All popular web browsers support JavaScript as they provide built-in execution environments.
2. JavaScript follows the syntax and structure of the C programming language. Thus, it is a structured programming language.
3. JavaScript is a weakly typed language, where certain types are implicitly cast (depending on the operation).
4. JavaScript is an object-oriented programming language that uses prototypes rather than using classes for inheritance.
5. It is a light-weighted and interpreted language.
6. It is a case-sensitive language.
7. JavaScript is supportable in several operating systems including, Windows, macOS, etc.
8. It provides good control to the users over the web browsers.

# History of JavaScript
In 1993, **Mosaic**, the first popular web browser, came into existence. In the year **1994**, **Netscape ** was founded by **Marc Andreessen**. He realized that the web needed to become more dynamic. Thus, a 'glue language' was believed to be provided to HTML to make web designing easy for designers and part-time programmers. Consequently, in 1995, the company recruited **Brendan Eich** intending to implement and embed Scheme programming language to the browser. But, before Brendan could start, the company merged with **Sun Microsystems** for adding Java into its Navigator so that it could compete with Microsoft over the web technologies and platforms. Now, two languages were there: Java and the scripting language. Further, Netscape decided to give a similar name to the scripting language as Java's. It led to 'Javascript'. Finally, in May 1995, Marc Andreessen coined the first code of Javascript named '**Mocha**'. Later, the marketing team replaced the name with '**LiveScript**'. But, due to trademark reasons and certain other reasons, in December 1995, the language was finally renamed to '**JavaScript**'. From then, JavaScript came into existence.

# Application of JavaScript
JavaScript is used to create interactive websites. It is mainly used for:

- Client-side validation,
- Dynamic drop-down menus,
- Displaying date and time,
- Displaying pop-up windows and dialog boxes (like an alert dialog box, confirm dialog box and prompt dialog box),
- Displaying clocks etc.

# JavaScript Example
Javascript example is easy to code. JavaScript provides 3 places to put the JavaScript code: within body tag, within head tag and external JavaScript file.

Let’s create the first JavaScript example.

```

<script type="text/javascript">  
document.write("JavaScript is a simple language for Educatque learners");  
</script>  

```
The script tag specifies that we are using JavaScript.

The text/javascript is the content type that provides information to the browser about the data.

The document.write() function is used to display dynamic content through JavaScript. We will learn about document object in detail later.

# 3 Places to put JavaScript code


1. Between the body tag of html
2. Between the head tag of html
3. In .js file (external javaScript)

# JavaScript Code Between Any Body Tag
In the above example, we have displayed the dynamic content using JavaScript. Let’s see the simple example of JavaScript that displays alert dialog box.

```
<script type="text/javascript">  
 alert("Hello Javatpoint");  
</script>  
```

# JavaScript Code Between The Head Tag
Let’s see the same example of displaying alert dialog box of JavaScript that is contained inside the head tag.

In this example, we are creating a function msg(). To create function in JavaScript, you need to write function with function_name as given below.

To call function, you need to work on event. Here we are using onclick event to call msg() function.

```
<html>  
<head>  
<script type="text/javascript">  
function msg(){  
 alert("Hello Javatpoint");  
}  
</script>  
</head>  
<body>  
<p>Welcome to JavaScript</p>  
<form>  
<input type="button" value="click" onclick="msg()"/>  
</form>  
</body>  
</html>  

```
# External JavaScript file
We can create external JavaScript file and embed it in many html page.

It provides code re usability because single JavaScript file can be used in several html pages.

An external JavaScript file must be saved by .js extension. It is recommended to embed all JavaScript files into a single file. It increases the speed of the webpage.

Let's create an external JavaScript file that prints 'Hello JavaScript' in a alert dialog box.

## message.js

```
function msg(){  
 alert("Hello JavaScript");  
}  
```
Let's include the JavaScript file into html page. It calls the JavaScript function on button click.

## index.html

```
<html>  
<head>  
<script type="text/javascript" src="message.js"></script>  
</head>  
<body>  
<p>Welcome to JavaScript</p>  
<form>  
<input type="button" value="click" onclick="msg()"/>  
</form>  
</body>  
</html> 
```

# Advantages of External JavaScript

There will be following benefits if a user creates an external JavaScript:

- It helps in the reusability of code in more than one HTML file.
- It allows easy code readability.
- It is time-efficient as web browsers cache the external js files, which further reduces the page loading time.
- It enables both web designers and coders to work with html and js files parallelly and separately, i.e., without facing any code conflictions.
- The length of the code reduces as only we need to specify the location of the Js file.

# Disadvantages Of Using External JavaScript
There are the following disadvantages of external files:

- The stealer may download the coder's code using the url of the js file.
- If two js files are dependent on one another, then a failure in one file may affect the execution of the other dependent file.
- The web browser needs to make an additional http request to get the js code.
- A tiny to a large change in the js code may cause unexpected results in all its dependent files.
- We need to check each file that depends on the commonly created external javascript file.
- If it is a few lines of code, then better to implement the internal javascript code.
