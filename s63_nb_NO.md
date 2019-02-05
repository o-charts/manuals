---
layout: default_nb_NO
---

# S-63 UserPermits Conditions

- S-63 plugin is not available for Android or iOS.

- We do not sell S-63 charts, we just provide the S-63 *UserPermit* as the required tool to license charts from S-63 chart resellers like [Chartworld](https://www.chartworld.com/shop/off_enc).

- To buy a S-63 chart from any provider, you need an UserPermit. Charts licensed with the OpenCPN S-63 UserPermit can only be used in conjunction with OpenCPN as established in the S-63 standard.

- You are allowed to use every chart you buy in 5 *systems* simultaneously or you can save them to be used in case your system dies. We will generate an OpenCPN *InstallPermit* for every individual system. The InstallPermit links a S-63 chart set for OpenCPN to one system. Don not mistake the OpenCPN InstallPermit with the S-63 cell permits.

- *System* is the combination of computer and OS. If any of these items changes, your system will be presented as a new one, you will lose your license and you will have to consume another InstallPermit.

- If you have consumed your 5 shots, you will have to purchase a new UserPermit and hence license charts for this new UserPermit. As this is a new cycle, you will have 5 install opportunities (InstallPermits) again.

- Your license should survive to any OS, OpenCPN or plugin update but if you reinstall your OS you will lose your license.

- Once you have licensed an UserPermit we can not refund you.

- Once you have generated an InstallPermit for one system we can not cancel or move it to a different device/OS combination.

- Check the S-63 charts providers conditions about updating and expiration.

# Installing UserPermits/InstallPermits and S-63 charts

![steps](./assets/images/s63.png)

 1. *System* is the computer you will use for OpenCPN. The chart set you license from a VAR for this system can only be used on it. Download and install the [S-63 plugin](https://opencpn.org/OpenCPN/plugins/s63.html) (only for OpenCPN 4.6 version and above).

2. Go to OpenCPN, *Options → Plugins → S63* and enable it. Then, go to OpenCPN, *Options → Charts → S63 Charts → Keys/Permits* tab and create a system identifier file (*Fingerprint*) for your system pressing the *Create System Identifier file* button.

3. Go to [o-charts shop](https://o-charts.org/shop) and buy an UserPermit.

4. Go to the [My S-63 UserPermits](https://o-charts.org/shop/index.php?fc=module&module=ocpermits&controller=ocpermits) page and create an InstallPermit by uploading the Fingerprint file you generated before and linking it to your S-63 UserPermit.

5. Visit the shop of your VAR (S-63 chart provider) and license as many S-63 charts you need, using your OpenCPN S-63 UserPermit. Sometimes a VAR will ask for a "HW-ID", ignore the question. 

6. Download and uncompress your S-63 chart sets files. It shall contain a directory called ROOT_ENC (containing the chart cells) and you shall find a file called PERMIT.txt with the cell permits as well.

7. Go to OpenCPN, *Options → Charts → S63 Charts → Keys/Permits* tab. Enter your UserPermit and test it pressing the *New UserPermit* button. Enter your InstallPermit and test it pressing the *New InstallPermit* button.

8. Go to OpenCPN, *Options → Charts → S63 Charts → Chart Cells* tab. Install Cell Permits by using the button *Import Cell Permits* to find the file PERMIT.txt inside your S-63 chart sets. Import your S-63 chart sets by pressing *Import Charts/Updates* and finding the folder ENC_ROOT.

9. OpenCPN will create the necessary eSENC files and your are done!

# Frequently Asked Questions

> **Why S-63 charts?**
>
> They are the official and generally the most up-to-date chart material available. Vector charts for chart plotters used for the leisure market are at best derivatives (some will have some added features).
 
> **Why do I have to pay for the UserPermit?**
>
> We have to run this operation and respond to the IHO on a permanent base. The structure and costs are kept to a minimum. In case we have a great success economical speaking, funds will go back to OpenCPN.

> **As how many systems counts a dual boot system?**
>
> Each HW/SW combination is an individual one and requires its own InstallPermit.

> **And if I install the software in a Virtual Machine?**
>
> It will not run there. We have to prevent the system from being cloned.

> **I had to re-install my OS. Now the InstallPermit is not valid any longer**
>
> Please generate a new InstallPermit.

> **My PC died. Can I recover the charts?**
>
> Yes, and this case will “cost” you an InstallPermit for your new machine as well.

> **Can I have my InstallPermit and the charts on a USB stick and carry them between different systems?**
>
> This would be a hardware dongle solution. We feel that it is not viable for us to send USB sticks or DVDs all over the world. That's why we opted for a soft dongle. So, the answer today is - no.

> **What does S-63 charts cost (and why are they sometimes so expensive)?**
>
> The retail price is fixed by the individual HOs. Their customers are from the shipping industry or official bodies like governments, not the leisure market. This is a recognized issue and the reason why there are very few users of S-63 charts from this group, for now. We will need a lot of lobbying to get better solutions and better prices. Help or support from those who have the right contacts would be appreciated.

> **My temporary license will time out. What will happen?**
>
> The chart will not disappear, but there will be a warning displayed.

> **OpenCPN is open source. Where is the code for the plug-in?**
>
> To work with S-63 we have to ensure that no copies of the unencrypted cells are accessible during the execution of the software. Therefore, the plug-in has an open-source part and a binary. Similar to the commercial BSB4 or nv-chart plug-ins. 
