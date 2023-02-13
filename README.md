# Travelled-record
 This is a simple Python Jupyter notebook (with folium) to create a map showing your travel records.
# Pre-requisite
- Basic Python operations in Jupyter notebook.
- Anaconda environment (or any other Python system).
# How to use
1. The CSV file (our travel.csv) will hold your data to be plotted by the jupyter notebook.
- TripID is the grouping of each travel group.
- TripSeq is the consecutive series of each row belonging to the same group.
- Country is the country you want to highlight in your map.
- CountryColor is the color to use for the highlight.
- State, StateMap, StateMapKey and StateMapColor are not use for now.
- City is the City or point your want to mark out.
- Coordinates is the location on the map for city.
- RouteColor is the color for the line jointing each city of the same group.
- Marker and Circle is a boolean variable for highlighting the city. Use only either one.
- MarkerColor is the color to use, for both Marker and Circle.
- Tooltip and Popup is the text you want to show when the pointer is hovering over it.
2. You can edit the Jupiter notebook to customise your map, example, marker icon, line thickness, etc.

3. A html file (ourTravelmap.html) will be created which will show your travel map when open with most browsers, even on your mobile.

# Minimum operating environment
I use Anaconda. The easiest way to start is to create a new conda environment for this. Installing new packages in your existing conda environment most likely will create some package incompatibilties. I am using python 3.10 for my new environment. Below are the steps I used.
- conda create -n geo_env
- conda activate geo_env
- conda config --env --add channels conda-forge
- conda config --env --set channel_priority strict
- conda install python=3 geopandas

# Enjoy!
