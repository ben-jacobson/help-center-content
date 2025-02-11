---
title: "Configure your network for Arduino IoT Cloud"
---

The Arduino IoT Cloud uses the following domains and ports, which need to be whitelisted in your firewall.

| Domain                  | Port |
| ----------------------- | ---- |
| mqtts-up.iot.arduino.cc | 8884 |
| mqtts-sa.iot.arduino.cc | 8883 |
| wss.iot.arduino.cc      | 8443 |

You will also need to allow NTP access to [time.arduino.cc](time.arduino.cc). Note that the NTP port for [time.arduino.cc](time.arduino.cc) is **123 UDP**.

> A home network with a default configuration will usually not prevent any Arduino IoT Cloud connections. You do not need to add any of the configurations above unless you're experiencing problems, or will be using the service on a restricted network.
