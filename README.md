Will It Rain On My Parade? is an interactive web app built for the 2024 NASA Space Apps Challenge.
The goal: give users a personalized dashboard that shows the probability of adverse weather conditions at a chosen place and time...even months ahead.
Unlike a forecast, our tool uses historical NASA Earth observation data and statistical modeling to estimate the likelihood of extreme weather events such as:

🌡️ Very hot days

🥶 Very cold days

💨 High winds

🌧️ Heavy rainfall

😓 High humidity / uncomfortable heat index

The app helps users plan hiking trips, vacations, outdoor events, or parades with better insight into potential weather conditions.

Typical weather apps only provide forecasts 7–14 days out.
But NASA has decades of weather data (temperature, rainfall, windspeed, dust, cloud cover, etc.) that can reveal what’s likely to happen at a specific time of year.

Our goal:
Make this powerful NASA data accessible through a simple, friendly interface that anyone can use.

This project uses historical patterns (not real-time forecasting )to help users understand whether they’re walking into a:

heat wave

rainstorm

dry spell

windy day

high-humidity situation

…long before typical forecasting tools can say anything.

🛠️ Features
-Location-based selection

Users can input a location or drop a pin on a map interface.

- Date selection

Choose any month/day of the year to analyze.

-Dynamic weather probability calculation

We calculate:

chance of extreme heat

chance of extreme cold

probability of high wind speeds

likelihood of heavy rain

probability of high wet-bulb temperature / discomfort
(using statistical thresholds)

-Statistical modeling

Weather extremes are modeled using:

Weibull distributions → wind, rainfall

GEV (Generalized Extreme Value) → temperature extremes

SciPy probability functions

-Interactive dashboard

Frontend built with: HTML, CSS, JavaScript

Results are displayed as:

-probability scores

-dynamic text explanations

-plots (temperature trends, rainfall curves, extreme value distributions)

-map-based visualization
