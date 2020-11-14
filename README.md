# TM_Twitter_McConnell-McGrath
Text Mining Twitter pull with Tweepy

## Notes
The Mitch McConnell txt file is too large to add the the repo but the Amy McGrath file is added as reference.

There are three Python files in this repo. 
1 - "MA_McConnell & McGrath" is the code to pull the data from Twitter. 
2 - "Analyzing the Twitter Data" looks at basic statistics of the text files like number of tokens and lexical diversity.
3 - "Analyzing the Twitter Data Part 2" expands on the descriptive statistics to look at the top words found in the Twitter descriptions for each candidate. It looks at the top 1,000 words as well as just the unique top words between the candidates. Next, I created wordclouds from the unique words based on their frequency. 

The Word document "Text Mining A&A" is a write-up of the descriptive statitsics, top words, and images of the word clouds.

## Feedback

This looks good. Nice write-up, consider this **complete**.

The analysis notebook isn't really a "finished product", though that's okay for something that has a formal write-up. Some issues
include lots of printing
to the screen, some cells that seem like they could be cut/edited, and lines like this: `!pip install wordcloud`. On that latter, 
much more stable to install at the command line than run these pass through commands. 

The comparing groups and word cloud are solid starts, but it'd be worthwhile to think about ways in which you might 
extend the analysis to "more analytical" techniques like NB or LDA. 


