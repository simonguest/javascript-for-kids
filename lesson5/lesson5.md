## "JavaScript for Kids" Coding Class
### May/June 2015 - 4th and 5th Grade
### Lesson 5

--- 

## Welcome to Lesson 5!

---

# _Lesson 5_
- Recap of Lesson 4 (HTML)
- More HTML
-- Colors!
-- Comments
-- For Loops
-- Showing and Hiding Elements
-- Divs

---

# Colors in HTML

---

## Colors in HTML

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

## Colors in HTML

```html
<html>
<head>
    <title>My First Web Page</title>
</head>
<body>
    <h1 style="color:red">My First Web Page</h1>
</body>
</html>
```

--- 

## Task: Open colors.html in Firefox, and change the text

---

# Comments

---

## Use // to insert comments anywhere in JavaScript

---

## Comments

```javascript
var sayHello = function(){
    // this will say hello
    console.log('hello');
};
// you can put comments anywhere to help you
```

---

## Task: Open comments.html in Firefox, and insert some of your own comments

---

# For Loops

---

## For Loops

```javascript
for (var f=1; f<=10; f++){
    // do something ten times
}
```

---

## For Loops

```javascript
for (var f=1; f<=1000; f++){
    // do something one thousand times
}
```
---

## Task: Open forloop.html in Firefox, and change the number of lines to 50

---

# Showing and Hiding Elements

---

## Showing and Hiding Elements

```html
<h1 id="simon" style="visibility:hidden">Hello Simon!</h1>
<h1 id="tessa" style="visibility:visible">Hello Tessa!</h1>
```

---

## Showing and Hiding Elements

```javascript
document.getElementById("simon").style.visibility = "visible";
document.getElementById("tessa").style.visibility = "hidden";
```

---

## Task: Open hideme.html in Firefox, and create a new sentence that gets hidden and shown

---

# Divs

---

## Divs

```html
<h1>This is a sentence</h1>
<h1>This is another sentence</h1>
```

---

## Divs

```html
<h1 style="color:red">This is a sentence</h1>
<h1 style="color:red">This is another sentence</h1>
```

---

## Divs

```html
<div style="color:red">
    <h1>This is a sentence</h1>
    <h1>This is another sentence</h1>
</div>
```

---

## Task: Open divs.html and create a new div with three sentences, all set to blue
