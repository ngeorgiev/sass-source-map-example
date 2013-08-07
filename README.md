sass-source-map-example
=======================
This is a simple test of the Sass pre-processor and source maps integration in browsers (e.g. Chrome and DevTools).

Linux Compatibility
------
DevTools is not working on Linux currently.


Test:
---
The following test was performed with Ubuntu 12.04 and Chrome Version 30.0.1588.0 dev.

1) Uninstall Chrome:

    sudo apt-get purge google-chrome-stable
    sudo apt-get autoremove

2) Install the dev channel version of Chrome: http://www.chromium.org/getting-involved/dev-channel

Result:
---
You are able to edit in the Chrome DevTools, but you are not able to save to the file system. The error is: Changes to this file were not saved to file system.
