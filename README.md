# RR project 2022 - COVID19 in the EU

Authors: Arkadiusz Koszyk, Wojciech Konarzewski

## Project description

Our project allows to generate a report containing basic information about **Covid-19** pandemic in the European Union. A report can be generated for one selected country or for the entire EU. 

Project is based mostly on [COVID19](https://cran.r-project.org/web/packages/COVID19/COVID19.pdf) R package which provides very basic data regarding Covid-19 pandemic, such as inter alia number of tests, number of vaccines and number of deaths.

## How to generate a report?

1. Install required packages

Open RStudio and run ```installer.R``` script (open the file and press **Ctrl+Shift+Enter**).

2. Knit the report

Open ```covid_dashboard.Rmd``` file and use **Knit with parameters** option.

3. Select parameters

Select the desired parameters or leave the default ones and press **Knit**.
Your report will be generated as an **html** file.

## Software used

**RStudio**

- RStudio 2021.09.1+372 "Ghost Orchid" Release (99999999999999999999999999999999, 2021-11-08) for Windows
Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.8 Chrome/69.0.3497.128 Safari/537.36

- RStudio 2021.09.1+372 "Ghost Orchid" Release (8b9ced188245155642d024aa3630363df611088a, 2021-11-08) for macOS
Mozilla/5.0 (Macintosh; Intel Mac OS X 12_1_0) AppleWebKit/537.36 (KHTML, like Gecko) QtWebEngine/5.12.10 Chrome/69.0.3497.128 Safari/537.36

**R packages**

- [COVID19](https://covid19datahub.io/) version 3.0.2
- [dplyr](https://dplyr.tidyverse.org/) version 1.0.9
- [ggplot2](https://ggplot2.tidyverse.org/) version 3.3.6
- [sqldf](https://github.com/ggrothendieck/sqldf) version 0.4-11
- [scales](https://scales.r-lib.org/) version 1.2.0
- [tidyverse](https://tidyverse.tidyverse.org/) version 1.3.1
- [sf](https://r-spatial.github.io/sf/) version 1.0-7
- [rnaturalearth](https://github.com/ropensci/rnaturalearth) version 0.1.0
- [rnaturalearthdata](https://github.com/ropensci/rnaturalearthdata) version 0.1.0
- [rmarkdown](https://github.com/rstudio/rmarkdown) version 2.11

## References

Guidotti, E., Ardia, D., (2020), "COVID-19 Data Hub",
  Journal of Open Source Software 5(51):2376, doi:
  10.21105/joss.02376.
