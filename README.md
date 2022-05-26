# Final-Project-Python-Data-Analytics-

I had a difficult time finding a dataset that I thought I could work with on subjects that I actually had an interest in. I finally settled on a dataset that compared gas prices in NYS from January 2007 to May 2022. 
I got my data from https://data.ny.gov/Energy-Environment/Gasoline-Retail-Prices-Weekly-Average-by-Region-Be/nqur-w4p7
I thought I would be able to show how gas prices varied from Western NY to Central NY and if cities were different from rural areas and to prove/disprove that gas prices did infact increase during the summer. 

I did not find other peoples research but I did find other government websites with similar data
https://www.eia.gov/dnav/pet/hist/LeafHandler.ashx?n=pet&s=emm_epmr_pte_y35ny_dpg&f=m

What I concluded is that as any consumer of gasoline already knew gas prices are the highest they have been since 2022.
What I found interesting is that 2007 was not the lowest time for gas prices. It was actually in 2009 when the average was $1.83 a gallon. It flucuated up and down with no drastic changes until the beginning of 2020 where it remained pretty stable until 2021 and has steadily increased since. 

Steps I took with my data
Uploaded the data into Github
Imported the github raw data file into Google Colab
Printed the dataframe to get a look at what I was working with
Looked at the top columns to see how it was all sorted
Looked for null values
Took a count of the null values to see which columns they were in
Checked the info to see what datatype each column was in
Parsed the date column from an object to a datetime format as I was trying to later on graph and it would not let me with the date as an object
I chose to drop all the rows before 2018 as some of the regions prior to then did not record any data. I thought it would be easier working with a smaller sampling.
I checked to make sure all null values were removed.
I looked at my column names as the symbols in the names were causing errors when I tried to graph later on.
I renamed all columns to just the name of the area without any symbols.
I then made smaller groups of the regions, so instead of 15 I had 9, thinking it would be easier to graph.

I chose to use a displot and a historgram to show the distribution of the data using the NY State average.

I checked the data for outliers using a boxplot.

I calculated the frequency of all values in all columns

I calculated the means of all columns

I calculated the median.

I calculated the mode.

I was having a difficult time plotting the dates into the various graphs so I dropped 2 weeks out of each month to make the dataset smaller.

I sorted the date by date in ascending order because my graphs were backwards.

I made smaller dataframes by years. 

I dropped the time portion of the date/time as it was showing up on the graphs as 00:00:00 following all dates

I made some bar charts of the various years to compare by year so they would be easier to read. 

I used the smaller dfs of regions to make a scatterplot of some of them.

I made a stacked bar graph of all the regions over seperate years. 

I made a stacked bar graph of all the regions over all the years.

I am disappointed that I was not able to produce all the comparasions that I had envisioned when I started this project. I am not sure if it was poor choice of the data set or lack of skills being brand new, or a combination of the two. I was not sure of how to make comparasions with the data other than what was obvious from the beginning. Next time I would chose a different type of data, one that would enable more variations in comparasions and one without a date column. 
