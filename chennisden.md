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
- (this is the primary hardware part) Using Ethernet cables and our router, create a network with the Orange Pi set up to handle all incoming requests, and set up a DMZ to segregate outbound traffic from our personal machines and traffic on the server.
- Write a custom, light-weight Git host and self-host on the server (work is already happening at https://sr.ht/~dennisc/glee/)
- Migrate all non-profit code onto the host

## Budget

(We already have Ethernet cables and do not need to purchase them.)

| Product         | Supplier/Link                                | Cost   |
| --------------- | -------------------------------------------- | ------ |
| Orange Pi 3 LTS | https://orangepi.net/product/orange-pi-3-lts | $66.68 |
| Total           |                                              | $66.68 |
