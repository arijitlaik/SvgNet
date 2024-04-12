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

# SVGNet.js

SVGNet.js is a JavaScript library for creating and manipulating SVG (Scalable Vector Graphics) elements.

## Features

- Create SVG elements programmatically
- Manipulate SVG elements (e.g., change attributes, add/remove children)
- Support for SVG animations

## Installation

```bash
npm install svgnet.js
```

## Usage

First, import the library:

```javascript
const SVGNet = require('svgnet.js');
```

Then, you can create and manipulate SVG elements:

```javascript
let svg = SVGNet.create('svg', {width: 500, height: 500});
let circle = SVGNet.create('circle', {cx: 250, cy: 250, r: 100, fill: 'red'});
svg.appendChild(circle);
```

## API

### SVGNet.create(name, attributes)

Creates a new SVG element with the given name and attributes.

### SVGNet.prototype.appendChild(child)

Adds a child element to this SVG element.

### SVGNet.prototype.setAttribute(name, value)

Sets the value of an attribute on this SVG element.

## Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License

[MIT](https://choosealicense.com/licenses/mit/)