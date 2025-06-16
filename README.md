from pathlib import Path

# Recreate the enhanced, comprehensive HTML website content
enhanced_html = """
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1.0"/>
  <title>Caffeine & The Teenage Heart - Capstone</title>
  <style>
    body {
      font-family: 'Segoe UI', sans-serif;
      margin: 0;
      padding: 0;
      background: #f7f9fb;
      color: #1a1a1a;
      line-height: 1.6;
    }
    header {
      background: #0f172a;
      color: white;
      padding: 3rem 1rem;
      text-align: center;
    }
    nav {
      background: #4dd0e1;
      padding: 1rem;
      text-align: center;
    }
    nav a {
      color: #0f172a;
      margin: 0 12px;
      font-weight: bold;
      text-decoration: none;
    }
    nav a:hover {
      text-decoration: underline;
    }
    section {
      max-width: 1000px;
      margin: auto;
      padding: 2rem;
    }
    h2 {
      color: #0f172a;
      border-bottom: 2px solid #4dd0e1;
      padding-bottom: 0.3rem;
      margin-top: 2rem;
    }
    .highlight {
      background: #e0f7fa;
      border-left: 5px solid #4dd0e1;
      padding: 1rem;
      margin: 1.5rem 0;
      font-style: italic;
    }
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1.5rem;
    }
    th, td {
      padding: 0.75rem;
      border: 1px solid #ccc;
      text-align: center;
      font-size: 0.95rem;
    }
    th {
      background-color: #f1faff;
    }
    footer {
      background: #0f172a;
      color: white;
      text-align: center;
      padding: 2rem;
      margin-top: 4rem;
    }
  </style>
</head>
<body>
  <header>
    <h1>Caffeine & The Teenage Heart</h1>
    <p>A Capstone Project by Jasnoor</p>
  </header>

  <nav>
    <a href="#overview">Overview</a>
    <a href="#data">Data</a>
    <a href="#analysis">Analysis</a>
    <a href="#sources">Sources</a>
    <a href="#skills">Skills</a>
    <a href="#volunteer">Volunteering</a>
    <a href="#mentor">Mentor</a>
    <a href="#impact">Impact</a>
  </nav>

  <section id="overview">
    <h2>Project Overview</h2>
    <p><strong>Inquiry Question:</strong> How does caffeine consumption affect teenage heart rate and blood pressure?</p>
    <p>This project came from my curiosity and career goal to become a cardiologist. I noticed how common caffeine is in teen life — coffee before school, energy drinks after practice — and I wanted to explore its actual effect on a young body. Through real participant tracking and professional guidance, this project came to life as both a scientific study and a community campaign.</p>
  </section>

  <section id="data">
    <h2>Observational Data</h2>
    <table>
      <thead>
        <tr><th>Name</th><th>Age</th><th>Gender</th><th>Source</th><th>mg</th><th>Time</th><th>HR Before</th><th>BP Before</th><th>HR After</th><th>BP After</th><th>Notes</th></tr>
      </thead>
      <tbody>
        <tr><td>Maya</td><td>16</td><td>F</td><td>Coffee</td><td>95</td><td>8:00</td><td>72</td><td>110/70</td><td>88</td><td>126/78</td><td>Jittery</td></tr>
        <tr><td>Ansh</td><td>17</td><td>M</td><td>Energy Drink</td><td>160</td><td>5:15</td><td>70</td><td>111/70</td><td>95</td><td>135/82</td><td>Anxiety</td></tr>
        <tr><td>Anaya</td><td>16</td><td>F</td><td>Iced Tea</td><td>30</td><td>10:15</td><td>76</td><td>108/68</td><td>82</td><td>114/72</td><td>Focus</td></tr>
        <tr><td>Karen</td><td>17</td><td>M</td><td>Energy Drink</td><td>80</td><td>9:30</td><td>68</td><td>112/74</td><td>90</td><td>130/82</td><td>Alert</td></tr>
        <tr><td>Ajit</td><td>17</td><td>M</td><td>Coffee</td><td>95</td><td>7:45</td><td>66</td><td>109/69</td><td>84</td><td>123/75</td><td>Energy</td></tr>
      </tbody>
    </table>
  </section>

  <section id="analysis">
    <h2>Findings</h2>
    <p>💡 Higher caffeine doses led to increased heart rate and systolic blood pressure. Energy drinks caused the sharpest spikes (up to +25 bpm and +20 systolic BP), while iced tea had minor changes. Teenagers with lower baseline tolerance experienced shakiness and anxiety.</p>
    <div class="highlight">"This showed me how easily something we all drink could have real effects on our heart. And we almost never talk about it." — Participant Reflection</div>
  </section>

  <section id="sources">
    <h2>Research Sources</h2>
    <ul>
      <li>🧬 MDPI Journal – "Acute Cardiovascular Effects of Energy Drinks in Adolescents"</li>
      <li>📺 CBS News – Teen ER visits tied to caffeine overuse</li>
      <li>📚 Harvard Public Health – Caffeine and cardiovascular science</li>
      <li>📖 Journal of Psychosomatic Research – Long-term BP impact</li>
    </ul>
  </section>

  <section id="skills">
    <h2>Core Competencies</h2>
    <ul>
      <li>🧠 <strong>Critical Thinking:</strong> Designed and interpreted physiological data</li>
      <li>💬 <strong>Communication:</strong> Created website, charts, flyers, and survey</li>
      <li>💻 <strong>Digital Literacy:</strong> Analyzed Google Sheets data and built charts</li>
      <li>🤝 <strong>Social Responsibility:</strong> Centered safety, ethics, and health awareness</li>
    </ul>
  </section>

  <section id="volunteer">
    <h2>Volunteering & Ethics</h2>
    <p>I used consent forms, briefed all participants, and kept the environment safe. I will share this with my school community, health class, and possibly turn it into a mini-workshop.</p>
  </section>

  <section id="mentor">
    <h2>Mentor Reflection</h2>
    <p><strong>Mentor:</strong> Ms. Mahnaz Sabouri — a science educator who supported my organization, analysis, and motivation. She reminded me that science needs compassion, clarity, and a voice behind the numbers.</p>
  </section>

  <section id="impact">
    <h2>Final Thoughts</h2>
    <p>This project isn’t just about caffeine — it’s about realizing that even everyday habits affect our health. As a future cardiologist, I want to lead with science and empathy. I hope this capstone opens conversations about heart care, mental alertness, and informed choices for teens everywhere.</p>
  </section>

  <footer>
    <p>&copy; 2025 Jasnoor Kaur | Capstone Project on Teen Heart Health</p>
  </footer>
</body>
</html>
"""

