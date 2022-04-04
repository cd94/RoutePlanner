# RoutePlanner

# Using the route planner:
1. Add the following files to the repo:
    - nodes.osm
    - way.osm
    - nodes.csv
    - out.gpx
 
</br>Pre-populated versions of these files can be accessed here: https://heriotwatt-my.sharepoint.com/:f:/g/personal/cd94_hw_ac_uk/Ek_5cXjrLXtKl9cla0Dq8ykB5PiZ7U6TEVNC6NK-wdnrfA?e=2l0wTj

</br>This is the map for Edinburgh and <i>nodes.csv</i> is already populated.
</br>If you wish to map a different area use: https://extract.bbbike.org/ to get the map.osm data and split these into two files: <i>nodes.osm</i> and <i>way.osm</i>, each containing just the nodes and just the ways from <i>map.osm</i>

2. If using a new area, generate a Google Maps API key, following the instructions: https://developers.google.com/maps/documentation/elevation/start, then add the key in the quotes on line 47 of XMLReader.java. Then ensuring that <i>nodes.csv</i> is empty, run <i>XMLReader.java</i>

3. Once <i>nodes.csv</i> is populated, run <i>GraphGenerator.java</i> and follow the instructions in the console. This will populate the file <i>out.gpx</i> and using https://www.google.com/maps/d/ you can view the produced route
