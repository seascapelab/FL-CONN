# FL-CONN
A repository for coral reef connectivity products.

Stored here are several shapefiles (ESRI) that contain the results of a study of both coral and disease connectivity in Florida's Coral Reef (FCR), and an assessment of reef restoration value.

# Shapefiles

RScores.shp is a point shapefile that represents the centroid of every coral reef patch used in the model. Each point has geographic information, the out-degrees of each patch for each coral species simulated, the in-degree of coral disease, and the R-values for each species for a set of beta values (0:0.2:2), described in detail in the Final Report. These results assume a coral connectivity threshold of 0.001, and a disease connectivity threshold of 0.0001.

Acer_network.shp is a line shapefile that represents the connections in the A. cervicornis coral network, and their strengths.

Ofav_network.shp is a line shapefile that represents the connections in the O. faveolata coral network, and their strengths.

Dcyl_network.shp is a line shapefile that represents the connections in the D. cylindrus coral network, and their strengths.
