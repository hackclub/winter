---
name: "chennisden"
project: "Self-hosted server"
---

# Self-hosted server

## Summary

I plan to self-host a number of static websites and fullstack webapps for our non-profit, Math Advance (projects: a math contest portal, custom grading software for our online math program), along with hosting an email service.

The main thing I will be hosting is a custom web Git host, and that is what I will spend the bulk of the time working on, along with the actual hardware setup.

## Plan

- Burn Alpine Linux onto the disk
- Install Postgres (database)
- Install Postfix and Dovecot (email)
- Migrate and set up web services, as well as updating reverse DNS
- (long term) Write a custom, light-weight Git host and self-host on the server (work is already happening at https://sr.ht/~dennisc/glee/)
- Migrate all non-profit code onto the host
- Using Ethernet cables and our router, create a network with the Orange Pi set up to handle all incoming requests, and set up a DMZ to segregate outbound traffic from our personal machines and traffic on the server.
- Wire DHT22 temp/humidity sensor to the Orange Pi and run a cronjob to email myself whenever external temperature/humidity conditions are negatively impacting the performance of the server 

## Budget

(We already have cables and do not need to purchase them.)

Taxes/shipping are approximated from the DHT22 and 16GB SD Card; the Orange Pi's website already has both of these factored in.

| Product         | Supplier/Link                                                                      | Cost   |
| --------------- | ---------------------------------------------------------------------------------- | ------ |
| Orange Pi 3 LTS | https://orangepi.net/product/orange-pi-3-lts                                       | $66.68 |
| DHT22           | https://www.amazon.com/Aideepen-Digital-Temperature-Humidity-Replace/dp/B01IBBFOF0 | $9.95  |
| 16GB SD Card    | https://www.amazon.com/Micro-Center-Class-Flash-Memory/dp/B07K8339X8/              | $9.99  |
| Shipping + Taxes|                                                                                    |~$5.00  |
| Total           |                                                                                    |~$81.63 |
