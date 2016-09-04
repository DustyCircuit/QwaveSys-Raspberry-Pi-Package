# LabVIEW: QwaveSys-Raspberry-Pi-Package

QwaveSys Raspberry Pi package is a LabVIEW additional library based on LINX 3.0 (labviewmakerhub) for Raspberry Pi. It's works with LabVIEW 2014 only for Non-commercial use.

QwaveSys Raspberry Pi Package is a peripheral VIs provides enhance functions over LINX 3.0 standard library. it's an easy to use VIs and provided many examples. It's tested with Raspberry Pi 2B/3B and some functions also works with BBB and Orange Pi (H3) boards.

-----------------------------------------------------------------

Released 1.4.0.62 (09/2016)

  -Added shared object (.so) and souce code file to library folder.

  -Removed VIs block diagram password.
  
  -Added "wiringpi-dev" package.

-----------------------------------------------------------------

First Released 1.3.0.59 (08/2016)

Added library support for Raspbberry Pi 2B/3B:

>-WiringPi GPIO Library (http://wiringpi.com/)

>-OpenCV 3.1.0 Vision Library (http://opencv.org/)

>-RASPICAM Library (raspistill, raspivid and raspiyuvand more..)

>-ADC PCF8591 (http://wiringpi.com/extensions/i2c-pcf8591/)

>-DHTxx Temp Sensors (DHT11,DHT22)

>-DS18b20 1-Wire Temp Sensor (w1-gpio)

>-Sysfs GPIO Library (RasPi and Orange Pi)

>-Client_Server Library (STM,CVT)

-----------------------------------------------------------------
After installed the ".vip" package you can find examples as below path

    "C:\Program Files (x86)\National Instruments\LabVIEW 2014\examples\Q-Wave Systems Co.,Ltd\QwaveSys Raspberry Pi for LabVIEW Home-Education"

------------------------------------------------------------------
Add "Q-Wave Systems" feed sources server

    http://iosys.link/ipk/all

    http://iosys.link/ipk/armv7a-vfp

    http://iosys.link/ipk/raspberrypi2

------------------------------------------------------------------
Install additional OPKG package 

    opkg update 

    opkg install python 

    opkg install opencv 

    opkg install userland 

    opkg install packagegroup-core-buildessential 

    opkg install rpi-gpio 

    opkg install rpio

    opkg install wiringpi

    opkg install wiringpi-dev

------------------------------------------------------------------
QwaveSys-Raspbian-Jessie-OS 08/2016

We've made the customized Raspbian image (.img) that contain all pacakages and shared library (.so).

The file size is very large in serveral GB, As currently I have put at our private server. 

Please email me at "amornthep@qwavesys.com" the get the download link. 

------------------------------------------------------------------

-Raspberry Pi™ is a registered trademark of the Raspberry Pi foundation.

-LINX 3.0 for Raspberry Pi 2B/3B create by www.labviewmakerhub.com (LabVIEW 2014 only,***Non-commercial use)

-WiringPi is a GPIO access library based on BCM2835 library used in the Raspberry Pi. It’s released under the GNU LGPLv3 license created by Gordon Henderson. (http://wiringpi.com/)

-OpenCV is released under a BSD license and hence it’s free for both academic and commercial use. (http://opencv.org/)

Contact Information: 
Amornthep Phunsin (amornthep@qwavesys.com)
