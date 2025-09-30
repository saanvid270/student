---
layout: post
title: Tools Setup
description: Javascript
permalink: /sprint/1/javascript
breadcrumb: true
toc: true
nav: sprint_1.html
---

# JavaScript Frontend Basics

This week, I focused on improving my frontend skills using **JavaScript, HTML, and Markdown**. My goal was to create a more interactive, engaging user experience for a small web project while practicing good coding habits and documenting my progress in Markdown.

---

## Code Snippets & UI Components

I built a few **working UI components** using HTML, CSS, and JavaScript:

- Interactive buttons that respond to clicks  
- Dynamic content sections that expand or collapse  
- Simple form validation for user input  

> ⚡ *Example:* I used JavaScript to toggle the visibility of content sections, creating a cleaner, interactive layout.

**HTML: Toggleable Content Section**

```html
<!-- filepath: /home/saanv/student/assets/toggle.html -->
<button id="toggleBtn">Show/Hide Details</button>
<div id="details" style="display:none;">
  <p>This is some extra information that can be toggled.</p>
</div>
```

**JavaScript: Toggle Functionality**

```js
// filepath: /home/saanv/student/assets/toggle.js
document.getElementById('toggleBtn').onclick = function() {
  const details = document.getElementById('details');
  details.style.display = details.style.display === 'none' ? 'block' : 'none';
};
```

**CSS: Button Styling**

```css
/* filepath: /home/saanv/student/assets/css/custom.css */
button {
  background: linear-gradient(90deg, #6b4bd3 0%, #327fc7 100%);
  color: #fff;
  border: none;
  border-radius: 6px;
  padding: 10px 20px;
  font-size: 1em;
  cursor: pointer;
  transition: background 0.3s;
}
button:hover {
  background: linear-gradient(90deg, #327fc7 0%, #6b4bd3 100%);
}
```

**HTML: Simple Form Validation**

```html
<!-- filepath: /home/saanv/student/assets/form.html -->
<form id="myForm">
  <input type="text" id="username" placeholder="Enter username">
  <button type="submit">Submit</button>
  <span id="error" style="color:red;"></span>
</form>
```

**JavaScript: Form Validation**

```js
// filepath: /home/saanv/student/assets/form.js
document.getElementById('myForm').onsubmit = function(e) {
  e.preventDefault();
  const username = document.getElementById('username').value;
  const error = document.getElementById('error');
  if (username.trim() === '') {
    error.textContent = 'Username cannot be empty!';
  } else {
    error.textContent = '';
    // Proceed with form submission or further logic
  }
};
```

These small components made the interface more interactive and improved user engagement by providing immediate feedback.

---

## Commit History & Iteration

I documented my frontend progress with Git commits, which helped me track changes and experiment safely. Some notable commits include:

- feat: add toggleable content sections
- fix: correct button click event handling
- style: improve layout and spacing for readability

Keeping a clear commit history allowed me to reflect on incremental improvements and troubleshoot errors efficiently.

<img src="{{ site.baseurl }}/images/Commits.jpg" alt="Commits">

<img src="{{ site.baseurl }}/images/more_commits.jpg" alt="more_commits">

---

## Presentation & Interactivity

To improve presentation and interactivity, I applied several key techniques:

**Markdown for Documentation:**  
I used Markdown to clearly document each UI component, including code snippets, expected behavior, and usage instructions.

**HTML Structure:**  
Semantic HTML improved accessibility and organized content logically for the user and browser.

**JavaScript Enhancements:**  
Adding interactivity like button clicks, content toggling, and form validation made the site feel responsive and dynamic.

> *Reflection:* Even basic JavaScript interactions can significantly improve the user experience, making content more engaging and intuitive.

<img src="{{ site.baseurl }}/images/game.jpg" alt="game">

---

## Reflection and Learning

Through this work, I realized how important small, incremental improvements are in frontend development. I learned to:

- Think like a user when designing interactivity
- Document every step in Markdown for clarity and reflection
- Use JavaScript to enhance functionality without overcomplicating the interface

Moving forward, I want to add more dynamic components, like animated elements and interactive lists, to further improve engagement and presentation.