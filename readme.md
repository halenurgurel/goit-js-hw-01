# 🤖 JavaScript Basics — Functions Practice

This repository contains **three beginner-level JavaScript tasks** implemented as part of my training exercises.  
Each task focuses on basic function creation, parameter handling, and string/number operations.

---

## 🚀 Live Demo

👉 [**View on GitHub Pages**](https://halenurgurel.github.io/goit-js-hw-01/)

---

## 📂 Project Structure

```
📁 js-functions-tasks
┣ 📜 task-1.js → "Droid Transaction" function
┣ 📜 task-2.js → "Shipping Message" function
┣ 📜 task-3.js → "Element Width" function
┗ 📜 index.html → File to open and run the tasks in browser console

```

---

## 🧠 Tasks Overview

### 🧩 Task 1 — Droid Transaction

**File:** `task-1.js`

**Goal:**  
Create a function `makeTransaction(quantity, pricePerDroid)` that returns a message  
about a droid order’s total cost.

```javascript
function makeTransaction(quantity, pricePerDroid) {
  return `You ordered ${quantity} droids worth ${
    quantity * pricePerDroid
  } credits!`;
}

// ✅ Test calls:
console.log(makeTransaction(5, 3000)); // "You ordered 5 droids worth 15000 credits!"
console.log(makeTransaction(3, 1000)); // "You ordered 3 droids worth 3000 credits!"
console.log(makeTransaction(10, 500)); // "You ordered 10 droids worth 5000 credits!"
```

---

### 📦 Task 2 — Product Delivery

**File:** `task-2.js`

**Goal:**
Define a function `getShippingMessage(country, price, deliveryFee)` that calculates and returns a delivery message with the total cost.

```javascript
function getShippingMessage(country, price, deliveryFee) {
  const totalPrice = price + deliveryFee;
  return `Shipping to ${country} will cost ${totalPrice} credits`;
}

// ✅ Test calls:
console.log(getShippingMessage("Australia", 120, 50)); // "Shipping to Australia will cost 170 credits"
console.log(getShippingMessage("Germany", 80, 20)); // "Shipping to Germany will cost 100 credits"
console.log(getShippingMessage("Sweden", 100, 20)); // "Shipping to Sweden will cost 120 credits"
```

---

### 📏 Task 3 — Element Width Calculation

**File:** task-3.js

**Goal:**
Define a function getElementWidth(content, padding, border) that calculates the total element width assuming box-sizing: border-box.

```javascript
function getElementWidth(content, padding, border) {
  const contentValue = parseFloat(content);
  const paddingValue = parseFloat(padding);
  const borderValue = parseFloat(border);

  return contentValue + paddingValue * 2 + borderValue * 2;
}

// ✅ Test calls:
console.log(getElementWidth("50px", "8px", "4px")); // 74
console.log(getElementWidth("60px", "12px", "8.5px")); // 101
console.log(getElementWidth("200px", "0px", "0px")); // 200
```

---

## 🛠️ Tech Stack

**Language:** JavaScript (ES6)

**Editor:** Visual Studio Code

**Execution:** Browser Console

**Version Control:** Git & GitHub

---

### 🧱 Learning Objectives

- Function declaration and parameters

- Returning formatted strings using template literals

- Parsing numeric values from strings (parseFloat)

- Calculating totals and returning clean messages

- Writing clean, readable, and testable JavaScript code

---

## 👩‍💻 Author

**Halenur Gürel**
Homework Project - _JavaScript Function Exercises_
📍 JS · Functions · Template Literals · Parsing Numbers
🔗 [GitHub Profile](https://github.com/halenurgurel)

---

> 🎯 _“Each function was written with clarity and precision, focusing on core JavaScript fundamentals and clean output formatting.”_
