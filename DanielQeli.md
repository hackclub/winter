---
name: "@DanielQeli, @mjao1"
project: "Modular eBike"
---

# Modular eBike

Every bike can be an eBike

## Summary

Me and my friend Michael would love to build a custom ebike. I've had this project in mind for a while but have never had the money to do it. I have the goal of designing/building it as an easy add-on to almost any standard bike. It will have regenerative braking, an emergency kill switch, variable throttle assist, and a battery life adequate to go to school and back ~ at least 15 miles. On top of this, the throttle settings can be changed on the esc using the desc-tool Android app.

This project is inspired by Tom Stanton's designs - https://youtube.com/playlist?list=PLj3Bh6Krv9CWdRwVFwF1xS_-IQH9GBHyo

## Plan

1. Finalize my calculations for bike acceleration, top speed, battery life
2. Buy all parts on list
3. CAD brackets for, esc, motor, and tensioner
4. CAD large pulley for back wheel
5. 3D print parts - pulley will be printed in two parts and attached with epoxy and alignment grooves
6. Assemble motor to bracket and bracket to back left of bike frame or rear rack - depends on frame interference
7. Assemble pulley to left of rear wheel spokes with high strength zip ties
8. Put tensioner roller on rear left of bike frame
9. Attach esc to rear inside of the bike's triangle frame
10. Attach throttle control to handlebar
11. Attach battery bracket to inside bottom of frame triangle
12. Solder XT90 adapter to Anderson connector on battery
13. Wire motor and throttle control to esc
14. Put bike on lift hand for first throttle test
15. Put battery plug in easily reachable location for unplug - will add actual estop button later
16. Plug in battery and do first throttle test
17. If it acts as predicted, take on bike path and test ride
18. Set up wireless settings tuning with vesc-tool
19. Adjust throttle curves, motor sensors, and regenerative braking to preference
20. Test ride again, this time receiving metrics from vesc-tool
21. Readjust if necessary - First revision is complete!

## Budget

What materials will you need for your project? Where will you get them? How much does it cost? Please include all materials, including components you already own. Make sure to factor in shipping costs and sales tax.

| Product         | Supplier/Link                         | Cost   |
| --------------- | ------------------------------------- | ------ |
| Turnigy SK8 6374-192kV Sensored Brushless Motor   | https://hobbyking.com/en_us/turnigy-sk8-6374-192kv-sensored-brushless-motor-14p.html | $59.99  |
| VESC 6 MkVI | https://trampaboards.com/vesc-6-mkvi-the-amazing-trampa-vesc-6-mkvi-gives-maximum-power-original-p-27536.html  | $281.98 |
| 48v 13Ah eBike battery with BMS | https://www.amazon.com/Unit-Pack-Power-Ebike-Battery/dp/B081N8TLP4/ref=sxin_14_pa_sp_search_thematic_sspa?crid=1S9R7F2I0RWCZ&cv_ct_cx=48v%2B20ah%2Blithium%2Bbattery&keywords=48v%2B20%2Bah%2Blithium%2Bbattery&pd_rd_i=B081N8WYMX&pd_rd_r=acd4bd83-ae6d-4ebb-9a03-b0ade1fc7af2&pd_rd_w=u70K3&pd_rd_wg=GDeZh&pf_rd_p=e2fbde06-fdfe-405b-9a4a-aa3a1757321c&pf_rd_r=9Q3H8QZRGF3621CKGH40&qid=1647278112&sprefix=4v%2B20%2Bah%2Blithium%2Bbattery%2Caps%2C143&sr=1-2-a73d1c8c-2fd2-4f19-aa41-2df022bcb241-spons&spLa=ZW5jcnlwdGVkUXVhbGlmaWVyPUEySUJKUUtOVjFDMlVMJmVuY3J5cHRlZElkPUEwNTc4NzU0Mlk4ODBCMFlPNTBNTiZlbmNyeXB0ZWRBZElkPUEwMDQxODkwUUxJOUc5MjAxUjhBJndpZGdldE5hbWU9c3Bfc2VhcmNoX3RoZW1hdGljJmFjdGlvbj1jbGlja1JlZGlyZWN0JmRvTm90TG9nQ2xpY2s9dHJ1ZQ&th=1 | $269.00 |
| Total           |                                       | $21.90 |
