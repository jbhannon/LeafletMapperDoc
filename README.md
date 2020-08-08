# Leaflet Mapper

General mapper that charts a set of points using *leaflet.js*

## Inputs
- **Target_div**
	- string
	- id of desired div for map placement
- **Input_type**
	- string
	- "file" or "pointset"
- **Input_name**
	- string or int
	- string of file url **-OR-** id of desired pointset
- **Filter_string**
	- object
	- default = {}
	- "lat-min"
	- "long-min"
	- "lat-max"
	- "long-max"
- **Appearance_obj**
	- object
	- ***"width"***
		- string
		- default = "400px"
	- ***"height"***
		- string
		- default = "400px"
	- ***"background"***
		- string
		- default = "streets-v11"
		- possible inputs:
			- "streets-v11"
			- "outdoors-v11"
			- "light-v10"
			- "dark-v10"
			- "satellite-v9"
			- "satellite-streets-v11"
	- ***"draw-bounds"***
		- bool
		- default = false
	- ***"zoom-state"***
		- string
		- default = null
		- *Must Have state-lat-long.json in source folder to work*
		- possible inputs:
			- "AL"
			- "AK"
			- "AS"
			- etc. (Any of the 56 US state/territory postal abbreviations)
	- ***"zoom-lat-long"***
			- array
			- default = null
			- [lat_min, long_min, lat_max, long_max]

note: default zoom (if no zoom type is selected)will bound around the inputted points with some margin

## Links
- [Leaflet Mapper](http://in-ibrc-iisdev4.ads.iu.edu/open/platform/LeafletMapper.html)
- [Available Point Sets](http://in-ibrc-iisdev4.ads.iu.edu/open/platform/point_response.aspx?list_request=pointsets)
- [Point Set 1](http://in-ibrc-iisdev4.ads.iu.edu/open/platform/point_response.aspx?list_request=points&pointset=1)
- [Point Set 2](http://in-ibrc-iisdev4.ads.iu.edu/open/platform/point_response.aspx?list_request=points&pointset=2)
- [Local Example File](http://in-ibrc-iisdev4.ads.iu.edu/open/platform/source/leaflet_source.json)
- [state-lat-long.json](http://in-ibrc-iisdev4.ads.iu.edu/open/platform/source/state-lat-long.json)
- [Leaflet Documentation](https://leafletjs.com/)
