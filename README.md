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

![Grove Sensor](https://e7.pngegg.com/pngimages/1016/479/png-clipart-proximity-sensor-ultrasonic-transducer-passive-infrared-sensor-parking-sensor-parts-shop-electronics-electronic-device-thumbnail.png)

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
