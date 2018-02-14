# A map to software for different communities

An entry point for users from particular domains to sets of repositories and information of interest.

## Water Forecasting

Information on how to set up water forecasting packages (R or Python) is available at [a streamflow forecasting onboarding guide](https://github.com/jmp75/streamflow-forecasting-tools-onboard). As of 2018-02 this refers to software that is not open source (yet). An R package has been added to [read/write ensemble forecast time series](https://github.com/jmp75/efts).

The packages refered to in the onboarding guide depend on some generic components, some of them are publicly available. The audience for these is probably more for software engineers, or modellers well versed in software. 
* C++ source code for [model calibration](https://github.com/jmp75/wila)
* A key capability of these water forecasting tools is the availability from higher level languages. Handling data conversions is done using ["Interop Commons"](https://github.com/jmp75/rcpp-interop-commons), a [cross-module memory management system](https://github.com/jmp75/moirai), and [tools to generate 'glue' code](https://github.com/jmp75/rcpp-wrapper-generation) 

