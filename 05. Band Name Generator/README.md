# 🎸 Band Name Generator

This project is a **fun and interactive Band Name Generator** built using **Express.js** and **EJS**. With just one click, it generates a random band name by combining an **adjective** and a **noun**.

---

## 🚀 Features

- **Random Name Generation**: Generates a unique band name by randomly selecting an adjective and a noun from predefined lists.
- **Dynamic Rendering with EJS**: Uses Embedded JavaScript (EJS) to dynamically update and display the generated band names.
- **Express.js Backend**: A simple and efficient backend using Express.js.
- **Styled UI**: Custom CSS for a **dark-themed**, modern look.

---

## 🛠️ Technologies Used

- **Node.js**: JavaScript runtime environment
- **Express.js**: Lightweight web framework
- **EJS**: Templating engine for rendering dynamic content
- **Body-parser**: Middleware to parse form data
- **CSS**: Custom styles for a visually appealing interface

---

## 🎯 How It Works

### **1️⃣ Load the Home Page (`/`)**
- The server renders `solution.ejs`, which includes a "Generate Name" button.

### **2️⃣ Generate a Band Name**
- When the user clicks **"Generate Name"**, a `POST` request is sent to `/submit`.
- The server selects a **random adjective** and **random noun** from predefined arrays.

### **3️⃣ Display the Result**
- The generated band name is dynamically inserted into the `solution.ejs` template and displayed on the page.