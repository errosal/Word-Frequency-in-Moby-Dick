# Word-Frequency-in-Moby-Dick

What are the most frequent words in Herman Melville's novel Moby Dick, and how often do they occur?

Note that the HTML file you are asked to request is a cashed version of this file from Project Gutenberg.

Your project will follow these steps:

The first step will be to request the Moby Dick HTML file using requests and encoding it to utf-8. 

Here is the URL to scrape from: https://s3.amazonaws.com/assets.datacamp.com/production/project_147/datasets/2701-h.htm

Next, you'll extract the HTML and create a BeautifulSoup object using an HTML parser to get the text.
Following that, you'll initialize a regex tokenizer object tokenizer using nltk.tokenize.RegexpTokenizer to keep only alphanumeric text, assigning the results to tokens.
You'll transform the tokens into lowercase, removing English stop words, and saving the results to words_no_stop.
Finally, you'll initialize a Counter object and find the ten most common words, saving the result to top_ten and printing to see what they are.