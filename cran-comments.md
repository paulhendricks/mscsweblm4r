I have read and agree to the CRAN policies at
http://cran.r-project.org/web/packages/policies.html

## R CMD check test environments
* local Windows 10 install, R version 3.3.0 (2016-05-03)
* on travis-ci: ubuntu (R:release and R:devel)
* on travis-ci: osx (R:release and R:devel)
* on win-builder: (R-devel and R-release)

## R CMD check test results on all environments but win-builder
R CMD check results
0 errors | 0 warnings | 0 notes

## R CMD check test results on win-builder
R CMD check results
0 errors | 0 warnings | 1 note

* checking CRAN incoming feasibility ... NOTE
Maintainer: 'Phil Ferriere <pferriere@hotmail.com>'

Per [this comment on SO](http://stackoverflow.com/a/23831508), it appears safe to ignore this note.

This is a re-submission to address Kurt Hornik's 2 requests re: our original submission:

1/ In DESCRIPTION, we replaced "Maintainer: MSCS4R Maintainer <mscs4rmaintainer@gmail.com>" with "Maintainer: Phil Ferriere <pferriere@hotmail.com>"

2/ In DESCRIPTION, we replaced the unquoted, possibly mispelled word "mscsweblm" with "this package"

Regards,
Phil Ferriere <pferriere@hotmail.com>