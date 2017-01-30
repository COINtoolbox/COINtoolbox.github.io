<xmp theme="spacelab" style="display:none;">
  <meta name="description" content="">

<h1 class="title">COINtoolbox</h1> 
   [![DOI](https://zenodo.org/badge/7175/COINtoolbox/COINtoolbox.github.io.svg)](http://dx.doi.org/10.5281/zenodo.16376)
<img src="www/COIN.jpg", class="inline"/>

## Methodology and software for cosmology

<blockquote>
The COsmostatistics INitiative ([COIN](https://asaip.psu.edu/organizations/iaa/iaa-working-group-of-cosmostatistics/)), a working group built within the International Astrostatistics Association
([IAA](https://asaip.psu.edu/organizations/iaa/international-astrostatistics-association-overview
)), aims to create a friendly environment where hands-on collaboration between astronomers,
cosmologists, statisticians and machine learning experts can flourish. COIN is designed to
promote the development of a new family of tools for data exploration in cosmology.
</blockquote>

# *Teddy* and *Happy* photo-z catalogues <img  align="right" src="https://raw.githubusercontent.com/COINtoolbox/photoz_catalogues/master/images/coin.png" width="200"> 


This repository contains the photometric redshift catalogues presented in [Beck et al, 2016]() - *On the realistic validation of photometric redshifts, or why
Teddy will never be Happy*.

This is one of the products of the third edition of the [COIN Residence Program](http://iaacoin.wix.com/crp2016), which took place in August/2016 in Budapest (Hungary). 

Any questions/suggestions should be sent to iaa.coin@gmail.com .


A general overview of both catalogues is given bellow. Check the individual folders for detailed information on the files presented here. 

## *Teddy* 


This catalogue was designed to isolate the effect of limited spectroscopic sample coverage in colour/magnitude space.

It is constructed from the [SDSS DR12](http://www.sdss.org/dr12/) spectroscopic sample and is maintained by [Chieh-An Lin](http://linc.tw/) (CEA, France) 

## *Happy*


This catalogue was designed to reproduce the effect of distinct photometric error distributions and their convolution with colour/magnitude space coverage between the spectroscopic and photometric samples. 

All photometry was taken from [SDSS DR12](http://www.sdss.org/dr12/), and spectroscopy was gathered from a set of different sources (see  [Beck et al, 2016]() for further details). 

*Happy* is maintained by [Robert Beck](https://github.com/beckrob) (ELTE, Hungary).


 


## Approximate Bayesian Computation
[![arxiv](http://img.shields.io/badge/arXiv-1504.06129-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1504.06129)

>Approximate Bayesian Computation (ABC) enables the statistical analysis of
stochastic models for complex physical systems in cases where the true
likelihood function is unknown, unavailable, or computationally expensive.
ABC relies on the forward simulation of mock data rather than the
specification of a likelihood function.  The CosmoABC code was originally designed for cosmological parameter inference from galaxy clusters number counts based on Sunyaev-Zel’dovich measurements. 
Nevertheless, the user can easily take advantage of the ABC sampler along with his/her own simulator, as well as test personalized prior distributions, summary statistics and distance functions.

 <a href="http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:1504.06129" class="btn btn-primary">Link to ADS</a>
<a href="http://cosmoabc.readthedocs.org/en/latest/" class="btn btn-primary">Tutorial</a> 
 <a href="https://pypi.python.org/pypi/CosmoABC" class="btn btn-primary">Package</a> 
 
 ## Generalized Linear Models in Astronomy

> Statistical methods play a central role  to fully exploit astronomical catalogues and an  efficient  data analysis requires astronomers  to go beyond the traditional Gaussian-based models. This projects illustrates the power of generalized linear models (GLMs) for astronomical community,  from a Bayesian perspective.  Applications range from modelling star formation activity (logistic regression), globular cluster population (negative binomial regression), photometric redshifts (gamma regression), exoplanets multiplicity (Poisson regression), and so forth.

### Binomial Regression
[![arxiv](http://img.shields.io/badge/arXiv-1409.7696-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1409.7696)


>Suited to handle binary or proportional  data, also called absence and presence data. For example AGN activity, star-galaxy separation, fraction of bars in a galaxy, scape fraction, etc. 

 <a href="http://adsabs.harvard.edu/abs/2014arXiv1409.7696D" class="btn btn-primary">Link to ADS</a> 


### Gamma Regression
[![arxiv](http://img.shields.io/badge/arXiv-1409.7699-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1409.7699)

>Suited to handle non-negative continuous variables. Such as photometric redshifts, star formation rate, galaxy mass. The method naturally accounts for heteroskedasticity (non-constant variability). 

 <a href="http://adsabs.harvard.edu/abs/2015A%26C....10...61E" class="btn btn-primary">Link to ADS</a> 
 <a href="http://cosmophotoz.readthedocs.org/en/latest/" class="btn btn-primary">Tutorial</a> 
 <a href="http://ascl.net/1408.018" class="btn btn-primary">Package</a> 
 <a href="https://cosmostatisticsinitiative.shinyapps.io/CosmoPhotoz" class="btn btn-primary">Web App</a> 
### Negative Binomial  Regression
[![arxiv](http://img.shields.io/badge/arXiv-1409.7699-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1506.04792)

>Suited to handle non-negative discrete variables. Such as number of exoplanets, globular cluster population, richness of galaxy clusters, etc.  

 <a href="http://adsabs.harvard.edu/abs/2015MNRAS.453.1928D" class="btn btn-primary">Link to ADS</a> 

## Dimensionality Reduction And Clustering for Unsupervised Learning in Astronomy (DRACULA)
[![arxiv](http://img.shields.io/badge/arXiv-1512.06810-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1512.06810)
>DRACULA classifies objects using dimensionality reduction and clustering. The code has an easy interface and can be applied to separate several types of objects. It is based on tools developed in scikit-learn, with Deep Learning usage requiring also the H2O package.

 <a href="http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:1512.06810" class="btn btn-primary">Link to ADS</a> 
 <a href="http://ascl.net/1512.009" class="btn btn-primary">Package</a> 


## Analysis of Muldimensional Astronomical DAtasets (AMADA)
[![arxiv](http://img.shields.io/badge/arXiv-1503.07736-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1503.07736)

>AMADA allows an iterative exploration and information retrieval of high-dimensional data sets. This is done by performing a hierarchical clustering analysis for different choices of correlation matrices and by doing a principal components analysis in the original data. Additionally, AMADA provides a set of modern visualization data-mining diagnostics. The user can switch between them using the different tabs.

 <a href="http://adsabs.harvard.edu/abs/2015arXiv150307736D" class="btn btn-primary">Link to ADS</a>
 <a href="http://rafaelsdesouza.github.io/AMADA/" class="btn btn-primary">Package</a> 
 <a href="https://cosmostatisticsinitiative.shinyapps.io/AMADA/" class="btn btn-primary">Web App</a> 
 
<<<<<<< HEAD
=======
## Dimensionality Reduction And Clustering for Unsupervised Learning in Astronomy (DRACULA)
[![arxiv](http://img.shields.io/badge/arXiv-1512.06810-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1512.06810)
>DRACULA classifies objects using dimensionality reduction and clustering. The code has an easy interface and can be applied to separate several types of objects. It is based on tools developed in scikit-learn, with Deep Learning usage requiring also the H2O package.

 <a href="http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:1512.06810" class="btn btn-primary">Link to ADS</a> 
 <a href="http://ascl.net/1512.009" class="btn btn-primary">Package</a> 

## Is the cluster environment quenching the Seyfert activity in elliptical and spiral galaxies?
[![arxiv](http://img.shields.io/badge/arXiv-1512.06810-lightgrey.svg?style=plastic)](http://arxiv.org/abs/1603.06256)
>We developed a hierarchical Bayesian model (HBM) to investigate how the presence of Seyfert activity relates to their environment, herein represented by the galaxy cluster mass, M200, and the normalized cluster centric distance, r/r200. A propensity score matching approach is introduced to control for the effects of confounding variables.  The connection between Seyfert-activity and environmental properties in the de-biased sample is modelled within a Hierarchical Bayesian Model framework using the logistic regression technique.

<a href="http://adsabs.harvard.edu/cgi-bin/bib_query?arXiv:1603.06256">Link to ADS</a>
>>>>>>> origin/master

---
#### COIN Members on GitHub:
<a href="https://github.com/algolkm" class="btn btn-default">Alberto Krone-Martins</a>
<a href="https://github.com/bbuelens" class="btn btn-default">Bart Buelens</a>
<a href="https://github.com/drArli" class="btn btn-default">Arlindo Trindade</a>
<a href="https://github.com/efeigelson" class="btn btn-default">Eric Feigelson</a>
<a href="https://github.com/emilleishida" class="btn btn-default">Emille Ishida</a>
<a href="https://github.com/gieseke" class="btn btn-default">Fabian Gieseke</a>
<a href="https://github.com/hcc48" class="btn btn-default">Heather Campbell</a>
<a href="https://github.com/hocamachoc" class="btn btn-default">Hugo Camacho</a>
<a href="https://github.com/jonnybazookatone" class="btn btn-default">Jonny Elliott</a>
<a href="https://github.com/JHilbe" class="btn btn-default">Joseph  Hilbe</a>
<a href="https://github.com/DrMud" class="btn btn-default">Madhura Killedar</a>
<a href="https://github.com/mdastro" class="btn btn-default">Maria Luiza Dantas</a>
<a href="https://github.com/pennalima" class="btn btn-default">Mariana Penna-Lima</a>
<a href="https://github.com/Naminoshi" class="btn btn-default">Michel Aguena</a>
<a href="https://github.com/sasdelli" class="btn btn-default">Michele Sasdelli</a>
<a href="https://github.com/migueldvb" class="btn btn-default">Miguel de Val-Borro</a>
<a href="https://github.com/RafaelSdeSouza" class="btn btn-default">Rafael S. de Souza</a>
<a href="https://github.com/rsmiljanic" class="btn btn-default">Rodolfo Smiljanic</a>
<a href="https://github.com/vitenti" class="btn btn-default">Sandro Vitenti</a>
<a href="https://github.com/vbusti" class="btn btn-default">Vinicius C. Busti</a>
<a href="https://github.com/yabebalFantaye" class="btn btn-default">Yabebal Fantaye</a>

#### Contact: <rafael.2706@gmail.com>
</xmp>
<a href="https://github.com/COINtoolbox/COINtoolbox.github.io"><img style="position: fixed; top: 0; right: 0; border: 0; width: 149px; height: 149px; z-index: 1000; margin: 0;" src="images/right-cerulean.png" alt="Fork me on GitHub"></a>

<script src="http://strapdownjs.com/v/0.2/strapdown.js"></script>

