# Replication Paper Rant or Rave Variation Over Time in the Language of Online Reviews

## Project Overview
This repository contains the code for one of my fourth master's projects for the course "Social Media Data Analysis". In this course we had to do a final project where one possible task was to select an interesting publication, reproduce its results, replicate its analysis using a different dataset, and write a report about what we found due to the reproduction and replication process. I chose to replicate and reproduce the results for one of the three main datasets in the publication:

- Ziser, Y., Webber, B., & Cohen, S. B. (2023). Rant or rave: variation over time in the language of online reviews. Language Resources and Evaluation, 1-31.

This paper focuses on how the language of online reviews has changed over the last few decades. In particular, it focuses on the trends of change that affect the sentiment intensity, lexical diversity and comprehensiveness of online reviews.

## Objectives
- Reproduce the results of Ziser et al. (2023) for one of the three main studied datasets.
- Replicate the results using a different dataset than originally studied.

## Key Findings
- Ziser et al.'s (2023) results are reproducible, which means that reviews increase in the sentiment intensity, reduce in their lexical diversity, and decrease in the general comprehensiveness. These trends are also to a high degree statistically significant.
- Ziser et al.'s (2023) results are also replicable when studying more recent data.

## Technologies and Tools
- Sampling
- Natural Language Processing
- Sentiment Analysis

## Repository Contents
- `script`: Jupyter notebook that contains the the whole project's code including the data loading, preprocessing, sampling, and analysis.
- `report`: PDF of final term paper.
- `emoji_utf8_lexicon`:
- `vader`:
- `vader_lexicon`: vader lexicon versions containing sentiments as used by Ziser et al. (2023). Accessed from the authors Github repository https://github.com/yftah89/ReviewsOverTime
- Data folder: Folder includes a markdown file that states the links where the analysis's data sets can be downloaded, as they cannot be directly uploaded due to their size.
- Results folder: Folder stores all of my reproduction and replication analysis results as pickles.


## Installation
To run the code in this repository, you'll need to have Python installed. Clone this repository and install the required packages using:

git clone [repository-link]
cd [repository-name]

## Contact
For any questions or further information, please contact:

Gina-Maria Angelina Unger - gina-unger@gmx.de
