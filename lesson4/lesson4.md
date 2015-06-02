## "JavaScript for Kids" Coding Class
### May/June 2015 - 4th and 5th Grade
### Lesson 4

--- 

## Welcome to Lesson 4!

---

# _Lesson 4_
- Recap of Lesson 3 (Objects)
- HTML
-- Creating your first HTML Page
-- Calling JavaScript from HTML
-- Asking the user for input
-- Changing the page
-- Creating a simple form

---

# HTML

---

# HyperText Markup Language

---

# Every Web Page is created using HTML!

---

# What does HTML look like?

---

## What does HTML look like?

```html
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
	<h1>My First Web Page</h1>
</body>
</html>
```

--- 

## Task: Open step1.html in Firefox, and change the text.

---

# Adding JavaScript to your page

---

## Adding JavaScript to your page

```html
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
	<h1>My First Web Page</h1>	
</body>
</html>
```

---

## Adding JavaScript to your page

```html
<html>
<head>
    <title>My First Web Page</title>
    <script>





    </script>
</head>
<body>
	<h1>My First Web Page</h1>	
</body>
</html>
```

---

## Adding JavaScript to your page

```html
<html>
<head>
    <title>My First Web Page</title>
    <script>
   
    var sayHello = function(){
    	alert("Hello there!");
    };

    </script>
</head>
<body>
	<h1>My First Web Page</h1>	
</body>
</html>
```

---

## Adding JavaScript to your page

```html
<html>
<head>
    <title>My First Web Page</title>
    <script>
   
    var sayHello = function(){
    	alert("Hello there!");
    };

    </script>
</head>
<body>
	<h1>My First Web Page</h1>	
	<button onclick="sayHello()">Click me!</button>
</body>
</html>
```

---

## Task: Add the say hello method to your page

---

# Asking the user for information

---

## Asking the user for information

```html
<html>
<head>
	<meta charset="UTF-8">
    <title>My First Web Page</title>
    <script>
   
    var sayHello = function(){
    	alert("Hello there!");
    };

    </script>
</head>
<body>
	<h1>My First Web Page</h1>	
	<button onclick="sayHello()">Click me!</button>
</body>
</html>
```

---

## Asking the user for information

```html
<html>
<head>
    <meta charset="UTF-8">
    <title>My First Web Page</title>
    <script>
   
    var sayHello = function(){
    	var name = prompt("What is your name?");
    	alert("Pleased to meet you, " + name);
    };

    </script>
</head>
<body>
	<h1>My First Web Page</h1>
	<button onclick="sayHello()">Click me!</button>
</body>
</html>
```

---

## Task: Add the code to ask for the user's name 

---

# Changing the page

---

## Changing the page

```html
<html>
<head>
    <meta charset="UTF-8">
    <title>My First Web Page</title>
    <script>
   
    var sayHello = function(){
    	var name = prompt("What is your name?");
    	alert("Pleased to meet you, " + name);
    };

    </script>
</head>
<body>
	<h1>My First Web Page</h1>
	<button onclick="sayHello()">Click me!</button>
</body>
</html>
```

---

## Changing the page

```html
<h1 id="name"></h1>
```

---

## Changing the page

```javascript
document.getElementById("name").innerHTML = "Pleased to meet you, " + name;
```

---

## Changing the page

```html
<html>
<head>
    <meta charset="UTF-8">
    <title>My First Web Page</title>
    <script>
   
    var sayHello = function(){
    	var name = prompt("What is your name?");
    	document.getElementById("name").innerHTML = "Pleased to meet you, " + name;
    };

    </script>
</head>
<body>
	<h1>My First Web Page</h1>
	<button onclick="sayHello()">Click me!</button>
	<h1 id="name"></h1>
</body>
</html>
```

---

## Task: Add the code to change the page when the user enters their name

---

## Creating a simple form

---

## Creating a simple form

```html
<input id="age"/>
<button onclick="ageInDogYears()">My Age in Dog Years</button>
<h2 id="dogyears"></h2>
```

---

## Creating a simple form

```javascript
var ageInDogYears = function(){
	var age = document.getElementById("age").value;
	var ageInDogYears = age * 7;
	document.getElementById("dogyears").innerHTML = "In dog years, you are " + ageInDogYears + " years old";
}
```

---

## Creating a simple form

```html
<html>
<head>
    <meta charset="UTF-8">
    <title>My First Web Page</title>
    <script>
    var ageInDogYears = function(){
    	var age = document.getElementById("age").value;
    	var ageInDogYears = age * 7;
    	document.getElementById("dogyears").innerHTML = "In dog years, you are " + ageInDogYears + " years old";
    }
    </script>
</head>
<body>
	<h1>My First Web Page</h1>
	<input id="age"/>
	<button onclick="ageInDogYears()">My Age in Dog Years</button>
	<h2 id="dogyears"></h2>
</body>
</html>
```

---

## Task: Add the code to ask the user for their age and return the value in dog years