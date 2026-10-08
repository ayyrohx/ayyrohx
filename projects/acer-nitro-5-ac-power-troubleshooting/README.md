# Acer Nitro 5 AC Power Troubleshooting

## Overview

Investigated the AC power path of an Acer Nitro 5 AN515-55 after the laptop stopped responding to the power button.

## Symptoms

The system showed no signs of receiving usable power:

- No charging indicator
- No power indicator
- No fan movement
- No keyboard response
- No display

## Troubleshooting

### Battery Isolation

The internal battery was disconnected to separate battery-related behavior from AC power behavior.

### AC Test

The laptop was connected to the appropriate AC adapter while the battery remained disconnected.

The laptop continued to show no signs of power.

## Potential Failure Points

Based on the symptoms, possible failure points include:

```text
AC Adapter
    ↓
DC-In Connection
    ↓
Input Protection / Power Circuit
    ↓
Charging / Power Management
    ↓
Motherboard Power Rails
    ↓
System Startup
```

The exact failure point has not yet been confirmed.

## Planned Testing

Future testing will include:

- Measuring AC adapter output voltage.
- Inspecting the DC-in connection.
- Checking motherboard input voltage.
- Testing relevant power rails.
- Investigating potential shorts or failed power-management components.

## Skills Demonstrated

- AC power troubleshooting
- Hardware isolation
- Laptop diagnostics
- Power-path analysis
- Systematic troubleshooting

## Status

**Conclusion**

Testing the Acer Nitro 5 with the internal battery disconnected and the correct AC adapter connected produced no charging LED, power LED, fan activity, or other signs of startup.

The AC adapter was previously functioning normally with the laptop before the sudden shutdown. Combined with the confirmed near-zero-resistance short on the motherboard's battery power rail, the evidence indicates that the laptop's motherboard power circuitry is preventing normal AC power operation.

The AC adapter itself was not identified as the primary cause. The exact motherboard component responsible for the electrical failure was not isolated.
