Newsletter Project

This project creates a beautifully styled newsletter using CSS and HTML, based on freeCodeCamp's code samples and inspired design. This README includes an overview of the structure, images to represent key elements, and detailed directions.
Project Overview

The project implements a responsive newsletter layout with CSS Grid and Flexbox. It features several distinct sections, each styled for modern and accessible typography and layout. Key sections include:

    Hero Section: Large image with title and subtitle.
    Author Information: Author bio and social media links.
    Main Content: Project-driven content with quotes, history, and images.

Preview
Preview Image 1	Preview Image 2	Preview Image 3
Hero Section	Calculator Project	Quote Machine Project

Note: These images show placeholder designs from freeCodeCamp’s resource collection.
Installation and Setup

    Clone the Repository:

    git clone https://github.com/enock-niyonsaba/HTML-CSS-Building
    cd HTML-CSS-Building

    Open the Project: Open index.html in a web browser to view the newsletter structure.

    Edit Styles: Modify styles.css to customize fonts, colors, and layout as per project requirements.

Project Structure
CSS Styles

The CSS structure is designed for optimal readability and responsive adaptability. Key styles include:

*,
::before,
::after {
  padding: 0;
  margin: 0;
  box-sizing: border-box;
}
html {
  font-size: 62.5%;
}
body {
  font-family: 'Baskervville', serif;
  color: linen;
  background-color: rgb(20, 30, 40);
}

    Font Selection: Uses 'Baskervville' for body text and 'Raleway' for headings.
    Grid Layout: The main content is displayed using grid-template-columns, with responsive adjustments for smaller screens.

HTML Structure

The HTML follows a semantic structure with section and article tags, providing a clear division of content. Each section is structured to be easy to navigate and styled as follows:

<main>
  <section class="heading">
    <header class="hero">
      <img src="https://cdn.freecodecamp.org/platform/universal/fcc_meta_1920X1080-indigo.png" alt="hero image" class="hero-img" />
      <h1 class="hero-title">OUR NEW CURRICULUM</h1>
      <p class="hero-subtitle">Project-based learning approach</p>
    </header>
    <div class="author">
      <p>By freeCodeCamp</p>
    </div>
  </section>
</main>

Usage Instructions

    Update Text Content: Add your own text to sections like hero-title, author-name, and various paragraph elements.
    Add Images: Replace placeholder images with your own images, ensuring they fit within the .image-wrapper for responsiveness.

License

This project is licensed under the MIT License. See the LICENSE file for details.