Amazon Customers Data Analysis Project Description

In this data analysis project, I embarked on a journey to uncover insights from a dataset containing Amazon customer reviews. My exploration began by importing essential Python packages such as pandas, numpy, seaborn, and matplotlib to facilitate data manipulation and visualization.

The dataset was stored in a SQLite database, and I seamlessly connected to it using the sqlite3 library. Leveraging pandas' capabilities, I retrieved the data into a DataFrame, setting the stage for a comprehensive analysis.

To ensure the data was primed for analysis, I embarked on data preparation tasks. This involved basic cleaning processes such as removing invalid rows and duplicates. Additionally, I converted the 'Time' feature to datetime format for easier manipulation.

My analysis then delved into understanding user behavior for product recommendations. By aggregating data based on UserId, I gleaned insights into the number of summaries, texts, average scores, and the quantity of products purchased by each user. This provided valuable insights into customer engagement and preferences.

Identifying the most frequently sold products was another crucial aspect of my analysis. By analyzing product occurrences in the dataset, I pinpointed the top-selling items, offering valuable information for inventory management and marketing strategies.

Next, I segmented users into 'Frequent' and 'Not Frequent' categories based on their purchase history. Comparing the review score distributions between these segments provided insights into customer satisfaction and loyalty.

To understand user engagement further, I investigated whether frequent users tended to write longer reviews. Analyzing the length of feedback provided insights into user verbosity and engagement levels.

Finally, I conducted sentiment analysis on review summaries using the TextBlob library. By determining the polarity of sentiments expressed in the reviews, I identified common positive and negative keywords used by customers, offering actionable insights for product improvement and customer satisfaction enhancement.

In conclusion, this data analysis project provided valuable insights into Amazon customer behavior, product popularity, sentiment analysis of reviews, and user segmentation. These insights can inform strategic decision-making processes aimed at enhancing customer experience and driving business growth on the Amazon platform.

