# "Trends on Trends" - An Analysis of the Youtube Creator's influence on video trendability.

This project will explore how the Youtube creator affects the path from viewer to view, within the Youtube platform (excluding outside factors). 

## QUESTIONS TO EXPLORE

WHAT? 
* Is there a correlation between CONTENT properties inputted by the creator and trendability? 
* Is there a correlation between the creator's publishing TIMELINE and trendability? 

WHY?
* For Creators, are there any opportunities and or suggested behavior to encourage trendability?
* For Youtube, is it worthwhile to spend additional resources on the Youtube Creator? Are there any suggested changes to the existing platform?

## DATA BACKGROUND & PREVIEW

### What data is available?
* Source: https://www.kaggle.com/datasnaek/youtube-new
* "Daily Record of the Top Trending Youtube Videos"
* Up to 200 trending videos per day
* Two dataframes with the same columns (19). 
    * 'df' should contain one line per video with final numbers 
    * "df_all_timestamps" should contain snapshots throughout the day. 

### Limitations
* No data on the viewers or path to arrive to video. 
* Only 1 property of channel to be attributed to Youtube creator. More information on creator could lead to further insights.

### Unsanswered Questions
* What defines "trending"? 
    * What is the metric? Assumption: Unknown internal measure (Top X videos by views / time_unit)
    * Dynamic - Constantly changes throughout day (e.g. Jan 3 - 184, Jan 4 - 828, Jan 5 - 875).
    * Does it change by viewer's geographical region?
* What is "country''?

### Manipulations

DF
* Added tag_count column (which split the string in the tags column and added the individual elements)
* Replaced existing publish date column with data type "object" with new one with data type "datetime"
* Replaced existing trending date column with data type "object" with new one with data type "datetime"
* Added publish day of the week column
* Added trending day of the week column
* Added Time Live and Days Live columns

OTHERS
* New dataframe called "channel_count" created for Multiple Trenders analysis