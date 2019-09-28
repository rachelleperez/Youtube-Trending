# "Trends on Trends" - An Analysis of the Youtube Creator's influence on video trendability.

This project will explore how the Youtube creator affects the path from viewer to view, within the Youtube platform (excluding outside factors). 

## QUESTIONS TO EXPLORE

WHAT? 
* Is there a correlation between CONTENT properties inputted by the creator and trendability? 
* Is there a correlation between the creator's publishing TIMELINE and trendability? 

WHY?
* For Creators, are there any opportunities and or suggested behavior to encourage trendability?
* For Youtube, is it worthwhile to spend additional resources on the Youtube Creator? Are there any suggested changes to the existing platform?

## DATA BACKGROUND

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

## CONCLUSION 

### REVIEW OF INITIAL QUESTIONS

WHAT? 
* Is there a correlation between CONTENT properties inputted by the creator and trendability?
    * YES!
    * Category "Entertainment" is by far the most frequently used by trending videos
    * The vast majority of videos (98%) are open to comments and ratings
    * The following content suggestions are in line with most trending videos:
        * Description length should be within 225 and 536 characters
        * Tag count should be within 7 and 25 tags and should not be left blank (as every trending video had at least 1)
* Is there a correlation between the creator's publishing TIMELINE and trendability?
    * YES! 
    * The vast majority of trending videos (85%) achieved trending within 3 days of being published with 56% within the day.
    * Creators slightly favor weekdays over weekends to upload videos. 

WHY?
* For Creators, are there any opportunities and or suggested behavior to encourage trendability?
    * YES! 
    * A creator looking for trendability should use the upload content properties and timeline of past trending videos as a guideline.
* For Youtube, is it worthwhile to spend additional resources on the Youtube Creator? Are there any suggested changes to the existing platform?
    * YES!
    * Creators are the lifeline of Youtube. It is important they have the tools to do well and are guided by Youtube. Any support in training and or product development from Youtube to the creators can positively contribute to the continued success and usage of the platform. 


### WHAT IS NEXT FOR PROJECT?

* Qualitative Analysis: Particularly on Tags and Description
* Closer look at qualities provided for Multiple Trenders