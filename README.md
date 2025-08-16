# Movie_Recommender_using_Gradio
A  movie recommender using IMDb scraping, OMDb API Keys, Selenium, and Sentence Transformers. It encodes movie storylines and matches them with user queries via semantic search. Results are displayed in an interactive Gradio dashboard.

This project is a smart movie recommendation engine built by scraping IMDb data. It combines multiple technologies to deliver personalized movie suggestions based on storyline similarity.

🔧 Tech Stack & Workflow:
IMDb Scraping: Movie metadata and storylines are extracted using a combination of Selenium WebDriver, requests, and the OMDb API.
Data Preprocessing: The scraped data is cleaned and structured for efficient processing.
Semantic Encoding: Movie storylines are encoded using Sentence Transformers from Hugging Face, enabling deep semantic understanding.
User Query Matching: When a user enters a search query (e.g., a plot idea or theme), it is encoded and compared against the movie embeddings to find the closest matches.
Gradio Dashboard: A sleek and interactive UI built with Gradio allows users to input queries and instantly receive movie recommendations.

💡 Key Features:
Input a movie plot or theme and get recommendations that match its essence.
Uses sentence-transformers to understand storyline semantics.
Fast and responsive Gradio interface for real-time interaction.
Continuously expandable with new movies and genres.
