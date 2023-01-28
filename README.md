# Ford Go Bike System Data Analysis
## By Marzuk Sulemana

## Dataset

This data set includes information about individual rides made in a bike-sharing system covering
the greater San Francisco Bay area. The data set contains information of 183412 users.
Some of the features of the data includes the duration of rides in seconds, gender of the members,
whether members are customers or subscribers, member birth year, end and start station names etc.
The dataset can be found [here](https://www.google.com/url?q=https://video.udacity-data.com/topher/2020/October/5f91cf38_201902-fordgobike-tripdata/201902-fordgobike-tripdata.csv&sa=D&source=editors&ust=1654609222452382&usg=AOvVaw1Tbtx-fbMBlimouqoiYWzn).

## Tools
1. Python
2. Pandas
3. Seaborn

## Summary of Findings

The exploratory data analysis provided interesting information about the ford bike-sharing system.
The main feature I was interested in was the duration of members and how it is dependent on other
features of the data. I looked at the distribution of the duration in minutes and discovered that
most of the duration lie between 0 and 45 minutes. I then explored the relationship between the
duration in minutes and other features. I discovered that member bike duration was dependent on their
ages where the duration decreases with increasing age. I also found out that users who were customers
had more bike duration than members who subscribed to the bike-sharing system even though more of the
members in the system were subscribers. One observation that got me surprised was that, two females
with ages of 56 and 57 recorded bike duration more than 1200 minutes.

Aside the interested feature which is the member duration, there were relationships between other
features of the data. The number of male users was higher than female users in both subscribers and
customers. There were more males in both subscribers and customers. Also, the top two start
stations were also the top two end stations.

### See Part_I_exploration.ipynb

## Key Insights for Presentation

In the presentation, I will focus on the dependency of duration on the age of the users, the user types (subscribers or customers) and member gender (male, female, other).

I will start by introducing the distribution of the duration and show where most of the duration lies using histogram. I will then point out the relationship between duration and user age using a scatter plot. I will
also show the relationship between duration and gender in a bar plot and then duration and user type. The relationship between duration, age and gender will also be discussed using scatter plot. Finally, I will
touch on the relationship between member age and gender.

### See Part_II_slide_deck.ipynb
