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


# LLM Recommendation Engine

This repository contains the code and instructions to build a recommendation engine for Large Language Models (LLMs) using data from various sources such as the Hugging Face Leaderboard, Twitter, and GitHub. The recommendation engine utilizes semantic search combined with real-time analytics to provide accurate recommendations based on user-defined use-cases.

## Contents

1. [Step 1: Creating a Starter Workspace](#step-1-creating-a-starter-workspace)
2. [Step 2: Installing & Importing required libraries](#step-2-installing--importing-required-libraries)
3. [Step 3: Setting Key Variables](#step-3-setting-key-variables)
4. [Step 4: Designing your table schema on SingleStore](#step-4-designing-your-table-schema-on-singlestore)
5. [Step 5: Creating Helper Functions to load data into SingleStore](#step-5-creating-helper-functions-to-load-data-into-singlestore)
6. [Step 6: Loading data with embeddings into SingleStore](#step-6-loading-data-with-embeddings-into-singlestore)
7. [Step 7: Building the Recommendation Engine Algorithm on Vercel](#step-7-building-the-recommendation-engine-algorithm-on-vercel)

## Step 1: Creating a Starter Workspace

To begin, create a starter workspace for your project. This workspace will serve as the foundation for developing the recommendation engine.

## Step 2: Installing & Importing required libraries

Install and import the necessary libraries and packages required for data processing, analysis, and visualization.

## Step 3: Setting Key Variables

Define key variables such as API tokens, database connection details, and search parameters required for data retrieval and processing.

## Step 4: Designing your table schema on SingleStore

Design the table schema on SingleStore to store the data retrieved from different sources. Define the structure of the tables and specify the data types for each column.

## Step 5: Creating Helper Functions to load data into SingleStore

Develop helper functions to facilitate the loading of data into SingleStore. These functions will streamline the process of inserting data into the database tables.

## Step 6: Loading data with embeddings into SingleStore

Load the retrieved data, including embeddings, into SingleStore. Ensure that the data is properly formatted and aligned with the table schema defined earlier.

## Step 7: Building the Recommendation Engine Algorithm on Vercel

Build the recommendation engine algorithm using the loaded data. Implement semantic search and real-time analytics to generate personalized recommendations based on user-defined use-cases. Deploy the recommendation engine on Vercel for accessibility.

Following these steps will guide you through the process of creating a robust recommendation engine for LLMs, leveraging data from multiple sources and advanced algorithms.

