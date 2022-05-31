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



## References

Guidotti, E., Ardia, D., (2020), "COVID-19 Data Hub",
  Journal of Open Source Software 5(51):2376, doi:
  10.21105/joss.02376.
