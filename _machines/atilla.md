---
layout: single
permalink: /machines/atilla/
title: "Atilla"
excerpt: "GOLD plus 7''"
header:
  overlay_image: /assets/images/atilla4.jpg
  image: /assets/images/atilla3.jpg
  teaser: assets/images/atilla3.jpg
---
* __Producer:__ [Atilla Roasters](http://www.atilla.com.br/), Brazil
* __Machine:__ all Atilla Gold plus roasters with 7" touch display (2/5/10/15/30 kg)
* __Connection:__ MODBUS TCP via the network
* __Features:__ 
  - logging of environmental temperature (ET), bean temperature (BT) and related rate-of-rise curves

### Setup

The computer running Artisan must be on the same IP network as the Atilla roaster which usually is configured to have IP 192.168.0.20. Configure your computer to use a static IP address in the range 192.168.0.x (but with x different from that of the roaster which usually has 15), so for example 192.168.0.15, and set the subnet mask to 255.255.255.0. This can be done on Windows using the Network Sharing Center by adding a TCP/IPv4 Local Area Connection with those properties. On OS X you set your Ethernet port in the Network Control panel to "IPv4: Manually" and fill in the IP and subnet mask accordingly.
{: .notice--primary}