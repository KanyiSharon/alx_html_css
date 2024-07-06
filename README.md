# Responsive Webpage Design

This project is a responsive webpage design that adjusts its layout for mobile devices when the screen width is 480px or less. The design includes hover and active state styles for links and buttons, as well as a maximum content width of 1000px centered on the page.

## Features

1. **Responsive Design**: The webpage switches to a mobile-friendly layout when the screen width is 480px or less.
2. **Hover/Active States**:
   - Links change color to `#FF6565` on hover and active states.
   - Buttons change opacity to `0.9` on hover and active states.
3. **Max Width of Content**: The main content is centered on the page with a maximum width of 1000px.

## Files

### index.html

This file contains the HTML structure of the webpage.

```html
<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Responsive Design Example</title>
    <link rel="stylesheet" href="styles.css" />
  </head>
  <body>
    <header>
      <!-- Header content here -->
    </header>

    <main class="content">
      <section class="hero">
        <h1>Lorem ipsum dolor sit amet</h1>
        <p>Consectetur adipiscing elit. Nulla convallis egestas rhoncus.</p>
        <button>Call to Action</button>
      </section>

      <section class="services">
        <h2>What we do...</h2>
        <p>Provide high-quality services that cater to various needs.</p>
        <div class="service-items">
          <div class="service-item">
            <h3>Service One</h3>
            <p>Lorem ipsum</p>
          </div>
          <div class="service-item">
            <h3>Service Two</h3>
            <p>Lorem ipsum</p>
          </div>
          <div class="service-item">
            <h3>Service Three</h3>
            <p>Lorem ipsum</p>
          </div>
        </div>
      </section>

      <section class="results">
        <h2>Our results speak for themselves</h2>
        <div class="result-items">
          <div class="result-item">
            <p>+2%</p>
            <p>Lorem ipsum</p>
          </div>
          <div class="result-item">
            <p>+2%</p>
            <p>Lorem ipsum</p>
          </div>
          <div class="result-item">
            <p>+2%</p>
            <p>Lorem ipsum</p>
          </div>
        </div>
      </section>

      <section class="contact">
        <h2>Contact us</h2>
        <form>
          <input type="text" placeholder="Name" />
          <input type="email" placeholder="Email" />
          <textarea placeholder="Message"></textarea>
          <button type="submit">Get in Touch</button>
        </form>
      </section>
    </main>

    <footer>
      <!-- Footer content here -->
    </footer>
  </body>
</html>
```
