## The Impact of San Francisco International Airport Noise Across the Bay Area

Objective: To inform new and current residents on the impact of SFO noises across the Bay Area

Data Source: SF Data (https://datasf.org/opendata/)

Technologies: Pandas, NumPy, Matplotlib, APIs

<b> Step 1: Collect consistent data </b>
- Sorted through data from Kaggle, SF Data, and APIs 
- Selected four consistent CSV files
  1. Air Traffic Passenger Statistics 
  2. Aircraft Noise Complaints
  3. SFO Runway Usage
  4. Airline Noise Exceedance Rating
  
<b> Step 2: Clean and normalize data </b>
- Read CSV files into Jupyter Notebook to clean missing fields and manipulate data sets
- Filtered data to only analyze from 2010 to 2018 to ensure consistency among all variables and to identify trends
- Utilized Pandas and NumPy for cleaning, grouping, filtering, and conducting calculations

<b> Step 3: Identify Patterns and Trends </b>

I analyzed each data set to find trends through the 10 year span. I began with the most general data set, Air Traffic Passenger Statistics, to confirm our hypothesis of a constant increase in flight travel to and from SFO. I generated a variety of graphs in Matplotlib to find the best way to represent the data. I chose to share the data as a bar chart where x represented each year and y represented the number of passengeres that deplaned and enplaned from SFO.

Then, I began to study the Aircraft Noise Complaints data set. This data contained count of complaints categorized by year and Bay Area neighborhoods. I used Pandas and NumPy to create summary tables to identify top areas where most complaints originated from. For a visual representation, I thought it would be best to share the data using heat maps. My goal was to highlight areas with most complaints and their distance from SFO. In order to plot these cities and counties, I used Google's geolocation API to extract the longitude and latitude coordinates for graphing. 

The data was suprising, as I noticed most complaints came from Brisbane up until 2015 - when complaints began to increase in Palo Alto/Los Gatos. This alerted me to dive deeper into the data and to investigate further into 2015 events. I began to conduct outside research by reading articles on related topics to SFO during that time frame. I came across an article where I learned FAA changed flight paths to and from SFO in 2015. The article specifically mentioned one path (28 L/R) passing through the Palo Alto area. This seemed like a credible reason for the influx in Palo Alto complaints and so I began to look at the SFO Runway Usage data to test my hypothesis. 

SFO Runway Usage data showed the number of flights using each of the runways. Again, I used Pandas to normalize the data and identify trends. From my analysis, 28 L/R has been utilized the most since 2015. It is the biggest runway at SFO, thus contributing to the increase in flights passing through Palo Alto. 

Once I completed my analysis and identified the problem, I began to brainstorm ideas on what I can do with this data and how I can share my discovery with others. This is where I used my final dataset, Airline Noise Exceedance Rating, to identify airlines that are contributing to the disturbance in these neighborhoods as well as prompt discussions among peers and city officials on how we can begin to control noise quality around these selected areas. 
