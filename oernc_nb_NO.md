---
layout: default_nb_NO
---

# oeRNC Charts Conditions

- oeRNC charts can only be used in OpenCPN.

- In general you can install every chart you license in 2 systems or more (see chart details). We call these enabled systems "assignments".

- You can use either all your assigments simultaneously or you can retain one to be used in case your main system dies or you have to make thorough changes on it which may kill your license.

- *System* is the combination of hardware and OS. If any of these factors changes, your system will be presented as a new one, invalidating the license and you will need to use a free assignment.

- Your license should survive any OS, OpenCPN or plugin update but if you reinstall your OS, even with the same OS in the same hardware, count that this will require a new assignment.

- When you have consumed all your assigments and you want to install your chart in a further systems, you will need to license the charts again.

- A *USB Key Dongle* is considered as a system. The USB Key Dongle allows to install the charts in as many devices as you want. However, only in the device where the USB Key Dongle is plugged in, the license is active and will display the charts.

- Once you have requested your charts for one system we can not refund you. If you have created and assigned a system to your chart but you have not requested your charts yet, we can still refund you.

- Once you have requested your charts for one system we can not cancel or move your system to a different hardware/OS combination.

- You will be able to update your charts during a year from the purchase date. Charts have different update periodicity:

    - Quarterly: Imray Charts Eastern Caribbean, Imray Adriatic and Ionian, Imray Aegean and Mediterranean East.
    - Undetermined: Explorer Charts (Bahamas).

- Your charts expire after a year from the purchase date. After expiration, charts will keep working on your system but you can not request updates for them any longer.

- During the one years period you can assign your charts to any system. Once the licensing period is over, no new system can be assigned any longer.

# Installing Charts

If the system where you want to install your charts **is connected to Internet** follow the steps in **Get charts online**. This is the easiest and recommended method.

If the system where you want to install your charts is **NOT connected to Internet** follow the steps in **Get charts offline**.

To install charts on **Android** follow the steps in **Get charts for Android**.

## Get charts online

1. Download and install the [oeRNC plugin](https://opencpn.org/OpenCPN/plugins/oernc.html) (only for OpenCPN 5.0 version and above). If you have already the oeRNC plugin installed, update to the latest version.

2. Go to OpenCPN, *Options → Plugins → oeRNC* and enable it.

3. Go to [o-charts shop](https://o-charts.org/shop/14-oernc) and license the chart sets you are interested in. Remember your access data to o-charts shop (email and password), you will need them later. Ignore this step if you have already bought your charts.

4. If you want to assign your charts to a [USB Key Dongle](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), plug it into a USB port now. Ignore this step if you do not have a dongle.

5. Go to OpenCPN, *Options → Charts → oeRNC charts* tab and press *Refresh Chart List*. Use the arrows to show the hidden tabs.

6. Login with your o-charts shop access data.

7. If you are using a USB Dongle ignore this step. First you will need to identify your system with a *System Name*. If you
install oeRNC charts the first time on this system, select *New* in the window that will pop-up and provide a name (3 characters minimum and 15 maximum, no symbols or spaces). If the system has been used already, select the *System Name* that corresponds to it from the list. In case you select a wrong *System Name*, the install of the charts may proceed but they will reject to work. If you are installing your chart in a second system or you have reinstalled your OS then select *New* to create a new assignment.

8. Follow on screen instructions to assign, download and install to your system or dongle the charts sets you licensed on the o-charts shop. Once you have consumed all your allowed assigments, the chart will not be available. 

### Updates - online

You should visit *Options → Charts → oeRNC charts* from time to time to see if a new update is available. Online updates are incremental but do not worry, oeRNC plugin will do all the job and will download all the intermediate updates you might have missed to install.

## Get charts for Android

Coming soon

## Get charts offline

For systems without Internet connection you will create a system identifier file to take it to another computer with Internet access and request and download the chart set for the target system. We assume that you have installed the latest versions of OpenCPN and oeRNC plugin in the target system.

1. If you want to assign your charts to a [USB Key Dongle](https://o-charts.org/shop/hardware/38-usb-key-dongle.html), plug it into a USB port now. Ignore this step if you do not have a dongle.
    
2. Go to OpenCPN, *Options → Plugins → oeRNC Charts* and enable it. 

3. Enter into *Preferences* and click either on *Create USB Key Dongle System ID file...* if you have a dongle or on *Create System Identifier file...* if you do not have a dongle. The plugin will report the path to a *Fingerprint* file. For Windows and macOS systems a copy is created directly on the desktop. For Linux systems the file is created in ~/.opencpn folder.

4. Copy the *Fingerprint* file onto some portable device and look for a computer with an internet connection.

5. Go to the [o-charts shop](https://o-charts.org/shop/14-oernc) and license the oeRNC chart sets you are interested in. Ignore this step if you have already bought your charts.
    
6. Go to the [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) page and create a *System identifier* uploading the *Fingerprint*. Leave *System name* blank if you are using a dongle.

7. Select the new *System identifier* for each chart set you want to assign to your system. Once assigned, it can not be changed.

8. Make a Request clicking the button *Request*. After few seconds you will get 2 download links, one for the charts and another one for the file containing the keys to decrypt them. Copy both files onto the portable device and go back to the boat.

9. On your target system unzip the charts file into a directory of your choice and copy the keys file into the same folder where the unzipped charts are (.oernc). Install your charts as always and you are done. If you have assigned your charts to a dongle, plug it in before to see the charts.

### Updates - offline

To update your chart sets go to [My oeRNC Charts](https://o-charts.org/shop/module/occharts/occhartsOernc) page. Column *Edition* will show the last edition you requested. Column *Current edition* will show the current available edition for that chart set. If they do not match, a *Request* button will appear. Offline updates are self contained, do not worry about intermediate updates you might have missed to install. Remove the old chart set from OpenCPN or keep it in different directory and install the new one as usual.

# Frequently Asked Questions

> **What OS are oeSENC/oeRNC plugins ready for?**
>
> oeSENC/oeRNC charts will work on Windows, Mac, Android and Linux systems (included ARM boards).

> **And if I install the software in a Virtual Machine?**
>
> It will not run there. We have to prevent the system from being cloned.

> **Can I use oeSENC/oeRNC charts on iOS?**
>
> No. There is no version of OpenCPN for iOS.

> **As how many systems counts a dual boot system?**
> 
> Each hardware/OS combination is an individual one.

> **Why do I have to pay for oeSENC/oeRNC charts?**
>
> We have to run this operation and respond to the charts licensors fees and conditions. The structure and costs are kept to a minimum. In case we have a great success economical speaking, funds will go back to OpenCPN.

> **OpenCPN is open-source. Where is the code for the plugins?**
>
> To work with oeSENC/oeRNC charts we have to ensure that no copies of the unencrypted cells are accessible during the execution of the software. Therefore, the plugins have an open-source part and a binary. Similar to the commercial BSB4 or nv-chart plugins.
