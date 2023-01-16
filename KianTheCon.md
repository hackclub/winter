---
name: "@KianTheCon"
project: "Monopoly Tablet"
---

# Monopoly Tablet

## Summary

I am going to build a tablet designed to be mounted to a table so that one can play a digital version of the board game Monopoly on it. It will utilize pieces with special shapes of conductive pads on the bottom (as indicated in this instructable https://www.instructables.com/Object-Interaction-With-Touchscreens) to differentiate the specific pieces, allowing for more specialized semi-physical UI interactions (differentiating which player is moving, letting players move their pieces in a more fun/entertaining way, etc). In the long run, I envision having online play capabilities and possibly other board games (but that is way too ambitious for a short hackathon so Im keeping it simple for now).

## Plan

First, I will first be following more or less this instructable (https://www.instructables.com/Object-Interaction-With-Touchscreens/) in order to set up several prototype game pieces. I will paint some felt pads with conductive filament and attach them to some metal game pieces I already have (or some similar conductive object if that doesn't work).
Second, I will hook up a 7" LCD Display to a NucBox S SBC (I realize that this may seem overkill for this project, but given that I could've payed a similar price for something less powerful than a raspberry pi with the way the pricing is gouged at the moment, I though it would be more appropriate to try and get something that had a better value) in order to allow my special game pieces to interact with my mini tabletop boardgame tablet.
Finally, I will program a Monopoly port that utilizes my different shaped pieces, hopefully creating an interesting digital/physical board game fusion that puts a unique spin on the classic game. 

## Budget

Note: I'm aware this goes a few dollars over budget but Im willing to just pay the excess myself if that is possible
| Product                    | Supplier/Link                                                                                    | Cost   |
| -------------------------- | ------------------------------------------------------------------------------------------------ | ------ |
| Felt Pads                  | https://www.amazon.com/Pack-Two-Colors-Furniture-Protector/dp/B07X941JP2/                        | 7.49   |
| 7" Touchscreen LCD display | https://www.waveshare.com/product/raspberry-pi/displays/lcd-oled/15.6inch-fhd-monitor.htm        | 62.99  |
| Conductive Paint           | https://www.amazon.com/Bare-Conductive-Electric-Paint-10ml/dp/B00KBXT6JW/                        | 13.97  |
| NucBox S (Intel SBC)       | https://www.gmktec.com/collections/mini-pc/products/nucbox-most-powerful-palm-sized-4k-mini-pc-1 | 169.99 |
| Total                      |                                                                                                  | 254.44 |
<!-- TBLFM: @>$>=sum(@2$>..@-1$>);%.2f -->
