# Name Letter Counter

This project demonstrates how to pass data between the **server** and **client** using **Express.js** and **EJS**. It allows users to enter their first and last names, calculates the total number of letters in their name, and displays the result dynamically.

---

## Features

- **Data Passing from Client to Server**: The user submits their first and last name via a form, and the data is sent to the server using a `POST` request.
- **Data Passing from Server to Client**: The server calculates the total number of letters in the name and sends the result back to the client, which is then displayed dynamically using EJS.
- **Dynamic Content Rendering**: Uses EJS to conditionally render content based on whether the result is available or not.

---

## Technologies Used

- **Express.js**: A fast and minimalist web framework for Node.js.
- **EJS**: A simple templating language for generating HTML markup with JavaScript.
- **Body-parser**: Middleware to parse incoming request bodies.
- **Node.js**: A JavaScript runtime for building scalable network applications.

---

## How It Works

1. **Client-Side Form Submission**:
   - The user enters their first and last name in the form and submits it.
   - The form data is sent to the server via a `POST` request to the `/submit` route.

2. **Server-Side Processing**:
   - The server uses `body-parser` to extract the form data (`fName` and `lName`).
   - It calculates the total number of letters in the name by adding the lengths of the first and last names.
   - The result (`numberOfLetters`) is passed back to the client by rendering the EJS template with the data.

3. **Client-Side Rendering**:
   - The EJS template (`solution.ejs`) conditionally displays either the result or a prompt to enter a name, depending on whether `numberOfLetters` is available.