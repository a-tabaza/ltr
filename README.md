# Learning to Rank Playground
This repository contains my experiments on two datasets, [KGRec: Sound and Music Recommendation with Knowledge Graphs](https://www.upf.edu/web/mtg/kgrec), methodology available in this [paper](https://dl.acm.org/doi/10.1145/2926718) (_behind a paywall, but available for free somewhere I'm sure_), and [LFM-1b](http://www.cp.jku.at/datasets/LFM-1b/), methodology available in this [paper](http://www.cp.jku.at/people/schedl/Research/Publications/pdf/schedl_icmr_2016.pdf) (_dataset is not up anymore, which implies it is accessible if there was a site that captures snapshots of sites and stores them somewhere by date_).

# What am I trying to learn?
- Train a PyTorch matrix factorization model from scratch
- Train an XGBRanker, CatBoostRanker and LGBMRanker on some notion of meaningful data for hybrid recommendation systems
- Learn how to evaluate
- Use the textual features effectively
- Use uv instead of pip for everything in this project
- _Maybe_ distributed training

# References (everything I've read so far and will read)
- [Beyond Matrix Factorization: Using hybrid features for user-business recommendations](https://engineeringblog.yelp.com/2022/04/beyond-matrix-factorization-using-hybrid-features-for-user-business-recommendations.html)
- [Learning to Rank](https://xgboost.readthedocs.io/en/stable/tutorials/learning_to_rank.html)
- [Winning The Transfer Learning Track of Yahoo!’s Learning To Rank Challenge with YetiRank](https://proceedings.mlr.press/v14/gulin11a/gulin11a.pdf)
- [Netflix Prize](https://en.wikipedia.org/wiki/Netflix_Prize)
- [Post about Netflix Prize](https://www.linkedin.com/feed/update/urn:li:activity:7187067122504687616/)
- [The BigChaos Solution to the Netflix Grand Prize](https://www.asc.ohio-state.edu/statistics/statgen/joul_aut2009/BigChaos.pdf)
- [Understanding Latent Style](https://multithreaded.stitchfix.com/blog/2018/06/28/latent-style/)
- [Core components of recommender systems](https://rezkaaufar.github.io/blog/2021/recsys-core-components/)
- [Graph Representation Learning and Its Applications: A Survey](https://www.mdpi.com/1424-8220/23/8/4168) 
