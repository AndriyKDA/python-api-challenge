# python-api-challenge
API homework challenge

this works contains two scripts:

1) WhetherPy: The script to visualize the weather of 500+ cities across the world of varying distance from the equator, utilizing a simple Python library, the OpenWeatherMap API, and using statistical methods and regresison analysis to analyze the data. The key takeaway of the analysis are included as a markdown in the  script, as well as at the end of this document. 

2)  VacationPy: based on the data of (1), the script uses Google Places API to plot humidity data and selection of cities based on the predetermined criteria


Key takeaways of the regession analysis of the weather of 500+ cities across the world
    
1) an intial analysis of the scatter plots suggests that data is more closely scatered for the latidude and temperature relation, indicating that there might be a stornger corelation bewteen these two variables
2) More detailed linear regresion analsyis confirms this argument:
        a)  The correlation between Max Temp vs. Latitude Linear Regression in Northern Hemisphere is relatively strong (-0.72) and the relation is inverse, meaning that the higher the latitude is, the lower the temerature gets. 
        b)  The correlation between Max Temp vs. Latitude Linear Regression in Southern Hemisphere is also relatively strong (0.77) and the relation is direct, meaning that the higher the latitude is, the higher the temerature gets.
3) the correlation bewteen latutude and other variables such as wind speed, cloudiness and humidity was very weak for both Northen and Southern Hemispheres, suggesting that the latidiude does have an impact on the cloudiness, humidity or the wind speed.
