# Super Jupyter

My personal `jupyter`. This dockerized `jupyter` supports `Scala` notebooks by both Toree and Spylon modes, `R`, `Python 3` with `Tensorflow`, and `PHP`. 

# Usage

Run by `docker run --name super-ipynb -p 8888:8888  -d abbychau/super-jupyter`

Get token by `docker logs super-ipynb`

# Sample notebooks
Sample notebooks are placed in `notebook-sample`. They are copied inside home directories.