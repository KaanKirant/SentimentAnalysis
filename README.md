Project Overview

The objective of this project is to build an automated classifier that can interpret consumer feedback across different industries (e.g., product reviews, movie critiques, and restaurant feedback). By training on diverse data sources, the model becomes more robust and capable of handling varying linguistic styles.

Dataset Breakdown

3,000 Total Samples: Sourced equally from Amazon, IMDb, and Yelp.

Target Labels: Binary classification where 1 denotes a positive review and 0 denotes a negative review.

Class Balance: The data is perfectly balanced with 1,500 samples for each sentiment class, ensuring no bias toward a specific outcome.

Methodology

Preprocessing: The data is cleaned for null values and shuffled to ensure the model doesn't learn based on the order of the platforms.

Feature Engineering: Text is converted into numerical data using the Bag of Words (BoW) model via

Stop Word Removal: Standard English stop words (e.g., "a", "the", "in") are removed to focus the model's attention on words that actually carry sentiment.

Data Splitting: An 80/20 train-test split is used to validate the model's performance on unseen data.
