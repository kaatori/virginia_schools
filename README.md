# Virginia Schools

An exploration into Virginia Department of Education public data on testing scores pre- and post-pandemic with a focus on Fairfax County elementary schools and Grade 3 test scores. 

This is not meant to be an exhaustive analysis.

Author: Cassandra Sperow

I am constantly improving this repo. If you have questions, please email ks3288a@student.american.edu. 

RPubs link to the main analysis file with the leaflet map [here](https://rpubs.com/kaatori/Fairfax_county_schools)

## Data Sources: 

- [Virginia Department of Education SOL Test Results](https://www.doe.virginia.gov/statistics_reports/sol-pass-rates/index.shtml)

- [Virginia Department of Education School Listings by Name](https://www.doe.virginia.gov/directories/index.shtml)

## Packages Required: 

- tidyverse (v 1.3.1)

- leaflet (v 2.1.0)

- keyring (v 1.3.0)

- ggmap (v 3.0.0) (Important Note: ```ggmap``` requires a Google API key. More info is below.)


## APIs Required: 

- Google Goecode API

To use the ```ggmap``` library, it is required to have a Google API for using the ```geocode()``` function. Please read and review the terms of obtaining a Google Geocode API key [here](https://developers.google.com/maps/documentation/geocoding/get-api-key#:~:text=Go%20to%20the%20Google%20Maps%20Platform%20%3E%20Credentials%20page.&text=On%20the%20Credentials%20page%2C%20click,Click%20Close.)

Please also read more about how the ```ggmap``` package works with a Google API key [here](https://cran.r-project.org/web/packages/ggmap/readme/README.html). Google API keys have limits of usage unless you pay for how many requests are run in your code; therefore, use caution and keep track of how many requests your Google API key is logging through the [Google Cloud Platform](https://cloud.google.com).





Citation for use of ```ggmap``` with Google Geocode API: 

D. Kahle and H. Wickham. ggmap: Spatial
  Visualization with ggplot2. The R
  Journal, 5(1), 144-161. URL
  http://journal.r-project.org/archive/2013-1/kahle-wickham.pdf


#### Disclaimer: This GitHub repository is for exploratory and educational purposes only and should not be construed as giving legal or any other form of advice on any matter. 
