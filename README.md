# Musical preferences Springfield vs Shelbyville
Project goal:

The objective of this project is to compare the musical preferences of users from Springfield and Shelbyville. Using data from an online music‑streaming service, the analysis evaluates whether the two cities differ in:
* Preferred music genres
* Preferred days of the week for listening
* Preferred hours of the day for listening

The project tests predefined hypotheses and explores user behavior patterns across both cities.

Results:

The analysis revealed several key insights:

1. Genre Preferences
Both cities share the same top three genres—pop, dance, and rock—although the order of preference differs slightly. Overall, the musical taste profile is very similar across the two populations.

2. Day Preferences
Listening behavior varies by city with distinct weekly engagement patterns:
* Springfield shows a clear peak on Fridays
* Shelbyville reaches its highest activity on Wednesdays

3. Hour Preferences

The peak listening hours in both cities are 20:00, 14:00, and 13:00, though the ranking differs. These hours consistently show the highest user activity.

4. Overall Listening Volume

Springfield users listen to music more than twice as much as Shelbyville users.
Possible explanations include population differences or the use of alternative music platforms, but the current dataset does not allow a definitive conclusion.

5. Business Insights
* Marketing strategies should consider city‑specific peak days and hours.
* Ads placed within the top genres (pop, dance, rock) are likely to achieve higher engagement.

Tools used:
* Jupyter Notebook
* Python (Pandas, NumPy, Matplotlib, Seaborn)

Skills/competencies acquired

Throughout this project, I strengthened several key data‑analysis skills:
* Cleaning, transforming, and aggregating datasets using pandas
* Creating visualizations with Matplotlib and Seaborn
* Grouping and comparing user behavior across categories
* Formulating and testing hypotheses
* Structuring a full analytical workflow from raw data to insights
* Communicating findings clearly through plots and narrative explanations

Areas for improvement

Future enhancements could include:
* Incorporating statistical significance testing (e.g., chi‑square, t‑tests)
* Adding more granular data, such as user demographics or subscription type
* Improving visualizations with interactive dashboards (Plotly, Tableau, Power BI)
* Automating parts of the analysis with reusable functions


The dataset includes:
* User IDs
* City (Springfield or Shelbyville)
* Timestamp of each listening event
* Genre information

Methodology:
1. Data Loading & Inspection
* Import CSV files
* Check for missing values, duplicates, and data types

2. Data Cleaning
* Remove duplicates
* Convert timestamps to datetime
* Extract hour and day of week

3. Feature Engineering (aggregated tables):
* Users per genre
* Users per day
* Users per hour

4. Visualization
* Bar plots for genre, day, and hour comparisons
* Color‑consistent plots for both cities

5. Hypothesis Testing
* Compare patterns and evaluate whether the cities differ significantly
* Insights & Conclusions
* Summarize findings and business implications

How to Run the Project?

Clone the repository: git clone https://github.com/Faissen/Musical-preferences-Springfield-vs-Shelbyville---Tripleten-Bootcamp

Navigate into the project folder: cd Musical-preferences-Springfield-vs-Shelbyville---Tripleten-Bootcamp

Install required libraries: pip install -r requirements.txt

Open the Jupyter Notebook and Run the notebook cells in order to reproduce the analysis.

Visual Summary
* Genre Preferences
[![Genre Plot](images/genre_plot.png)](https://github.com/Faissen/Musical-preferences-Springfield-vs-Shelbyville---Tripleten-Bootcamp/commit/7bf8bb5b340b6ed92a3bdb08fd89a5c2b522b970#r173553979)
* Day Preferences
![Day Plot](images/day_plot.png)
* Hour Preferences
![Hour Plot](images/hour_plot.png)
