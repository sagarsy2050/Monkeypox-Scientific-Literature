# Monkeypox-Scientific-Literature
What is Monkeypox?
Monkeypox was first discovered in 1958 when two outbreaks of a pox-like disease occurred in colonies of monkeys kept for research, hence the name ‘monkeypox.’ The first human case of monkeypox was recorded in 1970 in the Democratic Republic of Congo followed by an outbreak in May 2022 with several cases reported in Europe, North and South America, Asia, North Africa, and Australia.

For reliable source of information about the disease, please refer to this article by the World Health Organization.

This dataset contains all available scientific knowledge published on the topic of Monkeypox scraped from Pubmed, starting from as early as 1974 to 2022, up to the abstract level.

# working Points
* Initial Dataset Check
* Use of NLP methods on Target columns to get Information
# Target NLP Column ['Title']
* Clustering on Title column, 1)-KMeans by Bag of Words(BOW)
* Title column Words in the cluster
* Grouping Titles clusters on the ['PublicationType']
* Grouping Titles clusters on the Number Citations
* KMeans by TF-IDF
* Title and DOI column clusters
* Title and PublicationType column clusters
* Title and JournalCitation column clusters
* Title and Auther column cluster
# NLP on ['Abstract'] Column
# NLP on ['Keywords'] column

