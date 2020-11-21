For Project 1, we started out our project being very broad, but narrowed it down in the process of searching for usable data. 

We sought to visualize the change in life expectancy per (LE) U.S. county based on a dataset retrieved from The Institute for Health Metrics and Evaluation (IHME), a research center at the University of Washington Medical School. We then compared this to a record of rural hospital closures, as collected by the Sheps Center for Health Services Research at the University of North Carolina. These datasets spanned the following years:

    IHME: 1980 - 2014
    UNC: 2005 - 2020

We wanted to see if, by visualizing the data over time, we would be able to pick up on any qualitative changes in LE where rural hospital closures occured. We accomplished this by importing GeoPandas for the creation of our choropleth maps, which took in the ds. One extra step was needed to convert the zip codes used in the UNC ds to the Federal Information Processing Standards (FIPS) county codes used in the IHME ds. 

We hypothesized that we would be able to see a decrease in LE, but this turned out not to be the case. A few of the possible reasons for this could have been A) the hospital was defunct - could not accommodate modernized practices or equipment - and the establishment of a newer facility elsewhere in the county was better able to meet the medical needs of the area, B) demographic changes: that the aging of rural communities somehow affected this, C) for an actual effect to be seen, it would take longer than the number of years we had available. Or there simply was no effect. 