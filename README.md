Open Media Server
=================
This is an early version of UPNP/DLNA media server for Windows/Mac/Linux.


How to install and run
======================
The media server is available as pre built binaries or node-webkit application.

Version 0.1.1
-------------

* [Windows .zip](https://github.com/vf1/media-server/releases/download/v0.1.1/open-media-server-0.1.1-x86.zip)
* [Linux 32bit .tar.gz](https://github.com/vf1/media-server/releases/download/v0.1.1/open-media-server-0.1.1-ia32.tar.gz)
* [Linux 64bit .tar.gz](https://github.com/vf1/media-server/releases/download/v0.1.1/open-media-server-0.1.1-x64.tar.gz)
* [Node-Webkit .nw](https://github.com/vf1/media-server/releases/download/v0.1.1/open-media-server-0.1.1.nw)


Development
===========
The media server is [node js](http://nodejs.org/) application based on [upnpserver](https://github.com/oeuillot/upnpserver) powered by [node-webkit](https://github.com/rogerwang/node-webkit), [reactjs](http://reactjs.org) and other useful node-js modules.

    git clone https://github.com/vf1/media-server.git
    npm install --production
    flatten-packages

*The [flatten-packages](https://github.com/arifsetiawan/flatten) eliminates this [issue](http://stackoverflow.com/questions/13318364/how-to-deploy-node-js-application-with-deep-node-modules-structure-on-windows).*

Build node-webkit packages
--------------------------

There are two ways: using a *python* or *grunt* script.

### Python script

Requires [python 2.7](http://www.python.org/) to run the script.

    nodewebkit.py

### Gruntfile

Requres [grunt-cli](http://gruntjs.com/getting-started) to run ```Gruntfile```. Install project dev dependencies with ```npm install```.

    grunt