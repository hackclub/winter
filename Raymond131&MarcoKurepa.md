---
name: "@Raymond131" "@MarcoKurepa"
project: "Computer Vision Raspberry Pi Drone"
---

# Project Name: Computer Vision Raspberry Pi Drone

## Summary

Build a lidar capable 250mm sized drone using a stereo camera and Raspberry Pi Zero W setup.
The drone will be capable of 3D position and pose estimation using april tags or some other visual fiducials. 

## Plan

We are going to refer to this tutorial from theDroneDojo:
https://dojofordrones.com/pi-zero-drone/
Apriltag detection and pose estimation has already been tested on laptop cameras and is ready for implementation once we've figured out basic drone controls. 

## Budget


| Product                | Supplier/Link                                                                                                          | Cost   |
| ---------------        | -------------------------------------                                                                                  | ------ |
| Soldering kit        | https://www.amazon.com/Soldering-Iron-Kit-Temperature-Desoldering/dp/B07Q2B4ZY9/ref=sr_1_3?keywords=soldering+starter+kit&qid=1672984829&sr=8-3                                                                                               |$27.99|
| Tip tinner             | https://www.amazon.ca/gp/product/B00NS4J6BY/ref=ox_sc_act_title_3?smid=A614WYM65K035&psc=1                             |$8.90|
| Electrical solder      | https://www.amazon.ca/gp/product/B075WB98FJ/ref=ox_sc_act_title_1?smid=A25N4YN27ERTBB&psc=1                            |$13.98|
| Raspberry Pi Zero W    | https://www.walmart.ca/en/ip/Raspberry-Pi-Zero-W-Starter-Kit-And-Accessories/PRD4I8NV1BP9Y0M?skuId=4I8NV1BP9Y0M&offerId=AF223F6F822A4719ABD9AA5D2408B53E&utm_medium=paid_search&utm_source=google&utm_campaign=always_on&cmpid=SEM_CA_312_50W1NMFMAF_71700000099943876_58700008013744816&utm_id=SEM_CA_312_50W1NMFMAF_71700000099943876_58700008013744816&gclid=Cj0KCQiAn4SeBhCwARIsANeF9DI0D0fO9zcY1GQS2f9kmN9Vd_5pPNcfupDZJSm6ZTtGN8VJJnMoMT8aAo6kEALw_wcB&gclsrc=aw.ds                                                                                            |$41.53|
| Matek f405 hdte        | https://www.aliexpress.com/item/1005004245016541.html?pdp_npi=2%40dis%21CAD%21C%24%2074.06%21C%24%2074.06%21%21%21%21%21%402103239d16736511689713783e46e0%2112000028507305028%21btf&_t=pvid:f85eafcb-6d76-4152-8073-88e378681c41&afTraceInfo=1005004245016541__pc__pcBridgePPC__xxxxxx__1673651169&spm=a2g0o.ppclist.product.mainProduct |$68.65|
| jhemcu 4in1 esc        | https://www.aliexpress.com/item/1005003838395770.html?pdp_npi=2%40dis%21CAD%21C%24%2075.34%21C%24%2037.67%21%21%21%21%21%40210312ee16736508332157925e9b66%2112000027310030607%21btf&_t=pvid:98977ce7-2c43-4be9-966e-7a563519f05f&afTraceInfo=1005003838395770__pc__pcBridgePPC__xxxxxx__1673650833&spm=a2g0o.ppclist.product.mainProduct                         |$36.44|
| mounting screws and 
  rubber dampers         | https://www.aliexpress.com/i/4000640626186.html                                                                        |$7.63|
| 2205 motors            | https://www.aliexpress.com/item/1005004006627573.html?spm=a2g0o.productlist.main.3.4d8e3fd5VMlR70&algo_pvid=ae632000-2c0a-44c4-ba09-43625e87aadc&algo_exp_id=ae632000-2c0a-44c4-ba09-43625e87aadc-1&pdp_ext_f=%7B%22sku_id%22%3A%2212000027718503101%22%7D&pdp_npi=2%40dis%21CAD%2145.32%2131.73%21%21%21%21%21%402102111816737112486993237d0688%2112000027718503101%21sea&curPageLogUid=sQ5Fdbw0cOXq |$28.82|
| buck converter 6pack   | https://www.amazon.ca/eBoot-MP1584EN-Converter-Adjustable-Module/dp/B01MQGMOKI/ref=sr_1_7?crid=JIYBLVLTFK77&keywords=eBoot%2BMini%2BMP1584EN%2BDC-DC%2BBuck%2BConverter%2Bvoltage%2Bregulator&qid=1673712006&refinements=p_85%3A5690392011&rnid=5690384011&rps=1&s=industrial&sprefix=eboot%2Bmini%2Bmp1584en%2Bdc-dc%2Bbuck%2Bconverter%2Bvoltage%2Bregulator%2Cindustrial%2C190&sr=1-7&th=1 |$17.80|
| Totem 250mm frame      | https://hobbyking.com/en_us/hobbykingtm-totem-q250-quadcopter-kit.html               | $21 |
| propellars             | https://www.amazon.ca/HQProp-Watermelon-Tri-Blade-Propeller-Quadcopter/dp/B07TV284BK/ref=sr_1_9?crid=OACB4FC8VG4S&keywords=5%22+drone+props&qid=1673651919&sprefix=5+drone+props%2Caps%2C91&sr=8-9 |$22.04|
| wires                  | https://www.amazon.ca/Silicone-Electrical-Colors-Stranded-Flexible/dp/B08P4BPMZD/ref=asc_df_B08P4BPMZD/?tag=googleshopc0c-20&linkCode=df0&hvadid=579901165099&hvpos=&hvnetw=g&hvrand=13307836738394359913&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001107&hvtargid=pla-1191098481079&psc=1 |$11.02|
| capacitors             | https://www.aliexpress.com/item/1005002907532157.html?pdp_npi=2%40dis%21CAD%21C%24%201.52%21C%24%200.99%21%21%21%21%21%40210312ec16736522941627046e6cda%2112000022718307915%21btf&_t=pvid:00fbf120-4248-4d8a-a2aa-56fd0d6320dd&afTraceInfo=1005002907532157__pc__pcBridgePPC__xxxxxx__1673652294&spm=a2g0o.ppclist.product.mainProduct |$2.54|
| transmitter and receiver| https://www.aliexpress.com/item/32892186713.html?spm=a2g0o.productlist.main.51.14af1e30jHa4Tn&algo_pvid=9eae3cf2-80bf-4776-9816-aaf5fd0ff6af&algo_exp_id=9eae3cf2-80bf-4776-9816-aaf5fd0ff6af-25&pdp_ext_f=%7B%22sku_id%22%3A%2267179347319%22%7D&pdp_npi=2%40dis%21CAD%21131.56%2168.42%21%21%21%21%21%40212279a216737131785445529d0686%2167179347319%21sea&curPageLogUid=7sZeDIHUGAo2     |$63.56|
| battery charger         | https://www.aliexpress.com/item/1005003687797757.html?spm=a2g0o.productlist.main.33.7ebe3807K5mv2P&algo_pvid=9c65ea68-7877-4845-bcf9-a56eb7f9956d&aem_p4p_detail=2023011408261214197877837995170004907506&algo_exp_id=9c65ea68-7877-4845-bcf9-a56eb7f9956d-16&pdp_ext_f=%7B%22sku_id%22%3A%2212000026806052264%22%7D&pdp_npi=2%40dis%21CAD%217.96%216.53%21%21%21%21%21%402102172f16737135726908599d0674%2112000026806052264%21sea&curPageLogUid=TSdyAKxTmkI3&ad_pvid=2023011408261214197877837995170004907506_17&ad_pvid=2023011408261214197877837995170004907506_17   |$11.02|
| 2 rpi cameras         | https://www.amazon.ca/seeed-studio-Raspberry-Official-V2%EF%BC%8C1080p/dp/B07Y33ZQZN/ref=asc_df_B07Y33ZQZN/?tag=googleshopc0c-20&linkCode=df0&hvadid=335201232415&hvpos=&hvnetw=g&hvrand=17481634044660296103&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001107&hvtargid=pla-863733022264&psc=1 |$66.11|
| multicam adapter      | https://www.uctronics.com/arducam-multi-camera-adapter-doubleplexer-stereo-module-v2-for-raspberry-pi-zero-pi-3-3-b-4b.html |$33|
| Total           |                                                                                                                              |$481.93|


