---
name: ["@SiruX21", "@Look-Its-Sky", "@RartedRussian", "@Cimbobimb"]
project: "Cloud Computing setup on the go"
---

# Cloud Computing setup on the go 

## Summary


With the death of Stadia coming within the next week, we wanted to emulate the Stadia experience whilst also having more freedom. Stadia provided a remote cloud gaming computer that could play games from anywhere anytime. We want to emulate this system but also put in more freedom to do other things outside of gaming. Cloud technology has been always changing and this is a form of it, allowing us to access this remote workstation from elsewhere. We intend to use it as a proof of concept to learn more about VM-Passthrough, Linux, Host vs VM assigning, as well as the general gist of assembling a computer. We would also use it for gaming, compiling code, video editing, and much much more. The benefit of this local system that we would have is that the PC would be completely accessibly to everyone, giving a full fledge PC experience with no drawbacks whatsoever. We intend to use it for a variety of day to day tasks such as processing large-scale Excel files, gaming, compiling code, local network access, and more. There's also the added benefit of being able to access this kind of power on the go, being far away from home, close to home, and on the go. There is no need to bring around a large laptop with half of the power with a system when we can bring a Chromebook and have the most powerful device all a few clicks away. It would also mean that we would only need one computer to power two high power workstations. 

This system will also serve as hands-on testing units for our School's Cybersecurity Club by allowing our group members to more efficently work with hashing algorithms such as ones in use like SHA-256 and deprecated ones like MD5. Our hardware situation provides a more complex build than typical PC constructions. Our situation with virtual machines means we have to understand hardware and virtualization of hardware in order to provide an efficent and cost effective working experience. We'll also have to tune the hardware in order to ensure that we do not hit our power limits as well as manage the exhaust of thermal energy efficiently. In addition, we have to safely power our so there isn't thermal issues. As it stands our hardware issues entail that we will run into bottlenecks without hardware and software effiency.


## Plan


The current plan right now is to build a computer beefy enough to handle multiple users at the same time. This is going to be the easiest part. First off, the minimum in picking out a computer for this task is for the CPU to have a lot of cores. For this, we picked out the Ryzen 9 5950x because it comes with 16 cores and 32 threads, something that's very much needed with this sort of task. Because of the nature of it, we plan on splitting up the CPU into multiple Virtual Machine, or a VM. Each VM would get assigned its' own GPU, 30 gigabytes of RAM, and 6 cores and 8 threads. With any other AM4 CPU, we would have to have split 3 cores and 6 threads between the 2 VMs which is completely suboptimal for usage. The next parts that we need is 2x 1 TB NVMe SSDs, these are to function as the boot drives of the 2 VMs. One of them will be partially split into a 20 GB and 980 GB partition in order to host the Host OS. The remaining 2 1 TB SATA Drives will be assigned to both VMs as a storage drive. This means that overall with everything, the system should draw a total of 600 watts under full load. This is where the 850w Power Supply comes in whith enough PCIe cables to power both GPUs that are being used for the VM. Lastly, we'll have a GTX 970 assigned directly to the host to function as its' graphics card. This arrangement is ultimately to prevent hardware strain and equally distribute our workload to the best of our ability. In theory, this should allow us to provide workstation level performance using consumer grade hardware. We also plan on researching custom kernels to optimize hardware usage which loops back to our idea behind our headless multiperson workstation. 

For the more technical side, we intend on using Arch Linux as the Host OS for the VMs. The VMs will be running Windows 10 Home Edition in a custom built cut down version in order to minimalize load on the PC. We will use QEMU and Virt-Manager to manage the VMs. We will pass through the RTX 3070 to one VM and the RTX 3060 to another. As for the streaming side of things, the PC will be placed in a home with access to gigabit networking in order to minimalize latency and delay. In order to further help with this delay and image quality problem with cloud gaming, we intend on using the AV1 codec through software based methods in order to achieve better image quality and require less network bandwith for the same image. For the game host, because NVIDIA Gamestream is being sunset, we are instead using [Sunshine](https://github.com/LizardByte/Sunshine), an open-source alternative that functions much like Gamestream. For the client, we will use [Moonlight](https://github.com/moonlight-stream), a collection of a plethora of GameStream clients that's also compatible with Sunshine. In this way, we can leverage Moonlight's great support for devices ranging from Android, iOS, Apple TV, PC, Mac, PS Vita, Wii U, Chromebook, and LG WebOS TV. This level of device support is simply unparalleled compared to other streaming alternatives.


## Budget

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| AMD Ryzen 9 5950x | https://www.microcenter.com/product/630282/amd-ryzen-9-5950x-vermeer-34ghz-16-core-am4-boxed-processor-heatsink-not-included | $499.99 |
| Teamgroup DDR4-3200 2 x 32 GB |https://www.amazon.com/dp/B08HLY8CWN?tag=pcpapi-20&linkCode=ogi&th=1 | $165.99 |
| PNY 1 TB SSD x 2 |https://www.amazon.com/dp/B08KGXVXGM?tag=pcpapi-20&linkCode=ogi&th=1 | $159.98 |
| Teamgroup AX2 SSD x 2 | https://www.amazon.com/dp/B08CKFDPJ3?tag=pcpapi-20&linkCode=ogi&th=1 | $89.98 |
| Asus ROG B450-F Gaming |Owned|Owned|
| Thermaltake Core P3 |Owned|Owned|
| Gigabyte UD 850w PSU |Owned|Owned|
| Gigabyte  RTX 3070 |Owned|Owned|
| EVGA RTX 3060 |Owned|Owned|
| Zotac GTX 970 |Owned|Owned|
| Taxes      |                                       | $75.57|
| Shipping | |$0|
|Total           |                                       | $991.50 |

