## "JavaScript for Kids" Coding Class
### May/June 2015 - 4th and 5th Grade
### Lesson 3

--- 

## Welcome to Lesson 3!

---

# _Lesson 3_
- Recap of Lesson 2 (Arrays)
- Objects
-- Creating new objects
-- Setting properties on objects
-- Setting methods on objects
-- Passing parameters to methods
-- Create your own object!

---

## Objects

---

# What is an object?

---

![fit](images/tessa.jpg)

---

# My dog, Tessa

---

## Creating New Objects

```javascript
var tessa = {};
```

---

# Object Properties

---

# What is a property of an object?

---

## Properties (Strings, Numbers, Booleans)

```javascript
var tessa = {};
tessa.name = 'Tessa';
tessa.breed = 'Labrador';
tessa.age = 7;
tessa.weight = 80;
tessa.microchipped = true;
```

---

## Properties (Arrays)

```javascript
tessa.friends = ['Kona', 'Sam', 'Guy'];
tessa.likes = ['Walks', 'Dog Park', 'Treats'];
```

---

# Object Methods

---

# What is a method on an object?

---

# Object Methods

```javascript
tessa.bark = function(){ return "Woof!";}
```
---

# Calling properties and methods

```javascript
tessa.age;  
tessa.bark(); 
```
---

# Calling methods with parameters

```javascript
tessa.bark = function(times){ return "Woof!".repeat(times); }
```
---

# Calling methods with parameters

```javascript
tessa.bark(3);
```

---

## Create a method called "ageInDogYears" that returns Tessa's age in dog years.

### (Hint: use "this.age" to get the age)

---

# Dog Years

```javascript
tessa.ageInDogYears = function(){ return this.age * 7; }
```

---

# Create your own object!

---

## Create your own object. Add a variety of properties and methods. 

### Pages 64-76 if you need some ideas!