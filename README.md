# JJZM Project - The (under)talked problem of Climate Change

<p align="center">
  <img src="https://www.itu.int/en/mediacentre/backgrounders/PublishingImages/climate-change-backgrounder.jpg" alt="Climate change"/>
</p>

## Abstract

*"We have a single mission: to protect and hand on the planet to the next generation."* - Francois Hollande

Climate change is a global issue with global repercussions. We read, see, hear every day about the ecological disaster we are facing. 
We will try through this study to see if we can deny or not some prejudice about climate change. For example, what kind of people are concerned about climate change. Is it always the youngest? Left-wing politicians? 
As well, we will see the evolution of the vision of climate change through the years. In fact, with all the data we have, we want to see the correlation we can find between the author’s characteristics (age, country, city, political party, etc) and the quote.
Finally, we want to add some external database about climate change so that we can support our words.
## Research questions

1. What political parties have talked the most about climate change in the media?
2. Can we make a statement about the diversity between left-wing, center,  and right-wing parties' quotes about climate change?
3. Does the age of the speaker cause difference in the attitude and concerns one has about the climate change?
4. How is climate change discussed among people of different nationalities all around the globe?
5. Do people from one region of the world have different opinions about climate change than the ones from other regions?
6. What are the biggest concerns about the climate change in the world as shown in the media?

## Proposed additional datasets

For our research questions we will not need any additional datasets, except from the information obtained from Wikidata. More precisely, we are enriching the Quotebank dataset with additional data about the speaker - their nationality, age and political party.

## Methods

- Fasttext - The fasttext library will allow us to perform a classification and try to distinguish between the quotes that were stated by someone in a left-wing or in a right-wing political party.
- Observational study - Based on the sentiment score of every quote, we will execute an observational study. The goal is to determine if there would be a difference when we compare the sentiment scores among people with similar observed covarities. For this, we will compare groups from different regions, political parties, and age.
- Sentiment analysis - By adding the sentiment score and category to our quotes powered by the afinn library, we can conclude the statements and opinions that speakers have towards the issue of climate change.
- TextRank - We will implement this algorithm for the sake of summarizing the quotes we have about climate change. By searching for the words that appear more frequently, sentences that have those words would be marked as the key ones.
- LexRank - Another way of summarizing the information from the quotes. This time, we will observe the similarity between sentences, and the most similar ones will get picked for the summary.
- Luhn Summarizer - This algorithm has a different approach, it will leave out the low and high-frequent words as non-significant. Since 'climate change' or 'global warming' appear in every of our quotes, the algorithm will focus on the rest for the summary.

## Proposed timeline

| Deadline | Description                                                                                                                                                                                                                                                                                                  |
|----------|--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 19.11    | Deviding countries of the nationalities into regions based on geographical and social-economical aspect combined, performing additionl analysis between different regions and the popularity of the climate change topic in quotes from those regions, distinguishing between left-wing, centet and right-wing parties |
| 26.11    | Checking the results of analysis                                                                                                                                                                                                                                                                             |
| 03.12    | Analysing the first results of fasttext classification and text summarization algorithms                                                                                                                                                                                                                     |
| 10.12    | Comparing performances of summarization and classification methods                                                                                                                                                                                                                                           |
| 17.12    | Finalizing README, final comments on the code and performed analysis, finalizing the data story                                                                                                                                                                                                              |

## Organization within the team

- Jovana: Preparing the data for future work, performing the text summarization algorithms and comparing the results
- Maxence: Planning the data story and the final readme file
- Zoran: Implementing the classification using the fasttext library
- Jonatan: Primary data analysis, visualization of the key features for our problem, plotting the results

## To go further

 We can try to figure out climate change skepticism within the database through Machine Learning.

