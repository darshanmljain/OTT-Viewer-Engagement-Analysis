# 📺 OTT Viewer Engagement & Retention Risk Analysis

An end-to-end data analytics project exploring **viewer engagement, episode drop-off patterns, content performance, and retention risk** on an OTT streaming platform. This project uses Python-based exploratory data analysis (EDA) to investigate viewing behavior, identify potential audience disengagement patterns, and generate actionable insights to support content strategy and viewer retention.

---

## 📌 Project Objectives

- **Analyze Viewer Engagement:** Explore viewing behavior and engagement patterns across OTT content.
- **Identify Episode Drop-Off:** Investigate where viewers are more likely to disengage while progressing through episodes.
- **Evaluate Genre Performance:** Compare genres based on viewing activity and audience engagement.
- **Assess Retention Risk:** Analyze high-risk viewer segments and content associated with potential drop-off.
- **Explore Content-Level Patterns:** Examine show-level performance, pacing, introductions, and storytelling-related engagement indicators.
- **Generate Business Insights:** Translate analytical findings into recommendations for content discovery, engagement improvement, and retention strategies.

---

## 📊 Key Areas of Analysis

- **Viewer Engagement:** Viewing patterns and engagement-related metrics.
- **Episode Drop-Off Analysis:** Episode-level patterns that may indicate declining viewer interest.
- **Genre Engagement:** Comparison of engagement and viewing behavior across genres.
- **Retention Risk Analysis:** Exploration of viewers or content segments associated with higher retention risk.
- **Show Performance:** Comparison of shows using engagement and risk-related indicators.
- **Content Structure Analysis:** Examination of introductions, hooks, pacing, and cognitive or storytelling-related summaries.
- **Correlation Analysis:** Investigation of relationships among available numerical variables.

---

## 🛠️ Tech Stack & Tools

- **Environment:** Google Colab / Jupyter Notebook
- **Programming Language:** Python
- **Data Manipulation:** Pandas, NumPy
- **Data Visualization:** Matplotlib, Seaborn
- **Analysis:** Exploratory Data Analysis (EDA), aggregation, correlation analysis, and comparative analysis
- **Dataset:** `ott_viewer_dropoff_retention_us_v1.0.csv`

---

## 💡 Business Recommendations

The analysis can help inform the following business strategies, subject to validation against the notebook's actual findings:

1. **Improve Episode Continuity:** Investigate episodes with higher drop-off patterns to identify opportunities to improve pacing, storytelling, and episode transitions.
2. **Optimize Genre-Based Recommendations:** Use genre-level engagement patterns to inform content discovery and personalized recommendations.
3. **Prioritize At-Risk Segments:** Investigate high-risk viewer or content segments and evaluate targeted engagement campaigns.
4. **Strengthen Opening Episodes:** Examine introductions and early-episode engagement to identify opportunities to improve the first-viewing experience.
5. **Evaluate Content Performance Holistically:** Combine show-level engagement, episode drop-off, and retention-risk indicators rather than relying on a single metric.

---

## 📈 Visualizations & Analysis Outputs

The repository includes charts generated during the analysis, covering areas such as:

- Correlation heatmap
- Episode drop-off patterns
- Genre-level engagement and viewing behavior
- High-risk shows and retention-risk summaries
- Show-level performance comparisons
- Introduction, hook, pacing, and cognitive summaries
- Review and plot-related analysis outputs

See the `charts/` directory for the generated visualizations and the `tables/` directory for supporting analysis outputs.

---

## 📁 Repository Structure

```text
OTT-Viewer-Engagement-Analysis/
│
├── Hotstar_Viewer_Engagement_EDA_Complete.ipynb
├── project_summary.txt
├── data/
│   ├── df.csv
│   └── df_raw.csv
├── charts/
│   ├── cognitive_summary.png
│   ├── correlation_heatmap.png
│   ├── episode_dropoff.png
│   ├── genre_dropoff.png
│   ├── genre_engagement.png
│   ├── genre_watch.png
│   ├── high_risk_shows.png
│   ├── hook_summary.png
│   ├── intro_summary.png
│   ├── pacing_summary.png
│   ├── plot_data.png
│   ├── review.png
│   ├── risk_summary.png
│   ├── show_summary.png
│   └── table.png
├── tables/
│   └── Analysis output CSV files
└── README.md
```

---

## 🚀 How to Run the Project

1. Clone or download this repository.
2. Open `Hotstar_Viewer_Engagement_EDA_Complete.ipynb` in Google Colab or Jupyter Notebook.
3. Ensure the required dataset files are available in the expected locations.
4. Run the notebook cells in sequence to reproduce the analysis and visualizations.

### Install Dependencies

```bash
pip install pandas numpy matplotlib seaborn
```

---

## 🎯 Project Outcome

This project demonstrates an end-to-end exploratory data analysis workflow for OTT viewer engagement and retention-risk investigation. It combines data preparation, visual exploration, comparative analysis, and business-oriented interpretation to examine how viewing behavior and content characteristics may relate to audience engagement.

**Note:** The dataset and analysis outputs should be interpreted according to their underlying data-generation process and metric definitions. Associations and risk indicators do not, by themselves, establish causation or guarantee future viewer churn.

---

## 👨‍💻 Author

**Darshan Jain**

GitHub: [@darshanmljain](https://github.com/darshanmljain)
