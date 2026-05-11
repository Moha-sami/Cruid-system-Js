# Product Management System (CRUD) 🚀

A lightweight, interactive client-side **Product Management System** built during my early front-end web development journey. This project demonstrates essential JavaScript concepts, local storage integration, dynamic DOM manipulation, and responsive UI design using Bootstrap.

🔗 **Live Demo:** [View Live App](https://moha-sami.github.io/Cruid-system-Js/)

---

## 🛠️ Tech Stack Used
* **HTML5:** Semantic markup structure.
* **CSS3:** Custom styling and visual enhancements.
* **Bootstrap 5:** Fully responsive design and modern UI components.
* **JavaScript (ES6):** Dynamic application logic, calculations, and data persistence.

---

## ✨ Key Features & Functionality

This application provides a complete dashboard to manage product inventories with the following operations:

### 1. **Complete CRUD Lifecycle**
* **Create:** Add new products with details like Title, Price, Taxes, ADS, Discount, Category, and Count (for bulk adding).
* **Read:** Display all stored products in a clean, dynamically updated tabular layout.
* **Update:** Edit existing product details inline with one-click data loading.
* **Delete:** Remove a specific product or wipe out the entire dataset at once using the "Delete All" option.

### 2. **Real-time Price & Margin Calculator**
* Automatically calculates the total cost of a product on-the-fly as the user types the raw price, taxes, advertising costs (ADS), and discount.
* Dynamically changes the calculator background color to green when a valid total is calculated to give instant visual feedback.

### 3. **Persistent Local Storage**
* All product data is saved directly to the browser's `localStorage`.
* Prevents data loss, ensuring your inventory remains intact even after refreshing or closing the browser.

### 4. **Smart Bulk Creation (Count Property)**
* A dedicated "Count" input allows you to instantly generate and seed multiple duplicate records of the same product with a single click.

### 5. **Instant Live Search**
* Easily filter through your inventory using the real-time search engine.
* Supports searching dynamically by **Product Title** or **Category** with instant UI updates.

### 6. **Form Validation & Input Resetting**
* Safely clears out all form input fields automatically after every successful insertion.
* Basic validation to ensure fields are populated correctly before adding records.

---

## 📂 File Architecture

```text
├── index.html       # Application UI structure and layout (Bootstrap Integrated)
├── style.css        # Custom CSS overrides for theme styling
└── main.js          # Main application logic (Calculations, LocalStorage, DOM manipulation)


🚀 How to Run the Project Locally
No local server setup is required! You can run this app entirely in your browser:

1.Clone the Repository:
git clone [https://github.com/Moha-sami/Cruid-system-Js.git](https://github.com/Moha-sami/Cruid-system-Js.git)
cd Cruid-system-Js
2.Open the App:
Simply double-click the index.html file to open it in any modern web browser (Chrome, Edge, Firefox, Safari).
💡 What I Learned from This Project
Building structured dynamic UI components using modern JS.

Managing state and saving structured data in JSON format within localStorage.

Handling complex user inputs and event listeners (onkeyup, onclick).

Structuring clean conditional logic for both "Create" and "Update" states under a single form interface.
