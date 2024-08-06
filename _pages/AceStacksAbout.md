---
permalink: /projects/acestacks
title: "AceStacks Info"
excerpt: "Information about AceStacks, a custom SlimeVR tracker design."
author_profile: true
layout: single
classes: wide
last_modified_at: 2024-07-18T11:59:26-04:00
# toc: true
---
<span style="color:red">**Current Lead Times: Out of Stock! Allow at least 2-3 weeks for restocking.**</span>
<!-- <span style="color:green">**ACESTACKS V2 IS IN STOCK! Turnaround is quick (1 week to ship out) and I should be able to send trackers in short order**</span> -->
<!-- <span style="color:yellow">**Current Lead Times: Parts on order, Allow 1-2 weeks for restock + assembly.**</span> -->

[Buy Acestacks Now](https://ko-fi.com/s/f68f3c7944){: .btn .btn--success .btn--large}

![v2 Trackers]({{ site.url }}{{ site.baseurl }}/assets/images/AceStacks/PXL_20240717_204242217.MV~2.jpg){: .align-left}
Acestacks is an IMU-based, full body tracker design compatible with SlimeVR, an open-source VR Full Body Tracking solution. SlimeVR trackers work without using expensive lighthouses or base stations, and are compatible with any SteamVR enabled headset.

For more information about SlimeVR, and information on how to set up the software and hardware for SlimeVR, [visit the official documentation for SlimeVR](https://docs.slimevr.dev/)  

![v1 vs v2 Boards]({{ site.url }}{{ site.baseurl }}/assets/images/AceStacks/ASComparison.jpg){: .align-right}
#### Improvements From v1 to v2
- **Hybrid SMD Design** -> Better Reliability and Durability
- **BMI160 -> BMI270 Sensors**, longer time between resets!
- Improved Charging Circuit
- Better Power Switch
- Case Improvements
- Included 4 in 1 USB C Charging Cable

#### Tracker Bundles

| **Set** | **Main + Ext** | **Description**                                                                  |
|---------|----------------|---------------------------------------------------------------------------------|
| Lite     | 5 + 0          | Leg Tracking, can be paired with phone or JoyCon for extra tracking points       |
| Core     | 6 + 0          | Spine and Leg Tracking, the sweet spot!                                          |
| Enhanced | 6 + 2          | Same as Above w/ Feet Trackers for Foot Rotation                                 |
| Enhanced+| 8 + 0          | Full Trackers instead of Extensions, Which Can be Used for Either Feet or Elbows |
| Dance    | 8 + 2          | Same as Enhanced w/ Elbow Tracking                                               |

#### Tracker Specifications
- Compatible with SteamVR, VMC Protocol, and OSC for Tracking
- 100Hz Update Rate, Low Latency Tracking
- Uses Wi-Fi for Connectivity
- Upgradable with Newer SlimeVR Software and Firmware
- 47x57mm, 53g per tracker

#### Technical Specifications
- BMI270 Inertial Measurement Units (IMUs)
- TP4057 Charging Circuit w/ Protection
- IMUs come pre-calibrated (gyro, accel, and temp cal)
- Vapcell T8 850mAh Hotswappable 16340 Battery for ~8hr Battery Life
- 1x Micro-USB Port for Flashing, 1x USB C Port for Charging
- Ships with v0.4.0 SlimeVR Firmware
- Printed in Sunlu PLA+

#### Extra Options
- Chest Tracker: can be replaced with a GoPro Quick Release compatible case on request for free (strap or GoPro QR Mount not Included)
- Garter Straps for Thighs: an additional strap between the waist strap/belt and the thigh trackers for added stability and to prevent the thigh trackers from riding down ($20)

What's not Included?
- Micro-USB Data Cable Not Included

### Project Repo
This design is [open-source](https://github.com/AcerolaVR/AceStacksV2), feel free to check out the documentation, view attribution, build your own, or make modifications to this design with attribution

## List of Attributions for Work Used
- **SlimeVR Firmware**: [GitHub - SlimeVR-Tracker-ESP](https://github.com/SlimeVR/SlimeVR-Tracker-ESP)
- **Loud/BMI270 Main Branch**: [GitHub - l0ud/SlimeVR-Tracker-ESP-BMI270/tree/main](https://github.com/l0ud/SlimeVR-Tracker-ESP-BMI270/tree/main)
- **Strap Buckles from mike-d3v**: [GitHub - mike-d3v/slime-stuff](https://github.com/mike-d3v/slime-stuff)
- **GoPro QR Buckle from TactTM**: [Thingiverse - GoPro QR Buckle](https://www.thingiverse.com/thing:4541823/)
- **ErrorBox**: For the initial idea to stack the D1 Mini


## Changelist
v2
- Hybrid SMD Design -> Better Reliability and Durability
- BMI160 -> BMI270 Sensors
- Improved Charging Circuit
- Better Power Switch
- Case Improvements
- Included 4 in 1 USB C Charging Cable
  
v1.2 
- Moved all SMD components (resistor + diodes) to the back of the PCB
- Added a solder jumper for 5V power to build w/o diodes
- More information on the silkscreen for all solder connections
  
v1.1 
- Respaced D1 Mini for more reliable USB connectivity
- Swapped to larger 1206 resistor for battery sense
- Added battery protection diodes
- Cleaner and improved silkscreen, now with logo
  
v1.0 
- initial release!
- no battery protection diodes/circuits