
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

need set lidwake = 0 , else will cause problem when wake from suspend by opening lid, it will restart when shutdown

![Screenshot at Dec 02 05-16-14](https://github.com/limin9988/L380_YOGA_OPENCORE/assets/13900860/28bb27e0-d547-46e8-aac3-ff6dc19b650f)


