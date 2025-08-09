Disney Remake Exploration

📌 Project Overview
This project explores community sentiment and discussion topics around Disney live-action remakes using comments from the r/disney subreddit.  
It applies Natural Language Processing (NLP) techniques to extract insights about what the Disney fandom are talking about, how they feel, and which aspects of the remakes spark the most engagement.

📂 Contents
- `disney_remake_nlp_exploration.py` – Main Python script for data processing, sentiment analysis, topic modelling, and inputs for visualisations.
- `Disney_remake_exploration_plots.pdf` – Generated visualisations from analysis and model implementation.
- `README.md` – Project documentation.

🔍 Analysis Workflow
1. Data Collection
   - Comments scraped from r/disney posts related to Disney remakes using `praw` (Python Reddit API Wrapper).
   - Includes titles such as Snow White*, Lilo & Stitch*, and The Little Mermaid*.

2. Data Preprocessing
   - Expansion of contractions, standardising text casing, text substitution, tokenisation, stopword removal, lemmatisation.
     
3. Exploratory Analysis
   - Term Frequency analysis.
   - Noun Phrase Extraction analysis.

4. Topic Modelling
   - Latent Dirichlet Allocation (LDA) to uncover main themes of discussion.
   - Identifies clusters such as casting discussions, visual fidelity, soundtrack opinions, and nostalgia.

5. Sentiment Analysis
   - Using VADER SentimentIntensityAnalyzer to classify comments as positive, negative, or neutral.
   - Calculation of weighted sentiment scores based on Reddit upvote scores and compound sentiment.

