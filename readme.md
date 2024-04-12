# SvgNet

SvgNet is a web application for creating Structural Geology Plots Stereonet or Projection. It is built with SVG and JavaScript HTML5.

## Features

- Grids: You can toggle the visibility of the grids using the "Grids" switch in the "Options" section.
- Tap Input: This option allows you to input data by tapping on the screen.
- Quick Input: This option allows for faster data input.
- Opacity: You can adjust the opacity of the net using the "Opacity" slider in the "Options" section.
- Projection: You can switch between "Wulff Net" and "Schmidt Net" projections.

## Usage

1. Open the SvgNet in your web browser.
2. Click on the "INPUT" tab to enter data, select the type of data then click the "PLOT" button.
3. The Right Hand Rule (RHR) i.e "strike + 90°=dip direction" is to be followed when entering the data.
4. Select the data in the "DATA" tab for calculations, click on the "save" icon to save as Vector and the "photo" icon to save as raster.

## Author

SvgNet is created by Arijit Laik.

## Stylesheets

SvgNet uses the following stylesheets:

- material.min.css
- mdl-selectfield.min.css

This project uses the PouchDB library for handling database operations and the Material Design Lite (MDL) library for the user interface.

## Libraries Used

### PouchDB

PouchDB is a JavaScript library that allows you to store your data locally while offline, then synchronize it with CouchDB and compatible servers when you are back online, keeping your user's data in sync no matter where they next go online.

### Material Design Lite

Material Design Lite lets you add a Material Design look and feel to your websites. It doesn’t rely on any JavaScript frameworks and aims to optimize for cross-device use, gracefully degrade in older browsers, and offer an experience that is immediately accessible.

## Files

- js/pouchdb.min.js: This file contains the minified version of the PouchDB library.
- js/material.min.js: This file contains the minified version of the Material Design Lite library.
- css/material.min.css: This file contains the minified CSS for the Material Design Lite library.

## License

This project is licensed under the Apache-2.0 License.
