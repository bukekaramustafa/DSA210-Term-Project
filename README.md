# DSA210 Term Project

## Project Topic

This project analyzes how daily factors such as sleep, stress, outdoor time, negative events, and weather perception are related to students' mood and productivity.

The dataset contains daily survey-like observations from multiple participants. Each row represents one person's answers for one day.

## Files

- `data/data_synthetic.csv`: dataset used in the analysis
- `notebooks/eda.ipynb`: exploratory data analysis, hypothesis testing, and simple machine learning model
- `requirements.txt`: Python libraries needed to run the notebook

## Variables

- `person_id`: participant number
- `day`: survey day
- `mood`: daily mood score
- `productivity`: perceived productivity score
- `energy`: energy level
- `sleep_hours`: sleep duration
- `negative_event`: whether a negative event happened that day
- `stress`: stress level
- `outdoor_time`: time spent outdoors
- `weather_feeling`: perceived weather effect

## Main Analysis Steps

1. Load and inspect the dataset
2. Check missing values and summary statistics
3. Visualize distributions and relationships
4. Analyze correlations
5. Test simple hypotheses
6. Build a basic machine learning model to predict high mood

## How to Run

Install the required libraries:

```bash
pip install -r requirements.txt
```

Then open the notebook:

```bash
jupyter notebook notebooks/eda.ipynb
```

## Note

This project is mainly focused on practicing a complete data science workflow: data loading, EDA, interpretation, statistical testing, and basic prediction.

## Limitations and Future Work

This project has several limitations. First, the dataset is based on self-reported responses, which may include subjective bias. In addition, the observations were collected over a limited time period. Some variables, such as weather feeling, are also perception-based rather than objective measurements.

For future work, real weather API data could be integrated into the analysis. A larger participant group and longer data collection period could improve the reliability of the findings. More advanced machine learning models could also be explored.

## AI Assistance Disclosure

AI tools were used to support code organization, formatting, and editing. The project topic, dataset structure, interpretations, and analysis decisions were reviewed and finalized by the student.
