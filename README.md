# BubbleOrWave2

These notebooks document my experiments with data mining using MongoDB's aggregation framework, Pandas, and SciKit Learn.

The dataset is a collection of over 4000 tweets responding to the Wet'suwet'en crisis and is available by request. The scripts I used to retrieve and store the tweets can be found at https://github.com/clearthecity/BubbleOrWave.

Submitted for COMP4610, April 2020.


### Notebooks

  + **AggregateAndBucketFavoriteCounts:** check distribution of favo(u)rite counts; extract most fields to `aggregation.csv`.
  + **ClusterTextBigrams**: attempt to cluster the tweets using word frequency analysis (Tf-Idf) and k-means
  + **ClusterText**: similar, this time assessing the robustness of the clusters with silhouette scores
  + **UserDescriptions**: attempt to cluster user descriptions
  + **TopicModels**: attempt to make topic models of the tweets using Latent Dirichlet Allocation
  + **QuoteTweets_Grouping**: Extract all unique users to `users.json`. See which users are most frequently quote-tweeted. Extract quote-tweet information for visualization in a network graph (`quote_links.json`).

### Visualizations, etc.

  + D3.js network graph of quote-tweet connections: https://observablehq.com/@clearthecity/quote-tweet-network
