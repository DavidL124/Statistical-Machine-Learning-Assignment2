# Statistical-Machine-Learning-Assignment2

The ipynb files in this folder are used to run the models described in the report. They are as follows:

- Model2NoText: uses the number of co-authors, and importantly the combined word counts of the abstract and title are included in the column "text".
- Model2Counts: combines the abstract and title and represents the result using word counts. Co-authors are also categorised into bins.
- ModelOriginal: combines the abstract and title and represents the result using TF-IDF. Also uses the number of co-authors.
- Model10SelectKBest: uses the SelectKBest function with the parameter k set at 2000. Also uses the number of co-authors.
- ModelManualFeatureSelection: pre-processes the combined title and abstract by removing words that appear too frequently. Also uses the number of co-authors.
- ModelRestrYear: restricts the number of instances, based on year, for authors identified to have a low average F1 score (using the results of ModelOriginal). 
Also uses the number of co-authors.
 
