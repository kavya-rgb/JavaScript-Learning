
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
