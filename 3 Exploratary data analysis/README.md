# Research of advertisements for the sale of apartments


### Data
Data from the Yandex Real Estate service - an archive of advertisements for the sale of apartments in St. Petersburg and neighboring settlements for several years. For each apartment for sale, two types of data are available. The first ones are entered by the user, the second ones are obtained automatically based on cartographic data. For example, the distance to the center, airport, nearest park and pond.

**Description of data:**

- airports_nearest — distance to the nearest airport in meters (m)
- balcony — number of balconies
- ceiling_height — ceiling height (m)
- cityCenters_nearest — distance to the city center (m)
- days_exposition — how many days the ad was posted (from publication to removal)
- first_day_exposition — publication date
- floor - floor
- floors_total — total floors in the house
- is_apartment — apartments (boolean type)
- kitchen_area — kitchen area in square meters (m²)
- last_price — price at the time of removal from publication
- living_area — living area in square meters (m²)
- locality_name — name of the locality
- open_plan - free layout (Boolean type)
- parks_around3000 — number of parks within a 3 km radius
- parks_nearest — distance to the nearest park (m)
- ponds_around3000 — number of ponds within a 3 km radius
- ponds_nearest — distance to the nearest body of water (m)
- rooms — number of rooms
- studio - studio apartment (boolean type)
- total_area — apartment area in square meters (m²)
- total_images — number of photos of the apartment in the ad

### The goal of the project
Set parameters in order to learn how to determine the market value of real estate. This will allow you to build an automated system: it will track anomalies and fraudulent activity.

### Completed tasks

Processing/filling gaps, processing anomalies, converting data types, additional calculations and adding new features, processing explicit and implicit duplicates, visualization and exploratory data analysis.

The project is finished.

### Key takeaways:
Objects throughout the database were analyzed and the following was identified:

- The highest cost is for properties with a large area (50-100 sq. m.), 3 rooms and close to the center.
- The highest cost of objects located not on the first or last floors.
- The highest prices for properties advertised on Monday and Tuesday in September 2015.
- Of the cities with the largest number of advertisements (10 cities), the highest cost per square meter is in St. Petersburg, the lowest is in Vsevolozhsk.

Next, the objects of St. Petersburg were analyzed and the following was revealed:
- The highest cost per square meter is for properties with a large area, one room and a close location to the center.
- The highest cost of objects located not on the first or last floors, as throughout the entire database.
- Based on the calculated correlation, a positive linear relationship is clearly observed between the factors price and area.

### Libraries used

Pandas, numpy, matplotlib, seaborn
