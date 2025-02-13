# About

ESPHome firmware for [TRMNL](https://usetrmnl.com/) devices.

# Installation

You can use the button below to install the pre-built firmware directly to your device via USB from the browser.


## Basic Firmware

This firmware contains only definitions of the hardware and has a basic display page for testing.

<esp-web-install-button manifest="firmware/trmnl.manifest.json"></esp-web-install-button>

## TRMNL Cloud Firmware

This firmware contains the above plus will register itself and fetch the current image from the TRMNL cloud playlist.

<esp-web-install-button manifest="firmware/trmnl-cloud.manifest.json"></esp-web-install-button>


<script type="module" src="https://unpkg.com/esp-web-tools@10/dist/web/install-button.js?module"></script>
