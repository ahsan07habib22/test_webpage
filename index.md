<html>
<body>
       
<style>
.column {
  float: left;
  padding: 5px;
}

.left {
  width: 50%;
}

.right {
  width: 50%;
}
</style>

<div class="column">       
<h1> Model Setup </h1>
A numerical model has been developed using <a href="https://oss.deltares.nl/web/delft3d">Delft3D</a>, 3-dimensional modeling suite for hydrodynamics, sediment transport and morphology and water quality for estuarine and coastal environments. A curvilinear orthogonal grid was created with grid size ranging from 14 m in inlet to 475 m in the coastal area and with 5 sigma layers.  The grid represents coastline from Wabasso Beach to Indialantic Beach.
<a href="Sebastian Inlet Full Grid.jpg"> <img src="Sebastian Inlet Full Grid.jpg"> </a>
<a href="Zoomed Grid Sebastian Inlet.jpg"> <img src="Zoomed Grid Sebastian Inlet.jpg"> </a>
</div>

<div class="column">
<h1> Offshore Boundary Conditions </h1>
The model is driven by water elevation time series that includes tides and lower frequency sea level oscillations, and meteorological forcing. The temperature, salinity and sea surface elevation along north, south and east open boundaries were derived from <a href="https://www.hycom.org/data/gomu0pt04/expt-90pt1m000">HYCOM and NCODA Gulf of Mexico 1/25° Analysis</a>. The meteorological forcing (relative humidity, air temperature, wind forcing, heatflux, evaporation and precipitation) was derived from <a href="https://www.ncdc.noaa.gov/data-access/model-data/model-datasets/north-american-mesoscale-forecast-system-nam">North American Mesoscale Forecast system (NAM).</a>
</div>  

<div class="column">
<h1> Model Validation </h1>
Model results for waterlevel timeseries were compared with data from buoy data near Sebastian Inlet. There is a good match between model results and buoy data for water level timeseries with small difference in amplitude but very good match between phases. Correlation comparison is well over 90%.Following figures show some comparison.

<a href="Sebastian Inlet Water Level Timeseries.jpg"> <img src="Sebastian Inlet Water Level Timeseries.jpg" width="900"> </a>   
</div>

<div class="column"> 
<h1> Real Time Forecast </h1>
3 days of forecast timeseries data has been provided here for LOBO, Sebastian Inlet and North Jetty stations.
<a href="google earth.JPG"> <img src="google earth.JPG"> </a> 
 
<h3> Parameters Predicted </h3>

<ul>
    <li> Salinity</li>
    <li> Temperature </li>
    <li> Currents </li>
    <li> Tidal constituents </li>
    <li> Sig Wave Height</li>
    <li> Wave Direction</li>
    <li> Peak Period</li>
  </ul>
</div>

<div class="column left">
Water level timeseries forecast at Inlet station for 3 days       
<a href="waterlevel_sebastian_inlet.jpg"> <img src="waterlevel_sebastian_inlet.jpg" width="1000" align="justify"> </a>
</div>

<div class="column right">
Water level timeseries forecast at North Jetty for 3 days.       
<a href="waterlevel_northjetty.jpg"> <img src="waterlevel_northjetty.jpg" width="600" align="justify"> </a>
</div>

<div class="column">
Water level timeseries forecast at LOBO station for 3 days.       
<a href="waterlevel_lobo.jpg"> <img align="left" src="waterlevel_lobo.jpg" height="300"> </a>

Water level and Current forecast map.
<a href="waterlevel_currentmap.gif"> <img src="waterlevel_currentmap.gif" width="imgwidth"  align="center"> </a>
</div>

<div class="column">
<h3> Developed by </h3>

Ahsan Habib, PhD Candidate

<a href="https://www.fit.edu/faculty-profiles/8/gary-zarillo/">Dr. Gary Zarillo, PhD </a>

Dept of Ocean Engineering and Marine Sciences

<img src="Primary_horiz_tagline_crimson.png" width="400" align="justify">  
</div>

</body>
</html>
