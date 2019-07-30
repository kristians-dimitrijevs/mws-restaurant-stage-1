# Restaurant Review app

## Table of Contents
- [About Project](#about-project)
- [How to run this website](#how-to-run-this-website)
- [Additional information for design and code](additional-information-for-design-and-code)

## About project

This is the last project for the Front-End Web Development Nanodegree course. Udacity provided barely working base code for this project, and required student to fix it by:

- Adding fully responsive design for website,
- Implementing ServiceWorker, so that website is available offline,
- Making site more accessible (ARIA complaint, adding tabindex).

## How to run this website

- Live demo: https://kristians-dimitrijevs.github.io/mws-restaurant-stage-1/

- Download or clone this repository
- Open 'index.html' in a browser

Or

- Download or clone this repository
- In terminal check what version of Python you have `python -V`.
- If you have Python 2.x, you can start server by running the code in terminal `python -m SimpleHTTPServer 8000` (or other porit, if port 8000 is alreadey in use).
- If you have Python 3.x, you can start server bu runnong the code in termina. `python3 -m http.server 8000`
- With server running, visit the site `http://localhost:8000`
- If you don't have Python installed navigate to Pythons [website](https://www.python.org/) to download and install Python.

## Additional information for design and code

### Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future-proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
