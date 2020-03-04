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
  
<b> Step 2: Clean data </b>
- Read CSV files into Jupyter Notebook to clean missing fields and manipulate data sets
- Filtered data to only analyze from 2010 to 2018 to ensure consistency among all variables and to identify trends
- Utilized Pandas and NumPy for cleaning, grouping, filtering, and conducting calculations

<b> Step 3: Identify Patterns and Trends </b>

I analyzed each data set to find trends through the 10 year span. I began with the most general data set, Air Traffic Passenger Statistics, to confirm our hypothesis of a constant increase in flight travel to and from SFO. Then, I began to study the Aircraft Noise Complaints data set. This data set contained count of complaints categorized by year and Bay Area neighborhoods. I used Pandas and NumPy to create summary tables to identify top areas where most complaints originated from. 
  


