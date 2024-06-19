# Sentiment-Text-Analysis
To perform sentiment analysis in Python, one of the most straightforward ways is to use the Natural Language Toolkit (NLTK) library along with the VADER (Valence Aware Dictionary and sEntiment Reasoner) sentiment analysis tool it provides. VADER is particularly good for texts from social media, news, and texts where informal language is often used.


First, ensure you have NLTK installed, and then download the VADER lexicon. You can do this by running the following commands in your Python environment:

# Install NLTK
!pip install nltk


# Python code to download the VADER lexicon
import nltk
nltk.download('vader_lexicon')

![image](https://github.com/tohingit/Sentiment-Text-Analysis/assets/171322240/6c0cf461-1916-417d-b540-bd55c339dd7a)


Next step is to run the script STAnalysis.py with promth command:
python STAnalysis.py

This script defines a function analyze_sentiment that takes a piece of text as input and uses VADER's polarity_scores method to determine the sentiment of the text. The compound score is then used to classify the sentiment as either positive, negative, or neutral based on its value.
Remember, sentiment analysis can be more complex depending on the nuances of the text, so this is a basic starting point. You might need to adjust thresholds or use more sophisticated models for more accurate or nuanced sentiment analysis in different contexts.

# Output

Given the input text "I absolutely love this product! It works wonders for me.", the sentiment analysis code you've provided will classify this text as 'Positive'. This is because the text clearly expresses a positive sentiment towards the product, and the VADER sentiment analysis tool is designed to recognize such positive expressions, likely resulting in a high positive compound score.
Therefore, the output of the code will be:
![image](https://github.com/tohingit/Sentiment-Text-Analysis/assets/171322240/d3773ace-896d-4738-bbef-a37db3fc49a6)
