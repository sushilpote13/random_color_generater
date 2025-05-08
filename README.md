---

# 🎨 Linear Color Generator

A simple and interactive web-based tool that allows users to generate **random linear gradient background colors**. This project is created using HTML, CSS, and JavaScript. Users can click on two color buttons to randomly generate gradient colors and **copy the CSS code** to use in their own designs.

---

## 📌 Features

* ✅ Random linear gradient color generation on button click
* ✅ Real-time background color update on the webpage
* ✅ Copy-to-clipboard functionality for the generated CSS code
* ✅ Stylish and responsive UI using Google Fonts
* ✅ Clean layout and smooth hover effects for enhanced UX

---

## 🛠️ Technologies Used

* **HTML5** – Structure and layout of the webpage
* **CSS3** – Styling, layout, font integration, hover effects
* **JavaScript (ES6)** – Dynamic color generation, event handling, clipboard functionality
* **Google Fonts** – Modern font styles (Urbanist and others)

---

## 🧠 How It Works

1. Two buttons represent two color stops in the linear gradient.
2. When a button is clicked, a random HEX color is generated.
3. The background gradient updates instantly using the two colors.
4. The CSS code is shown below the buttons and can be copied by clicking on it.

---

## 📷 Preview

![image](https://github.com/user-attachments/assets/8a95b11d-147d-4e83-93e7-68c10cddab6a)


---

## 📋 Code Overview

### 🔹 HTML

The structure contains:

* Two color buttons (`btn-1`, `btn-2`)
* A heading to instruct users
* A `div` displaying the generated gradient CSS code

### 🔹 CSS

* Uses `linear-gradient` for background
* Modern UI styling with hover and animation effects
* Font imported from [Google Fonts](https://fonts.google.com)

### 🔹 JavaScript

* `colorGenerate()` creates random HEX codes
* Event listeners on buttons to trigger gradient change
* `navigator.clipboard.writeText()` allows copying the CSS code

---

## 🚀 Getting Started

### 📁 Clone the Repository

```bash
git clone https://github.com/your-username/linear-color-generator.git
cd linear-color-generator
```

### 🧪 Run Locally

Just open the `index.html` file in your browser.

---

## 💡 Use Case

This tool is perfect for:

* Web developers looking for quick gradient inspiration
* UI designers wanting to test out combinations
* Students learning about colors and JavaScript events

---

## ✅ To-Do (Future Enhancements)

* Add gradient angle customization
* Add color picker for manual color input
* Save favorite gradients to local storage
* Export CSS code directly as a `.css` file

---

## 📄 License

This project is licensed under the **MIT License** - feel free to use, modify, and distribute it for personal or commercial use.

---

## 🙌 Author

Made with ❤️ by **Sushil Ashok Pote**

---
