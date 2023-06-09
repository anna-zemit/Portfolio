Project Task List: Recommendation System for Pharmacies

1. Task: Data Collection and Preprocessing
   - Identify relevant data from customer purchase history
   - Extract necessary data fields
   - Utilize libraries like pandas, numpy, and sklearn for efficient data manipulation and preprocessing

2. Task: Natural Language Processing (NLP) Techniques
   - Utilize the pymorphy2 library for morphological analysis and stemming of Russian words
   - Apply the get_stop_words library to remove stop words from product descriptions
   - Implement the gensim library for word embedding and to create word vectors for product representations
   - Train a word2vec model using the product descriptions to capture semantic relationships

3. Task: Recommendation System Development
   - Design the recommendation algorithm, such as collaborative filtering or content-based filtering
   - Implement the chosen recommendation algorithm using Python, leveraging libraries like sklearn
   - Develop functions to calculate similarity scores between products using the trained word vectors
   - Generate recommendations based on user history, purchase patterns, or current shopping cart contents
   - Implement the hint display functionality during the checkout process
