# Vietnam Hybrid Methodology

This code will produce a 'hybrid' boundary for Vietnam from 1976 until present. It is used to plot out data on a consistent boundary set without having to deal with changing boundaries. 

1_vietnam_relationship.ipynb takes in a modern boundary set, a list of changes, and an initial relationship table file to produce a hybrid boundary shapefile.

2_merge_hybrid.ipynb then uses that shapefile to aggregate all of the data according to the merging conventions. It produces a CSV that can then be merged with the shapefile just on name to plot out any data from any year.
