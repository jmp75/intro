# A map to software for different communities

An entry point for users from particular domains to sets of repositories and information of interest.

## Ensemble Streamflow Forecasting

Information on how to set up water forecasting packages (R or Python) is available at [a streamflow forecasting onboarding guide](https://github.com/jmp75/streamflow-forecasting-tools-onboard). The core modelling code is not yet available via github, but there is an intent to make it available as a community modelling platform. Some packages and libraries are already open source:  

* An R package to [read/write ensemble forecast time series](https://github.com/jmp75/efts), [available on CRAN](https://cran.csiro.au/web/packages/efts/index.html)
* The R packages refered to in the onboarding guide depend on some generic components, and some of them are publicly available. The audience for these is probably more for software engineers, or modellers well versed in software. 
  * C++ source code for [model calibration](https://github.com/jmp75/wila)
  * A key capability of these water forecasting tools is the availability from higher level languages. Handling data conversions is done using ["Interop Commons"](https://github.com/jmp75/rcpp-interop-commons), a [cross-module memory management system](https://github.com/jmp75/moirai), and [tools to generate 'glue' code](https://github.com/jmp75/rcpp-wrapper-generation) 

