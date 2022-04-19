Steps to making the borders map
1. get county polygons
2. create segments of county borders from each polygon using qgis
3. use the intersection tool in qgis to assgin 2 county geoids to each line segment 
4. export results to use in mapbox
5. import vaccination data from cdc
6. calculate difference in rates between the pairs of adjacent counties for each line segment
7. set the color and thickness of each line segment based on the difference in vaccination rates