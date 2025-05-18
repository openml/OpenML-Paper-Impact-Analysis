# OpenML-Paper-Impact-Analysis
This repository contains the dataset and code used to analyse the impact of OpenML. The results are included in the OpenML cells paper. The analysis focuses on research papers citing the core OpenML paper, Python and R connectors, and benchmarking suite papers.

#### Contents
1. Data: \
`data/collected_papers.csv`: Contains the originally collected data on 1786 papers from Google Scholar. \
`data/Final_survey_data.csv`: The cleaned dataset (after filtering papers based on availability, language, and other criteria) with review results. 
2. Code: \
   `scripts/analysis.py`: Python scripts used to clean the data, run statistical analyses, and generate figures/tables for the paper.
3. Docs: \
   `docs/methodology.md`: Methodology used for impact analysis.
5. Documentation: \
`docs/methodology.md` Details of the review methodology and questionnaire used for the analysis.

Note: We exclude papers published in 2025 as the year is still in progress, to avoid skewed interpretations of trends.
