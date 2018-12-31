# AidTemp
Github repo for project #2 slider debugging files

The webpage is rendered using Flask-SQLAlchemy, so you need to run the app.py file. The sqlite file needs to be in the same directory as app.py.

The slider renders and moves, but I can't get a D3 event listener to trigger the update of the map when the slider moves.

The slider code is in the /static/js/slider.js file - this came from github repo below.

https://github.com/bobhaslett/d3-v4-sliders

The /static/js/logic.js file is the main javascript file.
- The slider code is called in lines 19-31
- the initial value is pulled in the "init" function in line 71.
    this part works fine - the initial map is drawn as expected.
- the event listener to trigger an update of the map when the slider
    is moved isn't working (lines 83-89)
