---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults

layout: default
---

<h2>Custom Samsung Kernel</h2>


[Samsung Galaxy TAB3 SM-T210 lt02wifi](https://github.com/asasoft/lt02wifi-kk-kernel/releases)
<ul>
<li>Security patches</li>
</ul>
<hr />

[Samsung Galaxy Pro Y B5510](https://github.com/asasoft/Kernel-B5510/releases)

<li>Swap support (kernel config only) (18/05/13)</li>
<li>I/O Schedulers CFQ , Deadline , No-op default</li>
<li>Ext3/Ext4 Support (No mount scripts)</li>
<li>Netfilter support for Droidwall (iptables)</li>
<li>init.d support (You need Busybox with run-parts and create /system/etc/init.d folder)</li>
<li>Fix bcmsdhc driver wake locks prevent deep sleep ( bcm_sdhc.3 wake lock )</li>
<li>Fix Frequency Table (CpuSpy, SetCPU and others work now)</li>
<li>Ondemand governor added</li>
