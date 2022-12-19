# Node-Red-Sonoff-DIY-Mode
Node-Red flows for manipulating Sonoff Devices via their [_RESTful API_](https://sonoff.tech/diy-developer/#7) in __DIY Mode__.

Well...

Sorta...

ATM, this is in the very early stages & consists of flows and subflows to test the idea.

## Subflows:
### Sonoff1
This subflow sends _RESTful API_ requests to the device.
### Sonoff2
This subflow actually uses __Sonoff1__ to retrieve the device info from the device.

## Flows:
### MiniR2
For talking to the [Sonoff MiniR2](https://itead.cc/product/sonoff-mini/) DIY Switch.
### MiniR3
For talking to the [Sonoff MiniR3](https://itead.cc/product/sonoff-minir3-smart-switch/) DIY Switch. (Which is mostly unrelated to the MiniR2 DIY Switch... :confounded: )
