
> :warning: **This project was moved to** https://xcratch.github.io/

# Xcratch
Extendable Scratch3 Programming Environment

Xcratch is a mod application of [Scratch3 by MIT](https://scratch.mit.edu/) to play with user-made extensions easily.

**online installation and auto-loading on demand**

You can install and use user-made extensions from the web. Once you make a project with extended blocks, the project can be opened on Xcratch without installing required extensions by user.

**Built-in Web Bluetooth API**

You don't need to run [Scratch Link](https://scratch.mit.edu/microbit) to play with micro:bit or BLE devices when your browser is Chrome, Edge or 'Web Bluetooth API' supporting one (the browser in Chromebook, [‎Bluefy](https://apps.apple.com/jp/app/bluefy-web-ble-browser/id1492822055) in iPadOS, like that).

## How to Make Own Extension

Almost all the code of extension for Xcratch is same as ordinary extension for Scratch3 by MIT. You need to write code according some rules to be accepted by extension loading process, and make the code and resources into one file as a module in JavaScript. 

Please refer to [yokobond/xcratch-example](https://github.com/yokobond/xcratch-example). You can make own extension based on this repo. 

## Sample Extensions

### ✨ Microbit More 

Download the latest connection program from [Releases · yokobond/pxt-mbit-more-v2](https://github.com/yokobond/pxt-mbit-more-v2/releases) into your micro:bit then connect it from following Microbit More link.

- [Microbit More connection test](https://yokobond.github.io/xcratch/?project=https://yokobond.github.io/mbit-more-v2/example/test/connection.sb3) 
