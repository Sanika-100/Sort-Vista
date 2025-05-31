# Sorting Algorithm Visualizer

## Overview
Sorting Algorithm Visualizer is an interactive web application that visually demonstrates the working of different sorting algorithms by animating their sorting process step-by-step. This project supports multiple sorting algorithms including Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort.

The visualizer helps users, students, and enthusiasts understand the internal mechanics of sorting algorithms in a clear and engaging way through animated bars representing array elements.

---

## Features
- Visual animations for 5 popular sorting algorithms:
  - Bubble Sort
  - Selection Sort
  - Insertion Sort
  - Merge Sort
  - Quick Sort
- Dynamic generation of random arrays with user-defined size
- Smooth swap and overwrite animations to demonstrate algorithm steps
- Responsive and clean UI design for better user experience
- Modular and maintainable code structure

---

## Technologies Used
- **JavaScript (ES6+):** Core language for implementing sorting algorithms and animations using modern ES6 modules.
- **HTML5:** Markup for the application’s structure and user interface.
- **CSS3:** Styling of bars, buttons, and layout including animations.
- **DOM Manipulation:** Dynamic creation and updating of bar elements to reflect sorting steps.
- **Asynchronous JavaScript (async/await):** To control animation timing and pauses between steps.
- **Structured Clone:** Used to deep-copy arrays for sorting simulations without modifying the original data.
  
---

## How It Works
1. The user selects a sorting algorithm from the dropdown menu.
2. The user inputs the desired number of bars (array elements) and generates a random array.
3. Upon clicking "Solve," the chosen sorting algorithm runs on a copy of the array, producing a list of swap or overwrite actions.
4. These actions are animated on screen by visually swapping bars or changing their heights, reflecting the sorting process step-by-step.
