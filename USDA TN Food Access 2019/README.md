**USDA Food Access Research Atlas 2019 Data Analyis in Python**

For this data analysis project, I am using the USDA Food Access Research Atlas 2019 dataset and have extracted the data for the state of Tennessee to investigate food accessibility based on:
1. Distance from a food store
2. Individual resources that impact accessibility (Income, Vehicle Availability)
3. Neighborhood-level indicators of resources (average income of the neighborhood, availability of public transit)

The use data analysis tools such as Python, pandas, matplotlib, and seaborn to perform the analysis and represent the data visually.

The first analysis is for identifying the three counties with the lowest median income in the state of TN.  first aggregated the data based on the column names and set 'MedianFamilyIncome' to the min the sorted the results in ascending order. The results are as follows:

              County  MedianFamilyIncome
32  Hamilton County             10156.0
18  Davidson County             10895.0
78    Shelby County             13875.0

I then wanted to identiy the counties with the highest value for a population that reside beyond 10 miles (Low Access Population 10 miles, Lapop10) from a supermarket sorting these values in descending order.

              County  lapop10
1410     Wayne County   3288.0
390   Franklin County   2540.0
538   Hardeman County   2227.0

I proceed to look at the counties with the highest poverty rates and then create a bar chart to display the top five counties with the highest values of a Lapop1_20 which represents the population count beyond 1 mile for urban areas or 20 miles for rural areas from supermarket
![Screenshot 2023-10-09 at 12 53 21 PM](https://github.com/mercedesknapp/Python-for-Data-Analysis/assets/144730735/3a530f82-1d06-439e-ace4-d068b82c9f90)

Scatter Plot
Census Tracts
Vehicle access
