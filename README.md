# fnirsi_2c23t

# How to change firmware:

Press and hold MENU button and turn device on. It will show "Bootloader" on it's screen.
Copy firmware file on a disk which will appear.
If the firmware update completes successfully, you will see the startup screen.
If this does not happen and you see "Bootloader 8%%" or something similar on the screen
just copy firmware file again (for example with cp in linux). Repeat until it will boot.

You can turn off the device using the POWER button on this stage.
Press and hold MENU, then press POWER to enter the bootloader again.
If you turn the device on without holding MENU, it will not boot,
and you will only be able to access the bootloader again by performing a reset as described below.


# Device is not powering on after firmware update.
Press and hold the MENU and POWER buttons simultaneously. 
Briefly press the button inside the small pinhole on the right side of the device. 
Keep holding MENU and POWER for a couple more seconds.
Bootloader will show it's message on the screen.

# Hidden functions

In Scope mode : 
Long press AUTO : scope calibration
Long press CENTER : reset CH position

In DMM Mode : 
Long Pressing CH1 & CH2 enters calib mode

