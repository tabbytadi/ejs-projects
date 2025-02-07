# EJS Tags Demonstration Project

This project demonstrates the use of **EJS (Embedded JavaScript)** templating with **Express.js**. It showcases various EJS tags and features, including dynamic content rendering, conditionals, loops, and including partials.

---

## Features

- **Dynamic Content Rendering**: Displays dynamic data such as the current second and a list of items.
- **Conditionals**: Uses EJS conditionals to display content based on whether the current second is even or odd.
- **Loops**: Iterates over an array of items and renders them in a list.
- **HTML Escaping and Unescaping**: Demonstrates the difference between `<%= %>` (escaped output) and `<%- %>` (unescaped output).
- **Partials**: Includes a partial template (`footer.ejs`) to modularize the code.

---

## Technologies Used

- **Express.js**: A fast and minimalist web framework for Node.js.
- **EJS**: A simple templating language for generating HTML markup with JavaScript.
- **Node.js**: A JavaScript runtime for building scalable network applications.

---

## How It Works

1. The server dynamically generates data (title, current second, list of items, and HTML content).
2. The data is passed to the EJS template (`index.ejs`).
3. The EJS template uses various tags to render the data:
   - `<%= %>`: Outputs escaped content.
   - `<%- %>`: Outputs unescaped content (e.g., raw HTML).
   - `<% %>`: Executes JavaScript code (e.g., conditionals and loops).
4. The template includes a partial (`footer.ejs`) to demonstrate modularization.