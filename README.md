# 🔗 Quick Link Saver (Chrome Extension)

A simple and lightweight Chrome extension built with **HTML, CSS, and JavaScript** to quickly save user-entered URLs into a viewable list. Ideal for keeping track of important links or articles to read later.

## ✨ Features

* **Input Saving:** Click the "SAVE INPUT" button to save the URL (or any text) entered in the field.
* **List Display:** Saved items are rendered in a simple list (`<ul>`).
* **Clickable Links:** Each list item is a clickable link that opens in a **new tab** (`target='_blank'`).
* **Pure JavaScript Logic:** All list and DOM management is implemented using Vanilla JavaScript.

## 🛠️ Technologies Used

* **HTML5:** Structure of the user interface (input field, button, list).
* **CSS3:** Basic styling for the extension pop-up.
* **JavaScript (Vanilla):** All the logic for event handling (`click`), array manipulation (`myLeads.push()`), and dynamically rendering DOM elements (`ulEl.innerHTML`).

## 🚀 How to Install and Use the Extension

Since this is a Chrome extension, the installation process is slightly different from simply opening an HTML file:

1.  **Clone the Repository:**
    ```bash
    git clone https://github.com/Michele20488/leads-tracker
    ```
2.  **Open Chrome Extensions Management:**
    * Navigate to `chrome://extensions/` in your Chrome browser's address bar.
3.  **Enable Developer Mode:**
    * Toggle the **"Developer mode"** switch on in the top right corner.
4.  **Load the Extension:**
    * Click the **"Load unpacked"** button.
    * Select the **root folder** of the project you just cloned.
5.  **Start Saving Links!**
    * The extension icon will appear in your Chrome toolbar. Click it to open the pop-up and start saving your links!

## 💡 Development Notes

This project serves as an excellent basic exercise for creating browser extensions and practicing fundamental JavaScript concepts, particularly:

* **DOM Manipulation:** Getting element references (`document.getElementById`) and dynamically updating HTML content (`ulEl.innerHTML`).
* **Event Listening:** Handling user interaction (`inputBtn.addEventListener("click", ...)`).
* **Data Structure Management:** Using a simple array (`myLeads`) to store the application state.
* **Template Strings:** Utilizing the `` \`...\` `` and `${}` format in JavaScript to construct HTML markup cleanly.

---

### Author

Michele Lombardi