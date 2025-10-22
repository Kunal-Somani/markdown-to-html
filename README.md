# Markdown Viewer Application

This is a simple, single-file web application designed to convert and display Markdown content from an `input.md` file into a formatted HTML page using [Marked.js](https://marked.js.org/) and styled with [Tailwind CSS](https://tailwindcss.com/).

## Features

*   **Markdown to HTML Conversion:** Automatically fetches `input.md` and renders its content as HTML.
*   **Responsive Design:** Utilizes Tailwind CSS for a responsive and clean user interface.
*   **Easy Setup:** A single `index.html` file contains all the necessary code, including external CDN links for Marked.js and Tailwind CSS.
*   **Typography Styling:** Integrates Tailwind's Typography plugin for beautifully formatted Markdown output.

## How to Use

1.  **Place `input.md`:** Ensure your Markdown file (`input.md`) is located in the same directory as `index.html`.
2.  **Open `index.html`:** Simply open `index.html` in any modern web browser.

The application will automatically load, parse, and display the content of `input.md`.

## Project Structure

```
.
├── index.html
├── input.md
└── README.md
└── LICENSE
```

## Technologies Used

*   **HTML5:** Structure of the web page.
*   **Tailwind CSS:** For styling and responsiveness, including the Typography plugin for markdown rendering.
*   **Marked.js:** A robust Markdown parser and compiler.
*   **JavaScript (ES6+):** For fetching the markdown file and dynamic content rendering.

## License

This project is open-sourced under the MIT License. See the `LICENSE` file for more details.