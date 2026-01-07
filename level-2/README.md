# Level 2: Analyzing your data
## Goals
To finish the level, achieve these goals.

- [ ] Understand the structure of your collected dataset
- [ ] Identify missing or inconsistent data and handle it
- [ ] Apply basic statistical analysis to your dataset
- [ ] Produce meaningful visualizations to discover trends or anomalies
- [ ] Document insights from the analysis

## Building blocks
To achieve the goals, use these blocks.

- [ ] Load your dataset into a suitable tool (Python with Pandas, Excel, R, etc.)
- [ ] Inspect the dataset (size, columns, data types, ranges)
- [ ] Clean the dataset (handle NaNs, remove duplicates, fix formats)
- [ ] Calculate descriptive statistics (mean, median, min/max, standard deviation)
- [ ] Create charts (line, bar, scatter, heatmap) to visualize trends
- [ ] Compare data against expected baselines or thresholds
- [ ] Save cleaned data and visualizations in your repository
- [ ] Update your project log with findings
- [ ] Share summary results with your support team

## Load and inspect data
- import pandas as pd
- df = pd.read_csv('sensor_data.csv')
- Use _.head() and _.describe() to understand the dataset.

## Clean data
- Identify and replace missing values
- Remove obviously incorrect readings

## Analyze data
- Group by date or location
- Calculate averages, min/max, compare daily vs. weekly trends

## Visualize data
- Create a line graph of temperature over time
- Build a scatter plot comparing CO₂ vs. temperature
- ...

## Document & commit
- Write a short summary of findings in _analysis_notes.md.
- Commit cleaned dataset and visualizations to GitHub with a meaningful message.

## Side quests
To learn more, consider these side quests.

- [ ] Try advanced plotting libraries (e.g., Seaborn, Plotly)
- [ ] Learn how to use Jupyter Notebook for interactive data exploration
- [ ] Explore correlation analysis to find relationships between variables
- [ ] Investigate anomalies using rolling averages or standard deviation thresholds
- [ ] ...
