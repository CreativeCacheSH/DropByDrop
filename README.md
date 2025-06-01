<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Charity: Water
  College Campaign</title>
  <link href="https://fonts.googleapis.com/css2?family=Proxima+Nova&display=swap" rel="stylesheet">
  <style>
    :root {
      --yellow: #FFC907;
      --navy: #003366;
      --blue: #77A8BB;
      --cream: #FFF7E1;
      --black: #1A1A1A;
      --gray: #CBCCD1;
      --font: 'Proxima Nova', sans-serif;
    }

    * {
      margin: 0;
      padding: 0;
      box-sizing: border-box;
    }

    body {
      font-family: var(--font);
      background-color: var(--gray);
      color: var(--black);
      line-height: 1.6;
    }

    nav {
      background-color: var(--black);
      padding: 1rem;
      display: flex;
      justify-content: space-between;
      align-items: center;
      color: cream;
      flex-wrap: wrap;
    }

    nav .logo {
      font-size: 1.5rem;
      font-weight: bold;
      color: var(--yellow);
    }

    nav ul {
      list-style: none;
      display: flex;
      gap: 1rem;
      flex-wrap: wrap;
      padding-top: 0.5rem;
    }

    nav ul li a {
      color: white;
      text-decoration: none;
      font-size: 1rem;
      transition: color 0.3s ease;
    }

    nav ul li a:hover {
      color: var(--yellow);
    }

    header {
      background: url('https://cdn2.dropmarkusercontent.com/52043/e81bc77957f16a7e4b6308fed5816d1aab58afb3/preview/JS_20170803_2859.jpg?Expires=1748764986&Signature=ZCflzrJXoh14U4pHALJ12zyAfwr7XsvXdoJ7pTH0bMvePi2nIfzb~Kx2Y0qUTOMzebfZDKmeNkQx9hGCWv27tLh00JwL7uwkusP29bYJzYlWueo6dlIO0dMIpt7CfGeCNHwOrYimaplQQhf-7vAgIrbcayok838xEbcT4mD6p33Y8~j-k3k7-TVCihdH5Fv181-etWh4xT4XMIlB9smD3rFDm~kYUPGw4hGzuTSHujSr-x7c-OxdNqXVQ-oWS6c7pIMf3DK46aawbSHs9sZ8Ug5z2SvILG0j4vnwCgZtmGqq1IRV4Uku2X1CSf3eEqOMo7cCXOzDCws82hzX-wOhsA__&Key-Pair-Id=APKAITQYWVEN757ZA4KQ') center/cover no-repeat;
      height: 90vh;
      color: white;
      display: flex;
      flex-direction: column;
      align-items: center;
      justify-content: center;
      text-align: center;
      text-shadow: 2px 2px 6px rgba(0,0,0,0.6);
      padding: 1rem;
    }

    header h1 {
      font-size: 2.5rem;
    }

    header p {
      font-size: 1.2rem;
      margin-top: 0.5rem;
      max-width: 700px;
    }

    .value-prop {
      padding: 2rem 1rem;
      max-width: 900px;
      margin: auto;
      background-color: white;
      border-radius: 10px;
      box-shadow: 0 0 10px rgba(0, 0, 0, 0.05);
      margin-top: 2rem;
    }

    .value-prop h2 {
      color: var(--navy);
      font-size: 1.8rem;
      margin-bottom: 1rem;
    }

    .cta {
      text-align: center;
      margin: 2rem 1rem;
    }

    .cta button {
      background-color: var(--blue);
      color: var(--black);
      border: none;
      padding: 1rem 2rem;
      font-size: 1.1rem;
      font-weight: bold;
      border-radius: 30px;
      cursor: pointer;
      transition: background-color 0.3s ease;
    }

    .cta button:hover {
      background-color: #e6b800;
    }

    footer {
      background-color: var(--gray);
      color: var(--black);
      text-align: center;
      padding: 1rem;
      font-size: 0.9rem;
      margin-top: 3rem;
    }

    @media (min-width: 768px) {
      nav ul {
        gap: 1.5rem;
      }

      header h1 {
        font-size: 3rem;
      }

      .value-prop h2 {
        font-size: 2rem;
      }

      .cta button {
        font-size: 1.2rem;
        padding: 1.2rem 2.5rem;
      }
    }
  </style>
</head>

<body>
  <nav>
    <div class="logo">
  <img src="HeroImage/Images/charitywater_logo_horizontal_AllWhite.png" alt="Charity: Water Logo" style="height: 40px;">
</div>
<nav>
    <ul>
      <li><a href="#">Home</a></li>
      <li><a href="#about">About</a></li>
      <li><a href="#take-action">Take Action</a></li>
    </ul>
  </nav>

  <header>
    <h1>Change the World, One Drop at a Time</h1>
    <p>You're not just a student—you’re a changemaker. Help bring clean water to communities in need.</p>
  </header>

  <section class="value-prop" id="about">
    <h2>Why Clean Water?</h2>
    <p>
      At Charity: Water, we believe access to clean water is a human right. In a world where smartphones and tech have
      reached the most remote places, millions still live without safe water. With our 100% model, every dollar you give
      directly funds water projects. Join a global movement—right from your campus—and help end the water crisis for good.
    </p>
  </section>

  <div class="cta" id="take-action">
    <button onclick="window.location.href='https://www.charitywater.org/donate'">
      Send Water, Not WiFi
    </button>
  </div>

  <footer>
    &copy; 2025 Charity: Water. All rights reserved.
  </footer>
</body>
</html>
