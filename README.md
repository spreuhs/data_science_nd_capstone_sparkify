# data_science_nd_capstone_sparkify

## Table of Contents
[Installation](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#installation)

[Project Motivation](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#project-motivation)

[File Descriptions](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#file-descriptions)

[Results](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#results)

[Acknowledgements](https://github.com/spreuhs/data_science_nd_capstone_sparkify/blob/main/README.md#acknowledgements)

## Installation

There should be no necessary libraries to run the code beyond the Anaconda distribution of Python. The code should run without issues using Python versions 3.*.

The following Packages were used in the implementation of the project:
- Pyspark
- Pandas
- Numpy
- Matplotlib
- Seaborn

## Project Motivation

The intent of this project is to predict churn for the fictional company Sparkify using Apache Spark.

### Questions answered in the following:
- what information are provided in the data?
- how do we define churn?
- how many users did churn in the past?
- are activities of churned users different from still active users?
- can we accurately predict churn?

## File Descriptions

The whole process is gathered in the jupyter notebook found in this directory. Detailed description regarding the code can be found in markdown cells and comments contained in the notebook.

## Results

Most of the results can be found in the notebook. Additional information and formatted results can be found in my Medium post [here](https://spreuhs.medium.com/please-dont-stop-the-music-sparkify-cd5dd10c80b1).

A brief summary of the results is that we can predict churn somehow well using a Gradient Boost Tree Classifier. As churn is not very likely, so the dataset is a bit imbalanced. Nonetheless, using thought-out Feature Engineering in combination with the GBT Model leads to somewhat reliable results.

## Acknowledgements

Thanks to Udacity for providing the data as part of their Data Science Nano Degree.
