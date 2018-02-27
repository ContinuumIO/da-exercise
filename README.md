# Data Analysis Exercise

This exercise is designed to demonstrate your basic data analysis skills and ability to communicate information about data.  (This should not require more than an hour or two.)

## The Data

In this repository is a `packages.csv` file.  This represents a small fraction of conda package download data from January 2018.  This file has the following columns:

* `date`: Calendar date when package was downloaded
* `pkg_name`: Name of conda package
* `pkg_version`: Version of conda package
* `pkg_platform`: Operating system required by package (not all packages are OS-specific)
* `pkg_python`: Version of Python required by package (not all packages require Python)

## Instructions

Create a Jupyter Notebook that loads the data and answers the following questions:

* How many packages are downloaded per day? (show in a plot)
  - Looking at this plot, is there periodic behavior?
* What are the top 5 most popular packages?
* How popular is each operating system?
* Should we stop supporting Python 3.5 in future Anaconda releases?

Use whatever packages in Anaconda you prefer to answer these questions.  Explain your results and interpretation in the notebook as if you were communicating to a technical colleague.
