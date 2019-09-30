# graph_FORScan_data
graph ODBII data from FORScan using pandas.  takes in raw files from FORScan, plots all of the data in relation to time and RPM.  

Also charts occurances of events (true/false) or their value when applicable.  

tested in Ford diesel, so this is heavily built around injectors and oil pressure.  RPM on seconary axis may need to be changed to whatever you vehicle is tagged as.

## how to
collect data via ODBCII on FORScan
change the filename and path in the notebook
run the two charts
