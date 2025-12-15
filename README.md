# Home Assistant - HACS - Bark notification
[![hacs_badge](https://img.shields.io/badge/HACS-Custom-41BDF5.svg)](https://github.com/hacs/integration)

This could be added to HACS on Home Assistant for notification push via [Bark](https://github.com/Finb/Bark/).

This repository could be cloned and [installed via HACS](https://www.hacs.xyz/).

## Installation

1. Install this repository on HACS using the three-dots menu on the top right.
(Install as an integration)
2. Reboot Home Assistant. Add an integration on Settings - Devices & Services.
3. Add Bark.
4. Set up the entry. In particular, use your API key (instead of device token)
in the third text box. (For some reason, it shows up as "device token" which
is a separate concept in Bark).

## Test

1. Go to "Developer tools" in the menu bar (lower left).
2. Select Actions tab.
3. Search for "Bark"
4. Fill in the texts, then click on "Perform Actions"
   
## Notes

[Bark](https://github.com/Finb/Bark/) is an iOS notification app.
