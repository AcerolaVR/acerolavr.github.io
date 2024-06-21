---
permalink: /projects/acestacks
title: "AceStacks Info"
excerpt: "Information about AceStacks, a custom SlimeVR tracker design."
author_profile: true
layout: single
classes: wide
last_modified_at: 2024-02-28T11:59:26-04:00
# toc: true
---
<!-- <span style="color:green">**Current Lead Times: In Stock! Allow 1 week for assembly, calibration, and testing.**</span> -->
<!-- <span style="color:yellow">**Current Lead Times: Parts on order, Allow 1-2 weeks for restock + assembly.**</span> -->
<!-- <span style="color:red">**Current Lead Times: Out of Stock! Allow at least 2-3 weeks for restocking.**</span> -->
<!-- <span style="color:red">**Current Lead Times: Out of Stock! Restock is normally 2-3 weeks but batteries are out of stock EVERYWHERE, Lead time are uncertain.**</span> -->

<span style="color:green">**ACESTACKS V2 IS IN STOCK! Turnaround is quick and I should be able to send trackers in short order**</span>

[Buy Acestacks Now](https://ko-fi.com/s/f68f3c7944){: .btn .btn--success .btn--large}

![v2 Trackers]({{ site.url }}{{ site.baseurl }}/assets/images/AceStacks/V2.jpg){: .align-left}
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



#### Tracker Bundles (Main + Aux Count)
- **5 + 0 Set:** Lite Set, Leg Tracking, can be paired with phone or JoyCon for extra tracking points
- **6 + 0 Set:** Core Set, Spine and Leg Tracking, the sweet spot!
- **6 + 2 Set:** Enhanced Set, Same as Above w/ Feet Trackers for Foot Rotation
- **8 + 0 Set:** Enhanced+ Set, Full Trackers instead of Extensions, Which Can be Used for Either Feet or Elbows
- **8 + 2 Set:** Dance Set, Same as Enhanced w/ Elbow Tracking

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
This design is [open-source](github.com/AcerolaVR/AceStacks), feel free to check out the documentation, view attribution, build your own, or make modifications to this design with attribution

#### Changelist
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