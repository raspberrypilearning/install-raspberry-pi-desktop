## Run the installation

Now you can use your USB drive installer to install the Raspberry Pi Desktop on a computer. Once the installation in complete, you can remove the installer from the computer. You can use the installer multiple times to install the Raspberry Pi Desktop on multiple computers.

**Warning:** remember, installing the Raspberry Pi Desktop will delete all the data on your computer. Be sure that you have backed up everything you need before continuing.

### Boot from the USB drive

To install the Raspberry Pi Desktop from your USB installer, you will need to boot your computer from the USB drive.

To be able to do this, you may need to press a key to open the **boot menu** and select **USB**. The key you need to press will depend on the make and model of your computer. It is likely be a function key.  

You can find out the **boot menu key** of many makes and models of computers at [rpf.io/usb-boot](http://rpf.io/usb-boot).

+ Insert the USB drive installer into the computer.

+ Turn on the computer.

+ As the computer is starting up, press the **boot menu key**. You may need to press it multiple times in order for the menu to appear.

A boot menu will appear that will look similar to this:

![boot menu](images/boot_menu.jpg)

+ Select the option for your USB drive, probably called **USB-HDD**, and press <kbd>Enter</kbd>.

### Install Debian Linux

The Debian installation menu will appear.

+ Select **Graphical install** from the **Debian GNU/Linux** menu.

**Note:** if you do not select **Graphical install** quickly enough, the installer will start using the default option. If this happens, turn off the computer and restart it.

![debian install menu](images/step11.PNG)

+ Select your keyboard type and click **Continue**.

![configure keyboard](images/step12.PNG)

The installation process will now install media and detect what hardware is present.

+ To set how you want to partition your hard disk, select **Guided - use entire disk**, and click **Continue**.

![partition disk](images/step13.PNG)

+ Select the disk to be partitioned (there will be only one), and click **Continue**.

![select disk](images/step13_5.PNG)

+ To set the partitioning scheme, select **All files in one partition (recommended for new users)**, and click **Continue**.

![partioning scheme](images/step14.PNG)

+ To confirm the partition settings, select **Finish partitioning and write changes to disk**, and click **Continue**.

![finish partitioning](images/step15.PNG)

+ Confirm that you wish to write the changes to the disk by selecting **Yes** and clicking **Continue**.

![confirm partitioning](images/step16.PNG)

The Debian operating system installation will now run.

![debian install](images/step17.PNG)

--- collapse ---

---
title: Need to install the GRUB boot loader?
---

Depending on the setup of your computer, you may need to install the GRUB boot loader. If that's the case, do the following:

+ Confirm you want to install the GRUB boot loader on a hard disk by selecting **Yes** and clicking **Continue**.

![install grub loader](images/step18.PNG)

+ Select the device `/dev/sda` for boot loader installation, and click **Continue**.

![select boot loader device](images/step19.PNG)

The installation will now continue.

--- /collapse ---

+ When the installation is finished, click **Continue**.

![installation finished](images/step20.PNG)

Your computer will automatically reboot and then show you the **GNU GRUB boot screen**.

![GNU GRUB boot screen](images/debian_boot_screen.png)

+ Press <kbd>Enter</kbd> to run **Debian GNU/Linux**.
