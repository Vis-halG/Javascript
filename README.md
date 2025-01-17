# Javascript
# JavaScript Operator Quiz

## Questions

### 1. What will the following code output?
javascript
let a = 5;
let b = a++ + ++a;
console.log(b);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 12  
  *Explanation:* a++ uses the current value (5) and then increments a to 6. ++a then increments a to 7, resulting in 5 + 7 = 12.
</details>

---

### 2. What will be the output of this code?
javascript
let x = 2;
let y = x * 3 - x++ + x;
console.log(y);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 7  
  *Explanation:* x * 3 is 6, x++ uses 2 (then increments x to 3), so 6 - 2 + 3 = 7.
</details>

---

### 3. What will this code output?
javascript
let str = "5" + 5 - 5;
console.log(str);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 50  
  *Explanation:* "5" + 5 becomes "55" (string concatenation), then "55" - 5 converts to 50.
</details>

---

### 4. What will be the output of this code?
javascript
let a = 1;
let b = 2;
let c = a = b;
console.log(c);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 2  
  *Explanation:* a = b assigns 2 to a and returns 2, so c is 2.
</details>

---

### 5. What will the following code print?
javascript
let d = null;
let e = 5;
let f = d ?? e;
console.log(f);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 5  
  *Explanation:* The nullish coalescing operator (??) returns the right operand (e) when the left operand (d) is null.
</details>

---

### 6. What will this code output?
javascript
let g = 0;
let h = g || "default";
console.log(h);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "default"  
  *Explanation:* The || operator returns the first truthy value; since g is falsy, it returns "default".
</details>

---

### 7. What will the following code print?
javascript
let i = 10;
let j = i > 5 ? "Greater" : "Smaller";
console.log(j);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Greater"  
  *Explanation:* The condition i > 5 is true, so the ternary operator returns "Greater".
</details>

---

### 8. What will this code output?
javascript
let k = [1, 2, 3];
let l = k[0] + k[1] + k[2] + "4";
console.log(l);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 64  
  *Explanation:* k[0] + k[1] + k[2] evaluates to 6, and then "4" is concatenated resulting in "64".
</details>

---

### 9. What will be the output of this code?
javascript
let m = 1;
let n = m++ + ++m;
console.log(n);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 5  
  *Explanation:* m++ uses 1 (then m becomes 2), and ++m makes it 3. So, 1 + 3 = 4.
</details>

---

### 10. What will this code output?
javascript
let o = 3;
let p = o * 2 == 6 ? "Yes" : "No";
console.log(p);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Yes"  
  *Explanation:* o * 2 is 6, so the condition is true, and it returns "Yes".
</details>

---

### 11. What will be the output of this code?
javascript
let q = 5;
let r = q++ + ++q;
console.log(r);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 12  
  *Explanation:* q++ uses 5 (then q becomes 6), and ++q becomes 7. So, 5 + 7 = 12.
</details>

---

### 12. What will this code output?
javascript
let s = "10" - 5;
console.log(s);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 5  
  *Explanation:* The - operator converts the string "10" to a number, resulting in 10 - 5 = 5.
</details>

---

### 13. What will the following code print?
javascript
let t = 1;
let u = t + (t = 3);
console.log(u);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 4  
  *Explanation:* The value of t before the assignment is 1, and the assignment t = 3 happens after the addition. So, 1 + 3 = 4.
</details>

---

### 14. What will this code output?
javascript
let v = 1;
let w = v === "1" ? "Equal" : "Not Equal";
console.log(w);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Not Equal"  
  *Explanation:* The === operator checks both value and type. Since 1 (number) is not strictly equal to "1" (string), it returns "Not Equal".
</details>

---

### 15. What will this code output?
javascript
let x = [1, 2, 3];
let y = x[0] + x[1] + "4";
console.log(y);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 34  
  *Explanation:* x[0] + x[1] evaluates to 1 + 2, which is 3, and then concatenates with "4" resulting in "34".
</details>

---

### 16. What will this code output?
javascript
let z = 5;
let a = z > 10 ? "Big" : z < 3 ? "Small" : "Medium";
console.log(a);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Medium"  
  *Explanation:* The first condition is false, but the second condition is also false, so it returns "Medium".
</details>

---

### 17. What will the following code print?
javascript
let b = 1;
let c = b + b++ + ++b;
console.log(c);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 5  
  *Explanation:* b starts at 1. The expression evaluates as 1 + 1 + 3 (after b is incremented twice), resulting in 5.
</details>

---

### 18. What will this code output?
javascript
let d = [1, 2, 3];
let e = d.join('-');
console.log(e);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "1-2-3"  
  *Explanation:* The join() method creates a string by joining the elements of the array with - as the separator.
</details>

---

### 19. What will the following code print?
javascript
let f = 1;
let g = (f += 2) + (f += 3);
console.log(g);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 11  
  *Explanation:* The first f += 2 makes f equal to 3. The second f += 3 makes f equal to 6. So, 3 + 6 = 9.
</details>

---

### 20. What will this code output?
javascript
let h = 1;
let i = h++ + ++h;
console.log(i);

<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* 5  
  *Explanation:* The first h++ uses 1 and then increments h to 2. The ++h increments h to 3, so the expression evaluates as 1 + 3 = 4.
</details>

---



# JavaScript Conditional Statements Quiz Questions

This repository contains a series of JavaScript quiz questions with detailed explanations of the expected outputs. It is designed to help developers improve their JavaScript knowledge and understanding of key concepts like comparison operators, conditional logic, truthy/falsy values, and more.


## Questions

### 1. What will the following code output?

javascript
let x = 10;
if (x = 5) {
    console.log("Equal");
} else {
    console.log("Not Equal");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Equal"  
  *Explanation:* The code uses the assignment operator = instead of the comparison operator ==. The value 5 is assigned to x, which is truthy, so the if block executes.
</details>

---

### 2. What will be the output of this code?

javascript
let a = 0;
if (a) {
    console.log("True");
} else {
    console.log("False");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "False"  
  *Explanation:* The value 0 is falsy in JavaScript, so the else block executes.
</details>

---

### 3. What will be printed when the following code is executed?

javascript
let b = null;
if (b == undefined) {
    console.log("Matched");
} else {
    console.log("Not Matched");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Matched"  
  *Explanation:* The == operator checks for equality with type coercion. null and undefined are considered equal when using loose equality.
</details>

---

### 4. What will the output be?

javascript
let c = "5";
if (c === 5) {
    console.log("Strictly Equal");
} else {
    console.log("Not Strictly Equal");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Not Strictly Equal"  
  *Explanation:* The === operator checks both value and type. Since c is a string and 5 is a number, they are not strictly equal.
</details>

---

### 5. What will this code return?

javascript
let d = 10;
if (d > 5 && d < 15) {
    console.log("In Range");
} else {
    console.log("Out of Range");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "In Range"  
  *Explanation:* Both conditions (d > 5 and d < 15) are true, so the first block executes.
</details>

---

### 6. What will be the output of the following?

javascript
let e = 10;
if (e > 5 || e < 5) {
    console.log("Condition Met");
} else {
    console.log("Condition Not Met");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Condition Met"  
  *Explanation:* The || operator checks if at least one condition is true. Since e > 5 is true, the first block executes.
</details>

---

### 7. What will this code print?

javascript
let f = 0;
if (f) {
    console.log("Truthy");
} else if (f === 0) {
    console.log("Falsy Zero");
} else {
    console.log("Default");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Falsy Zero"  
  *Explanation:* The first condition is false because 0 is falsy. The second condition checks if f is strictly equal to 0, which is true, so this block executes.
</details>

---

### 8. What is the output of this code?

javascript
let g = "Hello";
if (g.length > 5) {
    console.log("Long String");
} else {
    console.log("Short String");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Short String"  
  *Explanation:* The length of the string "Hello" is 5, which is not greater than 5, so the else block executes.
</details>

---

### 9. What will this code output?

javascript
let h = "0";
if (h) {
    console.log("Truthy");
} else {
    console.log("Falsy");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Truthy"  
  *Explanation:* Non-empty strings are truthy in JavaScript, so the first block executes.
</details>

---

### 10. What will the following code print?

javascript
let i = NaN;
if (i) {
    console.log("Not NaN");
} else {
    console.log("Is NaN");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Is NaN"  
  *Explanation:* NaN (Not-a-Number) is falsy in JavaScript, so the else block executes.
</details>

---

### 11. What will this code return?

javascript
let j = "false";
if (j) {
    console.log("Truthy");
} else {
    console.log("Falsy");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Truthy"  
  *Explanation:* The string "false" is non-empty and thus truthy.
</details>

---

### 12. What will be the output of this code?

javascript
let k = [1, 2, 3];
if (k) {
    console.log("Array is Truthy");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Array is Truthy"  
  *Explanation:* Arrays are objects in JavaScript and are considered truthy, so this block executes.
</details>

---

### 13. What will this code output?

javascript
let l = undefined;
if (l === null) {
    console.log("Null");
} else {
    console.log("Not Null");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Not Null"  
  *Explanation:* undefined is not strictly equal to null, so the else block executes.
</details>

---

### 14. What will the following code print?

javascript
let m = "10";
if (m == 10) {
    console.log("Loose Equality");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Loose Equality"  
  *Explanation:* The == operator performs type coercion, so the string "10" is converted to a number for comparison, resulting in equality.
</details>

---

### 15. What will be the output of this code?

javascript
let n = "2";
if (n + 2 == 4) {
    console.log("True");
} else {
    console.log("False");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "False"  
  *Explanation:* The expression n + 2 results in the string "22" due to string concatenation. When using ==, the string is coerced to a number and compared to 4, which results in false.
</details>

---

### 16. What will the following code output?

javascript
let o = 1;
if (o) {
    console.log("One");
} else if (o === 0) {
    console.log("Zero");
} else {
    console.log("Not One or Zero");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "One"  
  *Explanation:* The value 1 is truthy, so the first block executes.
</details>

---

### 17. What will this code print?

javascript
let p = [1, 2, 3];
if (p.length) {
    console.log("Array is Not Empty");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Array is Not Empty"  
  *Explanation:* The length of the array is 3, which is truthy, so this block executes.
</details>

---

### 18. What will the output be?

javascript
let q = "abc";
if (q === "abc") {
    console.log("Matched");
} else {
    console.log("Not Matched");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Matched"  
  *Explanation:* The string q is strictly equal to "abc", so the first block executes.
</details>

---

### 19. What will this code output?

javascript
let r = 5;
if (r > 0 && r < 10) {
    console.log("Between 0 and 10");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Between 0 and 10"  
  *Explanation:* Both conditions are true, so this block executes.
</details>

---

### 20. What will be the output of this code?

javascript
let s = 0;
if (s == false) {
    console.log("Equal to false");
}


<details>
  <summary>Click to view Answer and Explanation</summary>
  *Answer:* "Equal to false"  
  *Explanation:* The value 0 is loosely equal to false, so this block executes.
</details>

---

# DOM-MANIPULATION


# JavaScript DOM Manipulation with Examples ✨

This repository demonstrates various JavaScript DOM manipulation techniques with simple examples. The examples cover several important DOM methods and properties such as `querySelector`, `previousSibling`, `nextSibling`, `previousElementSibling`, `nextElementSibling`, and others.

## Table of Contents 📝
1. **Introduction to DOM Manipulation**
2. **Selecting DOM Elements**
3. **Changing DOM Elements**
4. **Adding, Removing and Replacing Elements**
5. **Event Bubbling**
6. **DOM Properties and Methods**
7. **To-Do List Example**
8. **Interview Questions & Answers**

---

## 1. Introduction to DOM Manipulation 📚

The **Document Object Model (DOM)** is a programming interface for HTML and XML documents. JavaScript can be used to manipulate this structure, making dynamic changes to a webpage.

---

## 2. Selecting DOM Elements 👨‍💻

In JavaScript, the most common way to select elements in the DOM is by using methods such as `document.querySelector`, `document.getElementById`, and `document.getElementsByClassName`.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Manipulation Example</title>
</head>
<body>
    <div id="container">
        <p id="text">Hello, world!</p>
    </div>
    <script>
        // Selecting elements
        const container = document.getElementById('container');
        const text = document.getElementById('text');
    </script>
</body>
</html>
```

---

## 3. Changing DOM Elements 🔧

You can use properties like `innerText`, `innerHTML`, `textContent`, and others to change the content or structure of DOM elements.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Changing DOM Elements</title>
</head>
<body>
    <div class="container">
        <p class="content">This is some text.</p>
    </div>
    <script>
        const content = document.querySelector('.content');
        // Change content using innerText
        content.innerText = "Updated text using innerText";
    </script>
</body>
</html>
```

---

## 4. Adding, Removing, and Replacing Elements ➕➖

You can manipulate the DOM by adding, removing, or replacing elements using methods such as `append()`, `prepend()`, `replaceWith()`, etc.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Replace Elements Example</title>
</head>
<body>
    <div id="container">
        <p id="original">This is the original paragraph.</p>
    </div>
    <button id="replace">Replace</button>
    <script>
        const originalParagraph = document.getElementById('original');
        const replaceButton = document.getElementById('replace');
        
        replaceButton.addEventListener('click', () => {
            const newParagraph = document.createElement('p');
            newParagraph.textContent = "This paragraph has replaced the original one.";
            originalParagraph.replaceWith(newParagraph);
        });
    </script>
</body>
</html>
```

---

## 5. Event Bubbling ⚡

Event bubbling is when an event propagates from the innermost element to the outermost one, triggering all handlers along the way.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Event Bubbling</title>
</head>
<body>
    <div class="container">
        Parent Div
        <div class="child">
            Child Div
            <button class="button">Click Me</button>
        </div>
    </div>
    <script>
        const parentDiv = document.querySelector('.container');
        const childDiv = document.querySelector('.child');
        const button = document.querySelector('.button');
        
        parentDiv.addEventListener('click', () => {
            alert('Parent Div Clicked');
        });

        childDiv.addEventListener('click', (e) => {
            alert('Child Div Clicked');
            e.stopPropagation();
        });

        button.addEventListener('click', (e) => {
            alert('Button Clicked');
            e.stopPropagation();
        });
    </script>
</body>
</html>
```

---

## 6. DOM Properties and Methods 🔍

### `querySelector()`, `previousSibling`, `nextSibling`, `previousElementSibling`, `nextElementSibling`:

These methods allow you to traverse the DOM to access elements relative to a given element.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>DOM Traversing Example</title>
</head>
<body>
    <div class="container">
        <p>This is the first paragraph.</p>
        <p>This is the second paragraph.</p>
    </div>
    <script>
        const container = document.querySelector('.container');
        
        const firstParagraph = container.firstElementChild;
        const nextSibling = firstParagraph.nextElementSibling;
        const prevSibling = nextSibling.previousElementSibling;

        console.log("First Paragraph:", firstParagraph);
        console.log("Next Sibling:", nextSibling);
        console.log("Previous Sibling:", prevSibling);
    </script>
</body>
</html>
```

---

## 7. To-Do List Example 📝

This example demonstrates how to create a simple to-do list with a feature to delete tasks.

### Example Code:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>To-Do List</title>
</head>
<body>
    <div class="container">
        <h2>To-Do List</h2>
        <input type="text" id="itemInput" placeholder="Type something...">
        <button onclick="add()">Add to Wishlist</button>
        <div class="itemlist"></div>
    </div>
    <script>
        let Input = document.getElementById("itemInput");
        let text = document.querySelector(".itemlist");

        function add() {
            if (Input.value == "") {
                alert("enter the task");
            } else {
                let newElement = document.createElement("li");
                newElement.innerHTML = `${Input.value} <i>click to delete</i>`;
                text.appendChild(newElement);
                Input.value = "";

                newElement.querySelector("i").addEventListener("click", remove);
                
                function remove() {
                    newElement.remove();
                }
            }
        }
    </script>
</body>
</html>
```

---

## 8. Interview Questions & Answers 🧠

### Q1: What is the difference between `previousSibling` and `previousElementSibling`?

**Answer:**  
- `previousSibling` returns the previous node in the DOM tree, which can be a text node or an element.
- `previousElementSibling` returns the previous sibling element (ignoring text or comment nodes).

### Q2: How do you prevent an event from bubbling?

**Answer:**  
Use `e.stopPropagation()` inside the event listener function.

### Q3: Explain the difference between `innerHTML` and `textContent`.

**Answer:**  
- `innerHTML` returns or sets the HTML content, including HTML tags.
- `textContent` returns or sets the text content, without any HTML tags.

---


---

### 1. **What is the DOM?**
   **Answer:** The DOM represents the document structure, allowing programs to interact with HTML or XML documents.

### 2. **What is the difference between `innerHTML` and `textContent`?**
   ```html
   <div id="example"></div>

   <script>
     const div = document.getElementById('example');
     div.innerHTML = '<p>This is <b>HTML</b> content</p>';
     console.log(div.innerHTML); // <p>This is <b>HTML</b> content</p>
     console.log(div.textContent); // This is HTML content
   </script>
   ```

### 3. **What is the use of `document.getElementById()`?**
   ```html
   <div id="myDiv">Hello, World!</div>
   <script>
     const element = document.getElementById('myDiv');
     console.log(element.textContent); // Hello, World!
   </script>
   ```

### 4. **What is the difference between `getElementById()` and `querySelector()`?**
   ```html
   <div id="uniqueId">Hello</div>
   <div class="class">Hello</div>

   <script>
     const idElement = document.getElementById('uniqueId');
     const classElement = document.querySelector('.class');
     console.log(idElement.textContent); // Hello
     console.log(classElement.textContent); // Hello
   </script>
   ```

### 5. **What is an event in the context of the DOM?**
   ```html
   <button id="clickBtn">Click Me</button>
   <script>
     const button = document.getElementById('clickBtn');
     button.addEventListener('click', function() {
       alert('Button clicked!');
     });
   </script>
   ```

### 6. **What is event delegation?**
   ```html
   <ul id="list">
     <li>Item 1</li>
     <li>Item 2</li>
     <li>Item 3</li>
   </ul>

   <script>
     const list = document.getElementById('list');
     list.addEventListener('click', function(event) {
       if (event.target.tagName === 'LI') {
         alert('You clicked on ' + event.target.textContent);
       }
     });
   </script>
   ```

### 7. **What does `event.stopPropagation()` do?**
   ```html
   <div id="parent">
     <button id="child">Click Me</button>
   </div>

   <script>
     const parent = document.getElementById('parent');
     const child = document.getElementById('child');
     
     parent.addEventListener('click', () => alert('Parent clicked!'));
     child.addEventListener('click', (event) => {
       alert('Child clicked!');
       event.stopPropagation();
     });
   </script>
   ```

### 8. **What does `event.preventDefault()` do?**
   ```html
   <a href="https://example.com" id="link">Go to Example</a>

   <script>
     const link = document.getElementById('link');
     link.addEventListener('click', (event) => {
       event.preventDefault();
       alert('Link click prevented!');
     });
   </script>
   ```

### 9. **What is the `document.createElement()` method used for?**
   ```html
   <script>
     const newDiv = document.createElement('div');
     newDiv.textContent = 'This is a new div';
     document.body.appendChild(newDiv);
   </script>
   ```

### 10. **What does `appendChild()` method do?**
   ```html
   <div id="container"></div>
   <script>
     const div = document.createElement('div');
     div.textContent = 'Appended Child';
     document.getElementById('container').appendChild(div);
   </script>
   ```

### 11. **What does `removeChild()` do?**
   ```html
   <div id="parent">
     <p id="child">This is a child paragraph</p>
   </div>

   <script>
     const parent = document.getElementById('parent');
     const child = document.getElementById('child');
     parent.removeChild(child);
   </script>
   ```

### 12. **What are `firstChild` and `firstElementChild`?**
   ```html
   <div id="parent">
     Text Node
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const parent = document.getElementById('parent');
     console.log(parent.firstChild); // Text Node (whitespace)
     console.log(parent.firstElementChild); // <p>Paragraph 1</p>
   </script>
   ```

### 13. **What are `lastChild` and `lastElementChild`?**
   ```html
   <div id="parent">
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const parent = document.getElementById('parent');
     console.log(parent.lastChild); // Text Node (whitespace)
     console.log(parent.lastElementChild); // <p>Paragraph 2</p>
   </script>
   ```

### 14. **What is the `childNodes` property?**
   ```html
   <div id="parent">
     Text Node
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const parent = document.getElementById('parent');
     console.log(parent.childNodes); // NodeList of all child nodes (including text nodes)
   </script>
   ```

### 15. **What is the `children` property?**
   ```html
   <div id="parent">
     Text Node
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const parent = document.getElementById('parent');
     console.log(parent.children); // HTMLCollection of child elements (excludes text nodes)
   </script>
   ```

### 16. **What does `parentNode` do?**
   ```html
   <div id="child">I am a child</div>

   <script>
     const child = document.getElementById('child');
     console.log(child.parentNode); // The parent element of the child div
   </script>
   ```

### 17. **What is `nextSibling`?**
   ```html
   <div>
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const firstP = document.querySelector('p');
     console.log(firstP.nextSibling); // Returns the next sibling node, which may be text
   </script>
   ```

### 18. **What is `previousSibling`?**
   ```html
   <div>
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const secondP = document.querySelectorAll('p')[1];
     console.log(secondP.previousSibling); // Returns the previous sibling node, which may be text
   </script>
   ```

### 19. **What is `nextElementSibling`?**
   ```html
   <div>
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const firstP = document.querySelector('p');
     console.log(firstP.nextElementSibling); // <p>Paragraph 2</p>
   </script>
   ```

### 20. **What is `previousElementSibling`?**
   ```html
   <div>
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const secondP = document.querySelectorAll('p')[1];
     console.log(secondP.previousElementSibling); // <p>Paragraph 1</p>
   </script>
   ```

### 21. **What does `querySelectorAll()` do?**
   ```html
   <div class="item">Item 1</div>
   <div class="item">Item 2</div>

   <script>
     const items = document.querySelectorAll('.item');
     console.log(items); // NodeList of all elements with class 'item'
   </script>
   ```

### 22. **What is `setAttribute()` used for?**
   ```html
   <img id="image" src="image.jpg" alt="Image">

   <script>
     const image = document.getElementById('image');
     image.setAttribute('src', 'new-image.jpg');
   </script>
   ```

### 23. **What is `getAttribute()` used for?**
   ```html
   <img id="image" src="image.jpg" alt="Image">

   <script>
     const image = document.getElementById('image');
     console.log(image.getAttribute('src')); // image.jpg
   </script>
   ```

### 24. **What is `removeAttribute()` used for?**
   ```html
   <img id="image" src="image.jpg" alt="Image">

   <script>
     const image = document.getElementById('image');
     image.removeAttribute('alt');
   </script>
   ```

### 25. **What is `createTextNode()`?**
   ```html
   <script>
     const text = document.createTextNode('This is some text');
     document.body.appendChild(text);
   </script>
   ```

### 26. **What is the purpose of `document.querySelector()`?**
   ```html
   <div id="uniqueDiv">Hello</div>

   <script>
     const element = document.querySelector('#uniqueDiv');
     console.log(element.textContent); // Hello
   </script>
   ```

### 27. **What is the `hidden` attribute in the DOM?**
   ```html
   <div id="hiddenElement" hidden>This is hidden</div>

   <script>
     const div = document.getElementById('hiddenElement');
     div.hidden = false; // Makes the element visible
   </script>
   ```

### 28. **What does `insertBefore()` do?**
   ```html
   <div id="parent">
     <p>Paragraph 1</p>
     <p>Paragraph 2</p>
   </div>

   <script>
     const newP = document.createElement('p');
     newP.textContent = 'Inserted Paragraph';
     const parent = document.getElementById('parent');
     parent.insertBefore(newP, parent.firstChild);
   </script>
   ```

### 29. **What is the `cloneNode()` method?**
   ```html
   <div id="original">
     <p>Original content</p>
   </div>

   <script>
     const original = document.getElementById('original');
     const clone = original.cloneNode(true);
     document.body.appendChild(clone); // Clone with child elements
   </script>
   ```

### 30. **What is `document.designMode` used for?**
   ```html
   <script>
     document.designMode = 'on'; // Turns on content-editable mode for the document
   </script>
   ```

---

