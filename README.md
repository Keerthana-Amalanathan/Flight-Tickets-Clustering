# Optimal Flight Deal Recommendation System

### Project Description

This project focuses on leveraging **clustering techniques** to analyze flight data and identify optimal deals based on critical factors such as travel duration, layover time, and pricing. Using web scraping, we extracted real-time flight data from the **Kayak** website to ensure relevance and accuracy. By clustering flights based on their attributes, we categorized options into groups, such as "best deals," which often feature shorter travel times, fewer layovers, and reasonable pricing.

### Motivation

The primary objective is to replace manual analysis with a machine learning-driven approach, automating selecting the best flight options for travelers. This system is designed for use in travel planning and offers clear, data-driven recommendations for the most suitable airline carriers and routes.

### Data Collection and Processing

- **Data Source**: Real-time data was scraped from the **Kayak** website using Python's **Beautiful Soup** library over four months (January to April 2024). 
- **Data Wrangling**: This involved cleaning, resolving distribution issues, handling outliers, and preparing features for clustering and model training.
- **Preprocessing**: Techniques such as PCA were applied to reduce dimensionality and highlight the most significant relationships among features.

### Clustering and Insights

The project employs clustering techniques to group flights based on their inter-feature associations and similarities. This approach enables:
- Identifying flights with minimal travel time and layovers as the best deals.
- Providing actionable insights into pricing trends and traveler preferences.
- Simplifying decision-making by offering logical and justifiable recommendations.

### Key Outcomes

The results demonstrated that clustering effectively categorizes flight options, aiding travelers in quickly identifying optimal choices based on their preferences and constraints. This methodology enhances the travel planning process, ensuring efficiency, clarity, and user satisfaction. 
