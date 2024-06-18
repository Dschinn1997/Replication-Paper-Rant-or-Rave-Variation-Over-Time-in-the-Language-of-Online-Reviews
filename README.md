# Replication Paper Rant or Rave Variation Over Time in the Language of Online Reviews

This repository contains the coding file and data set access links, that build the basis for the report "Reproduction and Replication of the Paper:  "Rant or Rave: Variation Over Time in  the Language of Online Reviews". 

The respective coding file, that includes all steps from the data loading, preperation, sampling, and analysis, as well as the table and figure generation, is the "Project.ipynb" file. The "Results" folder stores all analysis results as pickles, that can be loaded if wished to check the result correctness or generate different visualizations. 

The "Data" folder includes a markdown file that states the links where the complete unprepared data sets of the underlying analysis can be downloaded, as unfortunately an upload of them was not possible due to their size. If one would like to have the original data sets or their sampled versions please do not refrain from contacting me.




## Project Overview
This repository contains the code for one of my master's second semester term papers for the course "Web & Society: A Computational Social Science Perspective". For the term paper we, Trinidad Bosch Achondo and I, investigated the role of bots on social media given the widespread concern about an "malicious social bot pandemic". Thereby, we focused on analyzing the topics bots discuss, the sentiments they convey, and if we find indications for malicious intentions.

## Objectives
- Identify the main topics discussed by social media bots and valid users.
- Analyze the sentiment (positive, negative, neutral) associated with these topics.
- Evaluate whether the bots' interactions suggest any malicious intent.

## Key Findings
- Bots primarily discuss current and trending topics similar to those of valid users.
- Bots do not connotate topics universily with one sentiment, how they connotate a topic primarily depends on the areas studied. E.g. the topic “stock markets” has a quite neutral sentiment.
- No overarching malicious intentions were found, though this can vary by topic.

## Technologies and Tools
- Web Scraping
- Data Preprocessing
- Natural Language Processing
- LLM BERT Embeddings
- Dimensionality Reducation UMAP
- Cluster Detection HDBSCAN and k-Means 
- Topic Modelling
- Sentiment Analysis
- Data Visualisation

## Repository Contents
- `script`: Jupyter notebook that contains the the whole project's code including the data collection, preprocessing, and analysis.
- `requirements`: List of Python packages required to run the project.
- `paper`: PDF of final term paper.

- **Note:** We cannot provide the raw data used in this project as it belongs to the ‘TwitBot-20’ dataset (Feng et al., 2020) of which we are not owners. Processed datasets are also not included due to these restrictions.
-  Original Dataset: Feng, S., Wan, H., Wang, N., Li, J., & Luo, M. (2021). TwiBot-20: A comprehensive Twitter bot detection benchmark. In G. Demartini, G. Zuccon, J. S. Culpepper, Z. Huang, & H. Tong (Eds.), Proceedings of the 30th ACM International Conference on Information & Knowledge Management (pp. 4485–4494). ACM. https://doi.org/10.1145/3459637.3482019
-  Related publication: Feng, S., Tan, Z., Wan, H., Wang, N., Chen, Z., Zhang, B., ... & Luo, M. (2022). TwiBot-22: Towards Graph-Based Twitter Bot Detection. arXiv preprint arXiv:2206.04564.

## Installation
To run the code in this repository, you'll need to have Python installed. Clone this repository and install the required packages using:

git clone [repository-link]
cd [repository-name]
pip install -r requirements.txt

## Contact
For any questions or further information, please contact:

Gina-Maria Angelina Unger - gina-unger@gmx.de
Trinidad Bosch Achondo - tbosch.achondo@gmail.com
