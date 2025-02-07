# Weekend Or Weekday Web Application

This is a simple web application built with **Express.js** and **EJS** (Embedded JavaScript) templating. It dynamically determines whether today is a **weekday** or a **weekend** and displays an appropriate message to the user.

---

## Features

- **Dynamic Day Detection**: The application checks the current day of the week and determines if it's a weekday or the weekend.
- **Custom Messages**: Displays a motivational message for weekdays and a fun message for weekends.
- **EJS Templating**: Uses EJS to render dynamic HTML content.

---

## Technologies Used

- **Express.js**: A fast and minimalist web framework for Node.js.
- **EJS**: A simple templating language for generating HTML markup with JavaScript.
- **Node.js**: A JavaScript runtime for building scalable network applications.

---

## How It Works

1. The server checks the current day using JavaScript's `Date` object.
2. If the day is **Saturday (6)** or **Sunday (0)**, it sets the day type to "the weekend" and displays a fun message.
3. If the day is a weekday (Monday to Friday), it sets the day type to "a weekday" and displays a motivational message.
4. The result is rendered dynamically using an EJS template (`index.ejs`).