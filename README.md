# Data Analysis of google play store and app store
In this project analysis of data of two datasets is made by using simple python programming.
## Exploring two datasets
Firstly, after importing csv files of two datasets, the columns and rows of datasets are explored by using explore_data function.
## Cleaning the Data
The row 10472 of google play store have rating equals to 19 which is incorrect as maximum rating is equal to 5. So, we delete this row.
## Removing Duplicate Entries
We don't want to count an app more then once, so we removing duplicate rows from our datasets.
## Removing Non-English Apps
There are certain rows which are are not in english language. We analyze the data which have only ASCII characters.To minimize the impact of data loss, we'll only remove an app if its name has more than three non-ASCII characters.
## Isolating free apps
Our dataset contains both free and non-free apps and we'll need to isolate only free apps for our data analysis.
## Most Popular Apps by Genre on App Store and Google Play Store
To find most popular apps , we can calculate the average number of installs for each app genre.
## Conclusion
In this project, we analyzed data about the App Store and Google Play mobile apps with the goal of recommending an app profile that can be profitable for both markets. We concluded that taking a popular book (perhaps a more recent book) and turning it into an app could be profitable for both the Google Play and the App Store markets.
