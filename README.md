#QwaveSys Raspberry Pi Package for LabVIEW

![](http://ftp.qwavesys.com/tmp_pics/Rpi003.png)

![](http://ftp.qwavesys.com/tmp_pics/Rpi001.png)

![](http://ftp.qwavesys.com/tmp_pics/pi.png)

[**QwaveSys Raspberry Pi package**](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/blob/master/q_wave_systems_lib_qwavesys_raspberry_pi-1.4.0.62.vip) is a LabVIEW additional library based on [LINX 3.0.xx](http://sine.ni.com/nips/cds/view/p/lang/en/nid/212478) from [labviewmakerhub.com](https://www.labviewmakerhub.com) for Raspberry Pi. It's works with LabVIEW 2014 only for Non-commercial use

Anyone can get started with the [LabVIEW 45-Day Evaluation](http://ftp.ni.com/support/softlib/labview/labview_development_system/2014%20SP1/2014sp1LV-WinEng.exe) and buy LabVIEW Home Edition for non-commercial use. 

QwaveSys Raspberry Pi Package is a peripheral VIs provides enhance functions over LINX 3.0 standard library. it's an easy to use VIs and provided many examples. It's tested with Raspberry Pi 2B/3B and some functions also works with BBB and Orange Pi (H3) boards.

# Wiki!

[01.Setting Up the LabVIEW Raspberry Pi (QwaveSys Package)](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/01.-Setting-Up-the-LabVIEW-Raspberry-Pi-(QwaveSys-Package))

[02. Manual steps to install LabVIEW for Raspberry Pi](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/02.-Manual-steps-to-install-LabVIEW-for-Raspberry-Pi)

[03. [Tutorial] Create Executable calling from LabVIEW](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/03.-%5BTutorial%5D-Create-Executable-calling-from-LabVIEW)

[04. [Tutorial] Create Share Library (.so) calling from LabVIEW](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/04.-%5BTutorial%5D-Create-Share-Library-(.so)-calling-from-LabVIEW)

[05. [Tutorial] Create "WiringPi" GPIO Shared object (.so)](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/05.-%5BTutorial%5D-Create-%22WiringPi%22-GPIO-Shared-object-(.so))

[06. [Tutorial] Create your own GPIO Shared object (.so) base on WiringPi](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/06.-%5BTutorial%5D-Create-your-own-GPIO-Shared-object-(.so)-base-on-WiringPi)

[07. [Tutorial] Create "DHTxx" Temperature sensor shared object (.so) base on WiringPi](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/07.-%5BTutorial%5D-Create-%22DHTxx%22-Temperature-sensor-shared-object-(.so)-base-on-WiringPi)

[08. [Tutorial] Create "ADC PCF8591" ADC shared object (.so) base on WiringPi](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/08.-%5BTutorial%5D-Create-%22ADC-PCF8591%22-ADC-shared-object-(.so)-base-on-WiringPi)

[09. [Tutorial] OpenCV Pattern Matching calling from LabVIEW](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/09.-%5BTutorial%5D-OpenCV-Pattern-Matching-calling-from-LabVIEW)

[10. [Tutorial] OpenCV Object Tracking calling from LabVIEW](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/10.-%5BTutorial%5D-OpenCV-Object-Tracking-calling-from-LabVIEW)

[11. [Tutorial] OpenCV Object Tracking : Display UI at Pi Display](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/11.-%5BTutorial%5D-OpenCV-Object-Tracking-:-Display-UI-at-Pi-Display)

[12. [Tutorial] Create "DS18b20" Temperature sensor library (1 Wire)](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/12.-%5BTutorial%5D-Create-%22DS18b20%22-Temperature-sensor-library-(1-Wire))

[13. [Tutorial] Get OpenCV running on BeaglelBone Black (BBB)](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/13.-%5BTutorial%5D-Get-OpenCV-running-on-BeaglelBone-Black-(BBB))

[14. [Tutorial] Blinking LED on Orange Pi board (Armbian Jessie)](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/14.-%5BTutorial%5D-Blinking-LED-on-Orange-Pi-board-(Armbian-Jessie))

-----------------------------------------------------------------

**Released 1.4.0.62 (09/2016)**

> -Added shared object (.so) and souce code file to library folder.

> -Removed VIs block diagram password.
  
> -Added "wiringpi-dev" package.

-----------------------------------------------------------------

**First Released 1.3.0.59 (08/2016)**

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
**After installed the ".vip" package you can find examples as below path**

`"C:\Program Files (x86)\National Instruments\LabVIEW 2014\examples\Q-Wave Systems Co.,Ltd\QwaveSys Raspberry Pi for LabVIEW Home-Education`

------------------------------------------------------------------
**Add our feed sources server link.**

Refer this Wiki for this steps to manual setup.

[02. Manual steps to install LabVIEW for Raspberry Pi](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/02.-Manual-steps-to-install-LabVIEW-for-Raspberry-Pi)

    http://ftp.qwavesys.com/ipk/all

    http://ftp.qwavesys.com/ipk/armv7a-vfp

    http://ftp.qwavesys.com/ipk/raspberrypi2

------------------------------------------------------------------
**Install additional OPKG package**

Refer this Wiki for this steps to manual setup.

[02. Manual steps to install LabVIEW for Raspberry Pi](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/02.-Manual-steps-to-install-LabVIEW-for-Raspberry-Pi)

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
**QwaveSys-Raspbian-Jessie-OS v.003 (09/2016)**

The file size around 4.5GB. Please follow steps from this WiKi page for how to use setup this image. 

[Download Here from TH server>> QwaveSys-Raspbian-Jessie-OS](http://ftp.qwavesys.com/Qwave-Raspbian_qwavesys-rpi-003.zip)

[01. Setting Up the LabVIEW Raspberry Pi (QwaveSys Package)](https://github.com/QWaveSystems/QwaveSys-Raspberry-Pi-Package/wiki/01.-Setting-Up-the-LabVIEW-Raspberry-Pi-(QwaveSys-Package))

------------------------------------------------------------------

-Raspberry Pi™ is a registered trademark of the Raspberry Pi foundation.

-LINX 3.0 for Raspberry Pi 2B/3B create by `www.labviewmakerhub.com` (LabVIEW 2014 only,***Non-commercial use)

-WiringPi is a GPIO access library based on BCM2835 library used in the Raspberry Pi. It’s released under the GNU LGPLv3 license created by Gordon Henderson. `(http://wiringpi.com/)`

-OpenCV is released under a BSD license and hence it’s free for both academic and commercial use. `(http://opencv.org/)`

------------------------------------------------------------------
Created by `Amornthep Phunsin` and `Supawat Armart` (Q-Wave Systems Co.,Ltd)
Contact : `"amornthep@qwavesys.com"`
