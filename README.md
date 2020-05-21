# rhino
DSML

Bis 22.5: Weg suchen nicht Luftlinie sodern Fahrradweg zu berechnen

Data cleaning:
1. Average Speed: > 5kmh
2. Position: In boundaries(Freiburg/Bremen)
3. Min Distance: 100m 

NEW: 4. Bike not used for more than 4 days -> maybe broken

TO do`s:
1. calculate Distance (new column) via maps (not direct!)
2. get Postalcode via Maps (new column)
3. get and organize weather data (rain (mm) and °C as extra column)

KPI`s (per hour):
1. UtiliSation: usage/day/daytime
2. Density: bikes/area
3. Demand: time unused
4. Revenue: (basic rate the rental costs 1€ / 30min and maximum 12 € / 24h)
