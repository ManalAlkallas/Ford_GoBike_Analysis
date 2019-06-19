# USA Flight Analysis
## Overview </br>
  This project has two parts that demonstrate the importance and value of data visualization techniques in the data analysis process. In the first part, you will use Python visualization libraries to systematically explore a selected dataset, starting from plots of single variables and building up to plots of multiple variables. In the second part, you will produce a short presentation that illustrates interesting properties, trends, and relationships that you discovered in your selected dataset. The primary method of conveying your findings will be through transforming your exploratory visualizations from the first part into polished, explanatory visualizations.

- The following libraries are expected to be used in this project:
  - NumPy
  - pandas
  - Matplotlib
  - Seaborn
  
 ## Why this project?</br>
  Data visualization is an important skill that is used in many parts of the data analysis process. </br>
    - **Exploratory data visualization** generally occurs during and after the data wrangling process, and is the main method that you will use to understand the patterns and relationships present in your data. This understanding will help you approach any statistical analyses and will help you build conclusions and findings. This process might also illuminate additional data cleaning tasks to be performed.  
    - **Explanatory data visualization techniques** are used after generating your findings, and are used to help communicate your results to others. Understanding design considerations will make sure that your message is clear and effective. In addition to being a good producer of visualizations, going through this project will also help you be a good consumer of visualizations that are presented to you by others.

## Project Details
 This project is divided into two major parts. In the first part:</br>
  you will conduct an exploratory data analysis on a dataset of your choosing. You will use Python data science and data visualization libraries to explore the dataset’s variables and understand the data’s structure, oddities, patterns and relationships. The analysis in this part should be structured, going from simple univariate relationships up through multivariate relationships, but it does not need to be clean or perfect. There is no one single answer that needs to come out of a given dataset. This part of the project is your opportunity to ask questions of the data and make your own discoveries. It’s important to keep in mind that sometimes exploration can lead to dead ends, and that it can take multiple steps to dig down to what you’re truly looking for. Be patient with your steps, document your work carefully, and be thorough in the perspective that you choose to take with your dataset.

  In the second part, you will take your main findings from your exploration and convey them to others through an explanatory analysis. To this end, you will create a slide deck that leverages polished, explanatory visualizations to communicate your results. This part of the project should make heavy use of the first part of the project. Select one or two major paths in your exploration, choose relevant visualizations along that path, and then polish them to construct a story for your readers to understand what you found.rn?
  
  # Overview and Notes about the data set
 The original datasets report flights in the United States, including carriers, arrival and departure delays, and reasons for delays, from 1987 to 2008.


# The dataset should:

include at least 600 observations. (This is the number of rows after tidying your data - see the bullet point below about tidy data.)
include at least eight variables.
include at least one qualitative / categorical variable. (This can also be engineered / created.)
include at least one numeric variable.
be in a tidy format. In a nutshell, tidy data has each row as a single observation and each column reporting a single variable. You can read more about tidy data in Hadley Wickham’s paper [here]. You may need to do some cleaning and reshaping to tidy your dataset, before you actually get started with your exploration.
be in a common data format. This includes .csv, .tsv, .txt, and .xls. Basically, there should be a reasonable pandas.read_*() function to open up your data in a tidy format as a pandas DataFrame.
