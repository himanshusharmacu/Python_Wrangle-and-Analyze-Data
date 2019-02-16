# Python_Wrangle-and-Analyze-Data

* Real-world data rarely comes clean. Using Python and its libraries, I gathered data from a variety of sources and in a variety of formats, assess its quality and tidiness, then clean it. This is called data wrangling. 

* I had documented my wrangling efforts in a Jupyter Notebook, plus showcased them through analyses and visualizations using Python (and its libraries) and/or SQL.

## The dataset that i wrangled (and analyzed and visualized) is the tweet archive of Twitter user @dog_rates, also known as WeRateDogs.

* WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators, though? Almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because "they're good dogs Brent." 
* WeRateDogs has over 4 million followers and has received international media coverage.  
* WeRateDogs downloaded their Twitter archive and sent it to Udacity via email exclusively to use in this project. This archive contains basic tweet data (tweet ID, timestamp, text, etc.) for all 5000+ of their tweets as they stood on August 1, 2017. More on this soon.

## The following packages (libraries) need to be installed. You can install these packages via conda or pip.
* pandas
* NumPy
* requests
* tweepy
* json

# Project Files Description
* **wrangle_act.ipynb** : code for gathering, assessing, cleaning, analyzing, and visualizing data
* **wrangle_report.pdf** : documentation for data wrangling steps: gather, assess, and clean
* **act_report.pdf** : documentation of analysis and insights into final data
* **twitter_archive_enhanced.csv** : file as given
* **image_predictions.tsv** : file downloaded programmatically
* **tweet_json.txt** : file constructed via API
* **twitter_archive_master.csv** : combined and cleaned data
