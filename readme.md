# CUSF_tawhiri_ui

The purpose of this repository was to create a new prototype user interface for Cambridge University Spaceflight's [Tāwhirimātea](https://github.com/cuspaceflight/tawhiri) project. The user interface may be tried at [mattjudge.github.io/CUSF_tawhiri_ui](https://mattjudge.github.io/CUSF_tawhiri_ui/).

**Please note:** No guarantee is given for the accuracy, precision or reliability of the data produced by this software, and you use it entirely at your own risk.

## Tawhiri

Tawhiri is the name given to the newest version of the CUSF Landing Prediction Software, the purpose of which is described on [CUSF's wiki](http://www.cusf.co.uk/wiki/landing_predictor). In summary, the idea is to take global forecast data (from the [NOAA NOMADS GFS](http://nomads.ncep.noaa.gov/)), and predict the flight path and approximate landing of [high-altitude balloons](https://en.wikipedia.org/wiki/High-altitude_balloon). 

## User Interface

This UI was designed to provide a working prototype, with the intention of refreshing (and eventually replacing) the UI designed for the [older prediction](http://predict.habhub.org/) software. 

Several improvements were desired and implemented:

- The ability to display multiple predictions from a variety of launching times
- Support for both metric and imperial units
- Support local timezones
- Function well on mobile devices
- And of course, support the new predication API

### Libraries

The UI currently uses the following libraries:

- jQuery
- [Bootstrap](http://getbootstrap.com/) v3
- [Bootstrap Slider](http://www.eyecon.ro/bootstrap-slider)
- jQuery [DateTimePicker](http://xdsoft.net/jqplugins/datetimepicker/)
- And [Respond.js](https://github.com/scottjehl/Respond), [Modernizr](http://modernizr.com) and [HTML5 Shiv](https://github.com/aFarkas/html5shiv) to ensure compatibility with older devices.

A rewrite in Angular is definitely on the table.