<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Charity: Water College Campaign</title>
  <link href="https://fonts.googleapis.com/css2?family=Proxima+Nova&display=swap" rel="stylesheet" />
  <style>
    :root {
      --yellow: #FFC907;
      --navy: #003366;
      --blue: #77A8BB;
      --cream: #FFF7E1;
      --black: #1A1A1A;
      --gray: #CBCCD1;
      --pink: #FED8C1;
      --font: 'Proxima Nova';
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: var(--font);
      background-color: var(--black);
      color: var(--cream);
      line-height: 1.6;
      min-height: 100vh;
      display: flex;
      flex-direction: column;
      justify-content: space-between;
    }

    nav {
      background-color: var(--black);
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: var(--cream);
      flex-wrap: wrap;
    }

    .logo img {
      height: 40px;
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      padding-top: 0.5rem;
    }

    nav ul li a {
      color: var(--cream);
      font-family: var(--font);
      text-decoration: none;
      font-size: 1rem;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: var(--blue);
    }

    header {
      background: url('https://cdn2.dropmarkusercontent.com/52043/e81bc77957f16a7e4b6308fed5816d1aab58afb3/preview/JS_20170803_2859.jpg') center/cover no-repeat;
      height: 90vh;
      color: var(--cream);
      font-family: var(--font);
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      text-shadow: 2px 2px 6px rgba(0, 0, 0, 0.6);
      padding: 1rem;
    }

    header h1 {
      font-size: 1.7rem;
      margin-top: 40rem;
      max-width: 700px;
      margin-bottom: 50rem;
    }

    header h2 {
      max-width: 900px;
      margin: 4rem auto 4rem auto;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
    }

    section {
      max-width: 700px;
      margin: 2rem auto 5rem auto;
      padding: 0 1rem;
      text-align: center;
    }

    section h3 {
      background-color: var(--cream);
      color: var(--navy);
      border: none;
      padding: 1rem 2rem;
      border-radius: 20px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
      margin-bottom: 1rem;
    }

    section h4 {
      margin-bottom: 2rem;
      line-height: 1.5;
    }

    .blue-section {
      background-color: var(--blue);
      color: var(--navy);
      padding: 3rem 1rem;
      text-align: center;
    }

    .blue-section h3 {
      font-size: 1.5rem;
      margin-bottom: 1rem;
    }

    .blue-section p {
      font-size: 1rem;
      max-width: 600px;
      margin: 0 auto 2rem auto;
    }

    .button-group {
      display: flex;
      flex-wrap: wrap;
      justify-content: center;
      gap: 1rem;
      margin-top: 1rem;
    }

    .cta-button {
      background-color: var(--cream);
      color: var(--navy);
      border: none;
      padding: 1rem 2rem;
      font-size: 1.1rem;
      border-radius: 50px;
      cursor: pointer;
      transition: background-color 0.3s ease;
      font-family: var(--font);
      font-weight: 600;
      box-shadow: 0 4px 8px rgba(0, 0, 0, 0.15);
    }

    .cta-button:hover {
      background-color: var(--pink);
    }

    footer {
      background-color: var(--black);
      color: var(--cream);
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      font-family: var(--font);
      border-top: 1px solid var(--gray);
      margin-top: auto;
    }

    @media (min-width: 768px) {
      nav ul {
        gap: 1.5rem;
      }

      header h1 {
        font-size: 3rem;
      }
    }
  </style>
</head>

<body>
  <nav>
    <div class="logo">
      <img src="WhiteLogo.png" alt="Charity: Water Logo" />
    </div>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#take-action">Take Action</a></li>
    </ul>
  </nav>

  <header>
    <h1>Change the World, One Drop at a Time</h1>
    <h2>Swap scrolling for a tap, Be the reason someone's life changes today</h2>
  </header>

  <section>
    <h3>Why Change The World?</h3>
    <h4>
      Technology has reached many corners of the world—but millions still live without life’s most basic need: clean water. At Charity: Water, we fund community-led, sustainable water projects in places where the need is greatest. 100% of public donations go directly to the field, and every project is mapped and tracked. Join a generation that’s turning connection into compassion—and progress into clean water for all.
    </h4>
  </section>

  <section class="blue-section">
    <h3>Let's Make Waves</h3>
    <p>Every dollar you give goes directly to bringing clean water to communities in need. From digging wells to innovating purification systems, you're not just donating — you're transforming lives drop by drop.</p>
    <div class="button-group">
      <button class="cta-button">Once</button>
      <button class="cta-button">Monthly</button>
    </div>
    <div class="button-group">
      <button class="cta-button">$10 USD/mo</button>
      <button class="cta-button">$20 USD/mo</button>
      <button class="cta-button">$30/mo</button>
      <button class="cta-button">$40/mo</button>
    </div>
  </section>

  <section>
    <button class="cta-button">Send Water Not Just Wifi</button>
  </section>

  <footer>
    &copy; Charity: Water 2025
  </footer>
</body>
</html>

