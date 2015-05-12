## "JavaScript for Kids" Coding Class
### May/June 2015 - 4th and 5th Grade
### Lesson 2

--- 

## Welcome to Lesson 2!

---

# _Lesson 2_
- Recap of Lesson 1 (Numbers, Strings, Booleans)
- Arrays
-- Creating and defining arrays
-- Inserting / removing elements
-- Searching an array
-- Picking a random element from an array
-- Random body part generator!

---

## Arrays

---

## Creating and Defining Arrays

```javascript
var student1 = 'Ethan';
var student2 = 'Jose';
var student3 = 'Cooper';
var student4 = 'Rosa';
var student5 = 'Christina';
var student6 = 'Allan';
var student7 = 'Brad';
```

---

# An Array is a collection of elements

---

## Creating and Defining Arrays

```javascript
var students = ['Ethan', 'Jose', 'Cooper', 'Rosa', 'Christina', 'Allan', 'Brad'];
```

---

## Inserting and Removing Elements

```javascript
students.push('Mako');
```

---

## Inserting and Removing Elements

```javascript
students.pop();
```

---

## Get the length of an array

```javascript
students.length
```

---

## Indexing an array

```javascript
students[0]
```

---

## Indexing an array

```javascript
students[1] = 'Simon';
students;
```

---

## Joining Arrays

```javascript
var mondayClass = ['Cooper', 'Rosa'];
var tuesdayClass = ['Ethan', 'Jose'];
var bothClasses = mondayClass.concat(tuesdayClass);
```

---

## Turning Arrays into Strings

```javascript
bothClasses.toString();
bothClasses.join(' and ');
```

---

# Try it out!

## Safeway sells oranges and apples. QFC sells bananas and kiwis.

- Create two arrays for safeway and QFC
- Join them to make one array, and remove the last fruit
- Replace oranges with pineapples. How many fruits do you have?

## Pages 39 - 53 if you get stuck.

---

## Random Numbers

```javascript
Math.random();
```

---

## Random Number between 1 and 10
```javascript
Math.random() * 10;
```
--- 

## Rounding down and up a number

```javascript
Math.floor(3.141592);
Math.ceil(4.01);
Math.floor(10.99999);
Math.ceil(10.99999);
```
---

## Generating whole random numbers between 0 and 9

```javascript
Math.floor(Math.random() * 10);
```

---

## Random Fruit Selection!

```javascript
var fruits = ['Apple', 'Banana', 'Cherry', 'Pineapple', 'Kiwi'];
fruits[Math.floor(Math.random() * 5)]
```

---

## Would you like some random fruit?

```javascript
"Would you like some " + fruits[Math.ceil(Math.random() * 5)] + "?"
```

---

# Body Parts!

- Create three arrays: different numbers, different adjectives and an array of different body parts. 
- Select a number, adjective and body part at random
- Write some code that will prints "I like your 5 big arms!" or "I like your 10 smelly feet!"
