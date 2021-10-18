# Business Analytics: Google Data Analytics Certificate

This is a capstone project as part of the Google Data Analytics Professional Certificate. Throughout the certificate, I have learnt tools including Excel, SQL, Tableau and R for data analysis. This case study uses Excel and R for a piece of marketing analysis. Data is provided by the course and I have uploaded them onto Kaggle https://www.kaggle.com/chinghongfung/divvy-trip-data-recent-12-months.

A detailed report could be found in the RMarkdown file detailing the thought process in each stage of the project including: 1) Ask, 2) Prepare, 3) Process, 4) Analyse, 5) Share, 6) Act. A snapshot of the major points are shown below. Please refer to the more detailed report for a clearer presentaion.

Course is accredited: https://www.coursera.org/account/accomplishments/specialization/certificate/YUET66MQ4EU8

#### Business Task (More detail in description pdf file)
Our manager, Moreno has tasked us with analysing the pattern of bike trips focussing on the difference between casual riders (one-off customers) and subscribed riders. The hypothesis raised is that subscribed riders contribute to a larger proportion of annual revenue. If this were in fact true, we shall devise marketing strategies to convert casual riders into members. By analysing trip data, we hope to uncover a trend between the two types of customers and come up with recommendation plans moving ahead.

#### Average duration of trips
This plot shows the average duration of each trip undertaken broken down into the two customer groups for each day of the week.

![Average_duration](https://user-images.githubusercontent.com/91271318/137005291-4aec167e-1993-45b4-9ff1-a4f32f043402.png)

#### Number of rides
This plot shows the number of rides broken down into the two customer groups for each day of the week.
![Number_of_rides](https://user-images.githubusercontent.com/91271318/137005294-25389fa6-e0fd-448f-b1ec-42426758c12f.png)


#### Recommendations
Recommendation 1: Include data regarding customers' details and pricing of the services. The former could be difficult to achieve due to privacy issue. Private data is kept internally with Divvy and there is hardly any open source data that could be used as alternatives given the nicheness of the market. With only the number of rides in a year, we could not calculate the revenue distribution between the two rider types. Hence, we need to gather more data before making justified decisions.

Recommendation 2: Focus on pricing strategies by creating statistical models with regards to the casual rider duration. This allows minute-based and hour-based rates to be set optimally to maximise profit. Further data could be gathered after an A/B test of the newly designed pricing to observe their performance. If the casual rider sector were to perform better, one could strategise for a shift from membership plan to one-off uses only.

Recommendation 3: Carry out marketing plan to encourage more membership uptake. As the proportion of number of rides between the two sectors seem to be relatively even, with a little pricing deviations, Cyclistic could incentivise more users to sign up for annual memberships. Marketing plans could be done within the mobile application or using social media platforms. Further data could be gathered to measure metrics such as click-through rate to quantify which marketing scheme is the most influential.
