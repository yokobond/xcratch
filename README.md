# xcratch
Extendable Scratch3 Programming Environment

Xcratch is a mod application of [Scratch3 by MIT](https://scratch.mit.edu/) to play with user-made extensions easily.

You can install user-made extensions in Scratch3 from Internet and play the project which has extended blocks. 

You don't need to run [Scratch Link](https://scratch.mit.edu/microbit) to play with micro:bit or BLE devices when your browser is Chrome, Edge or 'Web Bluetooth API' supporting one (the browser in Chromebook, [‎Bluefy](https://apps.apple.com/jp/app/bluefy-web-ble-browser/id1492822055) in iPadOS, like that).

## Sample Extensions

### ✨ Microbit More 

Download the latest connection program from [Releases · yokobond/pxt-mbit-more-v2](https://github.com/yokobond/pxt-mbit-more-v2/releases) into your micro:bit then connect it from following Microbit More link.

- [connection test](https://yokobond.github.io/xcratch/?project=https://yokobond.github.io/mbit-more-v2/example/test/connection.sb3) 

## How to Build Modules

Your extension can be converted to a loadable extension module for Xcratch by [rollup.js](https://rollupjs.org/guide/en/). 

Please reffer to [mbit-more-v2/src at master · yokobond/mbit-more-v2](https://github.com/yokobond/mbit-more-v2/tree/master/src) and [mbit-more-v2/build.js at master · yokobond/mbit-more-v2](https://github.com/yokobond/mbit-more-v2/blob/master/scripts/build.js).
