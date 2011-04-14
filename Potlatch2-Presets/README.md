<html>
<head>
<meta charset='utf-8'>
</head>
<body>
<h2>Customized Version of Potlatch2 Editor with Humanitarian Presets</h2>
<h3>Project under state of Evaluation</h3>
<p>Editing with the API is now on the main OSM Server. Below is the url to Edit using the API. The example shows parameters for latitude, longitude and zoom.<br /><a href="http://pierzen.dev.openstreetmap.org/hotpotlatch2/potlatch2.html">http://pierzen.dev.openstreetmap.org/hotpotlatch2/potlatch2.html?lat=38.2803&lon=140.87313&zoom=16</a>
</p>
<p>In this version of the API, Campsite, School and Hospital Features have been moved to the Humanitarian Features Group to facilitate editing for crisis events.</p>
<ul>
<li>HOT Transport Presets : Select a Road or Transport Feature. HOT Presets are in specific Tabs with HOT prefix.</li>
<li>Other HOT presets : Humanitarian Features Group has Presets for IDP Camps, Schools, Health Facilities and Waterpoints.</li>
</ul>
<hr />
<h3>Sources</h3>
<p> 
This repository includes the source files necessary to customize the
Potlatch2 editor, adding the Humanitarian Presets to the menu items.
A section at the end of map_features.xml contains features specific to
Humanitarian tags.</p> 

<h3>Installation instructions :</h3> 
<p>Copy a fresh installation of the Potlach2 Editor. See <a href="http://wiki.openstreetmap.org/wiki/Potlatch_2/Deploying_Potlatch_2">Potlatch 2/Deploying Potlatch 2</a> for Install Instructions.</p> 
<p>Copy the files of this Repository over this fresh installation
of the Potlach2 Editor.</p> 
<p>During the Development Phase, the api06.dev.openstreetmap.org/ Development Server is used. Once the development is finished, www.openstreetmap.org Main Server is used. The potlatch2.html file has to be modified to reflect this. As instructed in <a href="http://wiki.openstreetmap.org/wiki/Potlatch_2/Deploying_Potlatch_2">Potlatch 2/Deploying Potlatch 2</a>, the Developper must follow the steps below before users can access the API for editing :
</p> 
<ul>
<li>Open an account on the Server where the API will edit.</li>
<li>Register the customized version of Potlach2 under Settings /Oauth of the OSM account.</li>
<li>Specify in potlatch2.html default values for zoom, latitude and longitude coordinates for an area on the map.</li>
<li>modify potlatch2.html in accordance with OSM account, for values of
oauth_consumer_key and oauth_consumer_secret.</li>
</ul>  
<hr />
<h3>Quick links</h3>
<ul>
<li><a href="http://wiki.openstreetmap.org/wiki/Humanitarian_OSM_Tags">Openstreetmap Humanitarian Presets wiki page</a></li>
<li><a href="http://wiki.openstreetmap.org/wiki/Potlatch_2/Developer_Documentation/Map_Features">Potlatch2 Presets Syntax</a></li>
</ul>
<hr></hr>
</body>
</html>
