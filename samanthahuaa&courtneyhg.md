---
name: "@samanthahuaa and @courtneyhg"
project: "Custom Key Layouts"
---

# Custom Key Layouts

## Summary

We are going to be coding our own custom key layouts by forking QMK. We have no experience with building keyboards or coding in C so this will be a fun way to expose ourselves to something new! We want to program key layouts that will be more functional for our daily tasks such as dedicating certain keys to copying and pasting and controlling the volume. We want to also experiment with the different layers of our keyboard and immerse ourselves in that typing experience. As we learn more about the capabilities of QMK, our ideal key layout will most likely change as well! These keyboards will be used for everything from school to playing video games.

We will also modify the GMMK Pro keyboard so that it has wireless capabilities. This will allow for a more streamlined workflow and ease of access of the keyboard. The Keychron K6 Pro keyboard already has wireless capabilities so we will not need to modify that keyboard.

## Plan

We will first start by building our keyboards and lubing our switches so that we will have an actual keyboard to program. (We both don't already have a mechanical keyboard so this is a necessary first step) From here on, we will use [this Youtube Playlist](https://www.youtube.com/playlist?list=PLYEUsdlqPD2a3kzQgnF98Prj-4IzZJGYG) to guide us. Next, we will familiarize ourselves with the files in [QMK github repo](https://github.com/qmk/qmk_firmware) and in particular, those that are designed for our keyboards. We will use the documentation linked below in our separate parts so we can begin programming. We will reference [this documentation](https://docs.qmk.fm/#/keycodes) for all of the possible keycodes we can use. Once we have designed the key layout of our dreams, we will flash our keyboards and test it out!

Alongside what is outlined above, we will make the GMMK Pro keyboard wireless by following [this tutorial](https://hightech-lowlife.github.io/projects/004_wireless_keyboard/004_wireless_keyboard). We will also use [this tutorial](https://www.ivanyu.ca/blog/2014/2/2/wireless-das-keyboard-modification) to guide us. We will first plan out where all of the elements will go in the case or outside of it. Then we will layout how the pieces will be connected as the tutorials describe and slowly solder them together. We will test frequently throughout the process to ensure we did not mess up along the way. 

As we are going through this process together, we will help one another if we get stuck. We wanted to do this project together to share the knowledge we each have about keyboards and programming. It also allows us to share some resources like the switch lube. We both go to the same school so sharing the products with one another will be no issue.

Samantha - I will be using the GMMK Pro barebones as it has a lot of documentation on how to utilize QMK for my custom key layout. I found an in depth tutorial [here](https://www.gloriousgaming.com/blogs/news/step-by-step-guide-to-configuring-your-gmmk-pro-using-qmk#:~:text=The%20GMMK%20PRO%20also%20utilizes,be%20compatible%20with%20Glorious%20Core.).

Courtney - I will be using [this documentation](https://github.com/CanUnesi/QMK-on-K6) to guide me on how to use QMK for a Keychron K6. The guide is for Windows 10 users but I have Windows 11. I don't forsee that this will be an issue as the steps should be pretty similar.

Shoutout to [@Roizor](https://github.com/hackclub/winter/blob/main/Roizor.md) for inspiring us to create this project!

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Switch Film | [Amazon](https://www.amazon.com/Switch-Cherry-Gateron-Mechanical-Keyboard/dp/B09BCXCCVS/ref=sr_1_5?keywords=switch%2Bfilms&qid=1672287887&sprefix=switch%2Bfilm%2Caps%2C84&sr=8-5&th=1) | $13.80 |
| Switch Lube with Lube Oil| [Amazon](https://www.amazon.com/Keyboard-Switches-Grease-Gateron-Mechanical/dp/B09JYWC7BM/ref=sr_1_8?crid=3TX3K603026KX&keywords=Krytox%2B205g0&qid=1672288300&sprefix=krytox%2B205g0%2Caps%2C102&sr=8-8&th=1) | $18.89 |
| Glorious Panda Unlubed Switches | [Amazon](https://www.amazon.com/Glorious-Panda-Switch-UNLUBED-GLO-SWT-HPANDA/dp/B08DJXYGY8?th=1) | $42.50 |
| Matcha keycaps | [Amazon](https://www.amazon.com/keycaps-Double-Profile-Mechanical-Keyboard/dp/B09NRK5B3L/ref=sr_1_3?crid=S3V3U794HLMQ&keywords=oem%2Bprofile%2Bkeycaps%2B65%25&qid=1673753266&s=electronics&sprefix=oem%2Bprofile%2Bkeycaps%2B65%25%2Celectronics%2C101&sr=1-3&th=1) | $23.99 |
| Soldering Kit | [Amazon](https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07XKZVG8Z/ref=sr_1_9?keywords=soldering+kit&qid=1675296481&sr=8-9) | $9.99 |
| Shipping for Amazon | All of our products qualify for free shipping | $0 |
| GMMK Pro Barebones | [Microcenter](https://www.microcenter.com/product/649713/glorious-gmmk-pro-75-barebone-ansi-usa-white-ice) | $185.09 |
| Shipping for MicroCenter |  | $0 (Will be going to the store to pick up the item) |
| Gateron Pro 2.9 Yellow Switches | [Divinikey](https://divinikey.com/products/gateron-ks-9-pro-2-0-switches?_pos=1&_psq=%20gateron%20pro&_ss=e&_v=1.0) | $19.67 (We will use code LULZTHAX for a discount) |
| Stem Holder | [Divinikey](https://divinikey.com/collections/keyboard-tools/products/switch-stem-picker-4-pong) | $4.27 (We will use code LULZTHAX for a discount) |
| Shipping for Divinikey |  | $7.33 |
| Keychron K6 Pro Barebones | [Keychron](https://www.keychron.com/products/keychron-k6-pro-qmk-via-wireless-custom-mechanical-keyboard?variant=40119467802713) | $89 |
| Shipping for Keychron |  | $15 |
| Bluetooth Adapter | [Handheld Scientific](http://handheldsci.com/kb/) | $39.95 |
| Shipping for Handheld Scientific |  | $6 |
| Battery Charging Circuit Board | [AliExpress](https://www.aliexpress.us/item/3256801187950590.html?spm=a2g0o.productlist.0.0.5a3576a4JXtj7l&algo_pvid=686d729f-e1b9-42d4-9f35-9a1fd3cd6ced&algo_exp_id=686d729f-e1b9-42d4-9f35-9a1fd3cd6ced-22&pdp_ext_f=%7B%22sku_id%22%3A%2212000015851249830%22%7D&gatewayAdapt=glo2usa4itemAdapt&_randl_shipto=US) | $2.39 |
| Blue Keycaps | [AliExpress](https://www.aliexpress.us/item/3256803930199160.html?spm=a2g0o.productlist.main.57.53d418echPqhKN&algo_pvid=1824c31f-b81d-414d-853f-92f8feea106d&algo_exp_id=1824c31f-b81d-414d-853f-92f8feea106d-28&pdp_ext_f=%7B%22sku_id%22%3A%2212000028092548592%22%7D&pdp_npi=2%40dis%21USD%2135.59%2127.05%21%21%21%21%21%40212272e216752935988081340d0685%2112000028092548592%21sea&curPageLogUid=3lsrcL5r0KMG) | $27.05 |
| Rechargable Battery | [AliExpress](https://www.aliexpress.us/item/3256804705600013.html?spm=a2g0o.productlist.main.3.928f54f32Dp7uh&algo_pvid=5a4765ee-e1d3-49ac-a316-d651ce279b04&algo_exp_id=5a4765ee-e1d3-49ac-a316-d651ce279b04-1&pdp_ext_f=%7B%22sku_id%22%3A%2212000030914508361%22%7D&pdp_npi=2%40dis%21USD%219.86%216.9%21%21%21%21%21%40211bf49716752952667391003d06eb%2112000030914508361%21sea&curPageLogUid=sbZQEkv739uq) | $4.00 |
| Shipping for AliExpress |  | $3.05 |
| Total |  | $511.97 |
