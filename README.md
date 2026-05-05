

## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
- getElementById()  returns one element that address by this specific css selector id .
- getElementsByClassName()  returns all the class from live list that class contain in this page.
querySelector() query the first element when it find and return it.
querySelectorAll() query the all element when it find and return list.

### 2. How do you create and insert a new element into the DOM?
- first create new html tag
- let Div = document.createElement('div');
- Div.textContent = 'Hello World';
- newDiv.className = 'job'; 
- and then append with the end of the parent
- const parent = document.querySelector('.job-list');
- parent.appendChild(Div);


### 3. What is Event Bubbling? And how does it work?
- Event Bubbling is a behavior in JavaScript where if a event it start from specific element it goes to the parent and grand parent means to the root.It working gasture is like in a parent div have button which is child first the button event fires which is child then it bubbles up to the parent div

### 4. What is Event Delegation in JavaScript? Why is it useful?

### 5. What is the difference between preventDefault() and stopPropagation() methods?

---


**Technology Stack:**
- HTML
- CSS (Vanilla/Tailwind/DaisyUI)
- JavaScript (Vanilla)


