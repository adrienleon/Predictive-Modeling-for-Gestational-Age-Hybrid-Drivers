# Project Title: Prenatal Care Analytics and Commuter Vehicle Prediction

## Overview
This project encompasses two applied problems focusing on data analysis and predictive modeling using R. The first problem addresses the challenge of estimating gestational age in newborns in low- and middle-income countries using datasets from Bangladesh and Zambia (`GA_bangladesh.csv` and `GA_zambia.csv`). The second problem utilizes the 2017 National Household Travel Survey datasets (`drivers_train.csv` and `drivers_test.csv`) to predict whether an individual is a hybrid/electric vehicle driver in specific metropolitan areas.

## Prerequisites
Before running the project, users should have a basic understanding of statistical analysis and machine learning concepts, as well as familiarity with the R programming language. Additionally, certain R packages may be required to process the data and perform the analysis.

## Installation
To run the analysis, ensure you have R installed on your computer. You can download R from [The Comprehensive R Archive Network (CRAN)](https://cran.r-project.org/).

Once R is installed, open an R session and install the necessary packages (if not already installed) by running:

Libraries: install.packages(c("tidyverse", "caret", "randomForest", "e1071"))

## Usage
To replicate the analysis or conduct a new one, follow these steps:

1. Clone the repository to your local machine.
2. Load the R scripts associated with the applied problems.
3. Read the datasets using R's `read.csv()` function, e.g., `data <- read.csv("path/to/dataset.csv")`.
4. Follow the analysis steps outlined in the R Markdown file from pages 7-47.

Please refer to the accompanying R Markdown document (`Final Exam Spring 2023 Adrien.Rmd`) for detailed analysis steps and methodology.

## Authors
- Adrien Leon - Initial work and analysis

## Acknowledgments
- The datasets used for Applied Problem 1 (`GA_bangladesh.csv` and `GA_zambia.csv`) were provided by [relevant source or institution].
- The datasets used for Applied Problem 2 (`drivers_train.csv` and `drivers_test.csv`) come from the [2017 National Household Travel Survey](https://nhts.ornl.gov/).
- Thanks to the instructors and collaborators who provided guidance and support throughout the course of this project.
