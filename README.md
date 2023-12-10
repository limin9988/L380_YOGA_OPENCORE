
###### **Thinkpad L380 Yoga Opencore EFI**

No guide provided , use at your own risk

###### **hardware**
CPU  1.7 GHz Intel Core i5-8250U Quad-Core\
GPU  Integrated Intel UHD Graphics 620\
ram  16GB DDR 4 2400mhz\
disk  m.2 nvme 256gb Kingston NV2\
wifi  Intel 8265NGW\
sd card reader

###### **software**
OS  Monterey 12.6.2\
might work on Ventura , remember to change the wifi kext for ventura\
opencore 0.8.7\
device  MacBookPro15,2

###### **suggestion**
https://www.magesw.com/displayrotation/  <-- screen rotation app,good when flip laptop and rotate the screen


remember to generate your own smibios info\
wifi try visit https://github.com/OpenIntelWireless/itlwm/releases as different Macos need use different kext

###### **working**
<br>everything working GPU, bluetooth , wifi, touchpad , touchpoint ,stylus, touchscreen , camera , LED status\
<br>try not to update VoodooI2C.kext,VoodooI2CHID.kext,VoodooPS2Controller.kext as stylus will not work after update

###### **not working**
<br>fan sensor  - don't bother to find soluction , as this laptop doesnt hav this features,even in windows won't work

setting for AC
<br>sudo pmset -c standby 1
<br>sudo pmset -c hibernatemode 0

setting for battery
<br>sudo pmset -b standby 1
<br>sudo pmset -b standbydelayhigh 900
<br>sudo pmset -b standbydelaylow 60
<br>sudo pmset -b hibernatemode 25
<br>sudo pmset -b highstandbythreshold 70

setting for all
<br>sudo pmset -a acwake 0
<br>sudo pmset -a lidwake 1
<br>sudo pmset -a powernap 0

![Screenshot at Dec 07 22-13-33](https://github.com/limin9988/L380_YOGA_OPENCORE/assets/13900860/7f21972b-aa9f-40b7-853e-79d9b4614afd)




