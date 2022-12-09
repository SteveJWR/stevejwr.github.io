---
layout: default
---

I am a PhD candidate in the Department of Statistics at the University of Washington.  I have been fortunate to be advised by Professors [Yen-Chi Chen](http://faculty.washington.edu/yenchic/), and [Tyler McCormick](https://thmccormick.github.io/) as well as collaborate with [Kwun Chuen Gary Chan](http://faculty.washington.edu/kcgchan/).  Previously I recieved my MS in Statistics at the University of Toronto and BSc in Mathematical Physics at Queen's University. 

## Research 

My research is motivated by the applications and theory of latent variable models, particularly with applications to statistical network analysis and neurodegenerative disease research.  My theoretical interest lie in understanding the limits of deconvolution and identification of geometric properties of latent variable models.  Recently, I have also been interested in causality under interference. 

### Estimating Curvature of Latent Variable Models 
Models of Network formation often rely on assumptions that connections are drawn according to some model where nodes have positions on a latent space, and edge probabilities vary as the distances on the space. 

[Paper](https://arxiv.org/abs/2211.11673), [code](https://github.com/SteveJWR/lolaR)

### Nonparametric Data Harmonization 
In neuropsychological research collections of tests are used in order to measure particular cognitive traits.  Over the versions of tests may be changed, leading to challenges in longitudinal analysis over prolonged time periods.  We present a model for outcome imputation we refer to as DNoise which posits a nonparametric latent distribution and converts the scores via matching the quantiles of the corresponding measurements.  This allows a user to impute the missing outcomes on the desired scale, and allows for longer term study of cognitive decline. 

[Paper](https://arxiv.org/abs/2110.06077), [code](https://github.com/SteveJWR/Data-Harmonization-Nonparametric)

### Rate Optimal Deconvolution of the Semiparametric Rasch Model and High Dimensional Goodness-of-Fit Tests
We consider the semiparametric Rasch model, the canonical nonparametric item response theory model. This involves a random latent variable draws under the following model. 

$$\theta_i \in \mathbb{R}, \beta_j \in \mathbb{R} $$

$$ \theta_i \sim G$$ 

$$ P(Y_{ij} = 1|\theta_i, \beta_j) = (1 + \exp(-(\theta_i - \beta_j)))^{-1} $$

where $Y_{ij} \in \{0,1\}$ denotes the event of individual $i$ answering question $j$ correctly.  We consider the problem of optimally estimating $G$ under no distributional assumptions and show that minimax optimality is achieved for the nonparametric maximum likelihood estimator. 

Paper \(Preprint forthcoming\)


## Teaching
I have been a teaching assistant for the following courses.  
### University of Washington
*   STAT 535 Foundations of Statistical Machine Learning
*   STAT 311 Elements of Statistical Methods
*   STAT 340/342 Introduction to Probability and Mathematical Statistics I/III 

### University of Toronto 
*   STAT 220 The Practice of Statistics I
*   STAT 257 Probability, Statistics and Data Analysis I
*   STAT 261 Probability, Statistics and Data Analysis II 
*   STAT 305 Design and Analysis of Experiments





