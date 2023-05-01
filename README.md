WeRateDogs is a Twitter account that rates people's dogs with a humorous comment about the dog. These ratings almost always have a denominator of 10. The numerators are almost always greater than 10. 11/10, 12/10, 13/10, etc. Why? Because they are good dogs! 
The WeRateDogs dataset that was wrangled is a twitter user/account that primarily contains the ratings of different dogs and rates people’s dogs with humorous comments about the dogs. The wrangling process involves steps which include: 
i. 	Gathering the data ii. 	Assessing the data iii. 	Cleaning the data iv. 	Storing the data 
v. 	Analyzing the data 
GATHERING THE DATA:  The datasets were gathered from three different sources 
1.	Enhanced Twitter Archive: This is an archive of tweets, providing quite a number of information about the dogs like the text, name, dog stages etc. This data was extracted programmatically. 
  
2.	Image Prediction file: This dataset was gotten from the top three results of the image prediction after running the images in the WeRateDogs Twitter archive through the application of Neural Network that classifies breeds of dogs. This filo was loaded programmatically. 
  
 
3.	Additional Data via Twitter API: This data was gotten by querying Twitter’s API so as to obtain the retweet count, favorite count and the tweet id. 
 
2. ASSESSING THE DATA 
After the data from these different sources, the data were then assessed both visually and programmatically. The data were checked for quality and tidiness and these issues were identified: 
For quality issues: 
1.	The rating column numerator should be a float datatype 
2.	Timestamp and retweeted_status_timestamp datatypes should be datetime instead of object. 
3.	There are about 181 retweets in the retweeted_status_id column 
4.	Incorrect ratings of 75/10 and 5/10 
5.	The jpg_urls column in image_pred_copy contains duplicates 
6.	The name column contains 'None', an indication of incorrect imputations 
7.	The datatype of tweet_id for the three datasets is int 
8.	Unwanted columns in the df1 dataset  For the tidiness issues: 
i. The dog stages should be on one column ii. The three datasets should be one dataframe 
 
3.	CLEANING THE DATA: The quality and tidiness issues outlined above were addressed as the datasets were cleaned using the define-code-test method 
4.	STORING THE CLEANING: The cleaned dataframe was therefore, ready for analysis and vsiualizaton. 
 
 
 

