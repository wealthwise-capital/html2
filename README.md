<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <meta name="description" content="WealthWise Capital - Transparent capital management through strategic forex and commodities trading.">
  <meta name="keywords" content="WealthWise, Forex, Capital Management, Trading, Investment">
  <meta name="author" content="WealthWise Capital">
  <title>WealthWise Capital</title>
  <style>
    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: #0e1e3a;
      color: white;
      margin: 0;
      padding: 0;
    }
    header {
      background-color: #00e58f;
      color: #0e1e3a;
      padding: 20px;
      text-align: center;
      display: flex;
      align-items: center;
      justify-content: space-between;
      flex-wrap: wrap;
    }
    header img {
      height: 60px;
    }
    nav {
      display: flex;
      gap: 20px;
    }
    nav a {
      color: #0e1e3a;
      text-decoration: none;
      font-weight: bold;
    }
    section {
      padding: 40px;
    }
    h1, h2 {
      color: #00e58f;
    }
    .section-box {
      margin-bottom: 30px;
    }
    ul {
      list-style-type: none;
      padding-left: 0;
    }
    ul li::before {
      content: "\2022";
      color: #00e58f;
      display: inline-block;
      width: 1em;
      margin-left: -1em;
    }
    footer {
      background-color: #021023;
      padding: 20px;
      text-align: center;
      font-size: 0.9em;
      color: #aaa;
    }
    a {
      color: #00e58f;
    }
    form {
      background-color: #021023;
      padding: 20px;
      border-radius: 10px;
      max-width: 400px;
    }
    input, textarea {
      width: 100%;
      padding: 10px;
      margin-bottom: 10px;
      border-radius: 5px;
      border: none;
    }
    button {
      background-color: #00e58f;
      border: none;
      color: #0e1e3a;
      padding: 10px 20px;
      border-radius: 5px;
      font-weight: bold;
      cursor: pointer;
    }
    @media (max-width: 768px) {
      header {
        flex-direction: column;
        text-align: center;
      }
    }
  </style>
</head>
<body>
  <header>
    <img src="logo.png" alt="WealthWise Capital Logo" />
    <div>
      <h1>WealthWise Capital</h1>
      <p>Strategic, transparent capital growth management</p>
    </div>
    <nav>
      <a href="#about">About</a>
      <a href="#profit">Profit</a>
      <a href="#requirements">Requirements</a>
      <a href="#safety">Safety</a>
      <a href="#contact">Contact</a>
    </nav>
  </header>

  <section id="about">
    <div class="section-box">
      <h2>About Us</h2>
      <p>We are dedicated and disciplined traders focused on capital growth through strategic, risk-managed trading in the forex and commodities markets. Our transparent, results-driven model is built on trust, performance, and client success.</p>
    </div>
  </section>

  <section id="profit">
    <div class="section-box">
      <h2>Profit Sharing</h2>
      <ul>
        <li>No upfront fee</li>
        <li>You keep 70% of net profits</li>
        <li>I earn 30% — only when you profit</li>
      </ul>
    </div>
  </section>

  <section id="requirements">
    <div class="section-box">
      <h2>Requirements</h2>
      <ul>
        <li>Minimum Capital: $100</li>
        <li>No lock-in period</li>
        <li>Monthly reporting</li>
        <li>Agreement signed before trading begins</li>
      </ul>
    </div>
  </section>

  <section id="safety">
    <div class="section-box">
      <h2>Safety & Transparency</h2>
      <ul>
        <li>Your funds remain in your own account</li>
        <li>I trade only via broker platforms</li>
        <li>You can pause trading or withdraw at any time</li>
      </ul>
    </div>
  </section>

  <section id="contact">
    <div class="section-box">
      <h2>Let’s Talk</h2>
      <p>Whether you're looking to grow your savings or diversify your investments, I’d be happy to show you how I can help.</p>
      <form action="mailto:contact@wealthwisecapital.com" method="post" enctype="text/plain">
        <input type="text" name="name" placeholder="Your Name" required />
        <input type="email" name="email" placeholder="Your Email" required />
        <textarea name="message" rows="5" placeholder="Your Message" required></textarea>
        <button type="submit">Send Message</button>
      </form>
    </div>
  </section>

  <footer>
    &copy; 2025 WealthWise Capital. All rights reserved.
  </footer>
</body>
</html>
