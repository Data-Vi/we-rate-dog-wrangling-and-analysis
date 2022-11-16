Data Gathering Efforts
The three data concerned were twitter_archive_enhanced which was directly downloded, tweet image_predictions which was downloaded from udacity server using request library and the tweet_json.txt file which was downloaded also from Udacity server because I could not register a developer account and the code with tweepy library given by the instructor did not work. The tweet_json was a txt file. This file was opened into json format and read into pandas Dataframe. Of cause, not all the columns were required. The required columns were selected into a separate DataFrame which was used for the project.

Data Assessment
The data assessment efforts consist of both visual and programmatic assessments.

Visual assessment required display of the three datasets and visually assessing it for any dirtiness or messiness Programmatic assessment required use of assessment codes such as DataFrame(df).info(), df.sample(), df.head(), df.tail(), df.duplicated() etc on the three datasets. Explorative visualization codes were also used on one of the datasets to fine tune assessment. The assessment process produced 9** quality issues and **2 tidiness issues. The Quality issues spanned over completeness, validity, and consistency.

Data Cleaning
Data cleaning was carried out in an ordered manner such that each issue were addressed by

defining the cleaning efforts
writing the code for the effort
testing the issue in the dataset to see whether the issue is resolved
In the process of cleaning, a copy of each dataset was produced programmatically to keep the raw data safe.

Quality issues that had to do with missing or incomplete ata were addressed first. This was followed by addressing validity and inconsistent issues.

After cleaning, a masterdataset consisting of a combination of the three dataset was programmatically produced and stored as a csv file. This dataset was used for visualizations

Insights and Visualization
Four (4) insights were derived from the master dataset which had 4 corresponding visualizations.