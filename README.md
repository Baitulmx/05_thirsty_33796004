# 🍹 Thirsty Student Shop (EJS + Express)
 
building a simple web application using **Node.js**, **Express**, and **EJS templating**.

---

## 📘 Overview

The **Undehyrated Student Shop** is a drinks store website that displays product categories and shop branches dynamically using EJS templates.  
Users can navigate through several pages, search for drinks, register their details, and complete a short customer survey to give feedback.

---

## 🏗️ Features

✅ **Express Server**
- Handles routing for multiple pages: Home, About, Search, Register, and Survey.  

✅ **EJS Templates**
- All HTML pages are rendered dynamically using the EJS view engine.

✅ **Dynamic Data**
- Shop name and product categories are stored in `main.js` and rendered into templates.

✅ **Search Form (GET)**
- Users can search by name and category.

✅ **Register Form (POST)**
- Collects first name, last name, and email, and returns a confirmation message.

✅ **Survey Form**
- Collects user details, age, drink preference, and student status.

✅ **Styling**
- Styled using an external `style.css` file located in the `public` folder.

✅ **Shop Branch List**
- Displays all shop locations, managers, and addresses dynamically.

------------------------

## 📂 Project Structure

05_thirsty_12345678/

│
├── index.js # Main Express server setup
├── routes/
│ └── main.js # Route definitions for all pages
│
├── views/ # EJS templates
│ ├── index.ejs
│ ├── about.ejs
│ ├── search.ejs
│ ├── register.ejs
│ ├── survey.ejs
│ └── survey_result.ejs
│
├── public/ # Static assets (CSS, images, etc.)
│ └── style.css
│
├── package.json # Node.js dependencies
├── .gitignore # Ignores node_modules and other unneeded files
└── README.md # Project documentation
