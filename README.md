# GRASS GIS Scripts — AI/ML Land-Cover Classification of Landsat around Cheetham Wetlands, Australia

GRASS GIS shell scripts used to produce the figures in the peer-reviewed article by Polina Lemenkova. The scripts classify a Landsat 8-9 OLI/TIRS time series (2013, 2015, 2017, 2024) of the coastal area around Cheetham Wetlands, Port Phillip Bay (Melbourne, Victoria, Australia), comparing four AI/ML classifiers against traditional maximum-likelihood clustering.

**Published in:** *Journal of Marine Science and Engineering* **2024**, *12*(8), 1279
**DOI:** https://doi.org/10.3390/jmse12081279
**Journal (open access):** https://www.mdpi.com/2077-1312/12/8/1279

## Contents
Shell scripts calling GRASS GIS modules for raster import (r.import), clustering and classification (i.group, i.cluster k-means, i.maxlik maximum-likelihood), rejection-probability mapping, training-sample generation (r.random) and machine-learning classification (r.learn.train, r.learn.predict) with Random Forest (RF), Support Vector Machine (SVM), Multilayer Perceptron / ANN (MLP) and Decision Tree (DTC) classifiers from Python's Scikit-Learn library. One script and one cluster report per year (2013, 2015, 2017, 2024).

## LaTeX source
The LaTeX source (prose) of this article is in a separate repository: https://github.com/paulinelemenkova/ml-land-cover-australia

## Citation
Lemenkova, P. Artificial Intelligence for Computational Remote Sensing: Quantifying Patterns of Land Cover Types around Cheetham Wetlands, Port Phillip Bay, Australia. *Journal of Marine Science and Engineering* **2024**, *12*(8), 1279. https://doi.org/10.3390/jmse12081279
