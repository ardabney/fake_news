# fake_news

One interesting and timely problem would be to develop a model for classifying news stories as 'real' or 'fake'. We could, for example, scrape a bunch of articles from Breitbart News (http://www.breitbart.com/), and 'alt-right' news site, and CNN. We could label the Breitbart articles 'fake' and the CNN articles 'real'. We could then use a simple version of text analytics to build a classifier.

For the purposes of 489, it would be great if we could have Python code to scrape the websites for articles and store as separate SQL tables, SQL code to manage and merge the data tables, and Python code to derive some informative variables (e.g., average word length; frequency of words like 'conspiracy', 'crooked Hillary', etc.; number of exclamation points in the article). 

I wonder whether there is a resource online where articles have already been classified as 'real' vs. 'fake'. If so, that would be the place to start, rather than Breitbart vs. CNN; Breitbart, while full of lots of garbage, also links to 'real' news, so it wouldn't be a perfect source of 'fake' articles.
