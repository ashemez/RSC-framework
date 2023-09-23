# RSC-framework
Resume summarization and classification framework

## Data
Multilabel resume dataset is obtained from [Kaggle](https://www.kaggle.com/datasets/wahib04/multilabel-resume-dataset)
The dataset in this project is a cleaned subset of the original dataset. Created extractive summary of resumes in rscdata-X-summary.json and rscdata-X-test-summary.json for the corresponding resumes data files using [Bert Extractive Summarizer](https://pypi.org/project/bert-extractive-summarizer/) package. Targets are one-hot encoded and stored in rscdata-y.json and rscdata-y-test.json data files.

MSc. Data Science, University of London, Final Project
