This presentation will examine the tools, approaches, collaboration, and findings of the Web Archives for Historical Research Group around the capture and analysis of about 3M tweets during the 2015 Canadian Federal Election.  We hope that national libraries and other institutions will find our model useful as they consider how to archive ongoing events using Twitter. 

While Twitter is not a representative sample of broader society - Pew Research notes that it skews young, college-educated, and affluent (above $50,000 household income) – Twitter still represents an exponential increase in the amount of information generated, retained, and preserved from non-elite people. Therefore, when historians study the 2015 federal election, Twitter will be a prime source.

On August 3, 2015, the team initiated both a search API and stream API collection with twarc using the hashtag #elxn42. Data collection ceased on November 5, 2015, the day after Justin Trudeau was sworn in as the 42nd Prime Minister of Canada. We collected for a total of 102 days, 13 hours and 50 minutes.

To analyze the data set, we took advantage of a number of utilities that are available within twarc and twarc-report, as well as jq, Mathematica, and Apache Spark Notebook. In accordance with the Twitter ToS, we also hosted the tweet IDs in an institutional repository.

Our analytics included:

- running Jaccard similarity/dissimilarity comparisons on different sub-hashtags (the Conservative vs Liberal parties, for example);
- breaking tweet text down by day to track change over time;
- client analysis, allowing us to see how the scale of mobile devices affected medium interactions;
- URL analysis, comparing both to Archive-It collections and the Wayback Availabilty API to add to our understanding of crawl completeness;
- and image analysis, using an archive of extracted images.

Our presentation introduces our collecting work, the analysis we have done, and provides a framework for other collecting institutions to do similar work with our off-the-shelf open-source tools.
