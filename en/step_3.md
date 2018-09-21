## Create USB drive installer

The USB drive which will hold all the installation files required to setup your computer with Raspbian.

**Warning:** this will delete all of the data on your USB drive, if you need any files on it make sure you have made a backup.

+ Insert the USB drive into your computer.

+ Open Etcher to write the Raspberry Pi Desktop installation to the USB drive.

![etcher application](images/etcher.PNG)

--- collapse ---

---
title: Need to download and install etcher?
---

+ Download Etcher for your operating system from [etcher.io](https://etcher.io/).

![etcher website with link highlighted](images/download_etcher_annotated.PNG)

+ Run the installer you downloaded by double clicking it.

### Windows

+ Accept the **License Agreement**.

![etcher windows install accept license agreement ](images/etcher_install_step1.PNG)

The installation will run automatically and etcher will open when completed.

![etcher windows installation running](images/etcher_install_step2.PNG)

### Mac

+ Drag the Etcher icon to the Applications folder.

![etcher mac install](images/etcher_mac_install.PNG)

The installation will run automatically.

+ Open Etcher from Applications.

--- /collapse ---

+ Click **Select Image** and open the *Raspberry Pi Desktop* ISO you downloaded.

![selecting raspberry pi desktop image from etcher](images/etcher_select_image.PNG)

+ Check the USB drive selected is the correct one.

**Warning:** selecting the wrong drive will result in the data on it being deleted.

![drive selected in etcher](images/etcher_select_usb_annotated.PNG)

+ Click **Flash** to write the Raspberry Pi Desktop image to your USB drive.

![flash button highlighted in etcher](images/etcher_flash_annotated.PNG)

Etcher will show the message **Starting** before showing the **Flashing** progress.

![etcher showing the status starting](images/etcher_starting.PNG)

![etcher showing the status flashing](images/etcher_flashing.PNG)

When complete you will see a message saying **Flash Complete**.

![flash complete message in etcher](images/etcher_flash_complete.PNG)