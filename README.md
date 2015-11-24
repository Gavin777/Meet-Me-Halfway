# Meet-Me-Halfway

This is an interactive webpage that provides a map and directions (by car, walking, biking or public transport) for two people looking to meet halfway.

Takes a destination and search query (i.e. dinner) as inputs. Automatically retrieves user’s current location and provides directions to the halfway point or the location(s) of interest selected from the search query.

Note: I ran into an issue with Geolocation in Google Chrome as Chrome does not allow your location to be found if you simply open up the html file. I solved this issue by starting up a Python server (with Python 2.7.6). I ran "python -m SimpleHTTPServer 8000" in the correct directory and got to view my webpage at "http://localhost:8000/Maps.html".
