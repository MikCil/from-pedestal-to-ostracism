# From pedestal to ostracism: a quantitative social media analysis and conceptual framework on historical memory and pedagogical implications of Cancel Culture
Code, figures and additional materials for the paper "From pedestal to ostracism: a quantitative social media analysis and conceptual framework on historical memory and pedagogical implications of Cancel Culture"

# Content
The dataset.csv file contains the entire corpus made up of 95,432 extracted tweets, with complete metadata, anonymised user data and a series of computed scores and labels.

The search_strings.txt file contains the search strings utilised to extract the desired data from Twitter.

The Network directory contains all .gexf files for the analysed cancel culture cases. Each network has an hashtag-only version, where nodes are represented by hashtag and edges by their co-occurrences in the tweet corpus, and a bipartite version, where both users and hashtags are represented as nodes.

The Figures directory contains full-scale images of all the pictures contained in the paper, including .svg visualisations of all networks.

The stance classification model can be found at: https://huggingface.co/MikCil/cancel-culture-stance-classification
