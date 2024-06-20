# Trustpilot API Customer Review Sentiment Analysis

## Summary
This project fetches customer reviews from the Trustpilot website and performs sentiment analysis using OpenAI's GPT-4. The project involves fetching reviews, cleaning and preprocessing the data, analyzing sentiment, and visualizing the results. Finally, the processed data is stored in an Azure SQL Database for further analysis and reporting.

## Table of Contents
- [Summary](#summary)
- [Table of Contents](#table-of-contents)
- [Setup and Installation](#setup-and-installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Steps](#steps)
  - [Step 1: Import Libraries and Setup API Keys](#step-1-import-libraries-and-setup-api-keys)
  - [Step 2: Fetch and Parse Reviews from Trustpilot](#step-2-fetch-and-parse-reviews-from-trustpilot)
  - [Step 3: Clean and Preprocess the Data](#step-3-clean-and-preprocess-the-data)
  - [Step 4: Analyze Sentiment Using GPT-4](#step-4-analyze-sentiment-using-gpt-4)
  - [Step 5: Visualize Sentiment and Ratings](#step-5-visualize-sentiment-and-ratings)
  - [Step 6: Data Storage with Azure SQL Database](#step-6-data-storage-with-azure-sql-database)
- [Contributing](#contributing)
- [License](#license)

## Setup and Installation

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/trustpilot-sentiment-analysis.git
   cd trustpilot-sentiment-analysis
