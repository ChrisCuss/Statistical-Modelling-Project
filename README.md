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
   - Use `json` or `lxml` for parsing and handling API responses.

5. **Comparing API Data**
   - Use Pandas to compare Yelp and Foursquare data for coverage and quality.
   - Analyze which API provides better information for the selected area.

6. **Data Merging and Visualization**
   - Combine CityBikes data with Yelp and Foursquare data in Jupyter Notebook.
   - Utilize `matplotlib` and `seaborn` for data visualization to explore the combined dataset.

7. **Database Creation with SQLite**
   - Use SQLite for database management.
   - Create and structure a database to store the combined data.
   - Implement data validation to ensure accuracy and integrity.

8. **Building a Regression Model**
   - Use Python `statsmodels` in Jupyter Notebook to build a regression model.
   - Analyze the relationship between bike counts and POI characteristics.
   - Interpret the model results and provide insights.
   - Conceptualize the transformation of the regression problem into a classification problem and outline potential approaches.


## Results
(fill in what you found about the comparative quality of API coverage in your chosen area and the results of your model.)

## Challenges 
(discuss challenges you faced in the project)

## Future Goals
(what would you do if you had more time?)
