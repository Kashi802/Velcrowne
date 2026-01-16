<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Velcrowne</title>
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <style>
    body {
      margin: 0;
      font-family: 'Segoe UI', sans-serif;
      background: #0b0f1a;
      color: #fff;
    }
    header {
      background: linear-gradient(135deg, #6a00ff, #1e90ff);
      padding: 70px 20px;
      text-align: center;
    }
    header h1 {
      font-size: 42px;
      letter-spacing: 2px;
    }
    header p {
      opacity: 0.9;
    }
    nav {
      display: flex;
      justify-content: center;
      gap: 25px;
      background: #070a12;
      padding: 15px;
    }
    nav a {
      color: #aaa;
      text-decoration: none;
      font-weight: 600;
    }
    nav a:hover {
      color: #fff;
    }
    section {
      max-width: 1000px;
      margin: auto;
      padding: 40px 20px;
    }
    .card {
      background: #11162a;
      border-radius: 14px;
      padding: 25px;
      margin-bottom: 25px;
    }
    .members {
      display: grid;
      grid-template-columns: repeat(auto-fit, minmax(200px, 1fr));
      gap: 20px;
    }
    .member {
      background: #0c1020;
      padding: 15px;
      border-radius: 12px;
      text-align: center;
    }
    footer {
      text-align: center;
      padding: 20px;
      font-size: 14px;
      opacity: 0.6;
      background: #070a12;
    }
  </style>
</head>
<body>

<header>
  <h1>CLAN NAME</h1>
  <p>STANDOFF 2 • ESPORT • PRO TEAM</p>
</header>

<nav>
  <a href="#about">About</a>
  <a href="#members">Members</a>
  <a href="#rules">Rules</a>
  <a href="#join">Join</a>
</nav>

<section id="about">
  <div class="card">
    <h2>🔥 About Clan</h2>
    <p>Манай clan нь Standoff 2 тоглоомын competitive & esport чиглэлтэй. Бид хамтдаа ялалтад хүрнэ.</p>
  </div>
</section>

<section id="members">
  <div class="card">
    <h2>👥 Members</h2>
    <div class="members">
      <div class="member">
        <h3>Leader</h3>
        <p>ID: 000000</p>
      </div>
      <div class="member">
        <h3>Sniper</h3>
        <p>ID: 000000</p>
      </div>
      <div class="member">
        <h3>Rifler</h3>
        <p>ID: 000000</p>
      </div>
    </div>
  </div>
</section>

<section id="rules">
  <div class="card">
    <h2>📜 Clan Rules</h2>
    <ul>
      <li>Respect all members</li>
      <li>No cheating</li>
      <li>Active participation</li>
      <li>Follow leader decisions</li>
    </ul>
  </div>
</section>

<section id="join">
  <div class="card">
    <h2>🚀 Join Clan</h2>
    <p>Join хийх бол:</p>
    <p>Discord: yourdiscord#0000</p>
    <p>In-game ID: 12345678</p>
  </div>
</section>

<footer>
  © 2026 STANDOFF 2 CLAN • All Rights Reserved
</footer>

</body>
</html>
