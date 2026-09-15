# Education courses report — text edition

Text extracted from Joana’s original Word report. Original wording and historical figures are preserved; chart layouts are available in the downloadable documents. This is not a newly verified analysis.

2023JOANA OWUSU-APPIAHDATA ANALYST3/25/20232023JOANA OWUSU-APPIAHDATA ANALYST3/25/2023REPORT ON THE ANALYSIS OF THE EDUCATIVE COURSES DATAREPORT ON THE ANALYSIS OF THE EDUCATIVE COURSES DATA

2023

JOANA OWUSU-APPIAH

DATA ANALYST

3/25/2023

2023

JOANA OWUSU-APPIAH

DATA ANALYST

3/25/2023

REPORT ON THE ANALYSIS OF THE EDUCATIVE COURSES DATA

REPORT ON THE ANALYSIS OF THE EDUCATIVE COURSES DATA

Table of Contents

Background1

Problem Statement1

Design2

Data Cleaning2

Tools2

Findings2

Analysis5

Pricing5

Conclusion6

Background

Educative is an education technology company that offers online courses in four subjects: Web Development, Business finance, Musical Instruments and Graphic Design. As of 2017, the various subjects had the following number of individual courses:

Subject

Count of Courses

Web development

1203

Business Finance

1191

Musical Instruments

680

Graphic Design

602

The Head of Curriculum wishes to increase the prices of Web development courses since they are the most popular and needs to know ways to increase earnings for the next quarter.

The aim of this analysis, is to present recommendations on how Educative can increase revenue for the next quarter.

Problem Statement

After visualization, there is a noticeable dip in the number of subscribers and total course prices from 2016 to date. Out of the 4 subjects, even though web development and business finance have a difference of 12 courses, there are more subscribers for the former than the latter. Graphic Design has 602 courses, which implies relatively fewer subscribers; however, it recorded the highest reviews across all the levels compared to the other three subject areas.

Should the company increase the prices of web development courses, would it affect the number of subscribers for the subsequent years? Since graphic design has the potential to increase revenue, would increasing the number of lecturers and the number of courses affect the course subscribers?

Methodology

Data Cleaning

The data provided by Educative Company was in separate files according to the four subjects. I imported the folder into Excel, and since they had the same columns, I appended the various sheets into a single table.

For null values, some rows had no values recorded for specific columns, while some rows were entirely empty. I deleted the empty rows, segmented the rows with some empty column entries, and cleared them as well.

The web development column had this format:

Subject: Web development

This subject title was extraneous, and so with the find and replace tool, I replaced it with just Web development.

The published date column provided by the company had timestamps, so I created an entirely new column to house just the dates since they were the most relevant measure for the analysis.

I went ahead and summarized the entire 3676 rows into a pivot table to facilitate the entire analysis.

Tools

The bulk of the analysis was done in Microsoft Excel, but since the CEO of Educative required a Power BI visualization, I replicated the work on Power BI.

Findings

The yearly subscribers for all the courses declined after a rise for all subjects in 2015 and since 2016. Business Finance, however, had a steady curve from 2012 to its fall in 2017. The graphic design follows suit with a wavy performance, with its highest being in 2015.

The main difference between the course subscribers of Web development and the bottom-performing subjects is the number of individual courses under them. Graphic design and musical instruments have fewer subscribers compared to the top two because of the number of individual courses. 

The average prices of the subjects reveal that the web development courses are far more expensive than all the other courses, especially the Intermediate level courses. Business finance, graphic design, and musical instruments follow the web development courses in descending order of expense.

The course ratings, however, tell a very different story: Graphic Design courses have high ratings compared to the other courses, especially the expert-level courses. Business Finance courses follow before the popular web development courses and then musical instruments courses.

A different pattern in pricing is seen across the years. In 2015 when we recorded the highest subscribers, the subject prices shot up in 2016. But 2016 recorded a decline in subscribers which fell massively in 2017.

The average duration of the courses has the highest being 5.59 hours for web development, followed by Graphic design at 3.59 and business finance at 3.56, and ultimately musical instruments at 2.85 hours.

Analysis

Pricing

For web development courses between 2011 and 2012, there were 119K subscribers against a $310 total course price. 2012 – 2013 saw a sharp increase in subscribers and a $10000 dollar total price increase. Even though the number of subscribers stabilized in 2014, the total pricing was up to $20,000. After the prices totaled 67.83K in 2015, the subscribers fell drastically from 2016 to 2017. It is possible that at that peak, subscribers could no longer afford the average hence the fall. But even after the prices were drastically reduced to a total of $30000, the subscribers still reduced.

Increasing the prices of web development courses would not increase the number of subscribers. Ratings of the web development courses compared to the others suggests that they might generally be lacking in quality. The low ratings might be the cause of how saturated the courses have become in that subject. An alternative approach would be increasing the quality of the courses instead of the quantity and the pricing.

Years

Total subject price($ per 1000)

Subscribers(per 1000)

2014

23.80 

1,953

2015

67.83

3,475

2016

84.26

2,978

2017

54.22

1,000

Graphic Design

Since the graphic design courses have higher ratings, we can increase the pricing and also the number of courses, especially for the expect level.

Business Finance

The business finance courses have higher ratings than web development courses but averagely cost the same amount. However, the finance courses have 427K subscribers against 2173K subscribers for web development courses. We could reduce the prices to gauge customer interactions.

Number of Lecturers

The highest total ratings is uniformly accompanied by the highest number of lecturers, across all subjects. Total ratings for the subjects increase with an increase in the number of lecturers. The platform could invest in more lecturers especially for courses like the graphic design and web development. This will eventually affect the number of course subscribers. 

Conclusion

Web development courses are more popular than the business finance courses. This is seen in the fact that even when their prices were the same, there were more web development subscribers. However, since 2016, the subscribers keep reducing; if the course prices increase, subscribers will further decrease. To increase revenue with Web development courses, the company could invest in advertisement and marketing strategies to get more subscribers.

Resources should be diverted to growing the Graphic design courses, which have the least number of courses but the highest ratings. Higher ratings mean customer satisfaction hence an increase in pricing as well as the number of courses will generate more revenue.

Business Finance courses should also be reviewed. There are more paid business courses than there are for web development. Yet the staggering difference between their total prices throughout the years. Generally, people taking business finance courses online might require certifications to land jobs roles and so paying for just the courses wouldn’t be a worthy consumer investment. Course prices for business finance can be reduced and other sources of finances could be explored on the websites like running advertisements.
