# remix-synth
Replicate STATA code using R: Synthetic Control

Our first attempt at translating the book's Stata code was to simply use the Synth package in r. It runs apparently well, not until we try the placebo inference, which gives the error:

*in svd(c) : infinite or missing values in 'x'*

