---
layout: page
title: Smartphone Digital Forensics - iOS
description: Smartphone Digital Forensics Toolkit for iOS based handheld devices
img: assets/img/ios-1.jpg
importance: 3
category: Work
---

As the lead developer on the iOS Forensics project at <a href='https://nccs.pk/'> NCCS</a>, I designed and implemented a foundational framework for forensic analysis and live data acquisition on iOS devices, specifically focusing on most recent release of iOS 13 at time. This toolkit was developed to give forensic investigators reliable access to critical iOS data and app artifacts, with a unique capability for live imaging that respects data integrity and preserves evidence.

Given the complexities of iOS’s security architecture, I designed the toolkit to include both jailbreak and non-jailbreak techniques. Using non-jailbreak methods, we could securely access logical data from an iPhone without compromising device integrity, while jailbreak-based methods allowed for deeper, full filesystem imaging in controlled settings, making it ideal for comprehensive investigations.

One of the key features of this toolkit is its ability to handle iOS IPA files, which are app packages containing executable and resource files. By extracting and analyzing IPA files, the toolkit gives investigators visibility into app behavior, stored data, and user activity within apps—essential for modern forensic analysis, where app-based data is increasingly relevant.

<b> Tools & Technologies: </b>
<ul>
    <li>Python3: As the primary programming language, Python made it easy to automate acquisition and parsing processes, making the toolkit efficient and scalable.</li>
    <li>libimobiledevice: This suite of tools enabled non-jailbreak access to iOS devices, providing logical imaging and data transfer without altering the device’s state.</li>
    <li>iOS IPA File Analysis: Parsing IPA files allowed for analysis of app behavior, data usage, and storage, uncovering hidden activities or irregularities within app packages.</li>
    <li>File System Utilities (Linux & macOS): Critical for mounting and analyzing iOS filesystem images, ensuring cross-platform usability.</li>
    <li>Forensic Analysis SDKs: Enabled deeper insights into app behavior, user activity, and system logs, helping investigators see the full picture.</li>
</ul>

<b> Key Features: </b>
<ul>
    <li>Live Imaging of iOS Devices: Real-time imaging from iOS devices without affecting original data, preserving critical evidence.</li>
    <li>Jailbreak & Non-Jailbreak Methods: Flexible acquisition options depending on security needs and device restrictions, with jailbreak methods providing full access to the filesystem when needed.</li>
    <li>IPA File Analysis: Extracts and reviews IPA files for a detailed understanding of app activities, metadata, and functionality.</li>
    <li>Cross-Platform Compatibility: Designed to work seamlessly on both macOS and Linux, making it adaptable to different forensic environments and investigator preferences.</li>
    <li>This project was a rewarding experience as it pushed me to bridge the gap between secure data acquisition and robust forensic analysis on iOS devices. The toolkit is now a versatile asset for forensic teams, simplifying the complexities of iOS data access while supporting both secure and advanced investigative techniques.</li>
</ul>