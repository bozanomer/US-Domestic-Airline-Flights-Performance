# US-Domestic-Airline-Flights-Performance
This is a Dash project indicates US Domestic Airline Performance between 2005-2019.It was collected from United States Department of Transportation and preprocessed with Python.The project main aim is to analyze the performance of the reporting airline to improve fight reliability thereby improving customer relaibility.We are going to  run two reports.

Below are the key report items,

-   Yearly airline performance report 
-   Yearly average flight delay statistics

_NOTE:_ Year range is between 2005 and 2019.

## Components of the Report Items

1.  Yearly Airline Performance Report 

    For the chosen year provide,

    -   Number of flights under different cancellation categories using bar chart.
    -   Average flight time by reporting airline using line chart.
    -   Percentage of diverted airport landings per reporting airline using pie chart.
    -   Number of flights flying from each state using choropleth map.
    -   Number of flights flying to each state from each reporting airline using treemap chart.
2.  Yearly Average Flight Delay Statistics

    For the chosen year provide,

    -   Monthly average carrier delay by reporting airline for the given year.
    -   Monthly average weather delay by reporting airline for the given year.
    -   Monthly average natioanl air system delay by reporting airline for the given year.
    -   Monthly average security delay by reporting airline for the given year.
    -   Monthly average late aircraft delay by reporting airline for the given year.

## Results of  the Report Items

We have two kind of reports and each report has 5 different visualization which has demonstrate different kind of information.I do not want to make a depth analysis each of visaualization, I just want to show you which kind of visualization shows which information.

1.  Yearly Airline Performance Report 

I am going to choose year as 2019:
-   Number of flights flying from each state using choropleth map.

![alt text](https://github.com/bozanomer/US-Domestic-Airline-Flights-Performance/blob/main/Visualizations/Choloromap.PNG)

In choloroplethmap,  number of flights flying from each state can be seen. Thanks to hover in the dash, it can also be seen which state has how many per each airline flights.

-   Percentage of diverted airport landings per reporting airline using pie chart.

![alt text](https://github.com/bozanomer/US-Domestic-Airline-Flights-Performance/blob/main/Visualizations/newplot.png)

American Airlines has much more flights over its competitors.The rest ones has almost same number of flights.

-   Number of flights under different cancellation categories using bar chart.
![alt text](https://github.com/bozanomer/US-Domestic-Airline-Flights-Performance/blob/main/Visualizations/CancelletionCode.png)

The airline reports 3 kinds of cancellation which codes are A,B,C.These codes mean:
-       A = carrier, B = weather, C = NAS(The National Airspace System), D = security
It means there is no any cancellation because of security.As we focus on visualization, After 9th months, the weather does not has any impacts on cancellationa too and carrier problems cause in flight cancelletion occur in spring and autumn more.


2.  Yearly Average Flight Delay Statistics

What here i want to do is show  just whole visualizations together.The year is chosen as 2019 and the visualizations demonstrate how carrier affects delay time by airline, how weather gives rise to delay by airline,NAS effects on delay time by airline,average security delay time by airline and finally average late aircraft delay time by airline respectively.Who make a depth analysis can go on in the light of these visualizations.There are many outlier observations and in order to make the graph more meaningful and understandable these observations should take into consederations.
![alt text](https://github.com/bozanomer/US-Domestic-Airline-Flights-Performance/blob/main/Visualizations/Statistics.PNG)
