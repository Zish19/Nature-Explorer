# 🌿 Nature Explorer Web App

**Nature Explorer** is a responsive, single-page web application designed to showcase fundamental to intermediate **HTML5** and **CSS3** concepts. This project simulates a real-world landing page for a nature travel agency, built entirely without JavaScript.

![Project Banner](https://via.placeholder.com/1000x300?text=Nature+Explorer+App+Preview)
*(Replace this link with a screenshot of your actual project later)*

## 🚀 Project Overview

This project was built to demonstrate mastery of core web development layout techniques, including **Flexbox**, **Positioning**, **Media Queries**, and **CSS Animations**. It functions as a complete "mini-app" with navigation, interactive elements, and a responsive design system.

### 🎯 Key Objectives Met
* **Structure:** Semantic HTML5 (`<header>`, `<main>`, `<section>`, `<footer>`).
* **Layout:** extensive use of **Flexbox** for alignment and spacing.
* **Styling:** Global typography, color variables, and CSS resets.
* **Responsiveness:** Mobile-first logic with visual indicators for different device widths.

---

## ✨ Features

### 1. Navigation & Layout
* **Fixed Header:** A navigation bar that stays pinned to the top using `position: fixed` and `z-index`.
* **Hero Section:** A full-width entry point with centered content and call-to-action buttons.
* **Grid/Flex Layouts:** Feature cards aligned perfectly using Flexbox properties.

### 2. CSS Animations & Visuals
* **Infinite Loader:** A custom CSS-only loading spinner using `@keyframes` and `transform: rotate`.
* **Interactive Cards:** Hover states affecting opacity and cursor style.
* **Fixed Side Banner:** A "Love Nature" badge anchored to the right side of the screen, overlaying content.

### 3. Technical Demonstrations
* **Flexbox Deep Dive:** A dedicated section demonstrating the difference between `align-items` (parent) and `align-self` (child override).
* **Responsive Strip:** A visual indicator bar that changes color based on viewport width:
    * 🟢 **Green:** < 300px (Small Mobile)
    * 🌸 **Pink:** 300px - 400px (Large Mobile)
    * 🔴 **Red:** 400px - 600px (Tablet)
    * 🔵 **Blue:** > 600px (Desktop)

---

## 🛠️ Technologies Used

* **HTML5:** Semantic markup.
* **CSS3:** Styling, Animations, Flexbox, Media Queries.
* **No JavaScript:** All interactivity is handled via CSS.

---

## 📂 Project Structure

```text
/nature-explorer
│
├── index.html        # Main HTML structure
├── style.css         # All styling and responsive logic
└── README.md         # Project documentation
