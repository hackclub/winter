---
name: "@singhgurmehar"
project: "Secure VPN Travel Router"
---

# Secure VPN Travel Router

![shi](https://user-images.githubusercontent.com/121445557/209771047-dc92d8ad-8185-4681-a910-3f7ff17075ed.png)

## Summary

In Winter Hardware Wonderland, I plan to build a Secured Wifi Router using Raspberry Pie for travel with its own Dns Server & VPN server for providing an advanced security layer over public Wifi's.

Whenever we connect to any public wifi networks , being a Open Wifi, Wifi at coffee shops or Hotels. There's a always high risk to our privacy. To safegaurd our privacy and maintain our Anonymity, this router will let us connect to the internet over VPN. It will be connecting with the public Wifi network and will broadcast its own Wifi network that will be over a VPN server.With our own DNS server we will be able to safeguard our devices from ads & trackers by blocking them.

## Plan

I will be using a Raspberry Pie 4b as my router by installing Open-WRT over its firmware.

Detailed Steps are as below:
### Basic Router Config
1. First, of all will download OPEN-WRT image from its website and using Raspberry Pie Imager will boot that OS into memory card that will be attached to our pie.
2. Now will power the Pie and using an ethernet cable will connect the pie to my computer and will login to its default gateway in the browser for configuring the router further.
3. For configuration first we will use cmd using SSH to run commands on OpenWRT. Things to set up in configuration are config interface 'lan' , changing private ip address, config interface 'wwan'(to set up DHCP server), config interface 'vpnclient' (for setting up vpn client), firewall config wan zone, config wifi-device 'radio0' (wifi interface used to broadcast SSID), config wifi-iface 'default_radio0' (interface used to connect with public wifi). After successfull above configuration, we can access GUI interface for further config by entering Router Gateway, which include naming SSID's, setting up VPN client, DHCP setting, Setting up DNS servers,etc.  
4. After successful configuration, the usb wireless router will be attached with the pie to broadcast its own Wifi.
5. i will be using OPen VPN server for its VPN profile.
6. Basic Router config is done here.
Whenever we have to connect our pie to a public wifi we will login into its default gateway and there in available networks tab will put username and password of the wifi and our pie router will be connected to it to provide us internet over VPN.

### Setting up DNS server on Pie to Block Ad's & Trackers
I will be using Rust to create a DNS server on the Pie which will be able to block ip addresses containing ADware. FoBuilding a DNS server in Rust involves using libraries like trust-dns or rust-dns, which provide abstractions and tools for working with the Domain Name System (DNS) protocol. i will be using rust-dns 

Overview of steps involed in the process are:

1. We will use and install rust-dns as our library.
2. Next, will set up a UDP listener to receive incoming requests, as the DNS protocol uses UDP for communication.
3. Then will parse the incoming requests to extract information like the domain name being queried and the type of query.
4. Based on the type of query, either will have to look up the requested information in our local cache or will forward the query to another DNS server.
5. Now will have to build a DNS response to send back to the client.
6. Using the UDP connection, will send the response back to the client.
7. For each incoming request, we have to repeat this process.
8. For a fully fledged dns server that automates the above process i have to spend some more time, which i will be doing in the following days. 
After successfull configurations and DEbugging Issues (if any) our DNS server is ready to go.

### Setting Up VPN server
i will be using OPENVPN to run my own vpn server.
1. Will install PiVPN on our Raspberry Pi using command ``` curl -L https://install.pivpn.io | bash ```.
2. Now willr un PiVPN. Tell PiVPN whether you set up a static address (a DHCP reservation).we will choose between OpenVPN in the dialog box appeared.
3. Now we have to select a communication protocol. UDP is recommended for OpenVPN.
4. Now will Set the VPN port. The default OpenVPN port is 1194.
5. In Set the DNS provider dialog box. we will enter our own DNS server which we started using ADGuard.
6. Now will  select the Enable OpenVPN 2.5 features option. If PiVPN presents them, follow the steps for creating a security certificate and configuration file.
7. Now will enter in default gateway of our OpenWRT and we have to forward the VPN port to the internal IP address of our Raspberry Pi VPN server,  port for OpenVPN to be entered will be 1194 in our case.
Our Raspberry Pi VPN server will now be ready to go.

After successfully completing the above steps our VPN Travel router is ready to go.
## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pie 4b   | [https://www.amazon.in/Raspberry-Pi-8GB-Desktop-Computer/dp/B08B9XS3B6?th=1](https://amzn.to/3VnGGfX) | $169.87  |
| Pie Case | https://www.thingbits.in/products/raspberry-pi-official-case-for-pi-4-model-b?src=raspberrypi?src=raspberrypi  | $3.86 |
| Pie Case Fan | https://www.factoryforward.com/product/official-raspberry-pi-4-case-fan/  | $5.18 |
| Power Supply | https://www.thingbits.in/products/raspberry-pi-official-15w-usb-c-power-supply-for-pi-4?src=raspberrypi%3Fsrc%3Draspberrypi | $7.23
| USB Wifi Adapter | https://www.netgearstore.in/products/a6150-dual-band-wifi-usb-adapter-ac1200 | $25.93
| SD Card | [https://www.amazon.in/Samsung-microSDXC-Memory-Adapter-MB-MC64KA/dp/B09MT84WV5?th=1](https://amzn.to/3YQvZoZ) | $13.22
| SD Card Reader | [https://www.amazon.in/Brand-Conquer-Reader-Adapter-Portable/dp/B07YL54NVJ/ref=sr_1_3?crid=1Q2MAJP7CXNME&keywords=sd%2Bcard%2Breader&qid=1672164242&s=computers&sprefix=sd%2Bcard%2Ccomputers%2C1658&sr=1-3&th=1](https://amzn.to/3FYm48m) | $6.62 |
| Ethernet Cable | Already Owned | $0
| Total           |                                       | $231.91 |
