# Smart E-Invoice Using DOM Manipulation

## 📌 Project Overview

Smart E-Invoice is a simple web project developed using HTML, CSS, and JavaScript.
The system simulates an electronic invoice used in online shopping or payment systems.

This project demonstrates how JavaScript DOM Manipulation can dynamically update invoice data directly on the webpage.

---

# 🎯 Project Objectives

- Build a simple electronic invoice interface
- Practice JavaScript DOM Manipulation
- Update HTML content dynamically
- Handle user interactions using JavaScript
- Calculate invoice totals automatically

---

# 🛠 Technologies Used

## 1. HTML
Used to:
- Create invoice structure
- Create tables, buttons, and content
- Organize webpage layout

## 2. CSS
Used to:
- Design the user interface
- Improve layout and appearance
- Create a cleaner and more modern invoice design

## 3. JavaScript
Used to:
- Add interactivity
- Manipulate DOM elements
- Handle click events
- Calculate invoice values dynamically

---

# 🧠 DOM Manipulation Concepts

The project uses DOM Manipulation to access and modify HTML elements dynamically.

## Important DOM Methods and Properties

### getElementById()
Used to access a single HTML element by its id.

Example:
```javascript
let total = document.getElementById('TongThanhToan');
```

---

### getElementsByClassName()
Used to access multiple elements with the same class.

Example:
```javascript
const soLuong = document.getElementsByClassName('sl');
```

---

### innerHTML
Used to read or update HTML content dynamically.

Example:
```javascript
element.innerHTML = "1000";
```

---

### onclick
Used to handle click events.

Example:
```html
<button onclick="calculateInvoice()">Process Payment</button>
```

---

### parseInt()
Used to convert text into integer numbers for calculations.

Example:
```javascript
parseInt("5")
```

Result:
```javascript
5
```

---

# ⚙️ System Workflow

1. User clicks the "+" button
2. Product quantity increases dynamically
3. User clicks the "Process Payment" button
4. JavaScript reads all quantities and prices
5. Sub-total is calculated for each product
6. Grand total is calculated automatically
7. Invoice is updated on the webpage
8. Success notification appears

---

# 🧮 Invoice Calculation Formula

## Sub-total Formula

```text
Sub-total = Quantity × Unit Price
```

## Grand Total Formula

```text
Grand Total = Sum of all sub-totals
```

---

# 📂 Project Structure

```text
project-folder/
│
├── index.html
├── style.css
└── README.md
```

---

# 🚀 Main Features

- Display invoice information
- Increase product quantity dynamically
- Automatic invoice calculation
- Display grand total
- Payment success alert
- Dynamic HTML updates using DOM

---

# 📸 Demo Description

When the user clicks the plus button:
- Product quantity increases dynamically.

When the user clicks the "Process Payment" button:
- The system calculates the sub-total and grand total automatically.
- The invoice updates immediately.

---

# 📖 Knowledge Learned

Through this project, the following concepts were practiced:

- HTML Table Structure
- CSS Styling
- JavaScript Functions
- DOM Manipulation
- Event Handling
- Dynamic Data Update
- Invoice Calculation Logic

---

# 🔮 Future Improvements

Possible future upgrades:

- Add product images
- Add shopping cart system
- Connect database
- Improve UI/UX design
- Add product removal feature
- Add quantity decrease button

---

# 👨‍💻 Conclusion

This project demonstrates how JavaScript DOM Manipulation can create interactive and dynamic web applications.

The Smart E-Invoice system is a simple but practical example of applying frontend web development concepts in real-world payment systems.

