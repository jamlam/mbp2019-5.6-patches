# mbp2019-5.6-patches
Patches to support MacBookPro 16,1 Wifi, Audio, Bluetooth, SMC, Keyboard and Touchpad on kernel 5.6, tweaked from the originals from [@aunali1](https://github.com/aunali1/linux-mbp-arch) and [@mikeeq](https://github.com/mikeeq/mbp-fedora-kernel)

To make this work you'll also need the BCE drivers from [@mcmrarm](https://github.com/mcmrarm/mbp2018-bridge-drv/)

Note that while the Wifi patch will detect the card, at the moment there is no known working firmware. The model appears to be different to the BCM4364 in the MBP15,2 so no pre-Catalina firmware exists for the card. 
