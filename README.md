# nw.js webchimera demos

This repository demonstrates how to write a basic interface for [WebChimera](https://github.com/RSATom/WebChimera/) using nw.js (node-webkit) and either QML or HTML/CSS/JavaScript.

## Installation

1. [Download nw.js](https://github.com/nwjs/nw.js/)
2. [Download WebChimera](http://www.webchimera.org/download) for your operating system
3. Extract nw.js and copy the files of this repository to your nw root directory.
4. Install WebChimera
 - On OS X copy the `WebChimera.plugin`file to the `plugins` folder of this project in your nw root directory.
  - On Windows use the installer you downloaded to install WebChimera globally
  - Linux is not fully supported—*yet!*

## Usage

Once installed simply run nw. You will be presented with an index page containing 2 links: `QML` and `HTML, CSS & JavaScript`. Each of the links demonstrates how to write a simple interfaces using the specific languages. Dig into the code to see how it works.

## Further reading

To learn how to write QML, [@jaruba](https://github.com/jaruba) wrote a nice [tutorial on how to get started with QML](https://github.com/RSATom/WebChimera/wiki/Getting-started-with-QML) on the WebChimera Wiki.

To learn how to ship WebChimera on Windows without having your users using the WebChimera setup, jaruba set up [a repository](https://github.com/jaruba/WebChimeraPlayerNW) that includes everything needed.
