# OpenML-Paper-Impact-Analysis
This repository contains the dataset and code used to analyze the impact of OpenML. The results are included in OpenML cells paper. The analysis focuses on research papers citing the core OpenML paper, Python and R connectors, and benchmarking suite papers.

#### Contents
1. Data: `data/collected_papers.csv`: Contains the originally collected data on 1719 papers from Google Scholar. \
`data/Final_survey_data.csv`: The cleaned dataset (after filtering papers based on availability, language, and other criteria) with review results. 
2. Code:
   `scripts/analysis.py`: Python scripts used to clean the data, run statistical analyses, and generate figures/tables for the paper. \
   `scraped_paper_reviewer_assignment/assign_reviewer.ipynb`: Python script to collect paper id, paper URL and other information from the raw collected data (in JSON). Also assigns paper ID and reviewer (for analysis the paper). \
   `scripts/additional_sanity_check.ipynb`: Script for additional sanity check and correction in collected entries. 
4. Documentation: `docs/methodology.md` Details of the review methodology and questionnaire used for the analysis.
