# Human Detection System using Raspberry Pi

You may need following components to get the expected Results
</br>
## Hardware Components
* A raspberry pi 2 or 3 model B ([Raspberry pi 3 model 3](https://www.raspberrypi.org/products/raspberry-pi-2-model-b/) has been used in my case)
* A compatible camera module ([CAMERA MODULE V2](https://www.raspberrypi.org/products/camera-module-v2/))
* A power Adapter with 2.0A - 2.5A ([RASPBERRY PI UNIVERSAL POWER SUPPLY](https://www.raspberrypi.org/products/universal-power-supply/))
* A micro SD card (16Gb -32GB recommended)


## Software Requirements
* Any compatible Raspbian OS can be used. ([Raspbian Jessie](https://www.raspberrypi.org/blog/raspbian-jessie-is-here/) used for this project)
* Update the OS to latest `sudo apt-get update`
* Upgrade the OS `sudo apt-get upgrade`
* Update the Raspberry Pi firmware `sudo rpi-update`
* Should install OpenCV `sudo apt-get install libopencv`
* Should Install Python
* pip install imutils
* pip install dropbox

If you need to update openCV to latest version install following dependencies
  ```
  sudo apt-get install build-essential checkinstall cmake pkg-config yasm
  sudo apt-get install libtiff4-dev libjpeg-dev libjasper-dev
  sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libdc1394-22-dev libxine-dev libgstreamer0.10-dev libgstreamer-plugins-base0.10-dev libv4l-dev 
  sudo apt-get install python-dev python-numpy
  sudo apt-get install libtbb-dev
  sudo apt-get install libqt4-dev libgtk2.0-dev
  ```

## Usage
  ```
python pi_surveillance.py --conf conf.json
  ```
