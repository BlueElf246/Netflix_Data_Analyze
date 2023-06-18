# Netflix_Data_Analyze
In this repo, I will split into two part, the first one is about cleaning the dataset, which including reformating, handling outliers, nan values, change datatypes, ... Then I will EDA the dataset, which including visualize the trend, the pattern, all the thing about exploratory analysis. Then I will perform Diagnostic analysis, which dicuss about why it has the trend like this or why the number of film droped in 2019 
You can see it in my netflix_v1 notebook, which also explain under the graph.

For this 1st part, I will use R language to EDA, then for model building and feature selection, I will use Python since it has many libraries that provide  model building.

In the second part, I will build recommender system base on k_mean wil larget number of cluster with encoding to recommend some movie. The result will be movies that belong to cluster that has given movie. Next I will do some clustering analysis on description column. In this part, I will use TF_IDF and some preprocessing techniques to clean the text and turn into vector. Then I will reduce dimensionality with PCA and choose best n_cluster with knuckle technique and silhouette score. With the best number of feature is 4000 and number of cluster is 4. Then I analyzied and concluded some interting face about each cluster. For example, Documentary film is commonly making about the life of celebrity in music and sport, the format could be showing footage or interview, I can see other cluster analysis on my notebook


