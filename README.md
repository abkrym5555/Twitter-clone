# Twitter Clone

A beautiful and responsive Twitter clone built using HTML and Tailwind CSS. This project features a modern dark/light mode toggle and a clean, dynamic user interface mirroring the look and feel of Twitter.

## Features

- **Responsive Design**: Adapts beautifully to both desktop and mobile screens.
- **Dark/Light Mode**: Includes a fully functional dark mode toggle for a personalized viewing experience.
- **Modern UI**: Scalable formatting, dynamic hovering, and micro-animations mirroring the actual Twitter application.
- **Tailwind CSS**: Built with Tailwind CSS for utility-first styling.

## Getting Started

### Prerequisites

To run and edit this project locally, ensure you have Node.js and npm installed to use the Tailwind CLI.

### Installation

1. Clone this repository (or navigate to your project directory).
2. Install the dev dependencies:
   ```bash
   npm install
   ```

### Running the Project

You can compile the styles and watch for changes by running:
```bash
npm run watch
```
This script will watch for changes in the `./style.css` and HTML file and output the compiled Tailwind CSS into `./output.css`.

To preview the application, simply open `index.html` in your web browser.

## Project Structure

- `index.html` — The main structure and layout of the Twitter clone.
- `style.css` — Custom CSS entry point. Include your custom styles here.
- `output.css` — The compiled Tailwind CSS styles generated based on classes used in the HTML.
- `tailwind.config.js` — Configuration file for Tailwind CSS, containing custom color tokens and settings.
- `package.json` — Manages project dependencies and convenient run scripts.
