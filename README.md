# Developer Insights

# Data Overview
This data set comes from StackOverflow's 2017 developer survey, a yearly survey of developers who visit the site.  There are a number of questions in `data/survey_results_schema.csv`, as well as the column names they map to in `data/survey_results_public.csv`.  

A full mapping of the questions, as users saw them, and methods can be found in `data/DeveloperSurvey2017QuestionaireCleaned.pdf`.  Please note that the phrasing of the questions in this file can sometimes differ from the phrasing in `data/survey_results_schema.csv`.

## Insights

What insights can we gleam from this data? There are many interesting fields, from people's roles, job satisfaction, professional and personal interests, demographics, and a number of others.  The notebook `developer_insights.Rmd` contains a few interesting analyses to get you started. What other interetsting questions can you answer from this data?

## Model

Can you predict if a developer is a Data Scientist?  Your goal is to build a classifier to predict whether a developer is involved in the growing field of Data Science, using the answers they provide in the survey.  Developer classifications are stored in the `DeveloperType` column.  Be careful, as some questions may contain fields with target leakage that should not be used! You may also wish to use the existing features to engineer new features.
