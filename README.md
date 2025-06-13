
html_content = """
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
    table {
      width: 100%;
      border-collapse: collapse;
      margin-top: 1.5rem;
    }
    table th, table td {
      padding: 0.75rem;
      border: 1px solid #ccc;
      text-align: center;
    }
    table thead {
      background-color: #1e1e2f;
      color: white;
    }
    table tbody {
      background-color: #f4f4f4;
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
    <a href="#table">Table</a>
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
      <img src="https://uploadthing.com/f/7f27b84f-b27e-4f17-b008-d8bc7eabfbe7-A_capstone_project_webpage_titled_%22Caffeine_%26_The_.png" alt="Caffeine Study Graph" />
    </div>
  </section>

  <section id="table">
    <h2>Participant Data Table</h2>
    <div style="overflow-x:auto">
      <table>
        <thead>
          <tr>
            <th>Name</th><th>Age</th><th>Gender</th><th>Caffeine Source</th><th>Caffeine (mg)</th><th>Time Taken</th><th>HR Before</th><th>BP Before</th><th>HR After</th><th>BP After</th><th>Notes</th>
          </tr>
        </thead>
        <tbody>
          <tr><td>Maya</td><td>16</td><td>Female</td><td>Coffee</td><td>95</td><td>8:00 AM</td><td>72</td><td>110/70</td><td>88</td><td>126/78</td><td>Felt jittery in class</td></tr>
          <tr><td>Karen</td><td>17</td><td>Male</td><td>Energy Drink</td><td>80</td><td>9:30 AM</td><td>68</td><td>112/74</td><td>90</td><td>130/82</td><td>Reported alertness, mild headache</td></tr>
          <tr><td>Anaya</td><td>16</td><td>Female</td><td>Iced Tea</td><td>30</td><td>10:15 AM</td><td>76</td><td>108/68</td><td>82</td><td>114/72</td><td>Slight increase in focus</td></tr>
          <tr><td>Arjun</td><td>15</td><td>Male</td><td>Soda</td><td>40</td><td>3:45 PM</td><td>70</td><td>112/74</td><td>78</td><td>120/76</td><td>No noticeable change</td></tr>
          <tr><td>Sehej</td><td>17</td><td>Female</td><td>Energy Drink</td><td>160</td><td>6:00 PM</td><td>74</td><td>114/71</td><td>98</td><td>138/84</td><td>Felt shaky, hands trembled</td></tr>
          <tr><td>Amraj</td><td>16</td><td>Male</td><td>Coffee</td><td>95</td><td>7:30 AM</td><td>67</td><td>108/70</td><td>85</td><td>124/76</td><td>Jittery but energized</td></tr>
          <tr><td>Riya</td><td>15</td><td>Female</td><td>Soda</td><td>40</td><td>1:00 PM</td><td>73</td><td>106/72</td><td>80</td><td>116/75</td><td>Slightly dizzy after 20 minutes</td></tr>
          <tr><td>Guntaj</td><td>16</td><td>Male</td><td>Energy Drink</td><td>80</td><td>10:30 AM</td><td>71</td><td>110/73</td><td>89</td><td>127/80</td><td>More energy, no side effects</td></tr>
          <tr><td>Ravneet</td><td>15</td><td>Female</td><td>Iced Tea</td><td>30</td><td>2:00 PM</td><td>75</td><td>108/68</td><td>81</td><td>115/72</td><td>Mild boost in alertness</td></tr>
          <tr><td>Ansh</td><td>17</td><td>Male</td><td>Energy Drink (Large)</td><td>160</td><td>5:15 PM</td><td>70</td><td>111/70</td><td>95</td><td>135/82</td><td>Anxiety spike 30 mins later</td></tr>
          <tr><td>Raman</td><td>16</td><td>Female</td><td>Coffee</td><td>95</td><td>8:45 AM</td><td>69</td><td>107/69</td><td>87</td><td>125/76</td><td>Felt awake and productive</td></tr>
          <tr><td>Pargat</td><td>15</td><td>Male</td><td>Soda</td><td>40</td><td>12:30 PM</td><td>68</td><td>110/72</td><td>74</td><td>115/74</td><td>No major changes</td></tr>
          <tr><td>Jasmeet</td><td>16</td><td>Female</td><td>Iced Tea</td><td>30</td><td>3:00 PM</td><td>71</td><td>106/70</td><td>76</td><td>111/72</td><td>Light focus improvement</td></tr>
          <tr><td>Ajit</td><td>17</td><td>Male</td><td>Coffee</td><td>95</td><td>7:45 AM</td><td>66</td><td>109/69</td><td>84</td><td>123/75</td><td>Boosted morning energy</td></tr>
          <tr><td>Ishmeet</td><td>15</td><td>Female</td><td>Energy Drink</td><td>80</td><td>9:00 AM</td><td>73</td><td>113/72</td><td>89</td><td>128/79</td><td>Hands trembled slightly</td></tr>
        </tbody>
      </table>
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
"""

# Save HTML file
output_path = Path("/mnt/data/Teen_Caffeine_Project_Full.html")
output_path.write_text(html_content)

output_path.name
