# stackoverflow_survey_analysis
This repo is for an analysis project based on stack overflow survey data.

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>

The code should run with no issues using Python versions 3.*.
Libraries used in notebook are:
- pandas
- numpy
- matplotlib.pyplot
- seaborn

## Project Motivation<a name="motivation"></a>

For this project, I was interestested in using Stack Overflow data from 2017 to better understand:

1. Does developer's interest/preference impact their job satisfaction or career satisfaction?
2. What are developer's preferred, what are not?
3. What does developer care about when accessing a potential job?
4. What is important in Globex's hiring process?
5. When most developers prefer to start work?


## File Descriptions <a name="files"></a>

**survey_results_analysis.ipynb**: jupyter notebook available here to explore above questions. Each question has a title (Markdown cells) in the notebook, so it can be easily read from part to part.  

**survey_results_public.csv**: survey response data downloaded from Kaggle. This is the data source of our analysis.

**survey_results_schema.csv**: survey schema data downloaded from Kaggle. This help us understand the survey questions. 

**survey_results_schema(analysis).xlsx**: Draft file I use to analysis questions, and some draft for data process. Readers DON'T need to read this file.

**pictures folder**: it stores picture which might used for blog. Readers DON'T need to read this folder.


## Results<a name="results"></a>

The main findings of the code can be found at the post available [here](https://medium.com/@lsaicex/what-does-developer-really-care-about-e25d53387a5c).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>

Must give credit to Stack Overflow for the data.  You can find the Licensing for the data and other descriptive information at the Kaggle link available [here](https://www.kaggle.com/stackoverflow/so-survey-2017/data).  Otherwise, feel free to use the code here as you would like! 

