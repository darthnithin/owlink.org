---
layout: post
title:  "USENIX Security ’19 Paper Accepted"
date:   2019-05-16 05:00:00 +0200
---

We conducted a security and privacy analysis on AWDL and AirDrop and are proud to announce that the resulting paper **A Billion Open Interfaces for Eve and Mallory: MitM, DoS, and Tracking Attacks on iOS and macOS Through Apple Wireless Direct Link** was accepted at [USENIX Security ’19](https://www.usenix.org/conference/usenixsecurity19). [Read the paper](/publications/) and try out our [AWDL and AirDrop implementations](/code/). See you in California in August!

## Abstract

> Apple Wireless Direct Link (AWDL) is a key protocol in Apple's ecosystem used by over one billion iOS and macOS devices for device-to-device communications. AWDL is a proprietary extension of the IEEE 802.11 (Wi-Fi) standard and integrates with Bluetooth Low Energy (BLE) for providing services such as Apple AirDrop. We conduct the first security and privacy analysis of AWDL and its integration with BLE. We uncover several security and privacy vulnerabilities ranging from design flaws to implementation bugs leading to a **man-in-the-middle (MitM) attack enabling stealthy modification of files transmitted via AirDrop**, **denial-of-service (DoS) attacks preventing communication**, privacy leaks that enable **user identification and long-term tracking** undermining MAC address randomization, and DoS attacks enabling targeted or simultaneous **crashing of all neighboring devices**. The flaws span across AirDrop's BLE discovery mechanism, AWDL synchronization, UI design, and Wi-Fi driver implementation. Our analysis is based on a combination of reverse engineering of protocols and code supported by analyzing patents. We provide proof-of-concept implementations and demonstrate that the attacks can be mounted using a low-cost ($20) micro:bit device and an off-the-shelf Wi-Fi card. We propose practical and effective countermeasures. While Apple was able to issue a fix for a DoS attack vulnerability after our responsible disclosure, the other security and privacy vulnerabilities require the redesign of some of their services.

## Video of Man-in-the-Middle attack on AirDrop

<div class="video-container-wide"><iframe src="https://www.youtube.com/embed/5T7Qatoh0Vo?rel=0" allow="autoplay; encrypted-media" allowfullscreen></iframe></div>
