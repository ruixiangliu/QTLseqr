# QTLseqr 0.6.2
## Bug fixes
* Added responsive x axis brakes. Axis brake labels were getting squashed on small chromosomes.

# QTLseqr 0.6.1
## Updates
* added `plotSimulatedThresholds` function to help users visuallize their confisence intervals
* some manual corrections and mods

# QTLseqr 0.6.0
## Updates
* Added QTLseq analysis functionality
* `plotQTLStats` can now plot confidence intervals in $\Delta (SNP\text{-}index)$ plots
* Export functions run faster and allow for detection of QTL in either "Gprime" or "QTLseq" methods
* removed Bioconductor dependency

# QTLseqr 0.5.8
## Updates
* changed $\Delta SNP\text{-}index$ to $\Delta (SNP\text{-}index)$

# QTLseqr 0.5.7
## Updates
* `plotQTLStats` now allows for chromosome facet shape scaling using the 'scaleChroms' parameter

# QTLseqr 0.5.6
## Bug fixes
* Added package `locfit` to Imports. 

# QTLseqr 0.5.5
## Updates
* `plotGprimeDist` null distribution label more accurate.

# QTLseqr 0.5.4

## Updates
* `plotGprimeDist` now plots histograms of filtered and raw data. overlaid with the null dist. Is easier to interpret. 

# QTLseqr 0.5.3

## New features

* Added a `NEWS.md` file to track changes to the package.
* in `plotGprimeDist` plotting now includes density plots of all data, data after QTL filtering and the null-distribution assuming mean and variance of the filtered set.

## Bug fixes
* Corrected a bug in `getFDRThreshold` function that was using regular p-values and not adjusted pvalues to define threshold
