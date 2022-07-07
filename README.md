
# Housing-Rental-Analysis-for-San-Francisco
![San Fran gif](https://media.giphy.com/media/BCs20EzQnYRXi/giphy.gif)
## Instructions
I had to assume that i was an analyst at a proptech company that wants to offer an instant, one-click service for people to buy properties and then rent them. The company wanted to have a trial of this offering in the San Francisco real estate market. 
I was instructed to  to use my data visualization skills, including aggregation, interactive visualizations, and map analysis, to find properties in the San Francisco market that are viable investment opportunities.

## Steps 
I had to use the san_francisco_housing.ipynb notebook to visualize and analyze the real-estate data.
I was required  to create a visualization by using hvPlot and GeoViews. I also had to read the sfo_neighborhoods_census_data.csv file from the Resources folder into the notebook and create the DataFrame to do  the analysis.
The main outcome of this assignment was to visualize and analyze the real-estate data in  Jupyter notebook. 


1. Calculate and plot the housing units per year.


2. Calculate and plot the average prices per square foot.


3. Compare the average prices by neighborhood.


4. Build an interactive neighborhood map.




### Calculate and Plot the Housing Units per Year
* For this part of the assignment, I used numerical and visual aggregation to calculate the number of housing units per year, and then visualize the results as a bar chart. 


* I Used the groupby function to group the data by year. Aggregate the results by the mean of the groups.


* I then Use the hvplot function to plot the housing_units_by_year DataFrame as a bar chart. 


* I style and formated the line plot to ensure a professionally styled visualization.






### Calculate and Plot the Average Sale Prices per Square Foot
* For this part of the assignment, I used numerical and visual aggregation to calculate the average prices per square foot, and then visualized the results as a bar chart. 


* I grouped the data by year, and then average the results. 


* I created a new DataFrame named prices_square_foot_by_year by filtering out the “housing_units” column. The new DataFrame included the averages per year for only the sale price per square foot and the gross rent.


* I used hvPlot to plot the prices_square_foot_by_year DataFrame as a line plot.

* I styled and formated the line plot to ensure a professionally styled visualization.






### Compare the Average Sale Prices by Neighborhood
* For this part of the assignment, I used interactive visualizations and widgets to explore the average sale price per square foot by neighborhood. 


* I created a new DataFrame that groups the original DataFrame by year and neighborhood. I also aggregated the results by the mean of the groups.


* I filter out the “housing_units” column to create a DataFrame that included only the sale_price_sqr_foot and gross_rent averages per year.


* I created an interactive line plot with hvPlot that visualizes both sale_price_sqr_foot and gross_rent. 


* I styled and formatted the line plot to ensure a professionally styled visualization.



* I had to use the interactive visualization to answer questions





### Build an Interactive Neighborhood Map
* For this part of the assignment, I had to build a map, that usde the sfo_data_df DataFrame which included the neighborhood location data with the average prices.


* I had to read the neighborhood_coordinates.csv file from the Resources folder into the notebook, and create a DataFrame named neighborhood_locations_df. 


* I used the original sfo_data_df Dataframe and created a DataFrame named all_neighbourhood_info_df that grouped the data by neighbourhood.


* I then used to use the concat function to merge the  neighbourhood_locations_df DataFrame with the all_neighbourhood_info_df DataFrame. Then I cleaned the data and sets for null values


* I used hvPlot with GeoViews enabled to create a points plot for the all_neighbourhoods_df Data
Parameters given were

1. Set the size parameter to “sale_price_sqr_foot”.


2. Set the color parameter to “gross_rent”.


3. Set the frame_width parameter to 700.


4. Set the frame_height parameter to 500.


5. Include a descriptive title.





* I then had to use the interactive map to answer questions

![bridge](https://th.bing.com/th/id/OIP.O2eD-c7cE8T7z3w3GRulggHaFS?w=250&h=180&c=7&r=0&o=5&pid=1.7)