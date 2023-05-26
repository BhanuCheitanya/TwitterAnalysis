# TwitterAnalysis
The project aims at scraping through comments on twitter using a specified keyword. After getting the keyword from the user the script then logs into the twitter ID and then searches for all the top comments related to the keyword. Then the comment, userid, timestamp, reply, retweets, likes etc are collected and stored into a excel file. 
Then the "reply" column is taken from the excel file for performing sentimental analysis. For this project VADER algorithm used to calculate the sentimental score.
