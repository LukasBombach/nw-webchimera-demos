# nw.js webchimera demos

This repository demonstrates how to write a basic interface for [WebChimera](https://github.com/RSATom/WebChimera/) using nw.js (node-webkit) and either `QML` or `CSS & JavaScript`.

## Installation

### On OS X

1. [Download nw.js](https://github.com/nwjs/nw.js/#downloads), choose the `64bit` version
2. Extract nw.js and copy the files from this repository to your nw root directory.
3. [Download WebChimera](http://www.webchimera.org/download) for Mac
4. From your downloaded WebChimera disk image, copy the file `WebChimera.plugin` to the `plugins` folder in your nw root directory.
5. Rename the file `package_osx.json` to `package.json`

### On Windows

1. [Download nw.js](https://github.com/nwjs/nw.js/#downloads), choose the `32bit` version
2. Extract nw.js and copy the files from this repository to your nw root directory.
3. [Download the latest WebChimera from the releases at GitHub](https://github.com/RSATom/WebChimera/releases). Choose the file named WebChimera_X.X.X_vlc_X.X.X.zip
4. Extract all of the contents of the zip file to the `plugins` folder in your nw root directory.
5. Rename the file `package_win.json` from this repository to `package.json`

## Usage

Once installed simply run nw. You will be presented with an index page containing 2 links: `QML` and `HTML, CSS & JavaScript`. Each of the links demonstrates how to write a simple interface using the particular languages. Dig into the code to see how it works.

## Further reading

To learn how to write QML, [@gyzerok](https://github.com/gyzerok) wrote a nice [tutorial on how to get started with QML](https://github.com/RSATom/WebChimera/wiki/Getting-started-with-QML) on the WebChimera Wiki.
