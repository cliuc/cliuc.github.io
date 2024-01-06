<html lang="en-US">

<head>
  <title>Personal Endeavor</title>
</head>
  
<body>
<header>
<h1>hello world!</h1>
</header>
<nav>
  <ul>
    <li><a href="#home">Home</a></li>
  </ul>
</nav>

<section id = "home">
  <h2>This is where my home is. My home! My home address is [redacted]</h2>
</section>

<h2>Cal Poly</h2>
<img src="https://www.calpoly.edu/sites/calpoly.edu/files/2020-01/about-calpoly-aerial.jpg">
<script src="https://www.amcharts.com/lib/3/ammap.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/maps/js/usaHigh.js" type="text/javascript"></script>
<script src="https://www.amcharts.com/lib/3/themes/light.js" type="text/javascript"></script>
<div id="mapdiv" style="width: 1000px; height: 450px;"></div>
<div style="width: 1000px; font-size: 70%; padding: 5px 0; text-align: center; background-color: #535364; margin-top: 1px; color: #B4B4B7;"><a href="https://www.amcharts.com/visited_states/" style="color: #B4B4B7;">Create your own visited states map</a> or check out the <a href="https://www.amcharts.com/" style="color: #B4B4B7;">JavaScript Charts</a>.</div>
<script type="text/javascript">
var map = AmCharts.makeChart("mapdiv",{
type: "map",
theme: "light",
panEventsEnabled : true,
backgroundColor : "#535364",
backgroundAlpha : 1,
zoomControl: {
zoomControlEnabled : true
},
dataProvider : {
map : "usaHigh",
getAreasFromMap : true,
areas :
[
	{
		"id": "US-AZ",
		"showAsSelected": true
	},
	{
		"id": "US-CA",
		"showAsSelected": true
	},
	{
		"id": "US-GA",
		"showAsSelected": true
	},
	{
		"id": "US-IA",
		"showAsSelected": true
	},
	{
		"id": "US-ID",
		"showAsSelected": true
	},
	{
		"id": "US-IL",
		"showAsSelected": true
	},
	{
		"id": "US-KS",
		"showAsSelected": true
	},
	{
		"id": "US-MD",
		"showAsSelected": true
	},
	{
		"id": "US-MO",
		"showAsSelected": true
	},
	{
		"id": "US-MT",
		"showAsSelected": true
	},
	{
		"id": "US-NV",
		"showAsSelected": true
	},
	{
		"id": "US-NY",
		"showAsSelected": true
	},
	{
		"id": "US-OR",
		"showAsSelected": true
	},
	{
		"id": "US-UT",
		"showAsSelected": true
	},
	{
		"id": "US-WA",
		"showAsSelected": true
	},
	{
		"id": "US-WI",
		"showAsSelected": true
	},
	{
		"id": "US-WY",
		"showAsSelected": true
	}
]
},
areasSettings : {
autoZoom : true,
color : "#B4B4B7",
colorSolid : "#84ADE9",
selectedColor : "#84ADE9",
outlineColor : "#666666",
rollOverColor : "#9EC2F7",
rollOverOutlineColor : "#000000"
}
});
</script>

</body>
</html>

