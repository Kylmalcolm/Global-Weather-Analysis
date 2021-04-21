<h1> Global Weather Analysis </h1>

I used a python script to visualize the weather of 500+ cities across the world of varying distance from the equator using https://pypi.python.org/pypi/citipy and the https://openweathermap.org/api. First I generated a list of over 500 randomly selected cities and then ran those cities through the Open Weather Map API to gather additional data.

![image](https://user-images.githubusercontent.com/70925750/112420699-a6ea8780-8cfb-11eb-9df2-4a9227ddc170.png)

From there I was able to create multiple graphs to examine the impact of location on various enviromental attributes like cloudiness and temperature.

![City Latitude vs Max Temperature](https://user-images.githubusercontent.com/70925750/112420729-b1a51c80-8cfb-11eb-83ed-5fdf9c9e950f.png) ![City Latitude vs Cloudiness](https://user-images.githubusercontent.com/70925750/112420764-c08bcf00-8cfb-11eb-87d9-e223dbff335e.png)

In addition to this I was able to examine the different hemispheres and see if there was a strong correlation by location for those same attributes.

![Northern Hemisphere City Latitude vs Max Temperature](https://user-images.githubusercontent.com/70925750/112420904-0ba5e200-8cfc-11eb-9bf2-34ef5c8fe6fd.png) ![Southern Hemisphere City Latitude vs Max Temperature](https://user-images.githubusercontent.com/70925750/112420918-11032c80-8cfc-11eb-8299-4fd733fd5959.png)

After looking at weather patterns I filtered my search to those cities that were currently in an ideal temperature range of 75-80 degrees fahrenheit and used Google's map API (https://maps.googleapis.com/maps/api/place/nearbysearch) to search for nearby hotels.

![image](https://user-images.githubusercontent.com/70925750/112421108-7820e100-8cfc-11eb-827b-078aee01eaa9.png) 
