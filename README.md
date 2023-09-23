# nlp_semantic_similarity

I would like word2vec(ngram) to extract vectors to search for exact phrases, but I couldn't implement this.

### Code details using tfidf:
- Tokenizes and preprocesses the input text for analysis.
- Calculates similarity scores between input sentences/phrases and standardized phrases.
- Suggests replacements when similarity scores meet a predefined threshold.
- Customizable list of standardized phrases for comparison.

**Result of this code:**
Replace 'came consensus need better terms performance' with 'monitor performance metrics'
Replace 'aim efficient look ways creative daily tasks' with 'prioritise tasks'
Replace 'growth essential future equally important building strong relationships team members' with 'drive growth'
Replace 'reminder annual staff survey due next friday' with 'exercise due diligence'
