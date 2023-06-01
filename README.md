# Text-Analysis-of-Amazon-Product-Reviews
The objective of this project is to analyze a dataset of Amazon product reviews in order to understand customer sentiment and topics prevalent in the review text. The [selected dataset](https://cseweb.ucsd.edu/~jmcauley/datasets.html#amazon_reviews) for this analysis is the "5-core" dataset available from Jianmo Ni's collection of Amazon review data. This dataset contains over 75.26 million reviews from over 20 million users, wherein each product has at least five reviews. We will select a specific product category from this dataset for our analysis due to the huge volume of data.

## Topics

+ Data Acquisition and Cleaning: Download the 5-core dataset for a product category of choice from the aforementioned source. After acquiring the data, it will undergo a comprehensive cleaning and normalization process, which includes removing irrelevant data, handling missing values, normalizing text data, and ensuring the data is formatted suitably for subsequent analyses.

+ Bag-of-Words Analysis: With the cleaned text data, a bag-of-words model will be created to represent the review texts. This model will enable us to identify the most frequently used words in each star rating category, thereby providing insight into the sentiments associated with each rating.

+ Sentiment Analysis and Regression Modeling: The sentiment and polarity of the reviews will be analyzed using a suitable sentiment lexicon. This will entail determining the positive, negative, and neutral sentiments in the review texts. Additionally, a regression model will be built to evaluate the predictability of product ratings based on variables derived from the review text. We will provide justification for our choice of sentiment lexicon.

+ Topic Modeling: We will employ a topic model to analyze the dominant topics in the reviews for our chosen category. This analysis will focus on identifying the topics that are important to satisfied and dissatisfied customers, as well as understanding how specific product characteristics influence the prevalence of different themes in customer reviews.
