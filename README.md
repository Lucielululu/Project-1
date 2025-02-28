## Wisdom Sparke Book Store -- An Inventory Planning Project Through Pandas, NumPy & API 
### Project Overview

🎥 Presentation Link url https://docs.google.com/presentation/d/1cFXuBOhJrBxBhAgqdTXBF4CwwlaGHfubd5v7_OoMh3A/edit?usp=sharing

We are two passionate book lovers with a dream: to open a charming bookstore just around the corner!  But the big questions are:
  
✨ Which books should we stock?  
✨ How many copies should we order?

To answer these critical questions, we leveraged data analytics, automation, and API integrations using:

- Pandas & NumPy for data manipulation

- Visualization libraries for insights

- NYT API for real-time bestseller tracking


### Technical Approach

#### Step 1: Data Cleaning & Wrangling (CSV)

Filtered book data based on:

⭐ Ratings ≥ 4.5

📝 Review count ≥ 4000

- Analyzed category distribution (10 main categories)

- Selected Top 20 books within each category

- Examined price distribution to optimize stocking decisions

#### Step 2: Automating Future Inventory Selection

- Bestseller List Automation: Automatically fetches top-trending books 

- NYT Book Reviews API: Retrieves critical reviews for marketing & in-depth insights 

#### Step 3: Final Stock List Generation

- Generated a structured CSV file for easy inventory management 

- Ready-to-use data for purchasing decisions & business strategy  


### Authors
Lu Song  
Atefah Hassani
### Exteral Data Sources
📊 Amazon Kindle Book Sales Dataset (Kaggle)  
https://www.kaggle.com/datasets/asaniczka/amazon-kindle-books-dataset-2023-130k-books  
📰 New York Times Books API  
https://developer.nytimes.com/docs/books-product/1/overview
