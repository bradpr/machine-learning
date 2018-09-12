# Machine Learning Engineer Nanodegree
## Capstone Proposal
Richard Pritchett  
September 10, 2018

## Proposal
As we have seen through the Udacity MLND course, machine learning has utilities that span all areas of life. One useful area for the skills I've learned in this course is in the domain of medicine. For my capstone project I would like to examine how machine learning can be used to classify patient data to identify malignant breast cancer tumors.

To accomplish this, I will be exploring the "Breast Cancer (Wisconsin) Data Set" (https://www.kaggle.com/uciml/breast-cancer-wisconsin-data and https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29). This dataset is compiled from a 569 digitized images collected from fine needle aspirate of breast masses. 

My data exploration will include
  1) Analysis of the data to define features and labels
  2) Analysis of the data to determine correlations between features
  3) Evaluation of the strength of feature correlation with respect to their ability to predict outcomes
  4) Selection of features for use in outcome prediction
  5) Evaluation of machine learning models to use in predicting outcomes vs a random outcome selection model
  6) Selection of the preferred machine learning model for this task


### Domain Background

Breast cancer kills close to 42,000 women each year. 
Each year 266,000 women are diagnosed with invasive breast cancer, and 64,000 are diagnosed with breast cancer that has not progressed to an invasive stage. Cancer mortality statistics frequently 5 and 10 year survival rates. These rates refer to the average number of patients who are diagnosed surviving 5 and 10 years. With breast cancer, if the cancer diagnosis is made before spreading beyond breast tissue, the 5 year survival rate is 99%. If the initial diagnosis shows that the cancer has spread, the 5 year rate is 90%.

As with most cancers, early detection is crucial to improving prognoses. There are numerous methods to diagnose forms of breast cancer, and they all require actions to be taken by medical professionals. A typical process is that a patient undergoes a mammogram screening to visually identify masses in breast tissue that could potentially be cancerous. Once masses are identified, a needle is used to extract some cells from the mass. This extraction is referred to as Fine Needle Aspirate (FNA). These aspirate cells are then placed under a microscope for observation and diagnosis.

Any steps that could be taken to shorten the time between screening and diagnosis would mean earlier diagnosis and higher survival rates.

### Problem Statement

This project endeavors to reduce the time from screening to diagnosis in detecting and treating breast cancer. Manual, visual analysis of aspirate samples by medical professionals can be time-intensive. Providing medical professionals with a tool which can produce diagnoses predictions from digital measurements taken from FNA samples will allow them to identify malignancies more quickly. This will save lives. The ability to quickly diagnose malignant versus benign masses will increase early diagnoses for patients which will improve survival rates.

The product of this project will be measured against a coin-flip diagnosis as a baseline, which would yield 50% accuracy. This is because diagnoses can be either benign or malignant. A prediction model demonstrating an accuracy greater than 50% will be deemed succesful. I would. however, like to see this yield far greater accuracy.



### Datasets and Inputs
_(approx. 2-3 paragraphs)_

I will be using the "Breast Cancer (Wisconsin) Data Set" (https://archive.ics.uci.edu/ml/datasets/Breast+Cancer+Wisconsin+%28Diagnostic%29)
This dataset was made publicly available by The University of Wisconsin. I located this dataset while browsing Kaggle datasets.

The dataset contains 569 records with 30 features. These features were digitally measured from FNA-extracted cells of potential breast cancer patients. This project will use this dataset to build a model to predict breast cancer diagnoses.

### Solution Statement

This project will use data analysis and machine learning methods to create a prediction model that, with at least 50% accuracy, classify cellular material extracted from breast masses as either 1) Benign or 2) Malignant.

This solution will be reached by the following steps:
  1) Analysis of the data to define features and labels
  2) Analysis of the data to determine correlations between features
  3) Evaluation of the strength of feature correlation with respect to their ability to predict outcomes
  4) Selection of features for use in outcome prediction
  5) Evaluation of machine learning models to use in predicting outcomes vs a random outcome selection model
  6) Selection of the preferred machine learning model for this task

### Benchmark Model

I will be using a random-selection benchmark. 
There are two potential diagnoses: 1)Benign and 2)Malignant. These have equal probability of 50%. The benchmark accuracy afforded by the random-selection model will be 50%. If an improved model can deliver accuracy better than 50%, then I will have proven that a prediction model does exist that can assist with breast cancer diagnoses.

### Evaluation Metrics
_(approx. 1-2 paragraphs)_

In this section, propose at least one evaluation metric that can be used to quantify the performance of both the benchmark model and the solution model. The evaluation metric(s) you propose should be appropriate given the context of the data, the problem statement, and the intended solution. Describe how the evaluation metric(s) are derived and provide an example of their mathematical representations (if applicable). Complex evaluation metrics should be clearly defined and quantifiable (can be expressed in mathematical or logical terms).

### Project Design
_(approx. 1 page)_

In this final section, summarize a theoretical workflow for approaching a solution given the problem. Provide thorough discussion for what strategies you may consider employing, what analysis of the data might be required before being used, or which algorithms will be considered for your implementation. The workflow and discussion that you provide should align with the qualities of the previous sections. Additionally, you are encouraged to include small visualizations, pseudocode, or diagrams to aid in describing the project design, but it is not required. The discussion should clearly outline your intended workflow of the capstone project.

-----------

**Before submitting your proposal, ask yourself. . .**

- Does the proposal you have written follow a well-organized structure similar to that of the project template?
- Is each section (particularly **Solution Statement** and **Project Design**) written in a clear, concise and specific fashion? Are there any ambiguous terms or phrases that need clarification?
- Would the intended audience of your project be able to understand your proposal?
- Have you properly proofread your proposal to assure there are minimal grammatical and spelling mistakes?
- Are all the resources used for this project correctly cited and referenced?
