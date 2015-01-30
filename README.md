# Vega server

A simple node server that renders vega specs to SVG or PNG.

## Install

You may have to `export PKG_CONFIG_PATH=/opt/X11/lib/pkgconfig` if you see an error like `Package xcb-shm was not found in the pkg-config search path.`.

## Run

`npm run start`

## Use

* add some data
* run `curl -v -X POST -d @./test.json 'http://localhost:8888/?format=svg&header=true' --header "Content-Type: application/json"`
