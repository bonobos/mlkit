# ML Kit: a wrapper around scikit-learn
## Getting Started

* `make test`

* `make install`


## The idea:
ML-kit is a simple wrapper around scikit-learn and related libraries to simplify my job and hopefully reduce the boilerplate code in a typical ML project. The library includes a selection of Supervised and Unsupervisd models that I found useful/explored in the past.

## The pipeline:
MLkit extends the idea of PIPE operator explored in scikit-learn. The library allows to create a chain of trasformations (data in => data out) and models (data in => model out). Models can be combined in stacks and ensembles.

## Tests:
Testing is still a work in progress, coverage is only 34%. Tox expects python 3.6 installed on your laptop. If that is not the case, you can edit tox.ini by changing the testing environment (unless you want to download py36 binaries).
