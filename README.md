
TABLE OF CONTENT:

Summary Ask: Business Task Prepare:

a) Data Location

b) Data Organization

c) Data Credibility

d) Data License and Privacy

Process:

a) Creating a database and importing dataset to it

b) Dataset Preview

c) Data Cleaning, transformation and manipulation

Analyze and share

Act:

a) Recommendation

b) Conclusion


Bellabeat is a high-tech company that manufactures health-focused smart products that informs and inspires women around the world.Bellabeat created first health tracker made specifically for women. It helps you manage your health and wellness, from fertility to periods to sleep quality. These smart products collect data on activity, sleep, stress and reproduction health. The data collected allows Bellabeat to empower women with knowledge about their own health and habits. Our focus will be on one of the Bellabeat products: 'Time'


Time is a wellness watch that combines the timeless look of a classic timepiece with smart technology to track user activity, sleep, and stress. The Time watch connects to the Bellabeat app to provide users with insights into their daily wellness. Reason for choosing this product is its close similarities with the non-bellabeat product; Fitbit tracker; whose dataset was specifically suggested by the Co-founder and CEO of Bellabeat to use for this study.

ASK:

Questions guiding the analysis:

What are some trends in smart device usage?
How could these trends apply to Bellabeat customers?
How could these trends help influence Bellabeat marketing strategy?
Business Task:

Identify trends on how consumers use their non-bellabeat smart device, and proffer recommendation on how Bellabeat marketing team can leverage on this; to develop great marketing strategies for more growth opportunities.

Key Stakeholders:

Urška Sršen: Bellabeat’s cofounder and Chief Creative Officer
Sando Mur: Mathematician and Bellabeat’s cofounder; key member of the Bellabeat executive team
Bellabeat marketing analytics team
add Codeadd Markdown
PREPARE:

Data and its Location: The Data used for this case study is the Fitbit Fitness Tracker Data . It is a public dataset downloaded from Kaggle and was made available through Mobius

Data Organization: The Fitbit Dataset; Fitabase Data 4.12.16-5.12.16 is a structured dataset made up of 18 CSV files. Each csv file contains different quantitative data which includes information on physical activity, heart rate, and sleep monitoring of the users. The dataset is written in a long data format that is it contains values that do repeat in the first column. Every row in the file represents an observation belonging to a Unique user Id.Every user has a unique ID and different rows since data is tracked by day and time.

Data Credibility/Limitation:

Key demographics of the users in the dataset is not known; this is the first limitations of this data set. The total number of users is 30; this not a good representation of the intended population; therefore, we are dealing with sampling bias. Another challenge we have is that the data is not current, it was collected in the year 2016; Also, the data is a third-party data as it was made available through Mobius.

Data licensing & privacy: The Metadata of our data signifies that the data is an open-source data (license is CCO: public Domain) which means this data is visible to the public and can be used and re-used by the public.


PROCESS:

I will be using  R for visualization; this will explain my findings to the stakeholders in the simplest form.

Exploring the dataset, I was able to choose the dataset that will be used for this case study. Out of the 18 csv files, I used the following:

dailyActivity_merged
sleepday_merged
WeightLoginfo_merged The above 3 datasets were used because they bear the consolidated information from the remaining tables that were not included in the analysis.


Type of users per activity level
since we don't have any demographic variables from our sample we want to determine the type of users with the data we have. We can classify the users by activity considering the daily amount of steps. We can categorize users as follows:

Sedentary - Less than 5000 steps a day. Lightly active - Between 5000 and 7499 steps a day. Fairly active - Between 7500 and 9999 steps a day. Very active - More than 10000 steps a day. Classification has been made per the following article https://www.10000steps.org.au/articles/counting-steps/


Relationship between the steps taking per day by users and the class of activity they belong to:

These was to create a demographic for the users. I achieved this by creating a new table "usertype" and classifying the users with the criteria from the above article.

ACT:

Recommendations & Conclusion


RECOMMENDATIONS: At the end of my analysis, the following insights would help guide our marketing strategy for the company to improve the market for the “Bellabeat Time” and Bellabeat products as a whole:

Design: Since our target audience are women; The team need to go above and beyond the health features and throw in some jewels, amazing designs and colors on it. Having a considerable number of designs to choose from promotes inclusivity of women with different fashion taste. This will enable more users to also wear it to occasions outside workouts. Also, with the intent of the users wearing the time piece all day, promoting the water-resistant feature, long lasting battery and light weight (to enable the users sleep with it without discomfort will help boost users’ confidence in trying them.
“If you are only wearing it when you work out, you will never get an idea of your daily habit” – rack.com.

PS: Introducing Sleep function on the App will also help users that cannot wear the Bellabeat Time to sleep (this will ensure that all users sleep record are gotten;regardless what)

“Bellabeat Time” Beep and App Notifications:
i) A beep on the Time peice and/or an early morning notification as reminders on taking enough steps and engaging in some activities for the day will help remind users to make this a lifestyle. Also, notification in the middle of the day on how many steps is remaining to achieve a daily goal or how many hours one has engaged in sedentary activities would be a great feature to have on the Bellabeat Time and App.

PS: Users should be given the options to choose if they want the midday notifications or just once a day notification.

ii) From our analysis; users sleeps less than 8hrs per day. The users should be able to set up a desired sleeping time to meet up with the recommended sleep hours. They will be informed by an alarm going off on the Bellabeat time or on the app few minutes to the scheduled time to enable users prepare for sleep.

iii) A weekly summary on how users performed and where they should improve on in the next week shoul be given to users at the end of each week.

Insight column on the Bellabeat App:
This should contain some free resources that can help users fall asleep early (e.g., Relaxing music, instrumentals), Ideas on low-calories diet that can help lose weight, articles explaining benefits of the recommended steps per day as well as activities one can engage in to help actualize them like dancing, house cleaning etc.

Reward system: Having in mind that people are motivated differently and aiming to turn customers to brand loyalist; Bellabeat can introduce points for reaching and maintaining a particular milestone for some period of time. Users can win points which can be redeemed at a certain point. Different milestones has its different points. Points can be redeemed by giving free membership subscription or vouchers to purchase things in their preferred stores.

KYC (Know your customers):

It will be paramount for Bellabeat to have some level of information on who their customers are. This can be gotten at the point of “Bellabeat time” device set up or any other Bellabeat product set up. Questions like : “what is your age?”, “Any particular goal you want to achieve with our purchased product?” will help the company understand their customers better. This is will be helpful in improving of the product and its functions in future


CONCLUSION Bellabeat's mission is to empower women by providing them with the data to discover themselves.

In order for us to respond to our business task and help Bellabeat on their mission, based on our results, I would advice to use own tracking data for further analysis. Datasets used have a small sample and can be biased since we didn't have any demographic details of users. Knowing that our main target are young and adult women I would encourage to continue finding trends to be able to create a marketing stragety focused on them.

Thank You for walking through this with me
