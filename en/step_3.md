## Create a USB drive installer

The installer is the USB drive that will hold all the installation files required to set up your computer with Raspberry Pi Desktop.

**Warning:** setting up a USB drive as an installer will delete all the files on the drive. If you need any files on the drive you're planning to use, make sure you have backed them up.

+ Insert the USB drive into your computer.

+ Open the Etcher program to write the Raspberry Pi Desktop installation to the USB drive.

![etcher application](images/etcher.PNG)

--- collapse ---

---
title: Need to download and install Etcher?
---

+ Download Etcher for your operating system from [etcher.io](https://etcher.io/).

![etcher website with link highlighted](images/download_etcher_annotated.PNG)

+ Open the installer file you downloaded.

### Windows

+ **Accept** the License Agreement.

![etcher windows install accept license agreement ](images/etcher_win_install_step1.PNG)

The installation will proceed automatically, and when it is complete, the Etcher program will start up.

![etcher windows installation running](images/etcher_win_install_step2.PNG)

### Mac

+ Drag the Etcher icon to the **Applications** folder. The installation will then happen automatically.

![etcher mac install](images/etcher_mac_install.PNG)

+ Open the Etcher program from the **Applications** folder.

### Linux

+ Extract the Etcher AppImage from the `.zip` file.

![extract linux appimage from the etcher zip file download](images/etcher_linux_install_step1.PNG)

+ Run the Etcher AppImage installer.

![run the AppImage installer](images/etcher_linux_install_step2.PNG)

+ Open Etcher from the **Applications** menu.

--- /collapse ---

+ In Etcher, click **Select Image**.

+ In the window that opens, select the `Raspberry Pi Desktop` ISO file you downloaded, and then click **Open**.

![selecting raspberry pi desktop image from etcher](images/etcher_select_image.PNG)

+ Select the correct USB drive. If you need to change the one that is selected, click **Change**.

![drive selected in etcher](images/etcher_select_usb_annotated.PNG)

**Warning:** selecting the wrong drive and then proceeding to the next step will result in all the data on the drive being deleted.

+ Click **Flash** to write the Raspberry Pi Desktop image to your USB drive.

![flash button highlighted in etcher](images/etcher_flash_annotated.PNG)

Etcher will show the message `Starting`, and then it will show the `Flashing` progress.

![etcher showing the status starting](images/etcher_starting.PNG)

![etcher showing the status flashing](images/etcher_flashing.PNG)

When the process is complete, you will see the message `Flash Complete`.

![flash complete message in etcher](images/etcher_flash_complete.PNG)
