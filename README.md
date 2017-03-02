# R for Stata Users
## An R Tutorial for Stata Users

## Introduction
If you look through the applied economics journals that require data and code sharing, you'll find that the majority of work is done in Stata. But maybe R is on the rise. It is free, after all.

Thanks to [Bob Muenchen](http://r4stats.com/) and [John Ricco](http://johnricco.github.io/2016/06/14/stata-dplyr/). You may also find this [translation](https://github.com/vikjam/mostly-harmless-replication) of Mostly Harmless Econometrics into a few languages useful.  [Oscar Torres-Reyna](http://www.princeton.edu/~otorres/RStata.pdf)'s slides are great, too.

## List of Commands

### Data Cleaning
* use (load data)
* drop
* keep 
* drop if
* keep if
* gen
* replace
* rename
* sort
* egen
* foreach 

### Reshaping
* append
* merge
* reshape
* collapse

### Regressions
* regress y x
* outreg/estout
* regress y x, robust
* ivreg y x (z), 2sls
* xi: reg y x i.z / areg y x, absorb(z) / xtreg y x, fe
* regress y x, cluster (z)

### Plotting
There are too many
* scatter
* histogram
* choropleth
