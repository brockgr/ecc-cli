# ecc-cli
CLI for Elgato Key Lights using Elgato Control Center

## About

Author Gavin Brock

This software is not published by, nor supported by Elgato or Corsair Memory 
Inc.

## Usage

```
usage: ecc-cli [-h] [-a] [-l] [-d DEVICE] [-g] [-p {on,off,toggle}]
               [-b BRIGHTNESS] [-t TEMPERATURE] [-w]

Interact with Elgato Control Center.

optional arguments:
  -h, --help            show this help message and exit
  -a, --appinfo         Get Elgato CC info
  -l, --list            List all connected devices
  -d DEVICE, --device DEVICE
                        Specify Device ID. May be repeated. Defaults to all
                        devices.
  -g, --get             Get state of devices
  -p {on,off,toggle}, --power {on,off,toggle}
                        Change power state
  -b BRIGHTNESS, --brightness BRIGHTNESS
                        Set Brightness (0-100)
  -t TEMPERATURE, --temperature TEMPERATURE
                        Set temperature (2900-7000)
  -w, --watch           Watch for device events
```


## Installation

I have only tested this on OS-X but should work on any system supporting
Elgato Control Center, that has python.

You will need to install jsonrpc-websocket, probably using a command like

```$ pip3 install jsonrpc-websocket```

