# Change_Quotes-Project-
# Quote Changer Web Application

## Overview
This project is a simple web application that displays random inspirational quotes. Users can manually change the quote by clicking a button, or the quotes will automatically change every 5 seconds.

## Technologies Used
- HTML
- CSS (Bootstrap 5.3.3 for styling)
- JavaScript

## Features
- Displays a random quote upon page load.
- Allows users to change the quote by clicking a button.
- Automatically changes the quote every 5 seconds.
- Uses a predefined list of quotes and authors.

## File Structure
- `index.html` : Main HTML file containing the structure of the webpage.
- `styles` : Inline CSS for designing the layout.
- `Bootstrap` : Used via CDN for styling and responsiveness.
- `JavaScript` : Script for handling the quote changes dynamically.

## How It Works
1. The `blockquote` and `blockquote-footer` elements display a quote and its author.
2. A JavaScript function `changeQuates()` selects a random quote from an array and updates the content.
3. Clicking the "Change Quotes" button triggers the function to display a new quote.
4. The `setInterval` method calls `changeQuates()` every 5 seconds to change the quote automatically.

## How to Run
1. Open `index.html` in a web browser.
2. Click the "Change Quotes" button to manually switch quotes.
3. Observe automatic changes every 5 seconds.

## Live Demo
You need to host this file online to get a live link. You can use:
- **GitHub Pages**
- **Netlify**
- **Vercel**
- **CodePen**

### Deploying on GitHub Pages
1. Create a GitHub repository.
2. Upload the `index.html` file.
3. Go to **Settings** > **Pages**.
4. Set the branch to `main` and click "Save".
5. Your project will be live at `change-quotes-project-119a28nzn-rudra-gondaliyas-projects.vercel.app`.

Let me know if you need help with deployment!

