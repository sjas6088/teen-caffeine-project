<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Caffeine & The Teenage Heart</title>
  <link href="https://fonts.googleapis.com/css2?family=Poppins:wght@400;600&display=swap" rel="stylesheet">
  <style>
    :root {
      --primary: #1f2937;
      --accent: #00bcd4;
      --background: #f8fafa;
      --card: #ffffff;
      --text: #333;
    }

    * {
      box-sizing: border-box;
      margin: 0;
      padding: 0;
    }

    body {
      font-family: 'Poppins', sans-serif;
      background-color: var(--background);
      color: var(--text);
      line-height: 1.6;
    }

    header {
      background-color: var(--primary);
      color: #fff;
      padding: 4rem 1rem;
      text-align: center;
      box-shadow: 0 4px 10px rgba(0, 0, 0, 0.2);
    }

    nav {
      background-color: #2b3748;
      display: flex;
      justify-content: center;
      padding: 1rem 0;
    }

    nav a {
      color: var(--accent);
      text-decoration: none;
      margin: 0 1.5rem;
      font-weight: 600;
      transition: color 0.3s ease;
    }

    nav a:hover {
      color: #ffffff;
    }

    section {
      max-width: 1000px;
      margin: 3rem auto;
      padding: 0 1rem;
    }

    h2 {
      color: var(--primary);
      margin-bottom: 1rem;
      border-bottom: 2px solid var(--accent);
      display: inline-block;
      padding-bottom: 0.2rem;
    }

    ul {
      margin: 1rem 0 2rem 1.5rem;
    }

    .highlight {
      background-color: #e0f7fa;
      padding: 1.5rem;
      border-left: 6px solid var(--accent);
      margin-top: 1rem;
      border-radius: 8px;
    }

    .image {
      text-align: center;
      margin: 2.5rem 0;
    }

    .image img {
      max-width: 95%;
      border-radius: 10px;
      box-shadow: 0 6px 12px rgba(0, 0, 0, 0.1);
    }

    .caption {
      margin-top: 0.5rem;
      font-size: 0.9rem;
      color: #666;
    }

    footer {
      background-color: var(--primary);
      color: white;
      text-align: center;
      padding: 2rem 1rem;
      margin-top: 4rem;
    }

    .card {
      background-color: var(--card);
      border-radius: 10px;
      padding: 1.5rem;
      box-shadow: 0 2px 8px rgba(0, 0, 0, 0.1);
      margin-bottom: 2rem;
    }
  </style>
</head>
<body>

  <header>
    <h1>Caffeine & The Teenage Heart</h1>
    <p>Capstone Project by Jasnoor — Studying the effects of caffeine on teenage cardiovascular health</p>
  </header>

  <nav>
    <a href="#question">Question</a>
    <a href="#method">Method</a>
    <a href="#data">Data</a>
    <a href="#impact">Impact</a>
    <a href="#future">Future</a>
  </nav>

  <section id="question" class="card">
    <h2>Essential Question</h2>
    <p><strong>What effect does caffeine have on heart rate and blood pressure in teenagers, and what does this suggest about adolescent health in a caffeine-saturated society?</strong></p>
  </section>

  <section id="method" class="card">
    <h2>Methodology</h2>
    <p>Fifteen teenage participants aged 15–17 consumed caffeine from common sources (coffee, soda, iced tea, energy drinks). Heart rate and blood pressure were recorded before and 30–60 minutes after intake.</p>
    <div class="highlight">
      <strong>Research Tools:</strong>
      <ul>
        <li>Heart Rate & Blood Pressure Monitor</li>
        <li>Google Sheets for Tracking</li>
        <li>Stopwatch Timer</li>
        <li>Consent Forms & Anonymized Tracking</li>
      </ul>
    </div>
  </section>

  <section id="data" class="card">
    <h2>Data & Analysis</h2>
    <ul>
      <li><strong>Energy Drinks:</strong> Heart rate increase of 20–25 bpm</li>
      <li><strong>Coffee:</strong> Increased heart rate by 15–18 bpm</li>
      <li><strong>Soda & Iced Tea:</strong> Mild rise of 5–8 bpm</li>
      <li><strong>Noted Symptoms:</strong> Anxiety, jitters, focus boosts, tremors</li>
    </ul>

    <div class="image">
      <img src="images/heart-rate-chart.png" alt="Heart Rate Chart">
      <p class="caption">Average Heart Rate Change by Caffeine Type</p>
    </div>

    <div class="image">
      <img src="images/data-table.jpg" alt="Data Table">
      <p class="caption">Raw Participant Data: HR & BP Before/After</p>
    </div>
  </section>

  <section id="impact" class="card">
    <h2>Reflection & Impact</h2>
    <p>This study helped me realize how normalized caffeine use can hide real health impacts. Many participants experienced heart spikes or jitteriness within 30 minutes. As a teen, it's important to reflect on what we consume and how it affects our future health.</p>
  </section>

  <section id="future" class="card">
    <h2>Looking Forward</h2>
    <ul>
      <li>Launch awareness posters around exam week</li>
      <li>Create an app to track safe caffeine use</li>
      <li>Collaborate with school wellness committees</li>
      <li>Publish research insights with a student-led journal</li>
    </ul>
  </section>

  <footer>
    <p>© 2025 Jasnoor | Capstone Project | Teen Health Awareness</p>
  </footer>

</body>
</html>
