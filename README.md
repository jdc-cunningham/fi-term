### Fi Term

<img src="./temp.jpg"/>

This is a small 2.13" pi zero e-paper desktop display that's a web server, cycling through financial information like cash, debt, etc...

### Components

- Pi Zero W as an API with DB and display driver
- mobile app
- desktop app

### E-ink display

This is attached to a Pi Zero W through the 40-pin GPIO header. It is connected to my desktop computer by a USB cable for power, no battery.

### Dependencies

Need to look at the dep for [canvas](https://www.npmjs.com/package/canvas) specifically it calls to run this on ubuntu:

`sudo apt-get install build-essential libcairo2-dev libpango1.0-dev libjpeg-dev libgif-dev librsvg2-dev`

If you don't run that and try to install canvas you'll see a `node gyp` error
