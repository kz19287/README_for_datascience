# README_for_datascience

##  Tumour cell death rate over time

This is a pipeline written in order to process and visualise data collected from IncuCyte programs regularly used in cancer immunology laboratories. This software measures the area of the bottom of the plate covered by tumour cells. As tumour cells grow, the area covered by them increases. As cells die, the area shrinks. Immune cells can be incubated with the tumour cells which kill the tumour cells, thus shrinking the area. This data requires processing and visualisation which can be accomplished using a python script. 
To run: 
1.	Download the python script in this repository with the example data into a single directory
2.	Edit the range at which you would like to select for the 6 hour selected period. This is the period you decide is the optimum rate of cell death or cell growth in the system. The default is set from the 6th hour to the 12th. 
Our analysis shows that the control variable has a significant rate of growth while our independent variable has a significant rate of cell death driven by immune cell recognition and killing. This code can easily be expanded to process data from multiple cell lines simultaneously, allowing for visual comparison. This script could be expanded to calculate the rate cell death using the line gradient, however, this is enough to help scientists decide which condition results in the most efficient cell death. 
