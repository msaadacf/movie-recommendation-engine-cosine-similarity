This is a content based movie recommendation engine built using **Python, Pandas**, and **cosine similarity**.
This project uses movie metadata from the TMDB 5000 Movie Dataset to recommend similar movies based on textual and categorical features such as genres, keywords, cast, and crew.

**Project Overview**

This recommender system follows the content based filtering approach:

1. Load and merge TMDB movie and credits datasets
2. Then extract useful metadata (genres, keywords, cast, director)
3. Clean and preprocess text
4. Convert metadata into a single “**tags**” representation
5. Vectorize tags using **CountVectorizer**
6. Compute similarity scores using **cosine similarity**
7. Return top 5 most similar movies

The project is implemented entirely in a single Jupyter Notebook.
