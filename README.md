<!DOCTYPE html>
<html lang="en">
  <head>
    <meta charset="UTF-8" />
    <meta name="viewport" content="width=device-width, initial-scale=1.0" />
    <title>Landing Page</title>
    <style>
      body {
        margin: 0;
        font-family: "Roboto", sans-serif;
      }

      .header {
        font-size: 24px;
        color: #f9faf8;
        background-color: #1f2937;
      }

      .hero-section {
        font-size: 48px;
        color: #f9faf8;
        font-weight: 900;
        background-color: #1f2937;
      }

      .hero-subtitle {
        font-size: 18px;
        color: #5e7eb0;
      }

      .button {
        background-color: #3882f6;
      }

      .information-headings {
        font-size: 36px;
        color: #1f2937;
        font-weight: 300;
      }

      .quote {
        background-color: #e5e7eb;
        font-size: 36px;
        color: #1f2937;
        font-weight: 300;
        font-style: italic;
      }

      .footer {
        font-family: "Roboto", sans-serif;
        background-color: #1f2937;
        font-size: 24px;
        color: #f9faf8;
      }
    </style>
  </head>
  <body>
    <header class="header">
      <nav>
        <ul>
          <li>Header</li>
        </ul>
      </nav>
    </header>

    <main>
      <section class="hero-section">
        <h1>This website is awesome</h1>
        <p class="hero-subtitle">This website has some subtitle</p>
        <button class="button" type="button">Call to action</button>
      </section>

      <section class="information-headings">
        <h2>Information</h2>
      </section>

      <blockquote class="quote" cite="https://www.caregivers.org.za">
        This is a quote from the caregivers website.
      </blockquote>
    </main>

    <footer class="footer">
      Footer
    </footer>
  </body>
</html>
