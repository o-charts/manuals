---
layout: default_en_US
---

# oeRNC Charts Conditions

- oeRNC charts can only be used in OpenCPN.

- Normally you can install every chart you buy in 2 *systems* or more (see chart details). We name *assigments* to these allowed systems. 

- You can use either simultaneously all your assigments or you can save one to be used in case your main *system* dies or you have to make changes on it which may kill your license.

- *System* is the combination of hardware and OS. If any of these items changes, your system will be presented as a new one, you will lose your license and you will have to use a free assigment.

- Your license should survive to any OS, OpenCPN or plugin update but if you reinstall your OS, even with the same OS in the same hardware, you will lose your license.

- If you have consumed all your assigments and you want to install your chart in a new system, you will have to buy the charts again.

- A *USB Key Dongle* is considered as a system. The USB Key Dongle allows to install the charts in as many devices as you want. However, only in the device where the USB Key Dongle is plugged in, the license is active and will display the charts.

- Once you have requested your charts for one system we can not refund you. If you have created and assigned a system to your chart but you have not requested your charts yet, we can still refund you.

- Once you have requested your charts for one system we can not cancel or move your system to a different hardware/OS combination.

- You will be able to update your charts during a year from the purchase date. Charts have different update periodicity:

    - Quarterly: Imray Charts Eastern Caribbean, Imray Charts Greece & Turkey.
    - Undetermined: Explorer Charts (Bahamas).

- Your charts expire after a year from the purchase date. After expiration, charts will keep working on your system but you can not request updates for them any longer.

- During the one years period you can assign your charts to any system. Once the licensing period is over, this will not be possible any longer.

# Installing Charts

If the system where you want to install your charts **is connected to Internet** follow the steps in **Get charts online**. This is the easiest and recommended method.

If the system where you want to install your charts is **NOT connected to Internet** follow the steps in **Get charts offline**.

To install charts on **Android** follow the steps in **Get charts online**.

## Get charts online

1. Download and install the [oeRNC plugin](https://opencpn.org/OpenCPN/plugins/oernc.html) (only for OpenCPN 5.0 version and above). If you have already the oeRNC plugin installed, update to the latest version.

2. Go to OpenCPN, *Options → Plugins → oeRNC* and enable it.

3. Go to [o-charts shop](https://o-charts.org/shop/index.php?id_category=14&controller=category) and license the chart sets you are interested in. Remember your access data to o-charts shop (email and password), you will need them later. Ignore this step if you have already bought your charts.

### Online USB Key Dongle**

4. Plug the USB Key Dongle into a USB port of your device.

5. Go to OpenCPN, *Options → Charts → oeRNC charts* tab and press *Refresh Chart List*. Use the arrows to show the hidden tabs.

6. Login with your o-charts shop access data.

7. Follow on screen instructions to assign to your dongle, download and install the charts sets you licensed on the o-charts shop.

### Online Windows/Mac/Linux

4. Go to OpenCPN, *Options → Charts → oeRNC* charts tab and press *Refresh Chart List*. Use the arrows to show the hidden tabs.

5. Login with your o-charts shop access data.

6. You will be asked for a *System Name* to identify your system. If this is the first time you install oeRNC charts on this system, select *New* and provide a name 3 characters minimum and 15 maximum, no symbols or spaces. If you have already installed other oeRNC charts on this system, the *System Name* should be already assigned. If not, you have to select the *System Name* that corresponds to this system from the list. If you select the wrong *System Name*, you could be able to download your charts but they will not work. If you are installing your chart in a secondary system or you have reinstalled your OS you have to choose *New* to use a new assigment. Once you have consumed all your allowed assigments, the chart will not be available. 

7. Follow on screen instructions to assign, download and install to your system the charts sets you licensed on the o-charts shop.

### Online Android

Coming soon

### Online updates

You should visit *Options → Charts → oeRNC charts* from time to time to see if a new update is available. oeRNC updates are incremental but do not worry, oeRNC plugin will do all the job and will download all the intermediate updates you might have missed to install.

## Get charts offline

### Offline USB Key Dongle

In the target system download and install the [oeSENC plugin](https://opencpn.org/OpenCPN/plugins/oesenc.html) (only for OpenCPN 5.0 version and above). If you have already the oeSENC plugin installed, update to the latest version.

1. Plug the USB Key Dongle into a USB port.
    
2. Go to OpenCPN, Options → Plugins → oeSENC and enable it. Create a **USB key System ID file** (Fingerprint) from Preferences. The plugin will report the path to the file. For Windows and macOS systems a copy is created directly on the desktop. For Linux systems the file is created on ~/.opencpn folder.

3. Copy the Fingerprint onto some portable device and look for a computer with an internet connection.

4. Go to [o-charts shop](https://o-charts.org/shop/index.php?id_category=8&controller=category) and license the chart sets you are interested in. Ignore this step if you have already bought your charts.
    
5. Go to My [My oeSENC Charts](https://o-charts.org/shop/index.php?fc=module&module=occharts&controller=occharts) page and create a System identifier there uploading the Fingerprint. Leave System name blank, it will be assigned automatically.

6. Select the new *System identifier* for each chart set you want to assign to your dongle. Once assigned, it can not be changed.

7. Make a Request clicking the button that will appear on the column *Last requested* and the chart set will be processed. Processing time depends on the chart set size, the queue on the server and the network charge at that moment but will be never more than 2 hours. Actually we are talking about minutes.

8. You will get an email with a link to download your chart set. You can download it from [My oeSENC Charts](https://o-charts.org/shop/index.php?fc=module&module=occharts&controller=occharts) page too. If you have not downloaded your chart set in a week, you will have to make a new Request. Download your chart, copy it onto some portable device and go back to the boat.

9. On your target system unzip the file into a directory of your choice and install your charts as always and you are done.  Plug in the USB Key Dongle to see the charts.


### Offline Windows/Mac/Linux

For target systems without connection to Internet you will create a system identifier file for it, take it to a site with Internet access and request and download the chart set. Copy the received file onto some portable device and copy it onto the target system.

1. In the target system download and install the [oeSENC plugin](https://opencpn.org/OpenCPN/plugins/oesenc.html) (only for OpenCPN 5.0 version and above). If you have already the oeSENC plugin installed, update to the latest version.

2. Go to OpenCPN, *Options → Plugins → oeSENC* and enable it. Create your system identifier file (*Fingerprint*) from *Preferences*. The plugin will report the path to the file. For Windows and macOS systems a copy is created directly on the desktop. For Linux systems the file is created on *~/.opencpn* folder.

3. Copy the *Fingerprint* onto some portable device and look for a computer with an internet connection.

4. Go to [o-charts shop](https://o-charts.org/shop/index.php?id_category=8&controller=category) and license the chart sets you are interested in. Ignore this step if you have already bought your charts.

5. Go to [My oeSENC Charts](https://o-charts.org/shop/index.php?fc=module&module=occharts&controller=occharts) page and create a *System identifier* there uploading the *Fingerprint* file and give it a *System name*.

6. Select a *System name* for each chart set you have licensed. Once assigned, it can not be changed. If your computer gets damaged, you are allowed to select a second *System name* for each chart set as a backup. In that case, create a new *System identifier* for the new computer.

7. Make a Request clicking the button that will appear on the column *Last requested* and the chart set will be processed. Processing time depends on the chart set size, the queue on the server and the network charge at that moment but will be never more than 2 hours. Actually we are talking about minutes.

8. You will get an email with a link to download your chart set. You can download it from [My oeSENC Charts](https://o-charts.org/shop/index.php?fc=module&module=occharts&controller=occharts) page too. If you have not downloaded your chart set in a week, you will have to make a new *Request*. Download your chart, copy it onto some portable device and go back to the boat.

9. On your target system, unzip the charts into a directory of your choice and install your charts as always and you are done!

### Offline updates

To update your chart sets go to [My oeSENC Charts](https://o-charts.org/shop/index.php?fc=module&module=occharts&controller=occharts) page. Column *Last requested* will show the last edition you requested. Column *Last update* will show the current available edition for that chart set. If *Last requested* is older than *Last update* you might consider to request the most actual edition. An update set is self contained, do not worry about intermediate updates you might have missed to install. Remove the old chart set from OpenCPN or keep it in different directory and download and install the new one as usual.

# Frequently Asked Questions

> **What OS is oeSENC plugin ready for?**
>
> oeSENC charts will work on Windows, Mac, Android and Linux systems (included ARM boards).

> **And if I install the software in a Virtual Machine?**
>
> It will not run there. We have to prevent the system from being cloned.

> **Can I use oeSENC charts on iOS?**
>
> No. There is no version of OpenCPN for iOS.

> **As how many systems counts a dual boot system?**
> 
> Each HW/SW combination is an individual one.

> **Why do I have to pay for oeSENC charts?**
>
> We have to run this operation and respond to the charts licensors fees and conditions. The structure and costs are kept to a minimum. In case we have a great success economical speaking, funds will go back to OpenCPN.

> **OpenCPN is open source. Where is the code for the plug-in?**
>
> To work with oeSENC charts we have to ensure that no copies of the unencrypted cells are accessible during the execution of the software. Therefore, the plug-in has an open-source part and a binary. Similar to the commercial BSB4 or nv-chart plug-ins.
