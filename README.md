# HealthWEbMapper

<img src="http://vision.sdsu.edu/su42/images/project/health_mapping.png" alt="HDMA_health" />

This project consists of two web-mapping applications. One is San Diego County Cancer Mapping Tool. The other one is San Diego Public Health Data Mapping Tool.

The program starts from here:
http://vision.sdsu.edu/health/  This website is the starting point.

San Diego County Cancer Mapping Tool : http://vision.sdsu.edu/su42/sdcancermap/  

San Diego Public Health Mapping Tool : http://vision.sdsu.edu/su42/sdcancermap/health.html 

The javascript codes of cancer.html and health.html are same. Only default color of the maps are different. Please note that cancer.js is imported for the cancer mapping tool, and health.js is imported for the health mapping tool.


This program does not have server side program. All data that have been used were saved in the format of Jason in javascript files. These are the data:

polygon.js  ( coordinates of all vertices of polygons)
cancer.js  (cancer data)
health.js (Diabetes, Alzheimers, Asthma, Heart Disease, Stroke and Chronic Obstructive Pulmonary Disease)
header_descriptions.js (header description of cancer data)
category_descriptions_master.js (need for grouping socioeconomic and demographic data)
CENSUS2010_v2.js (socioeconomic and demographic data 2010)
CENSUS2011_v2.js (socioeconomic and demographic data 2011)
CENSUS2012_v2.js (socioeconomic and demographic data 2012)
CENSUS2013_v2.js (socioeconomic and demographic data 2013)
NoShown.js ( remove some of variables that can be chosen on the top of the map)


Links for the related libraries and websites

Leaflet.Sync (https://github.com/turban/Leaflet.Sync)
Leaflet (http://leafletjs.com/)
Google Bar Charts (https://developers.google.com/chart/interactive/docs/gallery/barchart)
Colorbrewer was used for the map color (http://colorbrewer2.org/)
Bootstrap
AlaSQL (http://alasql.org/)
JQuery (https://jquery.com/)
Converter between JSON and CSV ( http://www.convertcsv.com/json-to-csv.htm )

***HealthWEbMapper was developed by HDMA center at SDSU. The main developer is Su Yeon Han. For questoins, email to hdmasdsu@gmail.com
* Technical Document: http://vision.sdsu.edu/su42/sdcancermap/Technical_Document.pdf *



## Copyright (c) 2017 HDMA-SDSU ##

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
