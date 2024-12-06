## STAT 545 UBC (Winter 2024, Term 1)
## Assignment B4
Author: Katia Rosenflanz 

### Overview
This repository contains the solutions to Assignment B4. 
Several exercises were completed: 
1. The most frequent words (disregarding stop words found in `tidytext::stop_words`) in *Persuasion* by Jane Austen were plotted. 
2. Linear models were generated to model penguin flipper length based on a penguin's body mass. A separate model was generated for each species of penguin, and 95% confidence intervals were calculated on the predicted values.

### Dataset Acknowledgment
The assignment solutions utilize datasets from the `janeaustenr` package, as well as the `palmerpenguins` package. 

### File Contents 
This repository contains:
-   **README.md** 
-   **Assignment B4.Rmd** This is the .Rmd source code for the assignment. 
-   **Assignment-B4.md** This is the knitted output of the Assignment B4.Rmd file.
-   **Assignment-B4_files/figure-gfm** The required figures for the .md file. 

### How to Access
In order to investigate or edit the code, first fork the repository. 
After cloning the repository to your personal device, open the Assignment B4.Rmd file in your desired IDE. Make sure to install any necessary packages. The required packages are: 
-   tidytext
-   janeaustenr
-   tidyverse
-   broom
-   palmerpenguins 
