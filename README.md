# Table of Contents

# Abstract
This is one of the main projects I worked on with my supervisor Alex during my internship at Yukka Lab in Berlin, Germany in the Summer of 2024. Yukka Lab extracts news articles everyday for the companies of interested. For each news article extracted,their model is able to detect the specific 'events' mentioned or implied in this article that are from the list of events we are interested at. In this project, I worked on a deep exploratory data analysis on all the events extracted from all companies throughout March 2024.

# Dataset
The dataset includes all the news articles throughout March 2024. We furthur organized it in a neat table that contains information such as language, timestamp, factuality, temporality, event, event_participant_id, event_participant_role, and amount. Each row represents a news article so there are 24852050 rows.

# File 1 : [event_march.ipynb](event_march.ipynb)
This jupyter notebook explores all the variables from this table to enhance a better understanding of this dataset. It answers the following questions : 

1. General distributions of events
- Total of 148 unique events
- 1st Percentile Events Frequency
  [event_freq.png]
2. Distributions of Factuality and Temporality
3. Detected Participant
- Participant rate for each event
  [Distribution of Participant Rates by Event.png]
4. Distribution of Language
5. Correlations between events
  [correlation.png]
- distribution : most events pairs are less correlated (have correlation < 0.2)
- We will focus on events pairs that have correlation > 0.5

# File 2 : [Q6_march.ipynb](Q6_march.ipynb)
This jupyter notebook explored the same dataset as the other file. Instead of generally exploring all variables, this notebook focuses on 'events' variable. How other variables interact with different 'events' and how each event interact with each other.
