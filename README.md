# Twitter-Sentiment-Analysis

Our goal was to study the sentiment analysis during the
first 6 months of COVID-19 spread. Our contribution in the
project revolves around exploring various Sentiment Analysis
tools modeled for sentiment analysis classification task. A
simple sentiment analysis task can lead to answering the
simple question: If the emotion of the sentence is positive or
negative? A more complex Sentiment Analysis task can lead
to answering: What is the emotion of the sentence in a ranking
scale of 1-5, 1 being very positive and 5 being negative.
Such emotion scaling are called finely grained emotions.
For effective sentiment classification: Negation is important.
When dealing with bag of words and each word has same
influence on deciding the sentiment of the sentence,correct
manipulation of word negation is crucial. Also, in some cases,
word occurrence may matter more than word frequency. Using
all words (pure na ̈ıve bayes) works well for some tasks but
not all. While the first method in the paper, Naive Bayes was
more easier to setup, but CoreNLP used multinomial na ̈ıve
bayes and found better fine grained classifications. There are
many more NLP sentiment classification tools used by the
researchers in recent times as discussed in the related section
of the paper. Significant takeaway from the paper is particular
on what investigation to be performed is imperative to evade

superfluous calculations that may back you off when working
with bigger informational collections.
