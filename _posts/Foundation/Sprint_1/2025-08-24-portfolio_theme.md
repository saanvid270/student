---
layout: post
title: Tools Setup
description: My blog
permalink: /sprint/1/theme
breadcrumb: true
toc: true
nav: sprint_1.html
---

# Reflecting on My Rock-Paper-Scissors Console Game

This week, I dedicated time to improving a simple Rock-Paper-Scissors game in Python. What started as a small coding experiment quickly turned into a deep reflection on **user experience, iteration, and learning design**. It reminded me that even simple projects can teach lessons about problem-solving, patience, and thoughtful design.

---

## Portfolio & Blogging

### Challenges and Solutions

When I first built the game, my main goal was functionality: get the game to run, let the user input choices, and compare against the computer. But almost immediately, I encountered my first challenge — **handling invalid inputs**.

Another challenge was keeping the game **engaging**. A single round felt flat — there was no sense of progress or achievement. Adding a **score system** and feedback after each round was a turning point. This small change created a **sense of competition and accomplishment**, making the game feel alive.

> *Lesson Learned:* Programs should guide users gracefully; we can’t assume everyone will type perfectly.
---

### How I Improved in LxD This Week

Working on this game pushed me to think like a **learning experience designer**, even though it was just a console program. I reflected on:

- **Guiding the learner:** Reducing friction and keeping players engaged.
- **Providing feedback:** Immediate reinforcement through scores and outcomes.
- **Iterative improvement:** Each version of the game was slightly better than the last. I didn’t aim for perfection first — I let the game grow organically.

> *Insight:* LxD isn’t about flashy visuals — it’s about thinking from the user’s perspective.

---

## Theme, Style, Layout

Even in a console program, the **layout of information matters**. Early versions dumped text without context, making it easy to get lost or feel frustrated. Later, I added small design touches that improved clarity and engagement.

Key design decisions:

- **Section headers:** Created a clear start to each round.
- **Score updates:** Kept players invested and motivated.
- **Quit option:** Gave control back to the user and reduced anxiety.

> *Reflection:* Even small design choices can transform the user experience from functional to enjoyable.

---

### Example CSS Improvements

If this project were a website, I could use CSS to enhance the visual experience and make the interface more engaging. Here are some example CSS snippets I could use:

**Highlighting the Current Round**

```css
/* filepath: /home/saanv/student/assets/css/custom.css */
.current-round {
  background-color: #e0f7fa;
  border-left: 4px solid #00796b;
  padding: 10px;
  margin-bottom: 16px;
  font-weight: bold;
}
```

**Score Display Styling**

```css
.score-box {
  background: #fff3e0;
  color: #e65100;
  border-radius: 8px;
  padding: 8px 16px;
  font-size: 1.2em;
  display: inline-block;
  margin: 10px 0;
  box-shadow: 0 2px 8px rgba(0,0,0,0.07);
}
```

**Button Enhancements**

```css
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

These CSS improvements would help make the site more visually appealing, guide the user's attention, and create a more enjoyable experience.

<img src="{{ site.baseurl }}/images/no_CSS.jpg" alt="NO_CSS">

<img src="{{ site.baseurl }}/images/CSS.jpg" alt="CSS">

---

## Reflection and Introspection

This project was more than a coding exercise — it was a lesson in **patience, empathy, and self-awareness**. I noticed myself getting frustrated when the code didn’t work at first, but iterating slowly taught me the value of small, incremental improvements.

I also realized that **my assumptions about users** were often wrong. I assumed everyone would type correctly or understand the rules instantly. Designing clear instructions and feedback forced me to step outside my perspective and imagine the experience from a beginner’s eyes.

Finally, I reflected on how **iteration and reflection** go hand-in-hand. Each change I made — a score display, a quit option, better text layout — was only effective because I paused, evaluated, and considered the user’s perspective. This mirrors real-world LxD work, where **understanding how learners experience a tool is just as important as building it**.

<img src="{{ site.baseurl }}/images/DB.jpg" alt="DB">

---

## Next Steps

Moving forward, I want to:

- Add a **best-of-N mode**, giving players a structured goal.
- Introduce a **learning AI**, so the computer adapts to player choices.
- Experiment with **console colors and formatting**, to make outcomes clearer and more engaging.

Even a small project like a console game taught me **big lessons about empathy, iteration, and design**. It reminded me that reflection — thinking carefully about the user experience — is just as important as coding itself.

