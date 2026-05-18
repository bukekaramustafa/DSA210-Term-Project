# DSA210 Term Project

## Project Topic

This project analyzes how daily factors such as sleep, stress, outdoor time, negative events, and weather perception are related to students' mood and productivity.

The dataset contains daily survey-like observations from multiple participants. Each row represents one person's answers for one day.

---

## Files

- `data/processed/data.csv` — dataset used in the analysis
- `notebooks/eda.ipynb` — exploratory data analysis and visualizations
- `requirements.txt` — Python libraries needed to run the notebook

---

## Variables

| Variable | Description |
|---|---|
| `mood` | Daily mood score |
| `productivity` | Perceived productivity score |
| `energy` | Energy level |
| `sleep_hours` | Sleep duration |
| `negative_event` | Whether a negative event happened that day (0/1) |
| `stress` | Stress level |
| `outdoor_time` | Time spent outdoors |
| `weather_feeling` | Perceived weather effect |

---

## Analysis Steps

1. **Load and inspect the dataset** — read CSV, preview with `df.head()`
2. **Summary statistics** — `df.info()` and `df.describe()`
3. **Distribution plots** — histograms for mood, productivity, and energy
4. **Relationship visualizations**
   - Sleep vs Mood (boxplot)
   - Negative Event vs Mood (boxplot)
   - Stress vs Productivity (scatterplot)
   - Weather Feeling vs Mood (scatterplot)
   - Outdoor Time vs Mood (boxplot)
5. **Correlation matrix** — heatmap of all numeric variables

---

## Key Findings

- Mood and productivity are positively correlated.
- Sleep duration has a noticeable effect on both mood and energy levels.
- Negative events are associated with lower mood scores.
- Higher stress levels tend to reduce productivity.
- Weather perception shows a mild relationship with mood.

---

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook notebooks/eda.ipynb
```

---

## Limitations and Future Work

This project has several limitations. The dataset is based on self-reported responses, which may include subjective bias. Observations were collected over a limited time period. Variables such as weather feeling are perception-based rather than objective measurements.

For future work, real weather API data could be integrated. A larger participant group and longer data collection period would improve reliability. More advanced machine learning models could also be explored.

---

## AI Assistance Disclosure

AI tools were used to support code organization, formatting, and editing. The project topic, dataset structure, interpretations, and analysis decisions were reviewed and finalized by the student.
