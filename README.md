# Authorship Representation Learning Datasets

This repository contains a curated collection of popular and high-quality raw and pre-processed datasets for text representation learning. These datasets are designed to facilitate research and experimentation with natural language processing (NLP) tasks, particularly focusing on authorship attribution, sentiment analysis, and other text-based tasks. One of the primary emphases of these datasets is that they all include author IDs, making them exceptionally valuable for authorship analysis tasks.

Additionally, the provided processing code allows you to conveniently organize the text data by author and create dataset chunks suitable for training pre-trained transformer models with a chunk size of 512 tokens.

## Datasets Included

### 1. Enron Email Dataset
- **Description:** The Enron Email Dataset consists of data from approximately 150 users and contains around 0.5 million email messages. This dataset is a valuable resource for tasks related to email text analysis.
- **Usage:** Useful for email text classification, topic modeling, and other email-related NLP tasks.

### 2. IMDb1M Authorship Attribution Dataset
- **Description:** The IMDb1M Authorship Attribution dataset comprises 271,625 movie reviews authored by 22,116 distinct authors. It is widely used for authorship attribution and sentiment analysis tasks.
- **Usage:** Ideal for authorship attribution, sentiment analysis, and author-specific text analysis.

### 3. Blog Authorship Attribution Corpus
- **Description:** The Blog Authorship Attribution corpus is a collection of blog articles from 2004 and earlier, sourced from blogger.com. It includes over 680,000 posts authored by more than 19,000 individuals, with an average of 35 posts per author. This dataset was originally used for studying the effects of age and gender on blogging.
- **Usage:** Suitable for authorship attribution, demographic analysis, and content analysis of blog posts.

### 4. Amazon Review Data (2018)
- **Description:** This dataset includes reviews (ratings, text, helpfulness votes), product metadata (descriptions, category information, price, brand, and image features), and links (also viewed/also bought graphs). It is an extensive resource for product review analysis.
- **Usage:** Ideal for sentiment analysis, product recommendation, and review summarization.

### 5. Fanfiction Dataset
- **Description:** The Fanfiction dataset was collected by crawling fanfiction.net. It contains fanfiction written by fans of other literary works, offering diverse and creative text data.
- **Usage:** Suitable for fanfiction analysis, genre classification, and author-specific analysis.

### 6. Million User Dataset (MUD) from Reddit
- **Description:** The Million User Dataset (MUD) comprises 300 million Reddit posts from 1 million users published over a year. It focuses on users who published at least 100 but no more than 1000 posts between July 2015 and June 2016, ensuring a mix of quality and volume.
- **Usage:** Useful for Reddit text analysis, user profiling, and topic modeling.

## Data Processing Code
The repository includes processing code to help you organize the text data by author and create manageable dataset chunks of 512 tokens each. This preprocessing step is essential for efficiently training pre-trained transformer models on these datasets.

## Brief Analysis
You will also find brief exploratory data analysis (EDA) and statistics for each dataset in the "analysis" directory. These insights can help you get started with understanding the data's characteristics and potential research directions.

## Citation

**Disclaimer:** The datasets provided in this repository have been collected from various sources and are intended for research and educational purposes. Please note that we do not have ownership of the data and therefore cannot provide a license or control its use. However, we kindly request that the data only be used for research purposes.

We hope this collection of datasets and processing code proves valuable for your text representation learning endeavors. Happy coding and research!
