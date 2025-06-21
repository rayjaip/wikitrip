# wikitrip

READ ME
############################

This program is test version of an idea I had for a roadtrip podcast app that narrated descriptions of points of interest along a route. 
It uses the Wikipedia API to search for articles along path of travel, synthesises the text of the article into an WAV speech file and stores 
5 of the most recent articles locally. run on jupyter notebook running Python 3.10.12.

The 'search_grid_visualization.ipynb' file can be used to visualize the search grid used by the main program.

Dependecies:
- time package
- requests package (for the API calls)
- math package (sub coordinate calculations)
- numpy package (for location simulation)
- pandas package (for dataframe manipulation)
- PiperVoice from piper (TTS)
	- The piper voice 'en_US-amy-low.onnx' files are provided as well (credit: https://github.com/rhasspy/piper)
- wave (opening wav files)
- IPython.display (jupyter notebook display)
- ipywidgets (displaying widgets in jupyter notebook)
- os package (directory creatiion and manipulation)
- folium package (display maps)
- threading package (to apply multithreading)
 
