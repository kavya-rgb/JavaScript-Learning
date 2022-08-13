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
This Code Shown Above Is Displayed In The [Index.html](https://kavya-rgb.github.io/JavaScript-Learning/JavaScript%20Example/index.html) File.