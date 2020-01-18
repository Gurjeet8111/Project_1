# Data Analysis of google play store and app store
In this project analysis of data of two datasets is made by using simple python programming.
## Exploring two datasets
Google Play Store: A dataset containing data about approximately ten thousand android apps from Google Play.
App Store: A dataset containing data about approximately seven thousand iOS apps from the App Store.
Firstly, after importing csv files of two datasets, the columns and rows of datasets are explored by using explore_data function.
## Cleaning the Data
The row 10472 of google play store have rating equals to 19 which is incorrect as maximum rating is equal to 5. So, we delete this row.
## Removing Duplicate Entries
If we explore the Google Play data set long enough, we’ll find that some apps have more than one entry.We don't want to count an app more then once, so we removing duplicate rows from our datasets.
## Removing Non-English Apps
There are certain rows which are are not in english language.One way to go about this is to remove each app whose name contains a symbol that is not commonly used in English text — English text usually includes letters from the English alphabet, numbers composed of digits from 0 to 9, punctuation marks (., !, ?, ;, etc.), and other symbols (+, *, /, etc.). All these characters that are specific to English texts are encoded using the ASCII standard. Each ASCII character has a corresponding number between 0 and 127 associated with it, and we can take advantage of that to build a function that checks an app name and tells us whether it contains non-ASCII characters.To minimize the impact of data loss, we'll only remove an app if its name has more than three non-ASCII characters.
## Isolating free apps
 we only build apps that are free to download and install, and our main source of revenue consists of in-app ads.Our dataset contains both free and non-free apps and we'll need to isolate only free apps for our data analysis.
## Most Popular Apps by Genre on App Store and Google Play Store
To find most popular apps , we can calculate the average number of installs for each app genre.
## Conclusion
In this project, we analyzed data about the App Store and Google Play mobile apps with the goal of recommending an app profile that can be profitable for both markets. We concluded that taking a popular book (perhaps a more recent book) and turning it into an app could be profitable for both the Google Play and the App Store markets.
