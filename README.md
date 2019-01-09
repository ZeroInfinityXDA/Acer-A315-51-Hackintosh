Summary
=======
This is a repo containing the files for Clover used to make most things working on the Acer Aspire 3.

The Acer Aspire 3 A315-51 contains many variations with the same model number. The specifications on the particular model will be stated below:

* Intel Core i3 8130u
* Kingston 128GB SATA SSD
* 4GB DDR4-2400 RAM
* Qualcomm Antheros QCNFA453 **(REPLACED WITH A BCM94352Z NGFF LENOVO)**
* 15" 1080p display

**NOTE FOR WIFI: YOU MUST TAPE OVER PIN 54 AND PIN 56 IN ORDER FOR THE WIFI CARD TO WORK ON MACOS, HOWEVER THIS WILL PREVENT WIFI FROM WORKING WITH OTHER OPERATING SYSTEMS!**

How To Use
==========

Install Clover to a USB drive (you can find various guides on the internet), then mount the EFI partition of the USB you installed Clover on.

Delete the **CLOVER** folder on your **USB Drive's EFI partition** and move the **CLOVER** folder **downloaded from this repo** onto your **USB Drive's EFI partition**.

Then you're ready to boot and install macOS.

**After installing macOS, you need to install Clover to your macOS/main OS drive. Then you will need to repeat the same process as you did with your USB and replace the installed CLOVER folder with the CLOVER folder downloaded from this repo.**
