weather-story
=============

# NOAA Weather Story for iPhone

The National Weather Service forecast offices within the Central Region Headquarters produce a weather product called the Weather Story, which is a single-image forecast summary and brief text forecast, varying in style from office to office. For example, here is the [Weather Story for the Chicago office](http://www.crh.noaa.gov/wxstory.php?site=lot).

This project combines that weather story with local radar information, formatted to fit an iPhone display. A favicon is included so you can add this forecast to your home screen.

To use this project, place the files on your own webserver, and then load the file in Mobile Safari, adding the site information as a URL parameter. A list of Central Region site codes is [available on Wikipedia](http://en.wikipedia.org/wiki/List_of_National_Weather_Service_Weather_Forecast_Offices#Central_Region). For example, the code for Paducah, Kentucky is PAH, so you would load `index.html?site=PAH`. The default site code is LOT, which should be the site with the greatest number of residents in the Central Region.

Other NWS Regions may offer something similar, but the HTML file would need to be edited to pull the proper source images and text forecast from those sites. I made this one for myself and just wanted to set it free.

# [See it in action! (Load this link on your iPhone)](http://stopgap-mefi.github.com/weather-story/?site=lot)

You should load it on an iPhone with a Retina display to get the full effect.
