---
name: "@griffinli"
project: "Supercomputer Box + Laptop"
---

# Supercomputer Box + Laptop

## Summary

On December 16, 2022, [Mighty](https://www.mightyapp.com/) shut down. They had built a Mac app that streamed Chrome, running on an 8 vCPU, 40GB RAM, ~4Gbps-internet, NVIDIA GPU-backed server in a datacenter in North Virginia, right next to the datacenters of AWS, Cloudflare, etc. (and with datacenters in various other locations across the US). All the computation would be done on their datacenter computers, and then the graphical output would be streamed to the MacOS client.

It was founded by [Suhail](https://twitter.com/Suhail), who had previously founded Mixpanel. I'd been a user of their product for a couple of months, and they managed to build it such that it felt like it was running locally — the latency was essentially unnoticeable. I had messaged him pitching that they build a small box similar to an Apple TV, whose sole purpose would be to connect to the Mighty cloud computer. He disagreed with the idea and explained his reasoning, but since then it's been one of the things I've wanted to try making, and I've wanted to see what it would be like to use it.

I'm going to build a tiny desktop box with a Raspberry Pi inside that streams Chrome at very low latency from an extremely powerful computer running on AWS. It'll be connected to my external display, and mouse and keyboard. It'll be intended to be used as a complete desktop computer (now that most of the apps I/we use are web-based), and it'll be like having a maxed-out desktop computer in a box the size of the palm of your hand. I'd want to also make it so that different user accounts (connected to different Chrome instances) can log in, such that any user's computer can be accessed from this box (or any other ones if there were more).

I'm going to build a laptop client as well (running on an old ThinkPad) — it would connect to the same AWS instance (and thus make the same computer accessible from both my desktop and on the go). 

## Plan

For the Raspberry Pi box, I'd first get it up and running with some barebones version of Linux, and then I'd look for something open-source that I can build on related to streaming display output in real time. I'd look for whatever would work best (I'm not sure yet how much of the streaming work it'll handle and how much I'd need to write myself). I'd create an initial version of authentication (probably just command-line-based) that points to different AWS instances depending on who logs in.

For the laptop, I'd purchase an old ThinkPad, clear out its operating system and install non-GUI Linux, and then use the code for the Raspberry Pi box. I'd get the inbuilt keyboard and trackpad working directly in Linux and just relay whatever input has been received to the AWS instance.

I'd then try to make whatever improvements would be helpful/useful, like lowering the latency or figuring out UI things like how files and downloads would be handled.

## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Raspberry Pi 4  | https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TC2BK1X | $159.89  |
| Raspberry Pi Case, 3D-printed | n/a (have access to a 3D printer) | $0
| Old ThinkPad (model depends on eBay offerings) | Eg: https://www.ebay.com/itm/155249855675  | ~ $100-200 |
| AWS EC2 t3.2xlarge (or similar, eg. g4ad.2xlarge for GPU) | https://aws.amazon.com/ec2/instance-types/t3/ | $0 (covered by AWS credits) |
| Total           |                                       | ~$259.89-359.89 |

I'll pay for costs over the grant amount
