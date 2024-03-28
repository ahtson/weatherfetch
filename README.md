# A very simple bash script for fetching a weather report for your location

This script utilizes [openweathermap API](https://home.openweathermap.org/) and [ipinfo API](https://ipinfo.io/) to get and parse information about weather at your current location and outputs it in your terminal using simple and minimalistic CLI.

## Dependencies:

[jq](https://jqlang.github.io/jq) $-$ a lightweight and flexible command-line JSON processor.

## Installation and usage:

Simply download ```weasherfetch.sh``` file, make it executable (```chmod +x weasherfetch.sh```), and simply run ```./weasherfetch.sh``` in your terminal to use it. Script will manage dependencies all by itself.

## Notes:
API keys are intentionally left right in the script as variables. A reason for this is to provide user with better customization possibilities.

