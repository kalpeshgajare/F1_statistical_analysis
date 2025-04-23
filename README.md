#  **F1 Statistical Analysis** 🏎️

This project dives deep into the world of Formula 1 racing using data analysis and visualization techniques. It aims to uncover trends, performance metrics, and interesting insights across drivers, teams, circuits, and seasons using Python and popular data science libraries.

## Project Overview

The notebook `F1_statistical_analysis.ipynb` performs exploratory data analysis on F1 datasets to:

- Analyze driver and constructor performance over time
- Visualize podium finishes, race wins, and championship stats
- Compare team consistency and driver contributions
- Explore circuit-specific statistics


## 🧰 Tech Stack

- **Python 3.8+**
- **Pandas** – for data manipulation
- **NumPy** – for numerical computation
- **Matplotlib & Seaborn** – for plotting and visualizations
- **Jupyter Notebook** – for interactive analysis
- **Scipy** - for statistics
- **Sklearn** - for model selection

## 📦 Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/kalpeshgajare/F1_statistical_analysis.git
   cd F1_statistical_analysis
   ```
2. Datasets
   ```python
   import kagglehub
   
   # Download latest version
   path = kagglehub.dataset_download("rohanrao/formula-1-world-championship-1950-2020")
   print("Path to dataset files:", path)
   ```
   This analysis is based on the Drivers and Driver Standings datasets, providing insights into individual performance, rankings, and historical trends across Formula 1 seasons.

## 📈 Sample Visualizations
- Bar charts of top performing drivers and teams
- Heatmaps of race wins by country or year
- Line graphs showing seasonal progress
  
<img width="1331" alt="Screenshot 2025-04-23 at 07 02 54" src="https://github.com/user-attachments/assets/7b25ecac-78e7-4d7a-b47d-67fcd010eeb6" />
<table width="100%">
  <tr>
    <td align="left" width="50%">
      <img src="https://github.com/user-attachments/assets/e98532af-303a-4054-a99f-785f6e491bb9" width="95%">
    </td>
    <td align="right" width="50%">
      <img src="https://github.com/user-attachments/assets/edc340c8-988c-4b6e-b7ac-dc621899c393" width="95%">
    </td>
  </tr>
</table>
<table width="100%">
  <tr>
    <td align="left" width="50%">
     <img src="https://github.com/user-attachments/assets/7b389788-6892-41c5-8d8b-8435830d76f1" width="95%"/>
    </td>
    <td align="right" width="50%">
     <img src="https://github.com/user-attachments/assets/85643a6c-11b3-4df3-a2a8-7ba1eb27bd1d" width="95%"/>
  </tr>
</table>

## 📌 Key Insights
These are examples of the kinds of conclusions or visualizations that your analysis can surface:

- Which drivers consistently outperform their teammates:  
By comparing driver standings or points within the same team over multiple seasons, you can identify who the stronger performers are—especially in equal machinery.

- How constructors have evolved in dominance:  
This shows the shift in team performance across years. For example, Red Bull dominating in the 2020s after Mercedes in the 2010s, Ferrari in the 2000s, etc.

- Which circuits are driver favorites:  
Some drivers perform exceptionally well at specific tracks. Analyzing wins or podium finishes per circuit can highlight these “specialist” circuits.

## 🚀 Future Enhancements
Ideas to take the project beyond basic stats:
- Add interactive visualizations with Plotly or Dash:  
Instead of static graphs, interactive charts let users hover, zoom, and explore data in real time. Great for dashboards and presentations.

- Use machine learning to predict race outcomes:  
Train models using past data to predict future race results, such as who’s likely to win a race or finish in the top 5.

- Automate data updates with a web scraper or API:  
Instead of manually downloading CSVs, use the Ergast API or a scraper to keep your dataset fresh with new races, standings, and stats.

## 📄 License

This project is licensed under the **MIT License**.  
You are free to use, modify, and distribute this software for any purpose, with proper attribution.  
See the [LICENSE](LICENSE) file for full details.
