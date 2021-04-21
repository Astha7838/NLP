# NLP
Assignment 1: Extracting Tweet-Like Summaries from the News

The purpose of this assignment is to gain some experience with text statistical variation, and likewise, to explore how it can be decoded for a given task and what can be done with the subsequently-learned information.

At a high level, the NewsTweet tweet prediction task's specific purpose was the determine if a given article contains a tweet. But if we think about applying this to out-of-set data as 'test' documents, what does it tell us?

Well, since we know tweets have limited size, one thought might be:

Can we use the CBOW classifier to discover where the tweet(s) are in the articles?

Satisfying this task would be a kind of extractive summarization task, in which the purpose is to predict a text span as being representative of some annotation. For us, there is certainly a portion of the text that represents our 'has tweet' annotation, at it is any of the tweet-text spans that a given article contains.

Let's see what CBOW can find!
