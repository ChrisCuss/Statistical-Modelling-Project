# Final-Project-Statistical-Modelling-with-Python

## Project/Goals
**Part 1: CityBikes API**
- Check out CityBikes API, get how it works.
- Pick a city, get all bike station info.
- Get lat, long, and bike numbers for stations.
- Put this data into a Pandas dataframe.

**Part 2: Foursquare & Yelp APIs**
- Connect to Foursquare and Yelp.
- For each bike station, find nearby restaurants/bars and other cool stuff.
- Make DataFrames for Yelp and Foursquare data.
- Compare which API gives better info for the area.

**Part 3: Joining Data**
- Mix CityBikes data with Yelp and Foursquare data.
- Use graphs or charts to see what the data says.
- Make an SQLite database to keep all this info.

**Part 4: Making a Model**
- Create a regression model to see if there's a link between bike numbers and what's around.
- Talk about what the model shows.
- Think about how to turn this into a yes/no type question (classification problem) and jot down ideas.

## Process
**Process Outline**

1. **Initial Setup**
   - Open Jupyter Notebook for coding and data analysis.
   - Ensure all necessary libraries (`pandas`, `requests`, `sqlite3`, `json`, `lxml`, `matplotlib`, `seaborn`) are installed.

2. **Exploring CityBikes API with Postman**
   - Use Postman to send requests to CityBikes API.
   - Familiarize with the API responses and data structure.

3. **Data Retrieval and Analysis in Jupyter Notebook**
   - Write Python code in Jupyter Notebook to connect and fetch data from the CityBikes API.
   - Select a city and retrieve bike station data (latitude, longitude, bike count).
   - Store and manipulate this data using Pandas dataframes.

4. **Interacting with Foursquare and Yelp APIs**
   - Explore Foursquare and Yelp APIs using Postman.
   - In Jupyter Notebook, write scripts to fetch data from these APIs for the selected bike stations.
   - Organize the data into Pandas DataFrames for analysis.
   - Use `json` for parsing and handling API responses.

5. **Comparing API Data**
   - Use Pandas to compare Yelp and Foursquare data for coverage and quality.
   - Analyze which API provides better information for the selected area.

6. **Data Merging and Visualization**
   - Combine CityBikes data with Yelp or Foursquare data in Jupyter Notebook.
   - Utilize `matplotlib` and `seaborn` for data visualization to explore the combined dataset.

7. **Database Creation with SQLite**
   - Use SQLite for database management.
   - Create and structure a database to store the combined data.
   - Implement data validation to ensure accuracy and integrity.

8. **Building a Regression Model**
   - Use Python `statsmodels` in Jupyter Notebook to build a regression model.
   - Analyze the relationship between bike counts and POI characteristics.
   - Interpret the model results and provide insights.


## Results
- I tried to predict the number of free bikes at a station based on it's location and the rating of nearby restaurants.
- This was a bad model because it resulted in a very low R-Squared value and the P-Value of all the variables was above 0.05 .

## Challenges 

When I worked on my statistical modeling project with Python, I faced a few challenges:

1. **Understanding API Data:** Figuring out the CityBikes, Yelp, and Foursquare APIs was tricky. Their data structures were complex, making it hard to extract the info I needed.
2. **Data Quality Issues:** Getting consistent and complete data from different APIs was a problem. There were format mismatches and some missing details, which made analysis tough.
3. **Merging Data:** Combining data from CityBikes, Yelp, and Foursquare into one usable format was challenging. Aligning the different data fields and dealing with missing values took some effort.
4. **Modeling Limitations:** Building the regression model was tough. The low R-Squared value indicated that the model wasn't great at predicting bike numbers based on location and nearby restaurant ratings.

## Future Goals
(what would you do if you had more time?)
1. **Get Better with APIs:** I want to improve how I handle API data, especially the tricky parts.
2. **Work on Data Cleaning:** I'll focus on cleaning and organizing data better before analyzing it.
3. **Learn More About Data Merging:** I'm aiming to get better at combining data from different sources.
4. **Upgrade My Modeling Skills:** I plan to learn more about making better predictive models.
5. **Boost Database Management Skills:** I want to get better at managing databases to handle data more efficiently.