## IBM-Applied-Data-Science-Capstone
# IBM Data Sicence Professional Certificate Capstone

# SpaceX Falcon 9 first stage Landing Prediction
# Introduction
In this capstone, we predicted if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because SpaceX can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against SpaceX for a rocket launch. 

The following is an example of a successful and launch.
![](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/landing_1.gif)

Several examples of an unsuccessful landing are shown here:
![Image](https://cf-courses-data.s3.us.cloud-object-storage.appdomain.cloud/IBMDeveloperSkillsNetwork-DS0701EN-SkillsNetwork/lab_v2/images/crash.gif)

# Lab 1: Collecting the data [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/01.-jupyter-labs-spacex-data-collection-api.ipynb)

In this lab, we collected and make sure the data is in the correct format from an API.

# Lab 2: Web scraping Falcon 9 and Falcon Heavy Launches Records from Wikipedia [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/02.-jupyter-labs-webscraping.ipynb)

In this lab, we performed web scraping to collect Falcon 9 historical launch records from a Wikipedia page titled List of Falcon 9 and Falcon Heavy launches.

# Lab 3: Data wrangling [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/03.-labs-jupyter-spacex-Data%20wrangling.ipynb)

In this lab, we performed some Exploratory Data Analysis (EDA) to find some patterns in the data and determine what would be the label for training supervised models.

In the data set, there are several different cases where the booster did not land successfully. Sometimes a landing was attempted but failed due to an accident; for example, True Ocean means the mission outcome was successfully landed to a specific region of the ocean while False Ocean means the mission outcome was unsuccessfully landed to a specific region of the ocean. True RTLS means the mission outcome was successfully landed to a ground pad False RTLS means the mission outcome was unsuccessfully landed to a ground pad.True ASDS means the mission outcome was successfully landed on a drone ship False ASDS means the mission outcome was unsuccessfully landed on a drone ship.

In this lab we  mainly converted those outcomes into Training Labels with 1 means the booster successfully landed 0 means it was unsuccessful.

# Lab 4: SQL Notebook for Peer Assignment [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/04.-jupyter-labs-eda-sql-coursera_sqllite.ipynb)

In this lab we first understand the Spacex DataSet by loading it into the corresponding table in a Db2 database and executed SQL queries to answer assignment questions.
Overview of the DataSet: SpaceX has gained worldwide attention for a series of historic milestones.

It is the only private company ever to return a spacecraft from low-earth orbit, which it first accomplished in December 2010. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars wheras other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage.

Therefore if we can determine if the first stage will land, we can determine the cost of a launch.

This information can be used if an alternate company wants to bid against SpaceX for a rocket launch.

This dataset includes a record for each payload carried during a SpaceX mission into outer space.

# Lab 5: Exploring and Preparing Data [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/05.-jupyter-labs-eda-dataviz.ipynb)

In this assignment, we predicted if the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is due to the fact that SpaceX can reuse the first stage.

In this lab, we performed Exploratory Data Analysis and Feature Engineering.

# Lab 6: Launch Sites Locations Analysis with Folium [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/06.-lab_jupyter_launch_site_location.ipynb)

The launch success rate may depend on many factors such as payload mass, orbit type, and so on. It may also depend on the location and proximities of a launch site, i.e., the initial position of rocket trajectories. Finding an optimal location for building a launch site certainly involves many factors and hopefully we could discover some of the factors by analyzing the existing launch site locations.

In the previous exploratory data analysis labs, we have visualized the SpaceX launch dataset using matplotlib and seaborn and discovered some preliminary correlations between the launch site and success rates. In this lab, we performed more interactive visual analytics using Folium.

# Lab 7: Build an interactive Dashboard with Ploty Dash [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/07.-spacex_dash_app.py)

In this lab, we built a dashboard to analyze launch records interactively with Plotly Dash

# Lab 8:Machine Learning Prediction [Link](https://github.com/jesushidalgosanchez/IBM-Applied-Data-Science-Capstone/blob/main/08.-SpaceX_Machine_Learning_Prediction_Part_5.jupyterlite.ipynb)

Space X advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each, much of the savings is because Space X can reuse the first stage. Therefore if we can determine if the first stage will land, we can determine the cost of a launch. This information can be used if an alternate company wants to bid against space X for a rocket launch. In this lab, we created a machine learning pipeline to predict if the first stage will land given the data from the preceding labs.

# Conclusions

Trought all different lab and assignments we had the opportunity to extract alnd load data from different data sources, perform exploratory data analysis and visualizations including the generation of an interactive dashboard. We observed that the landing outocmes are somehow corelated with the flight number, the machine leraning models generated as part of the capstone are able to predict the landing success with an acuuracy of 83%.
