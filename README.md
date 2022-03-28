06 Server-Side APIs Homework: Weather Dashboard
Developers are often tasked with retrieving data from another application's API and using it in the context of their own. Third-party APIs allow developers to access their data and functionality by making requests with specific parameters to a URL. In this homework assignment, your challenge is to build a weather dashboard using the OpenWeather API.

Instructions
- Build a weather dashboard application with search functionality to find current weather conditions and the future weather outlook for multiple cities. Following the common templates for user stories, we can frame this challenge as follows:

As a traveler
- I want to see the weather outlook for multiple cities
so that I can plan a trip accordingly
<img width="1463" alt="Screenshot 2022-03-27 204327" src="https://user-images.githubusercontent.com/98859025/160308835-df21e082-b65c-4a15-b309-ffc955c13574.png">
<img width="1367" alt="Screenshot 2022-03-27 204355" src="https://user-images.githubusercontent.com/98859025/160308839-891429e7-514e-41c0-8e7d-a03867d0f33b.png">


Display the following under current weather conditions:

- City

- Date

- Icon image (visual representation of weather conditions)

- Temperature

- Humidity

- Wind speed

- UV index

Include a search history so that users can access their past search terms. Clicking on the city name should perform a new search that returns current and future conditions for that city.

Include a 5-Day Forecast below the current weather conditions. Each day for the 5-Day Forecast should display the following:

- Date

- Icon image (visual representation of weather conditions)

- Temperature

- Humidity

- weather dashboard

Hints
Create multiple functions within your application to handle the different parts of the dashboard:

Current conditions

- 5-Day Forecast

Search history

- UV index
