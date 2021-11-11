# JJZM Project - The (under)talked problem of Climate Change

<p align="center">
  <img src="https://www.itu.int/en/mediacentre/backgrounders/PublishingImages/climate-change-backgrounder.jpg" alt="Climate change"/>
</p>

## Abstract

*"We have a single mission: to protect and hand on the planet to the next generation."* - Francois Hollande

Climate change is a global issue with global repercussions. We read, see, hear every day about the ecological disaster we are facing.

We will try through this study to see if we can deny or not some prejudice about climate change. For example, what kind of people are concerned about climate change. Is it always the youngest or, perhaps, politicians from a left-wing party? 

It is believed that all people, regardless of their background, should have an impact when it comes to facing the problem of climate change. Our goal is to determine how different groups of people react to this threat. Even though a person's nationality, age, political party, etc. separates him or her from other people, the desire for a better tomorrow is why the differences should be left aside.

## Research questions

1. What political parties have talked the most about climate change in the media?
2. Can we make a statement about the diversity between left-wing, center, and right-wing parties' quotes about climate change?
3. Does the age of the speaker cause a difference in the attitude and concerns one has about climate change?
4. How is climate change discussed among people of different nationalities all around the globe?
5. Do people from one region of the world have different opinions about climate change than the ones from other regions?
6. What are the biggest concerns about climate change in the world as shown in the media?
7. Do different groups of people (based on their age, nationality, and political party) have positive, neutral, or negative statements about climate change?

## Proposed additional datasets

For our research questions, we will not need any additional datasets, except the information obtained from Wikidata. More precisely, we are enriching the Quotebank dataset with additional data about the speaker - their nationality, age, and political party.

## Methods

The methods, libraries, and algorithms that we going to use rely on the principles of text analysis, text summarization, and sentiment analysis. With the intention of addressing our research questions, we have chosen the following methods as the ones we find most suitable for dealing with the Quotebank data set:

- *Fasttext* - The fasttext library will allow us to perform classification and try to distinguish between the quotes that were stated by someone in a left-wing, in a center or, in a right-wing political party.
- *Observational study* - Based on the sentiment score of every quote, we will execute an observational study. The goal is to determine if there would be a difference when we compare the sentiment scores among people with similarlz observed covariates. For this, we will compare groups from different regions, political parties, and ages.
- *Sentiment analysis* - By adding the sentiment score and category to our quotes powered by the afinn library, we can conclude the statements and opinions that speakers have towards the issue of climate change.
- *TextRank* - We will implement this algorithm for the sake of summarizing the quotes we have about climate change. By searching for the words that appear more frequently, sentences that have those words would be marked as the key ones.
- *LexRank* - Another way of summarizing the information from the quotes. This time, we will observe the similarity between sentences, and the most similar ones will get picked for the summary.
- *Luhn Summarizer* - This algorithm has a different approach, it will leave out the low and high-frequent words as non-significant. Since 'climate change' or 'global warming' appear in every one of our quotes, the algorithm will focus on the rest for the summary.

## Proposed timeline

| Deadline | Description                                                                                                                                                                                                                                                                                                  |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| **19.11**    | Dividing countries of the nationalities into regions based on geographical and social-economical aspects combined, performing additional analysis between different regions and the popularity of the climate change topic in quotes from those regions, distinguishing between left-wing, center and right-wing parties. |
| **26.11**    | Performing the fasttext classification and implementing different text summarization algorithms. Also, compare different groups with a focus on the sentiment scores and categories.                                                                                                                                                                                                                                                                           |
| **03.12**    | Analysing the first results of fasttext classification, sentiment analysis, and text summarization algorithms.                                                                                                                                                                                                                     |
| **10.12**    | Comparing performances of summarization and classification methods. The template for the data story has been defined and set up.                                                                                                                                                                                                                                           |
| **17.12**    | Finalizing README, final comments on the code and performed analysis, finalizing the data story. Hopefully, show that the issue of climate change has the place it deserves in the media.                                                                                                                                                                                                          |

## Organization within the team

- Jovana: Preparing the data for future work, performing the text summarization algorithms, and comparing the results
- Maxence: Planning the data story and the final readme file, compare groups based on sentiment scores
- Zoran: Implementing the classification using the fasttext library
- Jonatan: Primary data analysis, visualization of the key features for our problem, plotting the results

## To go further

We want to figure out climate change skepticism within the database through Machine Learning. Possibility of an external database integration with the purpose of backing all our findings up.

