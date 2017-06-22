# KORUZA-Pro


## KORUZA Pro repositories and licences:
The complete KORUZA Pro device is split in a number of repositories implementing specific functions and is made available under the listed licenses.

### Software
 * [KORUZA driver](https://github.com/IRNAS/koruza-driver) - core driver to implement an interface to all hardware modules
 * [Raspbian operating system](https://www.raspbian.org/) - core operating system on Raspberry Pi
 * [KORUZA RPi package](https://github.com/IRNAS/koruza-rpi-package) - packages all standalone code blocks and additional features into a single package to be installed on Raspberry Pi with [Raspbian](https://www.raspbian.org/)
 * [KORUZA move driver firmware](https://github.com/IRNAS/Koruza-Move-Driver-Firmware) - firmware running on the Move driver tandalone motor controller
 * [KORUZA UI](https://github.com/IRNAS/koruza-ui) -  KORUZA user interface available to the user though the web
 * [mjepg-streamer fork](https://github.com/IRNAS/mjpg-streamer) - fork of mjpeg-streamer with added functions required for KORUZA
 


### Hardware
  * [KORUZA compute module board](https://github.com/IRNAS/koruza-compute-module) - main KORUZA Pro electronics board with Raspberry Pi Compute module processor module
  * [KORUZA move driver](https://github.com/IRNAS/koruza-move-driver) - standalone motor controller board for dual unipolar stepper motors in KORUZA Pro for automatic alignment
  * [KORUZA HS holder](https://github.com/IRNAS/koruza-hs-holder) - small board to support the flexible circuit connecting to the SFP module
  * [KORUZA power supply](https://github.com/IRNAS/koruza-power-module) - power supply module between 24V PoE input and 5V and 9V power rails
  * [KORUZA HS flex](https://github.com/IRNAS/koruza-hs-flex) - high-speed flexible circuit between SFP module and KORUZA compute module board
  * KORUZA mechanical assembly - not yet available online, Cern OHL licensed.
  

### Tests and auxiliary systems
 * [KORUZA experiment v2](https://github.com/IRNAS/koruza-experiment-v2) - configuration and other details for measuring packet loss in a multi-link environment
 * [KORUZA accelerometer module](https://github.com/IRNAS/koruza-accelerometer-module) - software for vibration analysis on a standalone board with USB interface
 * [KORUZA use-case documentation](https://github.com/IRNAS/KORUZA-usecase) - documentation on some deployments and use-cases
 * [KORUZA test scrpts](https://github.com/IRNAS/KORUZA-testing) - test scripts used in various experiments
 * [KORUZA raw measurements](https://github.com/IRNAS/KORUZA-ScientificExperiments) - storage of raw measurements
 
### Dependencies and older versions
 * [KORUZA 1.0](https://github.com/IRNAS/KORUZA) - previous version of the system the current design is heavily based on. 
