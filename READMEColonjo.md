# My Music Markdown
## Jonathan Colon (Assignment 3)
## 2/13/2025<br>

### Where is the data from? ​

My data was collected from my own spotify account throught requesting my data<br>

### How was it collected?​
I downloaded the .json file containing my streaming history from Spotify
<br>
### How was it extracted?​
I was able to request the data via spotify, and then extracted it through converting it into a CVS file<br>

### What program was used to clean the data?​
Python<br>

### How was the data cleaned or transformed? Be specific.​
This current dataset was cleaned by merging two separate streaming history datasets (one from the previous year and one from the current). I also changed all columns to lowercase in case I use SQL with this dataset.
I also added a column to show the legnth of time each song is once converted from milliseconds.<br>


### What are the units of the numeric data?​
Currently milliseconds and seconds as the streaming history contains columns for song legnth <br>

### What were the formulas used in column creation?​<br>

mixtape['Minutesplayed'] = mixtape['msplayed'] / (60 * 1000) was used to convert milliseconds to seconds, which ultimately lead to a more comprehensive column being created<br>

### How is the data validated to ensure consistency?​

Spotify sends my downloaded data, which is backed by their privacy policies. I also was able to cross reference the data with my own library to make sure there was accurate data in the dataset

### What are the definitions for the column names? Include all columns in your dataset.​
endtime: Time the song was ended (date)
artistname: Name of artist
trackname: Name of track
msplayed:Song legnth in Milliseconds 
minutesplayed: Song length in minutes

### If there are set variable options in your dataset, what are thier definitions? ​
trackname: Name of song
artistname: Name of artist



### What are the regulations to using the data? 
From my understanding, there are any restrictions when using this data as it is my own
If you are referencing sources, be sure to include citations/references as needed.
