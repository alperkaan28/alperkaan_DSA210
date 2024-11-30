# alperkaan_DSA210
Alper Kaan Gözübüyük DSA 210 Project

So those are the 3 ideas that i have for my project i could not decide exactly because it will be our own data, im not sure which am i going to access and work on it without a problem.

1) League of Legends Data Analysis

## Description
This project analyzes my League of Legends gameplay data to uncover patterns and make predictions. By using machine learning techniques, I aim to predict:
1. The lane I'm playing in a game.
2. Whether I will win or lose the game.
3. My Kill/Death/Assist (KDA) ratio.

The project leverages in-game performance metrics to develop predictive models and provide insights into my gaming behavior.

## Dataset
- **Source**: Collected from Riot Games API (match history and performance statistics).
- **Data Fields**:
  - Champion played
  - Lane (e.g., Top, Mid, Jungle)
  - Game outcome (Win/Loss)
  - Performance stats (Kills, Deaths, Assists, CS, Gold earned, etc.)
  - Game duration and objectives (towers, dragons, etc.)

## Project Goals
1. **Predict Lane**: Identify the role/lane based on the champion and performance stats.
2. **Predict Win/Loss**: Determine the game's outcome using team and player performance metrics.
3. **Predict KDA Ratio**: Estimate the KDA ratio based on historical data.

## Plan
1. **Data Collection**: Retrieve and clean match data from the Riot API.
2. **EDA**: Explore patterns in win rates, KDA ratios, and lane performance.
3. **Feature Engineering**: Prepare variables like average stats, roles, and objectives.
4. **Modeling**:
   - Classification models for lane and win/loss predictions.
   - Regression models for KDA ratio prediction.
5. **Evaluation**: Validate models using metrics like accuracy, F1-score, and mean squared error.
6. **Visualization**: Present insights and predictions using interactive plots.
7. **Documentation**: Create a comprehensive project report and visualizations.


2) YouTube Music Data Analysis

## Description
This project explores my YouTube Music listening data to identify trends in my music habits, including preferred genres, artists, and listening times. Using machine learning and visualization, I aim to predict future listening preferences and analyze how my musical tastes evolve over time.

## Dataset
- **Source**: Exported using Google Takeout.
- **Data Fields**:
  - Song names
  - Artists
  - Genres
  - Timestamps (when the song was played)
  - Playback duration

## Project Goals
1. Identify favorite genres, artists, and songs.
2. Visualize listening patterns (e.g., time of day, weekday vs. weekend trends).
3. Predict future preferences based on historical data.

## Plan
1. **Data Collection**: Export and preprocess YouTube Music history.
2. **EDA**:
   - Identify most played genres and artists.
   - Explore time-based patterns (e.g., daily/weekly trends).
3. **Feature Engineering**: Categorize songs by tempo, mood, or genre.
4. **Modeling**:
   - Clustering for grouping similar songs.
   - Predictive modeling for future preferences.
5. **Visualization**:
   - Interactive charts showing top genres, listening times, and trends.
6. **Documentation**: Summarize findings and present recommendations.

3) # Phone Screen Time Analysis

## Description
This project examines my phone screen time data to understand app usage patterns, overall productivity, and potential impacts on daily life. The goal is to identify trends, compare app categories, and predict future screen time based on historical data.

## Dataset
- **Source**: Collected from phone’s screen time tracking feature.
- **Data Fields**:
  - Daily total screen time
  - App usage breakdown by category (e.g., social media, work, entertainment)
  - Notifications received
  - Time spent on individual apps

## Project Goals
1. Analyze which apps and categories dominate my screen time.
2. Explore time-based patterns in usage (e.g., weekday vs. weekend).
3. Predict future screen time trends.

## Plan
1. **Data Collection**: Export phone screen time data.
2. **EDA**:
   - Visualize app usage distribution.
   - Compare productivity vs. entertainment usage.
   - Explore correlations (e.g., notifications vs. screen time).
3. **Feature Engineering**: Aggregate app usage by category and time periods.
4. **Modeling**:
   - Regression models for predicting screen time trends.
   - Time series analysis for forecasting future usage.
5. **Visualization**: Create dashboards showing app usage and trends.
6. **Documentation**: Provide actionable insights and recommendations.
