# Real-Time-Transcript-Analysis
Web Scraping:
Web Scraping of a HTML web page to scrape the transacripts of all the comedians from "Scraps From The Loft".

Cleaning Data: 
It involves removal of punctuations, making text lower case, removal of numerical values, remove numerical values, remove common non-sensical text (/n), Tokenize text and Remove stop words.

Explore Data: 
Found out the most common words used by some specific comedian, generated word clouds, figured out the number of unique words, figured out the bad words used.

Sentiment Analysis :
Each word in a corpus is labeled in terms of polarity and subjectivity. A corpus sentiment is the average of these.
Polarity: How positive or negative a word is. -1 is very negative. +1 is very positive.
Subjectivity: How subjective, or opinionated a word is. 0 is fact. +1 is very much an opinion.

Topic Modelling:
Each document in the corpus will be made up of at least one topic, if not multiple topics. In this project, I covered Latent Dirichlet Allocation (LDA), which is one of many topic modeling techniques. It was specifically designed for text data. Result is a vector for each transcript that indicates probabilities for the presence of different topics.

Text Generation:
Used Markov chains for text generation. Think about every word in a corpus as a state. We can make a simple assumption that the next word is only dependent on the previous word - which is the basic assumption of a Markov chain.

Predict IMDb rating: 
Use the LDA vector along with a handmade binary target feature 'rating_type' (1 for above average and 0 for below average IMDb rating) to train an ensemble classifier.

The script will work to grab as many transcripts as are available at runtime.
