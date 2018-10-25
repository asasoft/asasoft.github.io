---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h4>Galaxy TAB3 SM-T210</h4>  
![SM-T210](/assets/img/samsung-galaxy-tab3-smt210.jpg){:class="img-responsive"}
<ul>
<li>Security patches</li>
</ul>
Flasheable ODIN image md5 b4746aad68bb2c801d137583b895f580

Don't decompress or modify the downloaded file. Open Odin (v3.09 recommended) put your tablet in download mode and connect your usb cable, open PDA box and select the file. Start Flash.

This is an ODIN flasheable kernel, before start make your own kernel/rom backup just in case.  

[Source Code](https://github.com/asasoft/lt02wifi-kk-kernel)  
[Download](https://github.com/asasoft/lt02wifi-kk-kernel/releases/download/v1.2.1/asasoft-1.2.1-kernel-smt210-lt02wifi-kitkat.tar.md5)
<hr />
<h4>Galaxy Pro Y B5510</h4>  
![SM-T210](/assets/img/samsung-galaxy-y-pro-b5510.jpg){:class="img-responsive"}
<ul>
<li>Swap support (kernel config only) (18/05/13)</li>
<li>I/O Schedulers CFQ , Deadline , No-op default</li>
<li>Ext3/Ext4 Support (No mount scripts)</li>
<li>Netfilter support for Droidwall (iptables)</li>
<li>init.d support (You need Busybox with run-parts and create /system/etc/init.d folder)</li>
<li>Fix bcmsdhc driver wake locks prevent deep sleep ( bcm_sdhc.3 wake lock )</li>
<li>Fix Frequency Table (CpuSpy, SetCPU and others work now)</li>
<li>Ondemand governor added</li>
</ul>
Don't decompress or modify the downloaded file. Open Odin (v1.84 recommended) put your phone in download mode and connect your usb cable,
open PDA box and select the file. Start Flash.  

Flasheable ODIN image md5 3f5e58ea9d9565f07da7b9a59b36f9d9  

[Source Code](https://github.com/asasoft/Kernel-B5510)  
[Download](https://github.com/asasoft/Kernel-B5510/releases/download/1.4.2/Samsung-B5510-Kernel-PDA-Odin.v1.4.2.tar)
<hr />
Disclaimer : Flashing firmware involves risk. You can brick your device, proceed with caution.<br/>The Software is provided "as is" without warranty of any kind, either express or implied.
