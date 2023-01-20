---
name: "@EpicCactus94"
project: "Self Balancing Reaction Wheel Cube"
---

# Self Balancing Reaction Wheel Cube

## Summary

Design and 3D print a reaction wheel cube and code it to be able to balance on a corner (even on inclined surfaces) and react to disturbances 
like pushing. I was inspired to build this project from videos online of how they're used in satelites.

## Plan

I've already begun designing the .stl files which will be used to print the cube, and I've assured access to 3D printers before the building week. 
I'll buy some screws and bolts to act as weights out of my own pocket as they're pretty cheap. Once the parts come in I should be ready to begin assembly 
day 1, and focus more on programming my project the rest of the week or so.

## Budget


| Product                | Supplier/Link                                                                                                         																							    | Cost |
| ---------------        | -------------------------------------                                                                                 																							    |------|
| Filament               | https://www.amazon.ca/Printer-Filament-Printing-Dimensional-Accuracy/dp/B0B4G2Z34W/ref=asc_df_B0B4G2Z34W/?tag=googleshopc0c-20&linkCode=df0&hvadid=578868884140&hvpos=&hvnetw=g&hvrand=17454927583378976190&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001106&hvtargid=pla-1876249594014&psc=1 |$22.98|
| Lipo Battery           | https://www.amazon.ca/EFL-EFLB4503SJ30-450mAh-11-1V-Battery/dp/B002FTKKKE/ref=asc_df_B002FTKKKE/?tag=googleshopc0c-20&linkCode=df0&hvadid=335979661141&hvpos=&hvnetw=g&hvrand=10495110802915175628&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001106&hvtargid=pla-772093357396&psc=1           |$15.39|
| Lipo Battery Charger   | https://www.amazon.ca/Battery-Balancer-Charger-7-4-11-1V-Compact/dp/B06XR87987/ref=asc_df_B06XR87987/?tag=googleshopc0c-20&linkCode=df0&hvadid=293019993829&hvpos=&hvnetw=g&hvrand=14277290759782485441&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001106&hvtargid=pla-577584115103&psc=1      |$14.99|
| 4 Nidec 24H motors     | https://campaign.aliexpress.com/wow/gcp/tesla-pc-new/index?UTABTest=aliabtest344316_486351&_randl_currency=CAD&_randl_shipto=CA&src=google&aff_fcid=14c4d4e62f39436cb6965e5112f036db-1673734156129-05834-UneMJZVf&aff_fsk=UneMJZVf&aff_platform=aaf&sk=UneMJZVf&aff_trace_key=14c4d4e62f39436cb6965e5112f036db-16
				73734156129-05834-UneMJZVf&terminal_id=2b2945a5745249759f314b00cffa1a65&wh_weex=true&wx_navbar_hidden=true&wx_navbar_transparent=true&ignoreNavigationBar=true&wx_statusbar_hidden=true&bt_src=ppc_direct_lp&scenario=pcBridgePPC&productId=1005003148100947&OLP=1084300508_f_group2&o_s_id=1084300508      |$22.16|
| MPU 6050 Gyroscope     | https://campaign.aliexpress.com/wow/gcp/tesla-pc-new/index?UTABTest=aliabtest344316_486351&_randl_currency=CAD&_randl_shipto=CA&src=google&src=google&albch=shopping&acnt=631-313-3945&slnk=&plac=&mtctp=&albbt=Google_7_shopping&albagn=888888&isSmbActive=false&isSmbAutoCall=false&needSmbHouyi=false&albcp=19
				373658608&albag=&trgt=&crea=en1005004577864733&netw=x&device=c&albpg=&albpd=en1005004577864733&gclid=CjwKCAiAwomeBhBWEiwAM43YINHFzs9cQJSeuSGXrxAggZBTBVBoTkOGs_If1ipZcybU6kSgdp189hoC7EQQAvD_BwE&gclsrc=aw.ds&aff_fcid=0e2f16d4529a4a39a3c3c52939717d5c-1673733986373-05500-UneMJZVf&aff_fsk=UneMJZVf&aff_pl
				atform=aaf&sk=UneMJZVf&aff_trace_key=0e2f16d4529a4a39a3c3c52939717d5c-1673733986373-05500-UneMJZVf&terminal_id=2b2945a5745249759f314b00cffa1a65&wh_weex=true&wx_navbar_hidden=true&wx_navbar_transparent=true&ignoreNavigationBar=true&wx_statusbar_hidden=true&bt_src=ppc_direct_lp&scenario=pcBridgePPC&pr
				oductId=1005004577864733&OLP=1084300508_f_group2&o_s_id=1084300508 ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |$00.97|
| ESP32 Develpment Board | https://www.amazon.ca/Development-Wireless-Module-Bluetooth-Arduino/dp/B07HG5XHLB/ref=asc_df_B07HG5XHLB/?tag=googleshopc0c-20&linkCode=df0&hvadid=335526236542&hvpos=&hvnetw=g&hvrand=13125919861204072284&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001106&hvtargid=pla-880970728247&psc=1   |$15.39|
|Board Prototyping Kit   | https://www.amazon.ca/Prototype-Soldering-Universal-Printed-Electronic/dp/B07F7WBY7Y/ref=asc_df_B07F7WBY7Y/?tag=googleshopc0c-20&linkCode=df0&hvadid=292957440852&hvpos=&hvnetw=g&hvrand=8605762176416675743&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001106&hvtargid=pla-494185443828&psc=1 |$19.99|
|Pin Head Connector Kit  | https://www.amazon.ca/Glarks-Connector-Assortment-Stackable-Breakaway/dp/B07CWSXY7P/ref=pd_day0fbt_img_sccl_1/142-5920760-9434629?pd_rd_w=NIe32&content-id=amzn1.sym.2788fe34-0865-4f82-b5fb-522b9cf2f5fd&pf_rd_p=2788fe34-0865-4f82-b5fb-522b9cf2f5fd&pf_rd_r=YYHWHTE8ZJQAKEQSCZ6E&pd_rd_wg=WIeNr&pd_rd_r=4669f9
				57-7223-4e57-9873-8b8267ddedc7&pd_rd_i=B07CWSXY7P&psc=1---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |$20.99|
|Soldering Kit           | https://www.amazon.com/Soldering-Iron-Kit-Temperature-Desoldering/dp/B07Q2B4ZY9/ref=sr_1_3?keywords=soldering+starter+kit&qid=1672984829&sr=8-3															                    |$27.99|
|Bread Jumper Wires      | https://www.amazon.ca/Elegoo-120pcs-Multicolored-Breadboard-arduino/dp/B01EV70C78/ref=asc_df_B01EV70C78/?tag=googleshopc0c-20&linkCode=df0&hvadid=292982668700&hvpos=&hvnetw=g&hvrand=3927578199861647801&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9001106&hvtargid=pla-362913641420&psc=1    |$15.99|
| Total           |                                                                                                                             																					 		 |$151.8USD|

