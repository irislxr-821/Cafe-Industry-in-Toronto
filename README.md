# Cafe-Industry-in-Toronto
This project consists of two parts: The first part uses NLP (Natural Language Processing) to analyze the Toronto café industry, while the second part offers business strategies for the Chinese Coffee Brand, Luckin, to enter the Toronto market, leveraging insights from the first part.

# 🏣Part #1 - Industry Analysis
## Description
As a coffee enthusiast, I'm interested in Toronto's café scene. It's competitive, so knowing what other cafés do well helps set yours apart. Learning about your customers' likes and gathering their feedback is crucial for creating a café that they'll love. Market research is key to standing out and ensuring a café's success in Toronto.

## Objective
Our team, acting as data consultants, is tasked with aiding a café in selecting the optimal location between Queen St. E. and Bay St., catering to its specialty in coffee and meal offerings for breakfast and lunch. The owner views their diverse menu as a key competitive edge but faces budget constraints affecting decisions on interior decor versus staff hiring to enhance customer experience initially. Beyond location and these decisions, they seek further advice for success.

## Data Collection and Methodology
To analyze the café industry in Toronto, we collected reviews from Google Maps for 12 cafes in Queen St. E. and Bay St. using web scraping. Our "getReviews" function, utilizing Selenium in Python, extracts review details like user name, date, rating, and text by interacting with Google Maps. We stored the data in a Pandas DataFrame, gathering 3262 reviews for market research insights.

## Results
The WordCloud Analysis reveals common words from customer reviews, aiding restaurateurs in pinpointing what matters most to patrons. For location decisions, we analyzed preferences in the Queen St E. and Bay St. areas. Additionally, logistic regression and Naive Bayes models highlighted "amazing," "downtown," "delicious," "awesome," and "friendly" as key positives in reviews, while negatives often mentioned "server," "overpriced," "use," "salad," and "bad." These insights help understand customer feedback and preferences.

## Business Insights
The analysis reveals that Queen St. E customers prioritize food, evident from its frequent mention in reviews, unlike in Bay St. This suggests Queen St. E as the better location for our client's food-focused café, especially since negative reviews highlight a demand for better food options. Given the emphasis on 'service' in reviews, investing in quality staff over interior design is advisable to stand out, particularly in Queen St. E where service often garners criticism.
Key recommendations include concentrating on breakfast with popular items like cheese, eggs, and salad to attract morning customers. Additionally, addressing complaints about long wait times in Queen St. E could significantly improve customer experience and competitive edge.

# ☕Part #2 - Strategies for Luckin to select a location
