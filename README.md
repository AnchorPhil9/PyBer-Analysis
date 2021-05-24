# Plotting PyBer with MatPlotLib

## Intro
Per V. Isualize’s request, we will use Python and MatPlotLib to look at PyBer data and not only calculate figures on PyBer’s fare revenue but also graph total weekly fares for each city type. Likely, we would use such data to track PyBer’s revenue success over the months of January through April as well as identify any needs for change.

## Graph Results
From our multiline graph, it is evident that urban cities rake in the most ride fares, followed by suburbs and finally rural areas. In particular, we find that total weekly fares for urban and rural areas tend to vary consistently by no more than $500, minus a pre-$2000 dip in early January for urban areas. For suburbs, the total weekly fares tend to hover around $1000, barring two spikes close to $1500 in late February and late April. Specifically in April, there is a definite increase in total suburb ride fares for the last 2 weeks. Perhaps these are indications of some significant meet ups – like a concert or fan convention – happening in the suburbs. Then again, we must also raise the possibility of PyBer adjusting their prices to meet expected higher demand for rides to and from the suburb. 

## DataFrame Results
Looking at our DataFrame, we find that, in line with our graph insights, urban cities rake in the most fares overall, followed by suburbs and rural areas. Intriguingly, though, the average fare per ride is the opposite situation. That is, it’s lowest in urban cities and rises the farther out one moves from urban cities. More surprisingly, suburban drivers collectively managed to bring in fare revenue (about $20,000) equal to half that of city drivers (about $40,000), despite there being at least four times as many city drivers as there are suburb drivers. Combined with the low average fare per urban driver ($16.57), this is a sign of the tense competition and extra work that city drivers face to make their living. That being said, city drivers still bring in the majority of Pyber’s total fare revenue (about $40,000 out of a total of $65,000). Lastly, while rural drivers are getting the biggest share of fare money, this is likely due to a combination of a small ridership base in rural areas, a small driver base for rural areas, and a longer travel time between rural areas and cities leading to higher fares being charged. Not to mention that it’s rural riders who pay the most for their ride compared to their suburban and urban counterparts.

## Recommendations
From our findings, we can conclude that PyBer’s operations have been steady and consistent but also have room for improvement.
For suburbs, we recommend that PyBer invest in their supply of suburb drivers to meet some of the increasing ridership demand, in turn reducing suburb ride fares and potentially attracting more people to take suburb rides. For urban cities, we recommend that PyBer give some incentives to urban drivers as compensation for their work in a highly competitive city rider market. For rural areas, we recommend Pyber offer reasonably discounted rates for rural riders to offset some of the high costs of their rides.

## Works Cited 

_4.7.8 Format Columns_. (2021). Bootcamp Spot. Retrieved May 22, 2021, from https://
	courses.bootcampspot.com/courses/577/pages/4-dot-7-8-format-columns

_4.11.4 Create a DataFrame for the Scores by School Spending_. (2021). Bootcamp Spot. Retrieved May 23, 2021, from https://
	courses.bootcampspot.com/courses/577/pages/4-dot-11-dot-4-create-a-dataframe-for-the-scores-by-school-spending

_5.1.3 Create Line Charts_. (2021). Bootcamp Spot. Retrieved May 23, 2021, from https://
	courses.bootcampspot.com/courses/577/pages/5-dot-1-3-create-line-charts

_5.1.4 Annotate Charts_. (2021). Bootcamp Spot. Retrieved May 23, 2021, from https://
	matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.xticks.html

_5.1.10 Plot a Pandas DataFrame and Series_. (2021) Bootcamp Spot. Retrieved May 23, 2021, from https://	courses.bootcampspot.com/courses/577/pages/5-dot-1-10-plot-a-pandas-dataframe-and-series

_5.3.2 Get the Number of Rides for Each City Type_. (2021). Bootcamp Spot. Retrieved May 22, 2021, from https://	courses.bootcampspot.com/courses/577/pages/5-dot-3-2-get-the-number-of-rides-for-each-city-type

_5.4.4 Create Box-and-Whisker Plots_. (2021). Bootcamp Spot. Retrieved May 23, 2021, from https://
	courses.bootcampspot.com/courses/577/pages/5-dot-4-4-create-box-and-whisker-plots

_5.5.1 Get the Percentage of Fares for Each City Type_. (2021). Bootcamp Spot. Retrieved May 22, 2021, from https://	courses.bootcampspot.com/courses/577/pages/5-dot-5-1-get-the-percentage-of-fares-for-each-city-type

_Accessing pandas dataframe columns, rows, and cells_. (2021). PythonHow. Retrieved May 23, 2021, from https://
	pythonhow.com/accessing-dataframe-columns-rows-and-cells/

_matplotlib.pyplot.xticks_. (2021). The Matplotlib development team. Retrieved May 23, 2021, from https://
	matplotlib.org/stable/api/_as_gen/matplotlib.pyplot.xticks.html

_Module 5 Challenge_. (2021). Bootcamp Spot. Retrieved May 22, 2021, from https://
	courses.bootcampspot.com/courses/577/assignments/11857

_pandas.DataFrame.pivot_. (2021). the pandas development team. Retrieved May 23, 2021, from https://
	pandas.pydata.org/	pandas-docs/stable/reference/api/pandas.DataFrame.pivot.html

_pandas.DataFrame.plot_. (2021). the pandas development team. Retrieved May 23, 2021, from https://
	pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.plot.html

Zach. (2020, September 20). Pandas: How to Group and Aggregate by Multiple Columns. Statology. Retrieved May 23, 2021, 	from https://www.statology.org/pandas-groupby-aggregate-multiple-columns/
