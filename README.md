#  Spotify Musical Tastes by City

![Concert](readmeimg/concert.png)

### Description
Analysis and visualization of Spotify listening preferences across 15 cities: listing city demographics alongside top artists and song for each city. Filters for genre, race, and gender.

**Note:** This project was part of a larger group project I took part in, called [Popular Music Insights](https://github.com/Anaisdg/Popular_Music_Insights).

App screenshot:
![Map](_readmeimg/map.jpg)

### Technologies Employed 

* [Spotipy API for Spotify](spotipy.readthedocs.io/en/latest/#api-reference)
* [Flask](http://flask.pocoo.org/docs/0.12/quickstart/) and [Flask-PyMongo](https://flask-pymongo.readthedocs.io/en/latest/)
* [Leaflet.js](http://leafletjs.com/)
* [D3](http://d3js.org)
* [Splinter](https://splinter.readthedocs.io/en/latest/)
* [Beautiful Soup](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
* [Lyrics Wiki](http://lyrics.wikia.com)
* Pandas
* MongoDB

### Folder Breakdown

**[vis_integration](https://github.com/Anaisdg/Popular_Music_Insights/tree/master/vis_integration)**
* Integration of all visualizations, with ```app.py``` to run Flask app.

**[spotify_data](https://github.com/Anaisdg/Popular_Music_Insights/tree/master/spotify_data)**
* Data retrieval, analysis, and storage of artist, genre, song, gender, race, and city demographic data - in support of the interactive Leaflet.js map. 

### Inspiration for map visualization
* [Spotify Insights Blog](https://insights.spotify.com/us/2016/12/07/musical-map-of-the-world-2-0/)



