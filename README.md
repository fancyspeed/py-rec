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

* random walk
    *  transition matrix

* factorization machines
    *  svd
    *  svd++

* keyword/topic based methods
    *  variable combinations of keywords, like N-gram
    *  Bayesian inference of p(topic|user) and topic popularities

* SNS based methods

    *  friend cf (user-friend relationships instead of user-user similarities in user cf)

* LBS based methods

* recommend users to users
    *  [EdgeRank](http://edgerank.net/)
    *  [Twitter's algorithm](http://blog.csdn.net/lzt1983/article/details/8755149)

* merging
    *  blending (weights of algorithms, weights of items of algorithms, user feedback)
    *  ensemble methods (LR, RBM, tree based methods)

* evaluation
    *  metrics (MAP, NDCG, ab-testing...)
    *  how to define asuccessful recommendation system? (CTR, percent conversion, user active degree, long tail item exploration) 


## Preferences:

* http://infolab.stanford.edu/~ullman/mmds/ch9.pdf
* http://ijcai13.org/files/tutorial_slides/td3.pdf
* https://www.coursera.org/course/recsys
* http://blog.csdn.net/lzt1983/article/details/7696578
* http://blog.csdn.net/lzt1983/article/details/7914536
* http://blog.csdn.net/bornhe/article/details/7425609
