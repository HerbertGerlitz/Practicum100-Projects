# Passengers' Preferences for Taxi Drives in Chicago
For the new ride-sharing company Zuber in Chicago we analyse the passengers' preferences and the impact of external factors on taxi rides. The given database is used for testing an hypothesis about the impact of weather on ride frequency. <br>
Hypothesis: "The average duration of rides from the Loop to O'Hare International Airport changes on rainy Saturdays."

In the previous steps of the project we retrieved data from a website and used SQL queries to get the table 'df_weather'
(Website: https://code.s3.yandex.net/data-analyst-eng/chicago_weather_2017.html). <br>
For each hour, we retrieved the weather descriptions and broke all hours into two groups: 'Bad' if the description field contains the words 'rain' or 'storm'; else 'Good'.
