# keyword-aware-hotel-recommender
Keyword Aware Hotel Recommender 

# Dataset Source

This dataset consists of 878561 reviews from 4333 hotels crawled from TripAdvisor sourced from [here](https://www.cs.cmu.edu/~jiweil/html/hotel-review.html). 

# Project Overview

Traditional online hotel searches rely solely on overall ratings, often neglecting individual needs. This can lead to frustrating recommendations, like suggesting a hotel praised for its location but criticized for its food if you prioritize dining experiences.

This project presents a data-driven solution that personalizes hotel recommendations based on YOUR unique preferences.

1. Unveiling Hidden Preferences: We leverage NLP to analyze hotel reviews, extracting specific preferences expressed by previous users (e.g., comfort, cleanliness, food quality). This goes beyond overall ratings, building detailed user profiles capturing individual priorities.

2. You simply select your desired features from a curated list of keywords. Our system then identifies other users with similar preferences, forming your "travel tribe."

3. PersonalBased on your  preferences, the top 5 hotels that are most likely to meet your individual needs are recommended.

We will be using Pandas for data cleaning, NTLK for text preprocessing, Jaccard and Cosine for similarity computation and custom ranking algorithms that prioritize hotels that best match your extracted preferences.





