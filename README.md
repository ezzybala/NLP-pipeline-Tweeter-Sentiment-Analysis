# NLP-pipeline

An NLP pipeline is constructed from the following steps:

Data acquisition,
Text extraction and cleaning,
Pre-processing,
Feature Engineering,
Modelling,
Evaluation,
Deployement,
Monitoring & Model updating,

Data Acquisition

The dataset used in this NLP task was  gotten from twitter through it's developer API which has now been monitized by twitter. The data stored as a CVs file in dataset folder in github

Data extraction:

The second step in the NLP pipeline is extracting the text from its native form (csv file).

Our dataset is a CSV(Comma Separated Values) file that contains tweets data. Each row contains the text of a tweet and a sentiment label. We will use the Pandas library to read the CSV file and load data into a dataframe.
