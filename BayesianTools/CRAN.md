This file contains CRAN submission info / communication

## Version 0.1.8

### Submission 1

This is minor update should re-instate BT to CRAN, after it was removed due to HTML validation problems connected to the recent switch to HTML5 for documentation pages in R 4.2.0, see also https://github.com/florianhartig/BayesianTools/issues/240. 

I had tried to upload a fix to CRAN, which, however, was not accepted due to detritus problems under Windows dev, which, after a long search, turned up to be caused by some stray parallel notes https://github.com/florianhartig/BayesianTools/issues/244

In any case, I hope this will re-instate the BT package to CRAN, sorry for the delay in fixing this. 

See NEWS for other changes.

This release was tested without apparent problems under

* local MAC OS 13.1, R 4.2.1 Apple
* http://win-builder.r-project.org/ - oldrelease / devel / release
* Github Actions https://github.com/florianhartig/BayesianTools/actions Windows: [release / devel], Mac [release], Ubuntu 20.04 [release / devel]

## Version 0.1.7

### Submission 1

This is minor update that was necessary because of a change to behavior of class(matrix) in CRAN devel, see https://github.com/florianhartig/BayesianTools/issues/191. See NEWS for changes.

This release was tested without apparent problems under

* local MAC OS 10.14.6 (Mojave), R 3.6.1
* http://win-builder.r-project.org/ - oldrelease / devel / release
* Linux (Travis CI) - oldrel / release / devel

## Version 0.1.6

### Submission 1

This is minor update, adding a few new functionalities and a few bugfixes (see NEWS).

This release was tested without apparent problems under

* local MAC OS 10.14.1 (Mojave), R 3.5.1
* http://win-builder.r-project.org/ - oldrelease / devel / release
* Linux (Travis CI) - oldrel / release / devel


## Version 0.1.5


### Submission 2

This update of the BayesianTools package contains a number of improvements and bugfixes. See NEWS for changes. 

CRAN MESSAGE: Please reduce runtime, e.g. by unning less important tests onyl conditional if some environment variable is set that you only define on your machine? 

--> I have added a skip_on_CRAN to most tests - I hope this fixes the incoming issue with the time for the tests 

This release was tested without apparent problems under

* local MAC OS 10.13.4 (17E199), R 3.5.0
* http://win-builder.r-project.org/ - oldrelease / devel / realease
* Linux (Travis CI) - oldrel / release / devel

### S1

This update of the BayesianTools package contains a number of improvements and bugfixes. See NEWS for changes. 

This release was tested without apparent problems under

* local MAC OS 10.13.4 (17E199), R 3.5.0
* http://win-builder.r-project.org/ - oldrelease / devel / realease
* Linux (Travis CI) - oldrel / release / devel


## Version 0.1.4

A bunch of smaller updates to the package. 

Tested under Mac (3.3.2), http://win-builder.r-project.org/ (oldrel / release / devel) and Travis CI  (oldrel / release / devel) without apparent problems.

## Version 0.1.3



## Version 0.1.2

### Submission 1

A bugfix release, fixing a few smaller inconsistencies in the user interface and class behavior

Tested under Mac (3.3.2), http://win-builder.r-project.org/ (oldrel / release / devel) and Travis CI  (oldrel / release / devel) without apparent problems.

## Version 0.1.1

### Submission 1

Mostly a bugfix release

Tested under Mac (3.3.2), http://win-builder.r-project.org/ (oldrel / release / devel) and Travis CI  (oldrel / release / devel) without apparent problems.

### Submission 2

This is release introduces a few smaller fixes and improvements. A previous upload of this release was rejected due to the new dynload policies in R 3.4, see https://github.com/florianhartig/BayesianTools/issues/31. This is now fixed. 

The package was tested under Mac (3.3.2), http://win-builder.r-project.org/ (oldrel / release / devel) and Travis CI  (oldrel / release / devel) without apparent problems.

## Version 0.1.0

### Submission 2


This is a new (re)submission. 

I have removed the non-standard folder and added details on samplers as requested

* local R version 3.3.2 (2016-10-31), Platform: x86_64-apple-darwin13.4.0 (64-bit), Running under: macOS Sierra 10.12.2
* http://win-builder.r-project.org/
 * with R-release / R-devel
* Travis CI, under standard settings for
 * oldrel / release / devel
 * See https://travis-ci.org/florianhartig/BayesianTools

### Submission 1

This is a new submission. 

The R package 'BayesianTools' contains various general-purpose MCMC and SMC samplers, plots and diagnostics for Bayesian analysis, with a particular focus on calibrating complex system models.

### Tested without problems under

* local R version 3.3.2 (2016-10-31), Platform: x86_64-apple-darwin13.4.0 (64-bit), Running under: macOS Sierra 10.12.2
* http://win-builder.r-project.org/
 * with R-release / R-devel
* Travis CI, under standard settings for
 * oldrel / release / devel
 * See https://travis-ci.org/florianhartig/BayesianTools
 
 ///
 
 Thanks,
please omit the redudnant "The R package 'BayesianTools'" and just start "Contains ...". Please try to elaborate a bit more about the samples etc.

We also see:

* checking top-level files ... NOTE
Non-standard file/directory found at top level:
  'util'

Please fix and resubmit.

Best,
Uwe Ligges


