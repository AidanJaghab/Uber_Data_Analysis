# Uber_Data_Analysis

# Download latest version
path = kagglehub.dataset_download("fivethirtyeight/uber-pickups-in-new-york-city")
print("Path to dataset files:", path)


This project analyzes ride data from April, May, June, and July in 2014 to find the most popular Uber destinations. Using latitude and longitude coordinates, we determine which places are the most "Ubered" and then visualize them using an interactive map. This past semester, as a freshman without a car, I reviewed my long list of Uber rides and realized I had traveled all over the city of Miami. It made me wonder, if others have the same experience in NYC and, more interestingly, where are they all going? 


The project strengthened my skills in Pandas using data manipulation, aggregation, and statistical analysis. I used Folium to create interactive maps with markers and heatmaps, while Python improved my ability to clean datasets, merge files, and standardize data. This project showed me how to manage large datasets, ensure data integrity, and how to use tools like Folium.


The dataset that I found on Kaggle, was loaded into a Pandas DataFrame and cleaned by finding missing values and standardizing coordinates. I grouped data by latitude and longitude to identify popular locations. The map was saved as an HTML file, and the most popular locations were exported as a CSV for further analysis.


The interactive map highlights popular destinations in NYC and gives insights into ride patterns. Saved as an HTML file, the map is easily shareable. A CSV file with the top locations was also created to find additional information. This project has areas for improvement, such as adding radius-based classifications for locations, expanding the dataset to include variables like ride duration or cost, and performing time-based analyses to find trends.

Technologies Used
Python was the primary language, with Pandas and NumPy handling data analysis and Folium and Matplotlib used for visualization.

Contact Information
Created by: Aidan Jaghab
Email: agj49@miami.edu
LinkedIn: linkedin.com/in/aidanjaghab
