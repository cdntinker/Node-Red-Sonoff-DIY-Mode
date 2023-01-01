# Node-Red-Sonoff-DIY-Mode
Node-Red flows for manipulating Sonoff Devices via their [_RESTful API_](https://sonoff.tech/diy-developer/#7) in __DIY Mode__.

Well...

Sorta...

ATM, this is in the very early stages & consists of flows and subflows to test the idea.

**NOTICE!!! The [SONOFF DIY MODE API PROTOCOL](https://sonoff.tech/diy-developer/#7) documentation supplied by iTead contains errors.**

One error that'll cause particular stress is that the example output provided is NOT actual output.  For example, the "Get Device Info" output bears little resemblance to what the device returns.  It does NOT return its __deviceid__ and the up to date __fwVersion__ is 1.4.1

## Subflows:
### Sonoff1
This subflow sends _RESTful API_ requests to the device.
### Sonoff2
This subflow actually uses __Sonoff1__ to retrieve the device info from the device.

## Flows:
### MiniR2 DIY Mode
For talking to the [Sonoff MiniR2](https://itead.cc/product/sonoff-mini/) DIY Switch.
### MiniR3 DIY Mode
For talking to the [Sonoff MiniR3](https://itead.cc/product/sonoff-minir3-smart-switch/) DIY Switch. (Which is mostly unrelated to the MiniR2 DIY Switch... :confounded: )
### BasicR3 DIY Mode
(future item)
Should be same as MiniR2
### RFR3 DIY Mode
(future item)
Should be same as MiniR2
### D1 DIY Mode
(future item)
### B05-BL DIY Mode
(future item)
### SPM-Main DIY Mode
(future item)
