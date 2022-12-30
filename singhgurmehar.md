---
name: "@singhgurmehar"
project: "Secure VPN Travel Router"
---

# Secure VPN Travel Router

![shi](https://user-images.githubusercontent.com/121445557/209771047-dc92d8ad-8185-4681-a910-3f7ff17075ed.png)

## Summary

In Winter Hardware Wonderland, I plan to build a Secured Wifi Router using Raspberry Pie for travel with its own VPN server for providing an advanced security layer over public Wifi's.

Whenever we connect to any public wifi networks , being a Open Wifi, Wifi at coffee shops or Hotels. There's a always high risk to our privacy. To safegaurd our privacy and maintain our Anonymity, this router will let us connect to the internet over VPN. It will be connecting with the public Wifi network and will broadcast its own Wifi network that will be over a VPN server.

## Plan

I will be using a Raspberry Pie 4b as my router by installing Open-WRT over its firmware.

Detailed Steps are as below:
1. First, of all will download OPEN-WRT image from its website and using Raspberry Pie Imager will boot that OS into memory card that will be attached to our pie.
2. Now will power the Pie and using an ethernet cable will connect the pie to my computer and will login to its default gateway in the browser for configuring the router further.
3. For configuring the router i will be refering to youtube video of Network Chuck https://www.youtube.com/watch?v=jlHWnKVpygw .
4. After successful configuration, the usb wireless router will be attached with the pie to broadcast its own Wifi.
5. i will be using Nord VPN server for its VPN profile.
6. After successfully completing the above steps our VPN Travel router is ready to go.

Whenever we have to connect our pie to a public wifi we will login into its default gateway and there in available networks tab will put username and password of the wifi and our pie router will be connected to it to provide us internet over VPN.

Furthermore, if all the above is successful i will try to run a VPN server on the pie for vpn connection and a DNS server using ADGaurd to block ads over the devices connected to pie router. (I will be reffering to youtube for these complex things.)
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
