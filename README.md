# Play-Store-App-Review-Analysis

## **Abstract:**
Android is a widely used operating system with more than 3 billion active users worldwide. In this project, we will analyze data from the Play Store App Reviews. Initially, Android was designed for cameras, but Google acquired it in 2005 and started offering it as an operating system for smartphones in 2007. Today, Android dominates a significant portion of the world's population. It is an open-source OS that allows developers to create applications. This abundance of data has made it crucial for data analytics professionals to analyze it. This analysis helps companies understand how to grow their business effectively and meet user needs. It also assists app developers in improving their products across different categories.

## Problem Statement:
The data for this project has been provided by ABC Advertising Pvt. Ltd. The goal is to analyze the data from various app categories and assist the company in meeting the needs of their global customer base. Through these analyses, the company can gain insights into customer preferences and improve different aspects of product development. The project aims to address the data provided by the company comprehensively, aligning it with their objectives, and helping them attract new customers, retain existing ones, and achieve sustainable growth. The datasets provided for analysis include Play Store Data.csv and User Reviews.csv.

## Play Store Data.csv columns:-
1. App - Name of the Application
2. Category - Category of the Application
3. Rating - Rating given to the Application
4. Reviews - No of reviews given to the Application
5. Size - Size of the Application
6. Installs - No of downloads of the Application
7. Type - Free or Paid
8. Price - Price of the Application if it is paid
9. Content Rating-It is Age appropriate or Not
10. Genres - Type of Genre the Application belongs to 11.Last Updated - When the last time the Application is Updated
11. Current Ver - Current version of the Application
12. Android Version- Minimum Android version required to run the Application

## User Review.csv columns:
1. App:- Type of Applications
2. Translated_Review:- Reviews being given by consumer
3. Sentiment:- Sentiment of trust from customer
4. Sentiment_Polarity:- It determines sentimental expression of the customer's opinion
5. Sentiment_Subjectivity:- Sentimental Subjectivity in terms is a personal opinion and it falls in range [0,1].

## Introduction:
Android is a big marketplace for app developers. When Google acquired Android in 2005, it opened up the market in 2007, allowing developers to create Android apps. This created opportunities for both developers and users. It also led to the growth of new businesses and professions. In the Android Play Store, there are three types of applications: "Background Services and Intent Receivers Applications," "Foreground Background Applications," and "Intermittent Applications."

![image](https://github.com/kuldeep-sngh/Play-Store-App-Review-Analysis/assets/112714096/b1c2eec1-f4ba-4b6c-a582-d52c62f8f66f)

In this project, we will thoroughly analyze the data available from Play Store App Reviews. Our objective is to address real-world problems and find solutions that lead to customer satisfaction and success. By examining every aspect of the data, we aim to identify and resolve challenges faced by customers in order to enhance their overall experience.

## knowing given data:
### **'Play Store Data.csv'**
**shape :** There are 10841 rows and 13 columns in this csv.
**columns :**
1. App - It tells us about the name of the application.
2. Category - It tells us about the category to which an application belongs.
3. Rating - It tells us about the ratings given by the users for a specific application.
4. Reviews - It tells us about the total number of users who have given a review for the application.
5. Size - It tells us about the size being occupied the application on the mobile phone.
6. Installs - It tells us about the total number of installs/downloads for an application.
7. Type - It tells us whether the application is free or a paid one.
8. Price - It tells us about the price of the application.
9. Content_Rating - It tells us about the target audience for the application.
10. Genres - It tells us about the various other categories to which an application can belong.
11. Last_Updated - It tells us about the when the application was updated.
12. Current_Ver - It tells us about the current version of the application.
13. Android_Ver - It tells us about the android version which can support the application on its platform.

### **'User Reviews.csv'**
**Shape :** There are 64295 rows and 5 columns in this csv.
**columns :** 
1. App : Name of app 
2. Translated_Review : Reviews given by users.
3. Sentiment : Positive, negative or Neutral opinion.
4. Sentiment_Polarity : Polarity is float which lies in the range of [-1,1] where 1 means positive statement and -1 means a negative statement.
5. Sentiment_Subjectivity : Subjectivity quantifies the amount of personal opinion and factual information contained in the text. The higher subjectivity means that the text contains personal opinion rather than factual information. Subjectivity lies between [0,1]

## Cleaning Data:
* Fixing or removing incorrect, corrupted, incorrectly formatted, duplicate, or incomplete data.
* Dealing With NaN values.

## Exploratory Data Analysis (EDA)
* Correlation between different Variables.
* what are the top categories in the play store which contains the highest number of apps?
* Top 10 Category based on average number of installs
* Which category has most number of installs?
* What are the Top 10 installed apps in 'GAME' category?
* Distribution of the ratings of the data frame.
* Distribution of 'Size' of the Apps.
* Apps with the highest number of reviews
  
**Free & Paid Comparison**
* what portion of the apps in the play store are paid and free.
* Category wise number of free and paid apps comparision.
* The top 10 expensive Apps in the play store.
* Top 10 apps that have made the highest earning.
* Most installed paid app.
* what portion of apps available in playstore under different content rating.
* Total number of apps available in playstore under different genres.
* Positive and Negative reviews comparison.
* Top 10 apps that have more positive Sentiment than negative.
* Distribution of 'Sentiment_polarity'
* Distribution of 'Sentiment_Subjectivity'

## Conclusion

we have gained valuable insights that can benefit businesses planning to launch their apps on the Play Store, as well as existing businesses seeking to improve their apps. Here are some of the key findings:

**Play Store Data.csv:**
* Variables such as Rating, Reviews, Size, and Installs show positive correlations among themselves. However, price has a negative correlation with other variables.
* The categories with the highest number of apps on the Play Store are Family, Game, and Tools, while Comics and Beauty have the fewest apps.
* The "Communication" category has the highest average number of installs, while "Events" and "Medical" have the lowest.
* The top categories with the highest number of installs are Game, Communication, Productivity, and Social.
* Subway Surfers is the most installed app in the "Game" category.
* Most apps in the Play Store have ratings ranging from 3.5 to 4.8.
* The size of the majority of apps falls between less than 1 MB to 30 MB.
* Facebook, WhatsApp Messenger, and Instagram have the highest number of reviews.
* Approximately 93% of apps in the Play Store are free.

**'User Reviews.csv':**
* Most apps have more positive sentiments compared to negative sentiments.
* Duolingo: Learn Languages Free has the highest count of positive sentiments.
* The majority of review sentiment polarity scores fall between -0.5 and 0.5, indicating a predominance of positive sentiments.
* The sentiment subjectivity scores of most reviews range from 0.3 to 0.8, indicating a higher presence of subjective opinions.

These findings are valuable for businesses as they provide insights to make better decisions and improve their apps on the Play Store. By understanding correlations, top categories, installs, ratings, and user sentiment, businesses can optimize their strategies to meet customer preferences and enhance satisfaction. This ultimately leads to greater success in the competitive Play Store environment.


