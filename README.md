# Tornado-Frequency-of-Counties-in-Texas

#Problem Statement:
###
On October 20, 2019 around 10 tornadoes hit Dallas, Texas.  It left numerous individuals with homes. 
There were no notice signs until the tornadoes started to cause a lot of harm.  Many began to say 
Dallas is not a decent place to live because it is in Tornado Alley which is where a high frequency of 
storms occurs. Because the storms occurred within a 2-mile radius of my home, it clearly is the motivation
of this dataset. The quest to search for the best dataset began for the frequency of tornadoes within the
Dallas, Texas area. There was not a lot of information in the first dataset I found.  However, I found 
another that gave more information and listed the whole state of Texas.  From those datasets, I can provide
the frequency of tornadoes that occur in Dallas, Texas. 
###
#Datasets: 
 ###
 https://data.world/dhs/historical-tornado-tracks/workspace/file?filename=Historical_Tornado_Tracks.csv
 ###

#Method:
###
This model was created using R using time-series.
###
###
In my approach, I cleaned the informational indexes to expel all NA's and - 999 to help comprehend the information.
At that point, I plotted the information utilizing ggplots, and qqplots. As I was endeavoring to plot dated related 
factors, I needed to isolate the dates with the administrator work to plot the information. The date variable was an
integer. The lubridate package was used to subset the dates to make date formatting simpler. In this clean dataset, 
I could not find out everything I wanted to know about the data.  The histograms were reviewed with ggplots and qqplots 
histogram Then, correlations were performed on the variables.  From there two linear regression models on data that correlated.  
However, the information related more to composition of a tornado like width, length, longitude, latitude.  Obviously,
those would relate.  I added loess function in a few of the plots to see if there was any correlation also. Because this 
dataset did not provide the right information relating to weather conditions, I decided to narrow my research to the city of 
Dallas with yearly frequency of tornadoes and the category of tornadoes.
###
