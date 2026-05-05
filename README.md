

## Answers to Questions

### 1. What is the difference between getElementById, getElementsByClassName, and querySelector / querySelectorAll?
- getElementById()  returns one element that address by this specific css selector id .
- getElementsByClassName()  returns all the class from live list that class contain in this page.
querySelector() query the first element when it find and return it.
querySelectorAll() query the all element when it find and return list.

### 2. How do you create and insert a new element into the DOM?
- first create new html tag
- let Div = document.createElement('div');
- set message in tag
- Div.textContent = 'New Job';
- set class name
- Div.className = 'job'; 
- and then append with the end of the parent where i have a previously class which is .job-list adding into that section
- const p = document.querySelector('.job-list');
- p.appendChild(Div);


### 3. What is Event Bubbling? And how does it work?
- Event Bubbling is a behavior in JavaScript where if a event it start from specific element it goes to the parent and grand parent means to the root.It working gasture is like in a parent div have button which is child first the button event fires which is child then it bubbles up to the parent div

### 4. What is Event Delegation in JavaScript? Why is it useful?
- Event Delegation is basicly instead of adding a single event listener in parent rather than multiple event listener for all the child element, let bubbling do the work.It's use full becuse suppose you have 3 button in a div so you need call multiple time eventListener for action.So you need loop.Where Event Delegation use parent and get the event and findout the targeted event.So complexity reduce.

### 5. What is the difference between preventDefault() and stopPropagation() methods?
- the main difference is where preventDefault() stop any kind of even in that element but it it pass the event to the parent root which means bubbling.On the Other hand stopPropagation() do not stop event of that id but it's stop the bubbling for that reason the event no go to the parent id.
---



