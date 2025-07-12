# 🏏 IPL Data Analysis (2008–2023)

This project performs exploratory data analysis (EDA) on IPL data using Python libraries like Pandas, Seaborn, and Matplotlib. The data includes match details, player performances, and team-wise statistics from the IPL seasons between 2008 and 2023.

## 📁 Dataset Used

- `matches.csv`: Match-level data
- `deliveries.csv`: Ball-by-ball delivery data
- `most_runs_average_strikerate.csv`: Batting performance metrics
- `teamwise_home_and_away.csv`: Team performance at home and away venues
- `teams.csv`: Team information
- `Players.xlsx`: Player metadata and info

## 📊 Key Analysis

- Matches played per season
- Top winning teams
- Toss vs match winner trends
- Top 10 run scorers
- Top 10 wicket takers
- Team-wise home vs away win % comparison

## 📌 Tools & Libraries

- Python 🐍
- Pandas 📊
- Seaborn 🎨
- Matplotlib 📈
- Jupyter Notebook 📓

## 📎 How to Run

1. Clone or download the repository.
2. Open the notebook `ipl_analysis.ipynb` in Jupyter.
3. Make sure all dataset files are in the same directory.
4. Run all cells to explore charts and insights.

## 📷 Sample Visualizations

- Matches per season bar chart
  
- Top run scorers horizontal bar chart  
- Wicket takers and their stats  
- Home vs Away win % grouped bar chart  

## ✅ Outcome

The project provides meaningful insights into team dominance, player consistency, and venue-based performance. It helps understand trends across IPL seasons.

---

🔗 **Feel free to fork, star, or use the analysis for your own cricket data project!**

<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>IPL Team-wise Home vs Away Win %</title>

  <!-- Google Fonts -->
  <link href="https://fonts.googleapis.com/css2?family=Roboto:wght@400;700&family=Bebas+Neue&display=swap" rel="stylesheet">

  <style>
    body {
      font-family: 'Roboto', sans-serif;
      background-color: #f9fafb;
      margin: 0;
      padding: 20px;
      color: #333;
    }

    h1 {
      font-family: 'Bebas Neue', cursive;
      font-size: 40px;
      text-align: center;
      color: #2c3e50;
      margin-bottom: 5px;
    }

    h2 {
      font-size: 20px;
      text-align: center;
      font-weight: normal;
      margin-top: 0;
      color: #7f8c8d;
    }

    .chart {
      max-width: 900px;
      margin: 30px auto;
      border: 1px solid #ddd;
      background-color: #fff;
      padding: 20px;
      box-shadow: 0 5px 20px rgba(0,0,0,0.1);
      border-radius: 8px;
    }

    iframe {
      border: none;
      width: 100%;
      height: 600px;
    }

    footer {
      text-align: center;
      margin-top: 50px;
      color: #aaa;
      font-size: 14px;
    }
  </style>
</head>
<body>

  <h1>🏏 IPL Team-wise Performance</h1>
  <h2>Home vs Away Win Percentage Comparison</h2>

  <div class="chart">
    <!-- Placeholder: You can replace this with an embedded chart (e.g., from plotly or image) -->
    <iframe src="chart_image_or_interactive.html"></iframe>
  </div>

  <footer>
    © 2025 IPL Data Analysis by Gauri
  </footer>

</body>
</html>
