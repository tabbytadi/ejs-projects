# EJS Partials Web Project

This project demonstrates how to use **EJS partials** to create a modular and reusable web layout with **Express.js**. The application serves a **Home**, **About**, and **Contact** page, using **EJS templates** for dynamic content rendering.

---

## Features

- **Modular Page Structure**: Uses **EJS partials** (`header.ejs`, `footer.ejs`) to maintain consistency across multiple pages.
- **Static File Handling**: Express serves CSS and other assets from the `public` directory.
- **Dynamic Routing**: Implements Express.js routes to render different pages (`index.ejs`, `about.ejs`, `contact.ejs`).
- **Responsive UI**: Styled using **Bootstrap** and **custom CSS**.
- **Navigation Bar**: Includes a **Bootstrap navbar** with links to all pages.

---

## Technologies Used

- **Express.js**: A lightweight web framework for Node.js.
- **EJS**: A templating engine for rendering dynamic HTML.
- **Bootstrap**: A front-end framework for responsive design.
- **CSS**: Custom styles for layout and aesthetics.
- **Font Awesome & Ionicons**: Icon libraries for social and navigation elements.

---

## How It Works

1. **Server Setup (index.js)**:
   - Sets up an Express.js server and serves static files from the `public` directory.
   - Handles GET requests for `/`, `/about`, and `/contact` to render respective EJS templates.

2. **EJS Templating**:
   - `header.ejs` and `footer.ejs` are included in every page for consistency.
   - The content in `index.ejs`, `about.ejs`, and `contact.ejs` is wrapped within the header and footer.

3. **Routing & Page Rendering**:
   - Visiting `/` loads the **Home Page** (`index.ejs`).
   - Visiting `/about` loads the **About Page** (`about.ejs`).
   - Visiting `/contact` loads the **Contact Page** (`contact.ejs`).