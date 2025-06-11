<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0" />
  <title>Caffeine & The Teenage Heart</title>
  <style>
    :root {
      --primary-color: #1e1e2f;
      --accent-color: #4dd0e1;
      --background-color: #f9f9f9;
      --text-color: #333;
      --section-padding: 2.5rem;
    }

    body {
      font-family: 'Segoe UI', Tahoma, Geneva, Verdana, sans-serif;
      background-color: var(--background-color);
      color: var(--text-color);
      margin: 0;
      padding: 0;
      line-height: 1.6;
    }

    header {
      background-color: var(--primary-color);
      color: white;
      padding: 3rem 1rem;
      text-align: center;
      box-shadow: 0 4px 6px rgba(0,0,0,0.1);
    }

    nav {
      background-color: #2e2e40;
      text-align: center;
      padding: 1rem 0;
      box-shadow: 0 2px 4px rgba(0,0,0,0.1);
    }

    nav a {
      color: var(--accent-color);
      margin: 0 20px;
      text-decoration: none;
      font-weight: bold;
      transition: color 0.3s;
    }

    nav a:hover {
      color: #fff;
    }

    section {
      max-width: 1000px;
      margin: auto;
      padding: var(--section-padding);
    }

    h1, h2, h3 {
      color: var(--primary-color);
    }

    .highlight {
      background: #e0f7fa;
      border-left: 6px solid var(--accent-color);
      padding: 1rem;
      margin: 2rem 0;
      border-radius: 6px;
    }

    .image {
      margin: 2rem 0;
      text-align: center;
    }

    .image img {
      max-width: 100%;
      height: auto;
      border-radius: 8px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    footer {
      background-color: var(--primary-color);
      color: white;
      text-align: center;
      padding: 1.5rem;
      margin-top: 4rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Caffeine & The Teenage Heart</h1>
    <p>Capstone by Jasnoor | A deep dive into how caffeine affects teen cardiovascular health</p>
  </header>

  <nav>
    <a href="#question">Question</a>
    <a href="#method">Method</a>
    <a href="#data">Data</a>
    <a href="#impact">Impact</a>
    <a href="#future">Future</a>
  </nav>

  <section id="question">
    <h2>Essential Question</h2>
    <p><strong>What effect does caffeine have on heart rate and blood pressure in teenagers, and what does this suggest about adolescent health in a caffeine-saturated society?</strong></p>
  </section>

  <section id="method">
    <h2>Methodology</h2>
    <p>Fifteen teenage participants, aged 15–17, consumed one of four common caffeine sources after recording baseline heart rate and blood pressure. Data was collected 30–60 minutes after intake to capture immediate effects.</p>
    <div class="highlight">
      <strong>Research Tools Used:</strong>
      <ul>
        <li>Digital Heart Rate & Blood Pressure Monitors</li>
        <li>Consent and Participant Tracking Sheets</li>
        <li>Google Sheets Data Log</li>
        <li>Timer for Accurate Monitoring</li>
      </ul>
    </div>
  </section>

  <section id="data">
    <h2>Data Analysis</h2>
    <p>Here are the average effects of caffeine across the sample group:</p>
    <ul>
      <li><strong>Energy Drinks:</strong> Increased heart rate by 20–25 bpm, and systolic blood pressure by up to 20 points</li>
      <li><strong>Coffee:</strong> Raised heart rate by 15–18 bpm</li>
      <li><strong>Soda/Iced Tea:</strong> Moderate heart rate increases of 5–8 bpm</li>
      <li><strong>Reported Effects:</strong> Anxiety, energy spikes, jittery hands, improved focus</li>
    </ul>

    <div class="image">
      <img src="/mnt/data/A_flat-style_digital_chart_titled_\"Average_Heart_R.png" alt="Chart showing average heart rate changes by caffeine source">
    </div>

    <div class="image">
      <img src="/mnt/data/A_flat-style_digital_chart_titled_\"Scatter_plot_Heart_vs_Caffeine.png" alt="Scatter plot of heart rate vs caffeine intake">
    </div>
  </section>

  <section id="impact">
    <h2>Reflection & Impact</h2>
    <p>Conducting this study helped me understand how teen health can be influenced by everyday habits. Caffeine, though normalized, has real, measurable effects on the heart — especially for younger individuals.</p>
    <p>I now want to lead campaigns at school to raise awareness and promote healthier caffeine habits, especially around exam season or sports events when usage spikes.</p>
  </section>

  <section id="future">
    <h2>Looking Forward</h2>
    <ul>
      <li>Increase sample size by collaborating with more schools</li>
      <li>Create an interactive web/app tool for tracking safe caffeine limits</li>
      <li>Design classroom posters with key takeaways</li>
      <li>Build a long-term awareness initiative through student health clubs</li>
    </ul>
  </section>

  <footer>
    <p>© 2025 Jasnoor's Capstone | Teen Wellness & Scientific Awareness</p>
  </footer>
</body>
</html>
