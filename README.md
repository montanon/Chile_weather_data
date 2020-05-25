# Chile_weather_data
Notebook for extracting, mounting and saving the weather data of governmental weather monitoring stations in Chile. 

***

You can get a `weather station ID` based on location from the map available in: 

https://climatologia.meteochile.gob.cl/application/informacion/mapaDeEstaciones/

***

The notebook can webscrap the entered station's registered measurements for the **variables** supported in the entered year range, mount them on a **DataFrame** and save them to local memory, if the extracted data is not already there. 

If the data was extracted and saved before, the notebook just loads the data in local memory.

  *The notebook currently supports just 3 of all the measured variables. **[Temperature, Precipitation and Humidity]***

***

After loading the data, the notebook includes some **plotting** functionalities that allow you to:

  1. **Plot the measured values of a variable for a single year.**
  
  1. **Plot all the measured values available for a variable.**
  
  1. **Create a comparative plot of different year ranges that allow to visually infer weather deviations.**

