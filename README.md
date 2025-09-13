<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>Student Wellness Monitor</title>
  <style>
    body {
      font-family: Arial, sans-serif;
      margin: 0;
      background: #f4f8fb;
      color: #333;
    }

    header {
      background: #4a90e2;
      color: #fff;
      padding: 20px;
      text-align: center;
    }

    header h1 {
      margin: 0;
    }

    nav {
      display: flex;
      justify-content: center;
      gap: 15px;
      background: #357abd;
      padding: 10px;
    }

    nav a {
      color: white;
      text-decoration: none;
      font-weight: bold;
    }

    main {
      padding: 20px;
      display: grid;
      grid-template-columns: 1fr 1fr;
      gap: 20px;
    }

    section {
      background: #fff;
      border-radius: 8px;
      padding: 20px;
      box-shadow: 0 4px 8px rgba(0,0,0,0.1);
    }

    section h2 {
      margin-top: 0;
      color: #4a90e2;
    }

    .mood-options button {
      margin: 5px;
      padding: 10px 15px;
      border: none;
      border-radius: 5px;
      cursor: pointer;
      background: #4a90e2;
      color: white;
    }

    .mood-options button:hover {
      background: #357abd;
    }

    .trend-graph {
      height: 200px;
      border: 2px dashed #bbb;
      display: flex;
      align-items: center;
      justify-content: center;
      color: #999;
    }

    footer {
      text-align: center;
      padding: 15px;
      background: #357abd;
      color: white;
      margin-top: 20px;
    }

    @media (max-width: 800px) {
      main {
        grid-template-columns: 1fr;
      }
    }
  </style>
</head>
<body>
  <header>
    <h1>Student Wellness Monitor</h1>
    <p>Track your mental health and well-being</p>
  </header>

  <nav>
    <a href="#">Mood Check-In</a>
    <a href="#">Recommendations</a>
    <a href="#">Trends</a>
    <a href="#">Reports</a>
  </nav>

  <main>
    <section>
      <h2>Daily Mood Check-In</h2>
      <div class="mood-options">
        <button>😊 Happy</button>
        <button>😐 Neutral</button>
        <button>😔 Sad</button>
        <button>😤 Stressed</button>
        <button>😴 Tired</button>
      </div>
    </section>

    <section>
      <h2>Personalized Wellness Recommendations</h2>
      <ul>
        <li>Take a short walk outside for fresh air.</li>
        <li>Try 5 minutes of mindful breathing today.</li>
        <li>Reach out to a friend or family member.</li>
      </ul>
    </section>

    <section>
      <h2>Sentiment Insights</h2>
      <p>Your recent mood entries suggest a mix of positivity and stress. Consider practicing relaxation techniques to balance emotions.</p>
    </section>

    <section>
      <h2>Trend Visualization</h2>
      <div class="trend-graph">
        Graph Placeholder (Integrate with Chart.js / D3.js)
      </div>
    </section>
  </main>

  <footer>
    <p>© 2025 Student Wellness Monitor. All rights reserved.</p>
  </footer>
</body>
</html>
# student-willness
