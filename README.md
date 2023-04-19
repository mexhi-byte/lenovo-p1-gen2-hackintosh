# lenovo-p1-gen2-hackintosh

latest opencore tested with bigsur/Monteray/Ventura

note: sometimes you need to installit from the tye-c port 

first of all you have to change your bios settings 

Thunderbolt 3 [In the BIOS, you need to set "Thunderbolt BIOS Assist": Disable, "Security level": No Security (allow automatic connection to Thunderbolt devices). In this way, the front-end type USB type-c port can work in macOS, the connection to the docking station is normal, and the Thunderbolt 3 device works normally (prerequisite: plugging in before cold start can be hot-swappable)]
secure boot disable
virtualization disable

the wifi doesent work in these model to make it working you have to install anather program "heli port" that makes a virtual wifi that works fine 
the link to install it
https://github.com/OpenIntelWireless/HeliPort

Keyboard Synaptics touchpad (PS/2) uses ApplePS2SmartTouchPad.kext, v4.7b5 of EMlyDinEsH, supports multi-touch gestures. clover5118 version has been replaced by voodooPS2

__________________________________________________________________________________________________________
tested 
     
     
    docking station on Thunderboald
    usb 
    card reader
    camera
    touchpad
    sleep and wake up function
_________________________________________________________________________________________________________
not working 


    The HDMI port becouse is connected direcly to the graphic card that is not supported in the mac os big sur/Monteray/ventura
    graphic card 
    wifi module

