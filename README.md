# Bike_Sharing_Data_Analysis_CaseStudy

### 1. Ask
###### Identify the business task.
###### The key business task in this case is to discover how casual riders and Cyclistic members use their rental bikes differently. Both the Director of Marketing as well as finance analysts have concluded that annual members are more profitable.

###### Therefore, the results of this analysis will be used to design a new marketing strategy to convert casual riders to annual members.


### 2. Prepare
###### Data was downloaded from https://divvy-tripdata.s3.amazonaws.com/index.html, and we will be using R for statistical analysis tools and data visualizations.

###### Identify how it’s organized.
###### All trip data is in comma-delimited (.CSV) format with 15 columns, including: ride ID #, ride type, start/end time, ride length (in minutes), day of the week, starting point (code, name, and latitude/longitude), ending point (code, name, and latitude/longitude), and member/casual rider.

###### Determine the credibility of the data.
###### Due to the fact that this is a case study using public data, we are going to assume the data is credible.


### 3. Process
###### Check the data for errors.
###### The code chunk below will import 12 individual .xlsx files as data frames, each representing 1 of the last 12 months of trip data. Some parsing errors persist, however, they represent less 0.25% of the data set, so this is still a representative sample.


### 4. Analyze
###### Aggregate your data so it’s useful and accessible.
###### This code chunk will combine the 12 individual data frames into one large data frame for analysis.


### 5. Share
###### Present findings using ggplot2 for data visualizations.


###### Summary of the key observations:

###### On average, each ride is about 30 minutes:
###### Casual users ride for 46 minutes on average.
###### Members ride for 16 minutes on average.
###### Regardless of being a member or not, the most popular day to rent a bike is Saturday.
###### Bike rentals start off at a low on Mondays, peak on Saturdays with a slight drop off on Sundays.
###### Members rent bikes on a more consistent basis throughout the entire week, whereas casual rentals are low Monday through Thursday and peak towards the weekend.
###### On any day of the week, casual users ride 2.7x to 3x longer than members.


###### My three recommendations for the new marketing strategy are as follows:
###### Offer a weekend-only membership at a different price point than the full annual membership to entice casual users towards a full annual membership. They can only unlock bikes on Friday, Saturday, or Sunday.
