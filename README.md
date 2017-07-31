# arcgis-js-api-widget-template
Want do develop your own widget for the ArcGIS JavaScript API 4.x? Avoid creating all the boilerplate by starting with this set of files.

## Goals of this repository:

* Starts with the demo widget code from the [ArcGIS API for JavaScript Sample Code](https://developers.arcgis.com/javascript/latest/sample-code/widgets-custom-widget/index.html), but also includes:
* Places the widget within the context of a map.
* Includes TSLint
* Follows semi-standard code formatting
* Includes a dev web server to get you going quickly

Currently updated to ArcGIS JavaScript API version: 4.4 (2017-07)

## Quick Start

1. Clone this repository.
1. Rename the project in the `package.json` file
1. Rename `HelloWorld.tsx` to your widget's name, and update the reference in `index.html`.
1. `npm install`
1. `npm start`