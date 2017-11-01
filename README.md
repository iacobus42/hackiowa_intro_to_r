# Overview
This repo contains the handout and practice data for the first of two R
workshops for HackIowa at the University of Iowa. 

## Data
The data dir contains csv versions of the data provided by the R package `nycflights13`. 
There are 5 files that describe the flights from NYC area airports. The files are

* `flights.csv` - information about the flights, start/end times, dest and origin airports
* `weather.csv` - hourly weather observations at each of the airports
* `airports.csv` - information about the dest airports
* `planes.csv` - information by tail number for the planes that made the flights in `flights.csv`
* `carriers.csv` - more detail about the carrier based on the 2-letter carrier code

## Handout
The `.Rmd` file is a R markdown file. This is a markdown file with embedded R code. We
will use a tool called `knitr` to work this file inside R. It is similar to a Python 
notebook, if that is familar.

The `.HTML` file is the "knitted" version of the R markdown file. 

# References
The contents of the notes, examples and exercies were inspired/adapted from 
the book [R for Data Science](http://r4ds.had.co.nz/), which is free to read online
and a wonderful resource for learning the tidyverse version of R. 
