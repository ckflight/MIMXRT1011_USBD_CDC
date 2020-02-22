# MIMXRT1010_USBD_CDC
USB Device Com Port Implementation on NXP MIMXRT1010_EVK Arm Cortex-M7 Microcontroller

When creating project on MCUXpresso IDE, select "Usb_device" from "Middleware" section which will include /usb folder
in the project directory. 

Use my virtual_com.c/.h files for user interface to interact with USB Device

Circular buffer for reception and a fast simple transfer buffer with 512 byte size is implemented. Also, printer methods are implemented to easily print integer, string, float etc.

Project also includes SYSTICK Interrupt in CK_TIME.c/.h files for time calculations.
