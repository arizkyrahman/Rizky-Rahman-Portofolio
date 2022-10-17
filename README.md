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

# Project 3: ETL Orchestration on AWS
- Understanding the working and creating a Redshift cluster
- Creating S3 buckets using AWS CLI tool.
- Setting up a Virtual Private Cloud(VPC).
- Implementing Redshift editor connection.
- Creation and execution of Glue jobs.
- Creating an Analysis dashboard on Tableau

![](https://github.com/arizkyrahman/Rizky_Portofolio/blob/main/images/redshift_etl.jpg?raw=true)

# [Project 4: Crawling For Inflation](https://github.com/arizkyrahman/rizky_rahman_web_crawler_for_online_inflation)
- AWS Athena to query indexed WARC Files using HTTP header information in WARC File	
- Keys to webpages of interest saved in parquet files on S3
- Parquet + WARC input to Spark with distributed processing over (10 GB) data per job
- Cleaning, filtering, and aggregating Product and Price tables with Pandas in Python.
- Plotting and tracking price trends with Dash

![](https://github.com/arizkyrahman/Rizky_Portofolio/blob/main/images/crawler_pipeline.png?raw=true)
