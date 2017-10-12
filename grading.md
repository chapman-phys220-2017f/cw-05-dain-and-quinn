# Instructor comments

1. Nicely done. Great looking plots. Good examples for vectorization and broadcasting.
1. For the Lorentzian, "100 samples, no more no less" is not an adequate analysis, I would say. The problem is that the tails have non-negligible probability for being sampled, all the way out to infinity, so it is very difficult to get enough samples to fully map out the distribution. No matter how many samples you try, you will get some stray sample out further in the tail. One possible solution is to truncate the domain and renormalize the distribution on a smaller domain.
