# Analog Clock 🕐

A simple analog clock built with **HTML, CSS, and JavaScript**.

This was my **first website/project**, created while I was learning the fundamentals of JavaScript, DOM manipulation, CSS positioning, and browser-based time handling.

🔗 **Live Demo:** https://devsubhamdas.github.io/analog-clock/

---

## ✨ Features

* Real-time analog clock
* Hour, minute, and second hands
* 12-hour clock face
* Minute indicators around the clock
* Second indicators around the clock
* Current hour highlighting
* AM/PM indicator
* Smooth visual transitions
* Built entirely with HTML, CSS, and vanilla JavaScript

---

## 🛠️ Built With

* **HTML5**
* **CSS3**
* **JavaScript**
* **Google Fonts**

The clock uses JavaScript's `Date` object to obtain the current time and updates the clock every second. The hand positions are calculated based on the current hour, minute, and second.

---

## 📐 How It Works

The clock is created using HTML elements styled and positioned with CSS.

JavaScript periodically reads the current time and rotates the clock hands accordingly:

* **Second hand:** 6° per second
* **Minute hand:** 6° per minute, with an additional adjustment based on seconds
* **Hour hand:** 30° per hour, with an additional adjustment based on minutes

The project also updates the visual indicators around the clock as time progresses.

---

## 📱 Responsive Behavior

The original project includes a small-screen CSS rule to adjust the clock's positioning.

---

## 🎯 Why I Built This

This project is special to me because it was one of my **first steps into web development**.

At the time, I was still learning how JavaScript worked and was experimenting with the DOM, CSS positioning, transformations, and real-time updates.

The code is intentionally kept in its **original form**. I have not refactored or modernized it because I want this project to remain a snapshot of where I started and how my coding skills have evolved over time.

---

## 📚 What I Learned

While building this project, I explored:

* JavaScript fundamentals
* DOM manipulation
* `Date` and time handling
* `setInterval()`
* CSS positioning
* CSS transforms and rotations
* Dynamic styling with JavaScript
* Creating visual components using HTML and CSS
* Turning an idea into a working browser application

---

## 🚀 Run Locally

Clone the repository:

```bash
git clone https://github.com/DevSubhamDas/analog-clock.git
```

Navigate into the project:

```bash
cd analog-clock
```

Then open `index.html` in your browser.

No build tools or dependencies are required.

---

## 📸 Live Preview

Visit the live version:

**https://devsubhamdas.github.io/analog-clock/**

---

## 📝 Note

This isn't intended to be a showcase of production-level code.

It's a reminder of where I started.

As I continue learning and building more projects, this repository stays untouched as a small piece of my development journey.
