Algorithms for recommender systems.

## TODO list:

* item cf (item based collaborative filtering)
    *  different similarity measurements (cosine, L2-distance, Jacard, Pearson)
    *  item popularity and freshness

* user cf
    *  user-user similarity calculation
    *  `topic constrained user cf`  (for news recommendation)
    *  `expert cf` (firstly detect domain experts, and rec items to users based on similar experts) 

* factorization machines
    *  svd++
    *  libfm

* keyword/topic based methods
    *  variable combinations of keywords, like N-gram
    *  Bayesian inference of p(topic|user) and topic popularities

* random walk
    *  transition matrix

* SNS based methods
    *  `trust cf` (user-friend relationships instead of user-user similarities in user cf)

* LBS based methods
    *  local hot reranking

* demographic based methods
    *  rec by demographic segmentation

* context-aware methods 
    *  tensor factorization
    *  sequential pattern based prediction
    *  [learning using context of user choise](http://www.eeshyang.com/papers/SIGIR11CCF.pdf)

* other methods
    *  editor's choise 
    *  rec by top list
    *  rec by commodity consumption cycle

* recommend items to items
    *  click cooccurence based methods
    *  keyword, topic based methods
    *  personalized relevance model
    *  recommend products by similar images

* recommend users to users
    *  [EdgeRank](http://edgerank.net/)
    *  [Twitter's algorithm](http://blog.csdn.net/lzt1983/article/details/8755149)

* merging
    *  `blending` (weights of algorithms, weights of items of algorithms, user feedback)
    *  `ensemble` (LR, RBM, GBM, random forest)
    *  switching (switch methods by context)
    *  cascading (multi-level model)

* evaluation
    *  offline metrics (MAP, nDCG, AUC, diversity...)
    *  online metrics (CTR, percent conversion, user active degree, long tail item exploration) 

* challenges
    *  page optimization: by explanation, by method, clustering (k-means, AP clustering, HDP)
    *  long-term interest vs. short-term action
    *  exploitation vs. exploration: multi-armed bandits 
    *  accurate vs. diverse
    *  freshness vs. stability
    *  navigation vs. attention


