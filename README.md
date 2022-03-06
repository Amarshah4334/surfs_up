# surfs_up

# Module 9 | Assignment - Surfs Up

# Overview
Use SQLite weather database with Python, Pandas,Matplotlib and SQLAlchemy and share the results with Flask.
Analysis of weather to ensure that the new venture of setting up a surf and shake shop serving surf boards and ice cream to locals and tourist is successful. 

1.Purpose:

By performing an analysis of weather the idea is to help W.Avy, who is is wanting to invest in this business i will perform an analysis to ensure that the new venture of setting up a surf shop is successful on the basis of weather data especially during the months of June and December. 

2.Tools:
. SQLite/SQLAlchemy
. Python
. Pandas
. Matplotlib
. Flask


# Results:
## Deliverable 1 : Summary Statistics for June
Summers in Oahu is excellent time to visit for a vacation especially in the month of June. Hence our first deliverable is based on that month with a dataset of 1700 recordsfor performing a temperature analysis and understand the weather fluctuations during that month. This will help W. Avy in understanding the potential for a successful investment.
Findings:
. The mean (average) temperature during June in Oahu is around 74 degrees.
. 25 percentile and 75 percentile temperature records were 73 degrees and 77 degrees. 
. The Max temperature that was recorded in the month of June for Oahu was 85 degrees.
. Oahu is a great place for surfing and ice cream sales in the month of June.

June_Statistics


## Deliverable 2: Summary Statistics for December
December is another popular vacation time in Oahu this is during the holidays, we wil perform an analysis of the temperature fluctuations and understand whether Oahu is a great vacation place during December. The analysis was done utilizing 1517 records to understand if thats too cold for surfing or ice cream sales.

Findings:
. The mean (average) temperature in December is Oahu is around 71 degrees.
. The 25 percentile and 75 percentile temperature records were 69 degrees and 74 degrees. 
. The Max temperature that was recorded in the month of December for Oahu was 83 degrees.
. The min temperature recorded was 69 degrees.
. Oahu is a great place for surfing and ice cream sales in the month of December.

December_Statistics




# Summary: 
Provide a high-level summary of the results and two additional queries that you would perform to gather more weather data for June and December.
As per our above analysis, it proves that Oahu has great weather for both surfing as well as for ice-cream sales. Especially the most popular vacation months being June and December, both have a favorable weather. In the above analysis, it would be great if we could the following two queries in order to gather more weather data:

Analyze the levels of precipitation to get an idea of rainfall during the month of June and December.
Analyze the gust of wind mph in order to know how favorable the weather is surfing. Will have to first source the records about the wind in the past few years and filter the records for the month of June and December.
Also, as this is a full-time business, we should run queries to create some seasonal reports in order to understand the seasonal demand. Running queries for Spring, Summer, Fall and Winter months will give us an overall picture as to what to expect in those months. This will give us an overall understanding of the demand in Oahu and help us to forecast the sales for the entire year as well as plan all the raw material and supplies in a advance for optimum utilization resources.

Summary
By looking at the results, opening a surf shop would be a smart investment. This is because there is an enjoyable average temperature in two months that are 6 months apart from one another. That shows that for most months of the year, there will be enjoyable temperature for people to come and use the surf shop.

To dive a little deeper, we looked at the percipitation levels through the two months as well. The major takeaways from this analysis are:

The average percipitation is 0.136 inches per day in June
The average percipitation is 0.217 inches per day in December
50% of days in June have less than 0.02 inches of percipitation and 75% have less than 0.12 inches of percipitation
50% of days in December have less than 0.02 inches of percipitation and 75% have less than 0.12 inches of percipitation
The maximum percipitation is 4.43 inches on a single day in June
The maximum percipitation is 6.42 inches on a single day in December
"june_prcp" "december_prcp"

By looking at this further analysis it shows that there is little amount of percipitation on a normal day, but there is still days with excessive rainfall. This shows that the surf shop will be able to stay open on most days while a few rainy days will help keep the island ecosystem lush and inviting to people wanting to visit the surf shop.
