# Mobile Web Specialaist Certification Course
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview

For the **Restaurant Reviews** projects, a static webpage is converted to a mobile-ready web application. 
In **Stage One**, a static design was converted to be responsive on different sized displays and accessible for screen reader use. A service worker was created to cache static assets and create a seamless offline experience for users.
In **Stage Two**, the web app was connected to an external web server. The app also uses IndexedDB to cache JSON responses from the server, so any page visited by the user is available offline.  

### Setup
1. Clone the [server code](https://github.com/berrybell/mws-restaurant-stage-2) and start the server according to instructions in the repository.

2. Clone this project to your computer. 

3. In project folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

4. With your server running, the site will be available at the following address: `http://localhost:8000`

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/).



