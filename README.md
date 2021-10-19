# Fractal alert using JavaScript

## Introduction
  Fractal alert is a repository for developing an effective warning system that would predict and prevent the impact of natural disasters such as earthquake, hurricanes, floods, etc.
[Fractal-Wikipedia](http://en.m.wikipedia.org>wiki>Fractal).
*A fractal is a never ending pattern.*

## How it works ##
Fractal Alert uses concept that earthquakes are a fractal distribution of clustering seismicity with the self similarity function. Same is for floods being continuous function of time and is characterized by its temporal fraction. Hurricanes is a large entity into which storms converges. Storms are composed of large series of air currents that has fractal dimension of even smaller entities. Floods are a fractal pattern of rivulets and sediments.
Also, fractal changes contributing to water-table fluctuations reflects the ongoing hydro-tectonics of the region.  

![Early Earthquake Warnings](https://prd-wret.s3.us-west-2.amazonaws.com/assets/palladium/production/s3fs-public/styles/atom_page_medium/public/thumbnails/image/fs2014-3083-1-mod.png). 


For Tsunami, early warning of high sea waves, that has fractal dimension of smaller chains in the sea bed contribute to larger Tsunami.   

![Dart](https://nctr.pmel.noaa.gov/Dart/Jpg/dart_mooring0.jpg)

*The mandelbrot set explains as that infinitely recursive algorithm can compute these fractals*.[Mandelbrot Set](https://en.m.wikipedia.org/wiki/Mandelbrot_set)

So, program can predict these disasters if it is able to compute the fractal data of such catastrophes, eg- it can analyse the large spatial consistency global positioning system-derived vertical velocities that expose small amplitude but spatially considerable, coherent pattern of  subsidence straddling the fault system.
The sensor picks up "infrasonic low pitched vibrations that are trigger to these catastrophes.
For calculations we know volume for surface area of the affected region that will be limited, and so iterating fractal program could be approximated so that we don't recur to infinity i.e. scaling factor *epsilon* that corresponds to scaling invariance shall be set to a finite value.

## Parameters
For hydro-seismic disasters, sensor will fetch spatial temporal changes in the fractures of the regions that have bad history of natural calamities. This shall be achieved by a recursive algorithm that will take into concern "the degree of multifractality","the sparseness" and "the degree of smoothness". The mentioned parameters can be computed via a JavaScript program. This data would be essential in determining the generation method of these hydro seismic disasters based on Fractal Geometry.
For earthquakes, the time duration of earthquakes over the years can be self-similar (the time series possess self-similarity in the Hausdorff Besicovitch dimension).
For floods, considering Hausdorff measure-H, Hurst component-H', fractal dimension-D, flood intensity-F and volumetric flow of river as function of time.For Hurricane prediction, Chaos Theory comes in handy. 
The sensor for the infrasonic low pitched vibrations must have a long endurance, long range and greater accuracy to sense those fractals.


![Grove Sensor](data:image/jpeg;base64,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IiAiIgIiICYXEuFUagYtqSz0JHxD+lhuPsZmxA574j8JoiqtTMCMsvOebGf05x02mo8S4Vc5y6tnuaypz74M7BxfQG1cqcOOmeh9jNTv0eoU4NFh91BcflcyNavXVncYa4+t/rzbLf6/LRK+E3qpCrycwwWcjOO+AOkq9XwVkxyuGJ7Ecv4M6TfwnVW7JUw/rwn/AJEf2mC/gnW83NmjH8Jds/8Ajj+8tjl3n7Z0t+1NfdbXMramQ4YEf3H5nibtxThNtG1tTIM/MRzIfow2lJbw1G6fCf5f9p1Z+VP5Rlr4l/jVJAmdfwt16fGPbY/iYTVFT8pB9xidGd516rn1jWfuhieNPWAx+s9LW02Tw74Wa1g9g5U9O5jfJnM7qMZu71GHwfgVmrszuE6c3TOPQTqXhvgSryqgwqH4n7f0j1P+P85PA+ChlHKPLqHcbM2OynsPf8eo2qqsIAqgKo2AGwE87e7u916GOOYnh7iIlVyIiAiIgIiICIiAiIgIiICIiAiIgIiICIiAiIgIiIHh6wwIIBB2IO4I9CJrnFfBOmuyUB07+teOXPuh2/GJs0QntyfifhLV0b8nnp/FTljj3T5vxn6yuShHGGAPbB7TtMwOI8Go1H+pWrN/GPhcf/obx68wv1TquZ8M4FTz8xAAG+52m88J4RzAF15U7L0Zh/N6D279/SZHD/DVNL84Lvj5RYVIU+uwGT9ZdR3b5tZ5xnPqPgE+xELkREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQEREBERAREQP/Z)


## Coding
1. Earthquake- (location)
```javascript
   {Latitude:"97.568722";
    Longitude:"73.791065";
   }
```
2. Natural Calamities in general- 
   (Current Weather,temperature,forecast,location)
```javascript
   {
    var weather = require('weather-js');
 
     // Options:
     // search:     location name or zipcode
     // degreeType: F or C
     weather.find({search: 'Lucknow,India', 
     degreeType: 'F'}, function(err, result) {
     if(err) console.log(err);
     console.log(JSON.stringify(result, null, 2));
     });
```
3. Generate Fractal (An illustration)
```javascript
var canvas = document.getElementById('myCanvas');
var context = canvas.getContext('2d');
```

## Conclusion
Fractal Alert aims to make change on earth, fostering hope among the masses that we can now predict therefore prevent  disasters by taking necessary action "beforehand", safeguarding those innocent lives. It's time to challenge interglot that calamities can't be predicted.  
[![Deploy to Azure](http://azuredeploy.net/deploybutton.png)](https://azuredeploy.net/)
