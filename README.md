**NASA Facilities Weather Tracker**

 Lists NASA facilities and displays their current local temperature.



 **Features**

- Fetches NASA facility names, cities, and countries.
- Gets current weather for each location based on latitude and longitude.
- Updates the page dynamically as weather data loads.



 **APIs Used**

- **NASA Facility Dataset:** `https://data.nasa.gov/docs/legacy/gvk9-iz74.json` (accessed via CORS proxy)
- **Open-Meteo Weather API:** `https://api.open-meteo.com/v1/forecast`



 **How It Works**

1. Fetches NASA facility locations.
2. Displays the facility details on the webpage with blank temperature placeholders.
3. Requests weather data for each facility using its coordinates.
4. Populates the temperature for each location once retrieved.




<img width="2879" height="1578" alt="image" src="https://github.com/user-attachments/assets/0205666d-a2a9-43f0-b7c6-72e51c2ba88a" />
