# Exploring_NYC_public_school_test_results_data-analysis
Using data manipulation to explore and analyse the statistics of test scores in public schools in New York.
This quick project is mainly focused on training to sort and subset data, rounding values and group summary statistics.

The goal was to analyse data to answer on these questions:
#### Which NYC schools have the best math results?
- The best math results are at least 80% of the *maximum possible score of 800* for math.
#### What are the top 10 performing schools based on the combined SAT scores?
- Save the results by creating a new column named "total_SAT", with results are the sum of math, reading, and writing scores.
#### Which single borough has the largest standard deviation in the combined SAT score?
- The DataFrame should contain one row, with the name of the NYC borough with the largest standard deviation of "total_SAT", the number of schools in the borough, the mean of "total_SAT", the standard deviation of "total_SAT". Also, round all numeric values to two decimal places.

## Contents

- `notebook.ipynb` – main notebook
- `schools.xlsx` – source data
- `schoolbus.jpg` – visual cover photo

## Getting Started

1. Clone the repo
2. Open `notebook.ipynb` in Jupyter Notebook
