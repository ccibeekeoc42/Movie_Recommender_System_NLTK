# Movie_Recommender_System_NLTK

In this repo, we build a movie recommender system that uses a content based filtering to recommend movies to the user. Enjoy!

### Software, Tools, and prerequisits

1. Access to Google Colab or some Jupyter Notebook.
2. Basic python programing.
3. Basic modular programming knowledge.

### Intro: What are Recommender Systems?

These are a branch of AI/ ML used to calculate similarities between variout items in a specific category like products, content, and/or services. This can be very helpful with matching these items with customers/ consumers.

There are basically 3 main types of recomender systems namely: Content-based filtering, collaborative filtering, and hybrid recomender systems.

- Content-Based Filtering: Uses similarities in products, services, or content features to make recomendations. The key here is it mostly uses info/ features about the underlying product.

  - Similarity here is usually created using the dot product or cosine similarity between the data/ vectors in question.

- Collaborative Filtering: Uses user profile to compute similarity to other users and recommend products or content based on what similar users enjoy.

- Hybrid Recomender Systems are a combination of both Content-Based Filtering and Collaborative Filtering

### Steps to completing the project

1. Import the necessary modules/ packages needed for this project.
2. Load and Prepare the dataset (this involves ensuring no null values).
3. Stem the data by cutting each word in the sentence to its stem/ root word.
4. Vectorize the features to get a numerical representation of the sentence.
5. Compute the similarities using the Cosine Similarity method.
