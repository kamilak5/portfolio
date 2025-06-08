<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>My Data Science Portfolio</title>
  <style>
    html {
      scroll-behavior: smooth;
    }

    body {
      font-family: Arial, sans-serif;
      margin: 0;
      padding: 0;
      line-height: 1.6;
      background-color: #f7f7f7;
      color: #333;
    }

    section {
      padding: 60px 20px;
      max-width: 800px;
      margin: 0 auto;
    }

    h1, h2 {
      color: #2c3e50;
    }

    .button {
      display: inline-block;
      padding: 10px 20px;
      background-color: #4a90e2;
      color: white;
      text-decoration: none;
      border-radius: 5px;
      font-weight: bold;
      margin-top: 20px;
    }

    .button:hover {
      background-color: #357abd;
    }

    ul {
      list-style: none;
      padding-left: 0;
    }

    ul li {
      margin-bottom: 10px;
    }

    a {
      color: #4a90e2;
    }

    a:hover {
      text-decoration: underline;
    }

    footer {
      text-align: center;
      padding: 20px;
      font-size: 0.9em;
      color: #888;
    }
  </style>
</head>

<body>

<!-- Home Section -->
<section id="home">
  <style>
    .intro {
      display: flex;
      align-items: flex-start;
      justify-content: space-between;
      gap: 20px;
      flex-wrap: wrap;
    }

    .intro-text {
      flex: 1;
      min-width: 250px;
    }

    .intro img {
      width: 250px;
      height: auto;
      border-radius: 10px;
      object-fit: cover;
      order: 2; /* To force image to appear after text visually */
      margin-top: 90px;
    }

    @media (max-width: 768px) {
      .intro {
        flex-direction: column;
        align-items: center;
      }

      .intro img {
        order: 0;
        width: 100%;
        max-width: 320px;
      }
    }
  </style>


  <div class="intro">
    <img src="zdj_cv.jpg" alt="Kamila Kubicka" />

    <div class="intro-text">
      <h1>Welcome to my page!</h1>
      <p>
  I'm a <strong> data scientist </strong> with a background in <strong> cognitive science </strong>, focused on creating intelligent, user-aware systems that combine technical precision with human-centered design. My interdisciplinary foundation gives me a strong base and I'm excited to keep learning, exploring new tools and methods to solve meaningful problems.
</p>
<p>
  I help teams turn data into actionable insight, working at the intersection of machine learning, human-centered design, and LLM integration. If you're looking to <strong>improve predictions, personalize user experience, or prototype AI-driven solutions</strong> — you're in the right place.
</p>

    </p><p>
        Here you’ll find a selection of <strong> my projects </strong>, including <strong> end-to-end ML applications, data exploration reports, and user-focused prototypes </strong>. Each project reflects my commitment to thoughtful design, clean data pipelines, and meaningful impact.
    </p>
   <p style="margin-top: 30px;">
  <a href="contact/" style="font-size: 1.2em; font-weight: bold; color: #4a90e2; text-decoration: underline;">
    Let’s solve smart problems together →
  </a>
</p>

  </section>


  <!-- Footer -->
  <footer>
    © 2025 Kamila Kubicka — All rights reserved.
       <a href="contact/">Contact</a>
      <a href="mailto:kamilakubicka5@gmail.com">kamilakubicka5@gmail.com</a> | <a href="contact/">Contact</a>
  </footer>

</body>
</html>
