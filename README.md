# Module 6 Challenge, Weather Analysis
Paul Schaefer 10/27/2024

Through the calculations performed, regression models were performed on provided data for both the nothern and southern hemisphere for temperature, humidity, cloudiness, and wind speed. Coding to perform hotel searches based off weather conditions are found in the VacationPy file.

# Temp:
Temperature for the northern hemisphere produces a negative linear relationship, the line dropping as it moves across the graph to the right. The southern hemisphere is the opposite, producing a positive linear relationship. The temperature relationships in the scatterplot charts are tightly grouped, especially the northern hemisphere. However, there was more scattering of values found in the southern hemisphere.

The especially strong r^2 value of 0.797 for the northern hemisphere is strong evidence to support the regression modelling. An r^2 of 0.548 for the southern hemisphere is also strong but gives away the more varied data displayed on the scatter plot.

# Humidity
Humidity is flat for northern hemisphere while very slightly positive for the southern hemisphere. These values were expected before plotting the regression line with the scatterplot values being spaced so erratically across the graph. The majority of humidity readings for both hemispheres were over 50.

An r^2 values of 0.0003 and 0.005 reinforce the randomness of the scatter plot and indicate there is little knowledge to be confidently pull from this data.

# Cloudiness
Cloudiness values were slightly positive for both northern and southern hemispheres, a bit more pronounced for the southern hemisphere. The regression line starting at approximately 40 for both meant the regression line wouldn't have a dramatic slope in either direction. Cloudiness is shown to increase as the latitude value increases but is overall fairly consistent. A lot of readings were along the 0 or 100 line, especially for the northern hemisphere.

The r^2 values of 0.009 and 0.026 reinfroce the randomness and varied values of cloud coverage we can see on the scatter plot.

# Wind Speed
Windspeed provided a positive linear relationship for the northern hemisphere and negative for the southern. The relationships came out as expected, with the line only slightly raising/dropping due to the majority of the values being tightly concentrated together. One oddity to note was southern hemisphere readings becoming more tightly concentrated as the latitude reading appraoched the equator.

The r^2 values of 0.029 and 0.0513 are not as strong as the temperature values or indicate this model is over any use, but values were still better than humidity and cloudiness.
