# Simple Sentiment Analyzer

This is a basic Python program that performs sentiment analysis on a list of customer reviews using keyword matching. It classifies each review as **Positive**, **Negative**, or **Neutral** based on predefined sentiment keywords.

## 🧠 How it Works

- A list of **positive** and **negative** keywords is defined.
- Each review is converted to lowercase and checked for the presence of these keywords.
- The program counts the number of positive and negative words in each review.
- It then classifies the review based on which count is higher.

## 🧾 Example Reviews

```python
reviews = [
    "I love this product, it's amazing!",
    "This was a terrible experience.",
    "Very satisfied with the service.",
    "The quality is bad and I am not happy.",
    "Excellent support team!",
    "Not what I expected, poor quality."
]

🧪 Sample Output
Review: "I love this product, it's amazing!"
Sentiment: Positive

Review: "This was a terrible experience."
Sentiment: Negative

Review: "Very satisfied with the service."
Sentiment: Positive

Review: "The quality is bad and I am not happy."
Sentiment: Negative

Review: "Excellent support team!"
Sentiment: Positive

Review: "Not what I expected, poor quality."
Sentiment: Negative

//??
