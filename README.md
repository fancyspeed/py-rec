Algorithms for recommender systems.

It's a long term work.

## TODO list:

* item cf (item based collaborative filtering)
    *  different similarity measurements (cosine, L2-distance, Jacard, Pearson)
    *  item popularity and freshness

* user cf
    *  user-user similarity calculation
    *  `topic constrained user cf`  (for news recommendation)
    *  `expert cf` (firstly detect domain experts, and rec items to users based on similar experts) 

* factorization machines
    *  svd
    *  svd++

* keyword/topic based methods
    *  variable combinations of keywords, like N-gram
    *  Bayesian inference of p(topic|user) and topic popularities

* random walk
    *  transition matrix

* SNS based methods
    *  `friend cf` (user-friend relationships instead of user-user similarities in user cf)

* LBS based methods
    *  local hot

* demographic based methods
    *  demographic prediction
    *  demographic segmentation and segment cf

* context-aware recommendation 
    *  tensor factorization
    *  sequential pattern based prediction
    *  [learning using context of user choise](http://www.eeshyang.com/papers/SIGIR11CCF.pdf)

* recommend items to items
    *  item cf
    *  keyword, topic based methods
    *  personalized relevance model

* recommend users to users
    *  [EdgeRank](http://edgerank.net/)
    *  [Twitter's algorithm](http://blog.csdn.net/lzt1983/article/details/8755149)

* merging
    *  `blending` (weights of algorithms, weights of items of algorithms, user feedback)
    *  `ensemble` methods (LR, RBM, tree based methods)
    *  switching
    *  multi-level model

* challenges
    *  page optimization: by explantion, by method, clustering (k-means, AP clustering, HDP)
    *  long-term interest vs. short-term action
    *  exploitation vs. exploration: multi-armed bandits 
    *  accurate vs. diverse
    *  freshness vs. stability
    *  navigation vs. attention

* evaluation
    *  offline metrics (MAP, NDCG, AUC, diversity...)
    *  online metrics (CTR, percent conversion, user active degree, long tail item exploration) 


## Preferences:

* http://infolab.stanford.edu/~ullman/mmds/ch9.pdf
* http://ijcai13.org/files/tutorial_slides/td3.pdf
* https://www.coursera.org/course/recsys
* http://blog.csdn.net/lzt1983/article/details/7696578
* http://blog.csdn.net/lzt1983/article/details/7914536
* http://blog.csdn.net/bornhe/article/details/7425609
