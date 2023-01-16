
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
everything working GPU, bluetooth , wifi, touchpad , touchpoint ,stylus, touchscreen , camera , LED status\
try not to update VoodooI2C.kext,VoodooI2CHID.kext,VoodooPS2Controller.kext as stylus will not work after update

###### **not working**
fan sensor  - don't bother to find soluction , as this laptop doesnt hav this features,even in windows won't work


![alt text](https://github.com/limin9988/L380_YOGA_OPENCORE/blob/main/image/Screenshot%20at%20Jan%2016%2013-30-38.png?raw=true "Power Setting")

