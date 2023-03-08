# ROADMAP
### Self Deriving Linear Regression from Exponential Family and GLM Assumptions
- Trying to use the more generalized form of the exponential family, to arrive at Linear Regression
- stuck/it's taking too much time for me to derive the formula necessary for me to get my hypothesis function 

### Creating my own Generalized Linear Model
- With above figured out, will be able to fib with parameters to create a model more tailored to my dataset

### Adding Features synthesized from dataset
- Feature 1: Adding Average rating of businesses
- Extracting more features from reviews of businesses (10 more features)
  - First technique: collecting normalized unigram and bigram of good and bad words [Source](https://ieeexplore.ieee.org/document/9213704)
    - Feature 2: count of bad words in reviews for business
    - Feature 3: count of good words in reviews for business
    - Feature 4 - 7: count of predetermined positive noun + adjective pairings in the following buckets (environment, location, service, tast)
    - Feature 8 - 11: same as above bug negative
  - Second technique: conduct structure and senitment analysis on each sentence of review [Source](https://people.cs.rutgers.edu/~amelie/papers/2009/WebDB2009.pdf)

### More Feature Engineering Experiments
- Take the first $n$ principal components of the attribute features and append to that the top $m$ principal components of review features


