# Data_Visualization_case_study_googleplaystore
 
## Problem Statement

The team at Google Play Store wants to develop a feature that would enable them to boost visibility for the most promising apps. Now, this analysis would require a preliminary understanding of the features that define a well-performing app. You can ask questions like:

Does a higher size or price necessarily mean that an app would perform better than the other apps?
Or does a higher number of installs give a clear picture of which app would have a better rating than others

## Solution 

### Understanding the data 

    -Identify the Target Variable 
    -Check for the data types

### Handling missing values for rating

    Ratings is the target variable
    drop the records

    Inspect the nulls in the Android Version column
    drop because only 3 values

    Inspect the null in the Current version column
    replace it by mode

    
### Handling Incorrect Data Types

    Size	          Numeric (Float)	   Represents the size of the app (e.g., 19000.00)	
    Installs	      Numeric (Float)	   Represents the number of installs (e.g., 10000.00)	
    Type	          Categorical	       Represents the type of the app (e.g., Free)	
    Price	          Numeric (Float)	   Represents the price of the app (e.g., 0.00)	
    Content Rating	  Categorical	       Represents the content rating (e.g., Everyone)	
    Genres	          Categorical	       Represents the genre(s) of the app (e.g., Art & Design)	
    Last Updated	  Date	               Represents the last update date (e.g., January 7, 2018)	
    Current Ver	      Text	               Represents the current version (e.g., 1.0.0)	
    Android Ver	      Categorical/Text	   Represents the required Android version (e.g., 4.0.3 and up)	
    Current_ver	      Text	               Represents the current version (e.g., 1.0.0)	
    Reviews	          Numeric (Float)	   Represents the number of reviews (e.g., 10000.00)	
    

### Sanity checks
    	
    Rating is between 1 and 5 for all the apps	
    Number of Reviews is less than or equal to the number of Installs.	
    Free Apps shouldn’t have a price greater than 0	









