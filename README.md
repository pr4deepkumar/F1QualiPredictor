### 🏎️ Project Overview: F1 Qualifying Time Prediction using Historical Data and Performance Factors

This project aims to **predict Formula 1 qualifying (Q3) lap times for the 2025 season** by combining historical race data and team/driver performance multipliers. It uses data from the 2024 and 2025 seasons, fetched via the `FastF1` API. For each 2025 race round, the model predicts lap times for all current drivers based on:

- **The best Q3 time from the corresponding round in 2024** (serving as a base reference),
- **Team and driver performance factors** (reflecting relative pace differences),
- And **random variation** to simulate real-world fluctuations.

Additionally, the model is trained using 2025 qualifying data (Rounds 1–4) to estimate relationships between Q1, Q2, and Q3 lap times using a linear regression model. The final output ranks drivers per round by their predicted Q3 times, allowing for comparative performance insights across teams and drivers throughout the upcoming season.
