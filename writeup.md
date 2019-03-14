# NLP Text classification
Create a machine learning model to identify negative review and identify the reason for the negativity. Identifying the negative review will give an opportunity to react to customer expectation and determine if the product needs to be removed from the product offers.

# Datasets
Reviews from Amazon review site (Polarity). https://course.fast.ai/datasets

- Review Text
- Review Score. Score 1 and 2 is nagative class. Score 4 and 5 is positive class. We can ignore score 3.

# Modeling Strategy
- Blazing Text Supervised Classification
- BlazingText's Word2Vec Unsupervised Model to generate word embeddings
- Linear Learner for 1:1 model interpretation, using word embeddings as features
- Clustering negative reviews to extract topics and key words

# End Goal
Once the model is ready, we can deploy it and automatically tag the reviews based on the text.


