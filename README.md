**The Coronavirus Dashboard: The case of Mexico**

This Coronavirus dashboard: The Case of Mexico provides an overview of the 2019 Novel Coronavirus COVID-19 (2019-nCoV) epidemic for Mexico. This dashboard is built with R using the R Makrdown framework and was adapted from these 
[dashboard](https://www.antoinesoetewey.com/files/coronavirus-dashboard.html) by Antoine Soetewey and [dashboard](https://ramikrispin.github.io/coronavirus_dashboard/) by Rami Krispin.

**Code**

The code behind this dashboard is available on [GitHub](https://github.com/josephignace/coronavirus_dashboard).

**Data**

The input data for this dashboard is the dataset available from the [`{coronavirus}`](https://github.com/RamiKrispin/coronavirus) R package. Make sure to download the development version of the package to have the latest data:

```
install.packages("devtools")
devtools::install_github("RamiKrispin/coronavirus")
```

The data and dashboard are refreshed on a daily basis.

The raw data is pulled from the Johns Hopkins University Center for Systems Science and Engineering (JHU CCSE) Coronavirus [repository](https://github.com/RamiKrispin/coronavirus-csv).

**Information**

More information about this dashboard can be found in this [article](https://www.statsandr.com/blog/how-to-create-a-simple-coronavirus-dashboard-specific-to-your-country-in-r/).

**Update**

The data is as of `r format(max(coronavirus$date), "%A %B %d, %Y")` and the dashboard has been updated on `r format(Sys.time(), "%A %B %d, %Y")`.



