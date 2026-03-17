Ex.No.6 Development of Python Code Compatible with Multiple AI Tools

# Aim: 

Write and implement Python code that integrates with multiple AI tools to automate the task of interacting with APIs, comparing outputs, and generating actionable insights with Multiple AI Tools.

# Explanation:

Develop a python code that integrates multiple AI tool by interacting with their APIs.
Compare outputs from different APIs.
Analyze the response and the Output.

The aim is to understand how to request help from AI tools for tasks like writing Python code, integrating with APIs, comparing outputs, and generating actionable insights.

# Program:

```from nltk.sentiment import SentimentIntensityAnalyzer
import nltk

nltk.download('vader_lexicon')

# Simulated AI-generated text
generated_text = input("Enter a review:")
print("Generated Review:\n")
print(generated_text)

# Sentiment analysis
sia = SentimentIntensityAnalyzer()
sentiment = sia.polarity_scores(generated_text)

print("\nSentiment Analysis:")
print(sentiment)

# Insight generation
if sentiment['compound'] > 0:
    print("\nInsight: The review is positive and suitable for marketing promotion.")
else:
    print("\nInsight: The review tone is neutral or negative.")
```
# Result: 
<img width="1055" height="253" alt="Screenshot 2026-03-17 092421" src="https://github.com/user-attachments/assets/15c9d7b3-1bb6-41a1-a60f-9380954766b0" />

<img width="765" height="255" alt="Screenshot 2026-03-17 094426" src="https://github.com/user-attachments/assets/68f8eefd-3853-42e3-8cc2-86144fc371ed" />



