# recommendation-engine
Real time LLM Recommendation Engine  

# LLM Recommendation Engine

This recommendation engine helps users identify the most suitable Large Language Model (LLM) for their use-case by aggregating data from various sources such as the Hugging Face Leaderboard, Twitter, and GitHub. It utilizes semantic search combined with real-time analytics to provide accurate recommendations.

## Requirements

1. **Data Sources:**
   - Pull data from the Hugging Face Leaderboard for LLM models and their scores. Update scores every hour.
   - Retrieve information from Twitter and GitHub on developers' feedback and active usage of LLM models. Update this data every hour.

2. **Search Interface:**
   - Provide an intuitive search interface where users can describe their use-case.
   - Perform hybrid search (vector + full-text search) across model descriptions, Twitter discussions, and GitHub repositories using LLMs.

3. **Analytics:**
   - Combine results from semantic search with analytics on public benchmarks, number of likes, and number of downloads for each model.

4. **Infrastructure:**
   - Power the application entirely on a SingleStore Free Shared Tier Workspace.
   - Ensure real-time updates by using SingleStore Notebook and Job Service to reflect the latest posts and scores.

## GitHub Readme Code

```python
# Placeholder for GitHub readme code
# This code would include the implementation details for pulling data, conducting semantic search, and displaying recommendations.
