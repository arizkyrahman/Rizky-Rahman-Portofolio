# [Project 1: Salary Estimator](https://github.com/arizkyrahman/ds_salary_project)
- Created a tool that estimates salaries (MAE ~ $ 11K) to help them negotiate their income when they get a job.
- Scraped over 1000 job descriptions from glassdoor using python and selenium
- Engineered features from the text of each job description to quantify the value companies put on python, excel, aws, and spark.
- Optimized Linear, Lasso, and Random Forest Regressors using GridsearchCV to reach the best model.
- Built a client facing API using flask

![](/images/positions_by_state.png)

# Project 2: Scraping Rental Price
- Using a fingerprint to verify against the data lake if a property needs to be downloaded or not.
- Placing an S3 API in front of object storage gateway-mode to stay cloud-agnostic. 
- Adding Database features to S3 – Delta Lake & Spark
- Automatic Schema Evolution.
- Open-Source dashboarding with Apache Superset

![](https://github.com/arizkyrahman/Rizky_Portofolio/blob/main/images/Scraping%20Rental%20Price_%201.jpg?raw=true)

# Project 3: Log Analytics
- Visualizing the complete Architecture of the system.
- Installing Spark and using it for data processing and cleaning.
- Reading data from Kafka via Spark structured streaming API.
- Installing Kafka and using it for creating topic.
- Continuously loading data in Cassandra for aggregated results.
- Displaying live stream, hourly and daily results using Python Plotly and Dash.

![](https://github.com/arizkyrahman/Rizky_Portofolio/blob/main/images/log%20analytics%20project1.jpg?raw=true)

# [Project 4: Customer Analysis](https://public.tableau.com/app/profile/achmad.rizky.avasyah.rahman/viz/customer_analytics_pract2/CustomerAnalysisDashboard?publish=yes)
Customer data visualization is fantastic in terms of helping a business analyze and improve its performance. It’s for that reason that the first step – before getting to visualizing data – is to define the main aspects of the customer journey. By defining the main points of the customer experience and taking informed decisions in relation to it, a company is more likely to boost its customer engagement and make the customer journey a pleasant one.  

In a few words, a customer-centric attitude increases customer satisfaction and makes a company more popular and successful. In order for a company to define what the main aspects of the customer experience are, it first needs to understand the steps through which their customers are passing and where such steps might lead. 

![](https://github.com/arizkyrahman/Rizky_Portofolio/blob/main/images/customer_analysis_tableau_achmad_rizky.jpg?raw=true)

# [Project 5: Crawling For Inflation](https://github.com/arizkyrahman/rizky_rahman_web_crawler_for_online_inflation)
- AWS Athena to query indexed WARC Files using HTTP header information in WARC File	
- Keys to webpages of interest saved in parquet files on S3
- Parquet + WARC input to Spark with distributed processing over (10 GB) data per job
- Cleaning, filtering, and aggregating Product and Price tables with Pandas in Python.
- Plotting and tracking price trends with Dash

![](https://github.com/arizkyrahman/Rizky_Portofolio/blob/main/images/crawler_pipeline.png?raw=true)

# [Project 6: Ball Image Classifier](https://github.com/arizkyrahman/ball-image-classifier)
I built a ball classifier to identify balls from different sports. This could be useful for someone who is new to sports from a certain country. They could take a picture of a ball and an app could serve them some information about the history and rules of the game. This is the underlying model for building something with those capabilities. 

I was able to get the model to predict the sport of the ball with 94% accuracy after minimal tuning. For most of the cases this would meet the need of an end user of the app. To get these results I used transfer learning on a CNN trained on resnet34. This created time efficiencies and solid results.

![](images/matrix_results.png)
