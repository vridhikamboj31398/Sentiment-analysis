
# Sentiment-Analysis-using-Python

One of the applications of text mining is sentiment analysis. Most of the data is getting
generated in textual format and in the past few years. Improvement is a continuous process and
many product-based companies leverage these text mining techniques to examine the
sentiments of the customers to find about what they can improve in the product. This
information also helps them to understand the trend and demand of the end user which results
in Customer satisfaction.

As text mining is a vast concept, the article is divided into two subchapters.

The main focus of this article will be calculating two scores: sentiment polarity and subjectivity using
python. 
The range of polarity is from -1 to 1(negative to positive) and will tell us if the text
contains positive or negative feedback. Most companies prefer to stop their analysis here but in

our second article, we will try to extend our analysis by creating some labels out of these scores.

# Data Preprocessing

In the above-given problem statement we have performed various pre-processing steps
on the dataset that mainly dealt with removing stopwords, removing emojis.

The text document is then converted into the lowercase for better generalization.

Subsequently, the punctuations were cleaned and removed thereby reducing the
unnecessary noise from the dataset. 

After that, we have also removed the repeating characters
from the words along with removing the URLs as they do not have any significant importance.

At last, we then performed Stemming (reducing the words to their derived stems) and
Lemmatization (reducing the derived words to their root form known as lemma) for better
results.

# Data Exploration

Let's form a WordCloud

A wordcloud is a visualization wherein the most frequent words appear in large size and
the less frequent words appear in smaller sizes.

