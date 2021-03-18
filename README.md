# python-api-challenge
A Python script to visualize the weather of 500+ cities across the world of varying distance from the equator.

**Part I - WheatherPy**

**Objetive:** to answer the question What's the weather like as we approach the equator?

As we expected (and the data confirms), it gets hotter... The dataset created is for 500+ cities around the world ramdomly choosen to evaluate the Max Temperature, Humidity, Cloudiness and Wind Speed.

**Findings and observations:**

- Temperature vs. Latitude: this plot shows that the closer the latitude is to 0°, the higer is the temprature.
- Humidity vs. Latitude: it is not a clear correlation but near latitude -20° and latitude 20° the humidity its a little less than the rest of latitudes.
- Cloudiness vs. Latitude: For this day in the year we can see that between latitude -20° and 0° there is almost 100% of cloudiness and 0% between 0° and 20°.
- Wind Speed vs Latitude: there is not visible correlation in this day (more data is required in another seasons.)
- Northen and Southern Hemispheres has very similar behaviors.

**Part II - VacationPy**

**Objetive:** analyze weather data to plan future vacations.

- Create your ideal weather and look up for cities that satisfied this requirement.
- Call an API for Google Places API to show hotels in these cities.
- Create a heatmap that display the humidity for every hotel and a pin containing the hotel name, city and country located within 5000 meters of the ideal weather cities from above.
