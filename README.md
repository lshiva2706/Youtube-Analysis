# Youtube-Analysis

About Data :

The dataset contains data on daily trending YouTube videos for several months. Data is available for the US, GB, DE, CA, FR, and IN (the United States, Great Britain, Germany, Canada, France and India respectively), with up to 200 trending videos listed each day.

The data for each region is stored in a separate file. The video title, channel title, publish time, tags, views, likes, dislikes, description, and comment count are all included in the data.
A category id field is also included in the data, which varies by region. Locate the associated JSON to retrieve the categories for a specific video. Each of the dataset's six regions has one of these files.


EXPLORATORY DATA ANALYSIS :

Our main focus is to perform different EDA on the data. We decided to analyze the data in the below various forms:


 EDA w.r.t to Time Series
 Most VIEWED or LIKED or DISLIKED video
 EDA related to channels
 Top 10 most trended channels
 Function to gather channel_title and its data per video
 Get the statistics for the given channels
 EDA on category attribute
 Analysis of cumulative data
 Sentimental and text analysis to find polarity for different categories


Results:

We have uncovered many correlations while performing EDA for example we found out that views, likes and comments count, likes have the maximum correlation which we further utilized to perform more deeper exploratory data analysis mainly with respect to channels and categories.
After observing the visualizations mainly from time series we inferred that 2017 and 2018 are the years with the most number of videos created, published and viewed. So, we have considered these two years as best performing years and have built many plots and graphs to better understand the statistics of the channels and categories.

After providing the 4 different types of EDA’s on specific countries, we also created cumulative analysis for 6 countries using the same EDA’s to  help the creators know how well other nation’s users are more interested in particular categories. This analysis also helps the creator to increase his/her own channel to the global wide reach by understanding and getting the insights from below analysis.
