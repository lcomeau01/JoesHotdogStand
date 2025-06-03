# 🌭 Joe's Hotdog Stand

**Joe's Hotdog Stand** is a mock website project built to practice the fundamentals of **JavaScript**, **HTML**, and **CSS**.

## Features

- Prompt-based input for ordering hotdogs, fries, and sodas  
- Automatic calculation and display of a receipt  
- Rounded pricing using a custom JavaScript function  
- Simple, clean layout styled with CSS  

## How It Works

When you open the page, you'll be prompted to enter the quantity of each item you'd like to order. The site will then display a formatted receipt showing item totals and overall cost.

---

## File Overview

### `index.html`: 
- The main (and only) HTML page of the website  
- Contains the overall structure of the site  
- Includes an embedded `<script>` with all JavaScript logic  
- Features a `showMoney()` function that formats a float integer to two decimal places (e.g., `3.5` → `$3.50`) and then converts that integer into a string. 

### `styles.css`: 
- Handles layout, fonts, spacing, and general styling
