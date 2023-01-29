---
layout: single
title:  "Updating Firmware on Zigbee Routers"
date:   2023-01-24 20:42:08 +0100
categories: home-automation zha zigbee
classes: wide
---

I have three zigbee routers that I've used over the years. A now very old Conbee Stick, an Electrolama zig-a-zig-ah! (zzh!) and a SONOFF Zigbee 3.0 USB Dongle Plus ZBDongle-P. I consider the Conbee to be dead. It's not, it works just fine, but my network has far outgrown its capabilities and it exhibits very odd behaviours if I try to connect eberything to it.

## SONOFF Zigbee 3.0 USB Dongle Plus ZBDongle-P
Ensure your current user is in the `tty` and `dialout` groups.

If not, you should run:
{% highlight bash %}
usermod -aG tty ${USER}
usermod -aG dialout ${USER}
{% endhighlight %}
