# WeRateDogs
### This project was done as a part of Udacity Data Analysis course 

Data Wrangling Report
at Feb 2021

This project was done as an assignment for Udacity Data Analysis Professional track provided by an ITIDA scholarship, This report illustrates the mainsteps done in the data-wrangling of "WeRateDogs" twitter account.

Step 1: Gathering the data:

In this step I have collected the data needed for this project , there were three main sources to collect the data from:

 - 1. Twitter_archive_enhanced.csv file: this file was sent over from WeRateDogs to Udacity specifically for this project where Udacity provided this file on the classroom to be downloaded manually as I have imported this file using Pandas' function "read_csv" to import the file to my working environment "Jupyter Notebook". The file contained the archive of posts done by "WeRateDogs"
 - 2. Image_prediction.tsv: This file was hosted on a webpage by Udacity, where it was required to be downloaded programmaticly and in order to download it programmatically, I have used the Requests' function "get" to download the file programmatically then later imported with pandas to my working environment. This file contained predictions of content of the images posted by WeRateDogs; the predictions were done by a nueral network by Udacity.
 - 3. tweet_json.txt : This file was supposed to be gathered using Twitter's API via tweepy library , but since I had problems getting a twitter developer account , this file was provided to me by udacity and downloaded manually to my working directory.


Step 2: Assessinging the data:

In this step I assessed the now gathered data using both visual and progrommatic assessment to catch tideness and quality issues, Each dataset was assessed individually at first I would check the quality issues in the given dataset then I would check for tideness issues then i would go on to the next dataset.
 - 1- Visual assessment: in this step I used visual studio code with "Excel Viewer" plugin  in order to assess the data where visual studio code was chosen due to the availability of several plugins and how easy and faster it was compared to spreadsheet programs.
 - 2- Programmatic assessment: this step was done using Jupyter notebooks.
 - 3- Documentation : after each assessment step I would document my findings in jupyter notebooks where Notes were written first then Quality issues then Tideness issues.


Step 3: Cleaning the data:

In this step I cleaned the data using the documentation I written in the assessment step where quality issues were adressed first then tideness issues as for each issue that was cleaned , a clear documentation was written for it in jupyter notebooks.

1- Quality issues:

	 - 2 quality issues were found in image_predictions dataset.
	 - 9 quality issues were found in twitter_archive dataset.
	 - 2 quality issues were found in tweets_stats dataset.
Total : 14 issues

2- Tideness issues:

	 - 1 general tideness issue was found.
	 - 1 Tideness issues was found in tweet_stats dataset.
	 - 1 Tideness issues was found in twitter_archive dataset.
Total : 3  issues

### Check Act Report PDF File for the visualizations that were produced.
