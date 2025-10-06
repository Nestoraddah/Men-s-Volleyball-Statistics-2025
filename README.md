# Men's Volleyball Statistics
Overview

This project provides a data-driven look into the 2025 NAIA Men’s Volleyball season, focusing on player and conference performance.
The goal was to uncover key performance patterns, identify top athletes by metrics such as Points Per Set, and compare conference-level strengths across the league.

Objectives

Clean, organize, and standardize raw performance data for analysis.

Segment teams by conference for deeper comparative insights.

Identify the top 5 players per conference based on offensive and defensive efficiency.

Visualize trends in player performance across major volleyball statistics.

Process

Data Cleaning & Preparation

Imported and explored the raw Excel dataset using pandas and numpy.

Renamed columns for clarity and consistency.

Removed redundant rows and cleaned team names (e.g., stripping state abbreviations).

Mapped each team to its athletic conference (AAC, Cal Pac, WHAC, and others).

Feature Engineering

Added a Conference column for segmentation.

Reorganized data to streamline analysis by player and conference.

Validated structure and summary statistics using .info() and .describe().

Exploratory Data Analysis (EDA)

Used Seaborn and Matplotlib for statistical visualization.

Grouped and ranked players to identify conference leaders.

Created performance comparisons across metrics such as:

Points Per Set

Hitting Percentage

Digs and Blocks

Serving Efficiency

Visualization & Insights

Designed bar and box plots to highlight performance distributions.

Compared offensive and defensive strengths across conferences.

Highlighted standout performers and statistical outliers.

Key Questions Answered

Which players led their conferences in overall performance metrics?

How do playing styles and strengths differ between conferences?

What trends define high-performing athletes at the NAIA level?

Which statistical factors most influence match success?

Key Insights

A few top-performing players consistently led their teams in total points and efficiency.

Conference-level trends revealed differences in strategy — some favored power offense, while others excelled defensively through blocks and digs.

Standardizing data across all conferences was essential for accurate comparison.

Tools & Technologies

Languages: Python

Libraries: pandas, numpy, matplotlib, seaborn

Environment: Jupyter Notebook

Dataset: 2025 NAIA Men’s Volleyball Statistics

Outcome

This analysis demonstrates the power of data analytics in collegiate sports, turning raw stats into actionable insights for coaches, analysts, and teams.
By combining technical data skills with sports expertise, the project helps visualize performance trends and supports strategic coaching decisions for future seasons.
