# CS506-Final-Project

Project Description -----------------

The goal of this project is to build a machine learning system that predicts the winner of professional tennis matches on the ATP tour using match and player statistics. I will collect publicly available ATP match data and make features that can capture player skill, recent form, and match context (surface type). 

Timeline -----------------

Week 1 – Setup
-Finalize datasets
-Create GitHub repo + README
-Set up environment (Python, dependencies)
-Define baseline metric (e.g., compare accuracy vs higher-ranked baseline)

Week 2 – Data Collection
-Download ATP match data
-Collect supplementary player stats if needed
-Save raw data + document sources

Week 3 – Data Cleaning
-Handle missing values and duplicates
-Encode categorical features (surface)
-Save cleaned dataset

Week 4 – Feature Engineering
-Build features (rank diff, recent win %, surface)
-Create visualizations to better understand patterns and relationships
-Finalize feature set

Week 5 – Baseline Model
-Train an initial prediction model
-Establish baseline comparison (e.g., always pick higher rank)
-Measure accuracy

Week 6 – Improved Models
-Train a more advanced model
-Compare with baseline model
-Examine influence of different features

Week 7 – Testing, Reproducibility, CI
-Final training/testing
-Automated checks to ensure code runs as intended
-Ensure reproducibility from instructions in README

Week 8 – Final Polish & Submission
-Final visualizations
-Clean code + comments
-Finalize README (how to run, reproduce results)
-Record results + limitations
-Prep report/presentation

Week 9 - Report and Presentation
-Finalize report and presentation


Project Goals -----------------

-Predict the winner of a tennis match using pre-match information
-Identify which features (e.g., ranking disparity, surface, recent win rate) are most predictive of match outcomes.
-Compare predictions between multiple models

Data Collection -----------------

Data Sources:
-Public ATP match datasets (e.g., match results from datasets on Kaggle or GitHub that include rankings, surface type, match outcomes, and other basic player statistics.)
Collection Method:
	
Collection Method:
-Download CSV files from publicly available datasets

Data to Collect:
-Match-level data: winner, loser, tournament, surface, date
-Player-level data: rankings, age, height, historical win rates, head-to-head record


