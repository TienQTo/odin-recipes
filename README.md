# Odin Recipes

## Project Overview

Odin Recipes is a simple static website built with HTML as part of [The Odin Project's Foundations course](https://www.theodinproject.com/lessons/foundations-recipes). The project showcases a collection of three recipes (Lasagna, Pizza, and Pasta), each with its own dedicated page. The website includes a homepage that links to individual recipe pages, which feature descriptions, ingredients, and step-by-step instructions for preparing each dish.

This project demonstrates basic HTML skills, including:
- Structuring web pages with semantic HTML.
- Creating navigation links between pages.
- Using lists (`<ul>` and `<ol>`) for ingredients and steps.
- Embedding images with proper attributes.

## Features

- **Homepage (`index.html`)**: Displays a list of recipe links in an unordered list (`<ul>`).
- **Recipe Pages (`lasagna.html`, `pizza.html`, `pasta.html`)**:
  - Each page includes a title, an image of the dish, a description, a list of ingredients, and step-by-step instructions.
  - A "Home" link allows users to navigate back to the homepage.
- Clean and organized file structure with a dedicated `recipes` directory.

## Directory Structure

<pre>
odin-recipes/
│
├── index.html      # Homepage with links to recipe pages
├── css/            # Directory for CSS styles
│   ├── styles.css      # Main stylesheet
├── recipes/        # Directory containing individual recipe pages
│   ├── lasagna.html    # Lasagna recipe page
│   ├── pizza.html      # Pizza recipe page
│   ├── pasta.html      # Pasta recipe page
└── README.md       # Project documentation
</pre>

## Getting Started

To view the Odin Recipes website locally:

1. **Clone the repository** (if hosted on GitHub):
   ```bash
   git clone <repository-url>
   cd odin-recipes
   ```
2. **Open the homepage**
   - Navigate to the `odin-recipes` directory.
   - Open `index.html` in a web browser (e.g., double-click the file or use a browser's "Open File" option).
3. **Explore the recipes**
   - Click the links on the homepage to view individual recipe pages.
   - Use the "Home" link on each recipe page to return to the homepage.

## Installation

No additional installation is required, as the project uses plain HTML and can be viewed in any modern web browser (e.g., Chrome, Firefox, Edge).

## Technologies Used

- **HTML5:** For structuring the website and content.
- **Images:** Sourced from [Depositphotos](depositphotos.com) for free, high-quality visuals.

## Acknowledgments

- **The Odin Project:** For providing the project guidelines and learning resources.
- **Depositphotos:** For free images used in the recipe pages.

## License

This project is open-source and available under the MIT License.