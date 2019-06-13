# AgScoresWeatherAnalytics
also goes by the name of AgScores Ensemble Debugger
                                                       
This project will produce visualisations of statistical comparisons between

 - weather observation data provided by the State of Queensland (SILO database)
    SILO © The State of Queensland 2019. The Queensland Government supports and encourages the distribution of its material. Unless    
    otherwise noted, all copyright material available on or through this website is licensed under a Creative Commons Attribution 4.0   
    International licence (CC BY 4.0). 
    https://www.longpaddock.qld.gov.au/silo/about.html

and 
 - weather forecast data from the Bureau of Meteorology (ACCESS-S forecast model)
    ACCESS-S Hudson et al, ACCESS-S1: The new Bureau of Meteorology multi-week to seasonal prediction system, 2017,   
    http://www.bom.gov.au/jshess/docs/2017/Hudson.pdf
    Operational Implementation of ACCESS-S1 Seasonal Prediction System,     
    http://www.bom.gov.au/australia/charts/bulletins/apob120_external.pdf
    
    Only one location will be used
      latitude=-35.99 & longitude=142.92, Birchip, Victoria
      https://dcdp.research.csiro.au/access-s?lat=-35.99&lon=142.92&format=csv&start=

AgScores will produce results to inform climate scientists of the efficacy of climate predictions, from the point of view of Agricultural productivity (wheat yield potential). This work enables climate scientists to debug their climate models when their predicted wheat yield potential does not match the predicted wheat yield potential of APSIM + SILO.

# File naming
## Find out what the fileshare (i.e. basefolder) is for the project (AgScore), then paths will be 
    AgScoreBasefolder/working/zin005/python/ (etc. e.g. R, data, )
    AgScoreBasefolder/working/nav00a/python (etc.)
    AgScoreBasefolder/scripts (these are the latest published version of scripts for people to use)
We adopt a mini-convention where we go for more descriptive filenames wherever possible.

# Field and variable naming
Longer, more descriptive names are better than shorter, non-descriptive names


