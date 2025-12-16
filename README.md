# Fitness & Lifestyle Data Analysis 

## Overview
This project analyzes a synthetic lifestyle and fitness data collected over 31 days to identify trends, correlations, and insights about daily activity, sleep, hydration, and mood. The analysis uses Python and popular data science libraries to perform exploratory data analysis (EDA) and visualize relationships between different metrics.

## Key Insights
- Average daily steps were approximately **10,500**, indicating moderate activity levels.
- Higher active minutes showed a strong positive relationship with calories burned.
- Sleep duration and activity levels appeared to influence mood scores.
- Water intake showed a mild positive association with overall mood.

## Dataset
The dataset `lifestyle_fitness_data.csv` contains the following columns:

| Column Name     | Description                                      |
|-----------------|--------------------------------------------------|
| Date            | Date of the record                               |
| Steps           | Number of steps taken daily                      |
| Calories        | Calories burned per day                           |
| ActiveMinutes   | Minutes of physical activity                      |
| SleepHours      | Number of hours slept                             |
| WaterIntake     | Daily water intake in liters                      |
| MoodScore       | Daily mood rating on a scale from 1 to 10        |

> Note: The dataset is synthetically generated using Python's `random` module to simulate real-world fitness and lifestyle data.

## Visualizations
The following visual analyses are included in this project:
- Daily steps trend over time
- Calories burned vs active minutes
- Distribution of sleep hours
- Mood score vs sleep hours
- Mood score vs active minutes
- Correlation heatmap of fitness and lifestyle metrics

## Tools & Libraries
- Python 3.x  
- Pandas (Data manipulation)  
- Matplotlib (Data visualization)  
- Seaborn (Statistical visualization)  

## How to Run
1. Ensure you have Python 3.x installed (Anaconda recommended).  
2. Install necessary packages if not already installed:
pip install pandas matplotlib seaborn
3. Open `fitness_lifestyle_data.ipynb` in Jupyter Notebook.
4. Run all cells from top to bottom to reproduce the analysis and visualizations.
