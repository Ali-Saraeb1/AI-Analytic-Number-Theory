Cite: [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15293203.svg)](https://doi.org/10.5281/zenodo.15293203)
The second part of the paper emperically verifies a
folklore conjecture in analytic number theory stating that
“the modulus 𝑞 of a Dirichlet character 𝜒 is uniquely determined by the initial non-trivial zeros {𝜌1, . . . , 𝜌𝑘 } (for
some 𝑘 ∈ N) of the corresponding Dirirchlet L-function
𝐿(𝑠, 𝜒)” for small modulus 𝑞. We form the dataset of
zeros from LMFDB database and turn the conjecture’s
statement into a classification problem where the feature
vectors are engineered from the initial zeros and the labels
are the corresponding moduli. We train a feed-forward
neural network and a random-forest classifier, and we get
two vectors of probabilities, which we aggregate via a
meta-ensemble to predict 𝑞. The model emperically verifies the conjecture for small 𝑞 in the sense that it achieves
a perfect test accuracy of 1.0, provided that sufficient
statistical properties of the zeros are incorporated in the
training process. Based on the emperical evidence, we
propose two new conjectures
