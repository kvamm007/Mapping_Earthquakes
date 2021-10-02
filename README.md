# Mapping Earthquakes

## Purpose
This can be used to view earthquakes mapped by USGS over the last 7 days. There is a layer of ALL earthquakes ("Earthquakes") as well as a layer with only "major" earthquakes of 4.5 magnitude or above. Tectonic plate lines may be toggled on or off. There are three map styles availbale- standard 'Streets', satellite view & a dark map which makes the earthquakes are fault lines stand out. 

Anyone should be able to use this code if they add their own Mapbox API key; final full version is "Earthquake Challenge"- copy folder structure, add an additional file in the JS sub-folder called 'config.js'and add the following code:
```
//API Key
const API_KEY = "(your key here)"
```

## Screenshot Previews (data as of 10/2/2021)

### Basic map, all markers
![Map- basic all markers](https://user-images.githubusercontent.com/85597801/135728338-50c5fbec-b46d-498e-abe5-b19ee03bb061.png)

### Dark map, all markers
![Map- dark all markers](https://user-images.githubusercontent.com/85597801/135728344-b7e0225d-0a5b-40ab-bf1d-bb8e3a741376.png)

### Satellite map, all markers
![Map- dark all markers](https://user-images.githubusercontent.com/85597801/135728352-d8d84f33-1bc0-4062-bb34-4791c95c24ea.png)

### Satellite map, major earthquakes only
![Map- satellite major only](https://user-images.githubusercontent.com/85597801/135728369-55641905-69e9-438a-b08d-06270ab7f55f.png)

### Additional Change 
I added an additional darker color, to accompany the "major earthquakes" segment, of an additional dark red for 6+ magnitude earthquakes. The code was changed from the original provided in these two places:
  - ![JS adding color 2](https://user-images.githubusercontent.com/85597801/135728388-61b7961e-840e-4536-a94d-e0aaa72f6864.png)
  - ![JS Adding Color](https://user-images.githubusercontent.com/85597801/135728390-dfb6b3b9-7283-4876-86d6-5a10b14a7891.png)

Darker circles are displaying correctly and the legend is updated to show the additional darker color.
