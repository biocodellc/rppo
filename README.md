
<!-- README.md is generated from README.Rmd. Please edit that file -->
rppo
====

[![Build Status](https://travis-ci.org/biocodellc/rppo.svg?branch=master)](https://travis-ci.org/biocodellc/rppo)

The global plant phenology data portal (PPO data portal) is an aggregation of plant phenological observations from [USA-NPN](https://www.usanpn.org/usa-national-phenology-network), [NEON](https://www.neonscience.org/), and [PEP725](http://www.pep725.eu/) representing 20 million phenological observations from across North America and Europe. The PPO data portal utilizes the [Plant Phenology Ontology](https://github.com/PlantPhenoOntology/ppo/) to align phenological terms and measurements from the various databases. The rppo R package enables programmatic access to all data contained in the PPO data portal.

For more information visit the [PPO global data portal](http://plantphenology.org/) or the [ppo-data-pipeline git repository](https://github.com/biocodellc/ppo-data-pipeline).

Installation
------------

The production version of rppo can be installed with (when available on CRAN):

``` r
#install.packages("rppo")  # this will work once package is available on CRAN
#library(rppo)
```

You can install the development version of rppo from github with:

``` r
install.packages("devtools")
devtools::install_github("biocodellc/rppo")
```

Install the library once it has been downloaded from CRAN or github.

``` r
library(rppo)
```

Examples
--------

Examples and instructions on using the rppo package can be found using the [rppo vignette](vignettes/rppo-vignette.md).

Citation
--------

To cite the 'rppo' R package in publications use:

       'John Deck, Brian Stucky, Ramona Walls, Kjell Bolmgren, Ellen Denny, Robert Guralnick' (2018). rppo: An interface to the Plant Phenology Ontology and associated data store.  R package version 1.0
       https://github.com/biocodellc/rppo

Code of Conduct
---------------

View our [code of conduct](CONDUCT.md)
