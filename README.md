# nightlightstats

The package allows to perform calculations on night light satellite data and build databases for any given region using the function "nightlight_calculate". Plots of the night lights in the desired area are also made very easy with "nightlight_plot". 

You can either work with yearly DMSP data ranging from 1992 to 2013 (https://www.ngdc.noaa.gov/eog/dmsp/downloadV4composites.html - Image and data processing by NOAA's National Geophysical Data Center, DMSP data collected by US Air Force Weather Agency) or monthly VIIRS data beginning in Apr 2012 (https://eogdata.mines.edu/download_dnb_composites.html - Earth Observation Group, Payne Institute for Public Policy, NOAA/NCEI). 

At the time of writing, the yearly VIIRS data is not uploaded so the package doesn't process yearly VIIRS data. Please contact the authors if you notice that this changed. You can either provide own shapefiles (region, country, etc.) or have them (in the case of countries) automatically downloaded from GADM (https://gadm.org/data.html). See the helpfiles for a detailed description of the functions and their arguments.
