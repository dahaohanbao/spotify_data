## Analysis on Rolling Stone's 500 Greatest Albums of All Time


Fang Yang, Dec 2017


## Summary

This project is to analyze the music genres via year. My dataset is rolling-stone-s-500-greatest-albums-of-all-time `data/albumslist.csv`. I want to see what music genres did rolling stone release at different age. All the data is in the `data` folder. The scripts in `src` folder do the coding part to analyze the data and export results tables and plots in `results` folder.

People should firstly run the `src/cookiecutter.sh` to construct the structure of our root folder and run `make all` and finaly generalstory.rmd to compelet the project.

## Hypothesis

Rolling Stone released almost same music genre albums at different age.

## Project Packages

R, version 3.4.1

Rstudio

R packages:`tidyverse`, `ezknitr`,`knitr`

## How to Use

- step1: Use `cd` to direct a locial folder
`cd your_path`

- step2: Clone the project repo `git clone https://github.com/dahaohanbao/rolling_stone_data.git`

- step3: Go to the folder you just cloned `cd rolling_stone_data`
- step4: Use makefile to run the code`make all`
- step5: Use makefile to clean the result`make clean`