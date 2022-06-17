# FYP-Arnau-Bonet-2022

This is the repo for the FYP of Arnau Bonet Farrés: Financial News Classification Model for NLP-based Portfolio Construction.

Model testing: This code contains the model constructed from scratch and all the tests that appear in the report for the accuracy of the classification model.

Categories MW NER: This is the code to classify articles into categories and send them to their relevant folders. This code is only for Marketwatch, but the same is used for The Motley Fool and for Reuters, I just used this one as an example.

Portfolio Baseline: This is the portfolio construction algorithm that I have used. In this case, it's for the benchmark portfolio using unclassified news. For the categorised portfolios it's essentially the same but using the categorised news.

New_training_set_all_sources_postNER.csv is the file that contains the labelled set of about 2000 articles, it has articles belonging to the 3 sources, and 10 categories. It is the labelled set that I use for testing purposes.

Corpus_training_set.csv contains the articles belonging to the corpus set. The corpus set is the set containing the defining articles for each category.
