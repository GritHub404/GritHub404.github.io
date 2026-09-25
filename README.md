# GritHub404.github.io

This repo contains milestone projects designed for DSCI 521. It includes an About page, blog posts with some computational posts written in R and Python.


## Prerequisites
Install the following software before building the site:

- Quarto 1.10.18
- uv 0.12.10
- R version 4.6.1 (2026-06-24 ucrt) 
- git version 2.55.0.windows.5


## Build instructions

### 1. Clone the repository
Run the following commands in a Git Bash terminal:

- git clone git@github.com:GritHub404/GritHub404.github.io.git
- cd GritHub404.github.io
- uv sync


### 2. Restore the R environment
From an R session started at the top level of the repository:

- renv::restore()

### 3. Build site
From the terminal at the top level of the repository:

- uv run quarto render

## Viewing site locally
The rendered website is generated in the 'docs/' directory.
To preview the website locally, from the top of the repository run:

- uv run quarto preview


## Dataset information
The Palmer Penguins dataset is used in both posts R and Python. Network is not needed to fetch the dataset. Source of the data is https://allisonhorst.github.io/palmerpenguins/, Palmer Station Antarctica LTER.