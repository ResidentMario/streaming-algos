# streaming-algos

These handful of notebooks implement three different quantile estimation algorithms. These algorithms are meant to be used to accurately estimate quantiles in large streaming data whilst using fewer computational and memory resources than simple histograms.

References:

* GK --- https://stevenengelhardt.com/2018/03/07/calculating-percentiles-on-streaming-data-part-2-notes-on-implementing-greenwald-khanna/
* Q-digest --- https://graphics.stanford.edu/courses/cs468-05-winter/Papers/Information_Aggregation/Suri_sensys04.pdf
* T-digest --- file:///Users/alex/Downloads/histo.pdf

TODOs:
- [ ] Implement forward decay (http://dimacs.rutgers.edu/~graham/pubs/papers/fwddecay.pdf)
- [ ] Browse through and implement more things from https://gist.github.com/debasishg/8172796
