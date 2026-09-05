# Basic-Informational-Site

A lightweight HTTP server built entirely with native Node.js modules (`http` and `fs`), requiring no external dependencies.

## Project Structure

Ensure all HTML files sit in the same directory as `index.js`:

```text
├── index.js
├── index.html
├── about.html
├── contact-me.html
└── 404.html
```

## Getting Started

1. Prerequisites: Ensure [Node.js](https://nodejs.org/) is installed on your machine.
2. Start the server:
   ```bash
   node index.js
   ```
3. Open your browser: Navigate to [http://localhost:8080](http://localhost:8080).

## Routes

| URL Path         | Served File       | Status Code |
| :--------------- | :---------------- | :---------- |
| `/`              | `index.html`      | 200         |
| `/about`         | `about.html`      | 200         |
| `/contact-me`    | `contact-me.html` | 200         |
| _Any other path_ | `404.html`        | 404         |
