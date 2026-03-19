# 🚀 JavaScript Learning Journey

## 📅 Day 1 - 05/07/2025

### 📚 Topics Covered
- 👋 Introduction
- ⚙️ Setup
- 🎉 Hello World

### 💡 Theory
- ❓ What is JavaScript? Why do we use it? How does JavaScript work in the webpage?
- 🔧 Different ways to implement JavaScript
- 🔗 How to link JS file to HTML
- 🖥️ Console.log - what and why we use it (common for rest two)
- ⚠️ Alert
- 📝 Document.write
- ❔ Can we run JavaScript without HTML and CSS and if yes how?

### ✅ Task 1
- 📁 Create a new repository called `javascript-basics`
- 📄 In that repository make an HTML page called `index.html`
- 🔘 Create a button with an alert saying "hello i am an alert from javascript" in external HTML
- 📢 Add a console message saying "hello javascript" in the HTML that is internal

---

## 📅 Day 2 - 06/07/2025

### 💡 Theory
- 📦 What are variables and data types in JavaScript?
- 🏷️ Learn all different types of data types in JavaScript
- 🔀 What is let, const, var in JavaScript and what is the difference between them?
- 🔍 How to find the type of variable in JavaScript?

### ✅ Task
- 🎯 Create all the different types of variables that you have learnt in a new webpage
- 🖨️ Display them by writing the data type then the value of that variable
- 💻 Log their values as well and find the type of each in the console

---

## 📅 Day 3 - 07/07/2025

### 💡 Theory
- ➕ Operators and their types, subtypes
- 🌊 Control flows and their types

### ✅ Task
- 🔢 Write a program that checks if a number is even or odd and prints a statement that says the given number is even or odd
- 📆 Write a switch that logs the day of the week
- 📑 Keep them separate for each

---

## 📅 Day 4 - 09/07/2025

### 💡 Theory
- 🔁 Learn what are loops and how they work in JavaScript
- 🔄 For, While, Do-While
- ⛔ What is break and continue statements and their uses?
- ❓ Is it a good practice to use the above statements?

### ✅ Task
- 🎯 Loop 1-10 using each loop
- 🔢 Print every 2nd number from 20-0 using loops

---

## 📅 Day 5 & 6 - 10/07/2025

### 💡 Theory
- 🔧 Functions
- ❓ What are functions in JavaScript?
- 🤔 What is the need of functions in JavaScript?
- 📋 Function declaration + parameters + return values + basic function expressions
- 📚 What are arrays?
- 🛠️ What are all the inbuilt features of arrays in JavaScript (methods of arrays)?
- 🔁 Looping through an array (for, forEach)
- 💾 What is caching? How does browser do caching?
- 🌐 How caching comes into picture with JavaScript?

### ✅ Tasks
- 📐 Write a function to calculate area of rectangle and print it on the screen
- 👋 Write a function called `greet(name)` which returns "hello my name is [parameter]" where the parameter is the name you sent to the function
- 📦 Keep both in one file
- 🎨 Create an array of five colors, loop through the array and log each color. Have two buttons - one to add a new color to the array and one to remove a color from the array

---

## 📅 Day 7 - 🎯 Object and Methods

### 💡 Theory
- 🗂️ Topic - Object and methods
- 💼 What are object literals?
- 🔧 Accessing and updating properties of objects?
- ⚙️ What are object methods? How to use and call them?
- 🎯 What is 'this' keyword? Why do we use it?
- 📚 What are arrays of objects?
- 💾 Learn how to store objects inside an array
- 🔁 Looping over arrays of objects
- ✏️ Editing and deleting an object from arrays of objects

### ✅ Tasks
- 🛍️ Create a page where there is an array of 5 products (name, description, price). Loop over them and display it on the page
- 👤 Create a page where you have an object called `person` with name, age, address, city and email
  - 🎤 Add a method `introduce()` which will log a full sentence with all details of the person
  - 🗑️ Add a method to delete the email of the person when you give the name of the person

---

## 📅 Day 8 - 🌳 Introduction to DOM Manipulation

### 💡 Theory
- 🎨 Introduction to DOM manipulation
- 🌲 What is DOM? Use of DOM, how is DOM important for dynamic webpages?
- 📄 What is "document" in JavaScript?
- 🔧 Different methods to manipulate DOM (example: `.getElementById()`, query selector, innertext, innerHTML etc)

### ✅ Tasks
- 📖 In a new webpage create a paragraph from your favorite book and add a button in HTML. On click of the button change the paragraph text to another paragraph from the book using JavaScript
- 🎛️ Create a dropdown with 1-5 numbers. Add another button which will change the values of the dropdown from numbers to alphabets (a-e). On selecting any value from the dropdown the selected value should be shown on the webpage

---

## 📅 Day 9 - ⚡ DOM Events

### 💡 Theory
- 🚀 Make the previous day tasks more efficient
- 🎪 DOM events - what are DOM events? How do they work?
- 👂 What is addEventListener?
- 📋 What are all the different types of events?

### ✅ Tasks
- ⌨️ Create an input field and change the color of the input field whenever you type anything inside it
- 🔘 Add a large button and add a hover effect to change the background color and text of the button
- 🔑 Learn about keyup events

---

## 📅 Day 10 - 💾 Local Storage & File Handling

### 💡 Theory
- 📝 Learn about how to read and write a file using JavaScript
- 📋 Learn specifically about reading and writing XML files in JavaScript
- 🏷️ What is an XML file? Why do we use XML files?

### ✅ Tasks

#### Task 1: 💬 Text File Save & Read
- 📝 Create a page where you have a text area to write paragraphs and have a save button
- 💾 After clicking the save button the text from the text area should be saved in a text file
- 📖 Add a button called "Read". After clicking the read button it should read the text file you have just created and display the contents on the screen

#### Task 2: 📊 XML File with Student Data
- ✨ Create a page which will have a button called "Create XML". After clicking the button you should create an XML file called `studentdata.xml`
- 📚 Add another button called "Get Student Data". After clicking the button it should read the `studentdata.xml`, get the data of students from XML and show it in a tabular format

**📌 Sample XML Structure:**
```xml
<?xml version="1.0" encoding="UTF-8"?>
<Students>
    <Student>
        <RollNo>101</RollNo>
        <Name>John Doe</Name>
        <Address>123 Main Street, New York, USA</Address>
        <DOB>2002-05-15</DOB>
    </Student>
    <Student>
        <RollNo>102</RollNo>
        <Name>Jane Smith</Name>
        <Address>456 Elm Avenue, Los Angeles, USA</Address>
        <DOB>2003-08-21</DOB>
    </Student>
</Students>
