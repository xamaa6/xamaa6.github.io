---
layout: page
title: Security Information & Event Management (SIEM) Solution
description: Security Information and Event Management (SIEM) solution to enhance real-time threat detection and response for SOCs.
img: assets/img/SIEM-1.jpg
importance: 3
category: Education
---

As part of my final year bachelor’s degree project, I designed and developed a custom Security Information and Event Management (SIEM) solution tailored for a Security Operations Center (SOC). This solution addresses the critical need for real-time log collection, parsing, and analysis, enabling SOCs to monitor, detect, and respond to security events more effectively. By integrating agent-based and agentless log collection methods, the solution offers flexibility and scalability, ensuring comprehensive coverage across diverse network environments.

<b> Key Features: </b>

<ul>
    <li>Log Collection: </li>
        <ul>
            <li>Agent-Based Log Collection: Designed and implemented a custom Windows log collection agent using C#. This agent ensures reliable log gathering from Windows systems, providing detailed event information.</li>
            <li>Agentless Log Collection: Integrated Rsyslog to enable seamless log collection from Linux and Unix-based systems. This approach eliminates the need for additional software installations, simplifying deployment in heterogeneous environments.</li>
        </ul>
    <li> Server-Side Processing: Built a robust server-side infrastructure in Python for log handling, real-time analysis, and threat detection. The system is capable of processing high volumes of logs while ensuring accurate identification of security events. </li>
    <li> Real-Time Threat Detection: Enabled the SOC to respond to potential security threats immediately through efficient log parsing and event correlation.</li>
</ul>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SIEM-3.png" title="Syslog Levels Chart" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SIEM-2.png" title="Normalized logs DB" class="img-fluid rounded z-depth-1" %}
    </div>
</div>

<div class="caption">
    Syslog Facility and Severity Levels Chart along with normalized logs in backend Database.
</div>

<b> Technologies Utilized: </b>
<ul>
    <li>Python: Designed and implemented the server-side components for processing, analyzing, and correlating logs to detect and respond to threats in real-time.</li>
    <li>C#: Developed the Windows log collection agent, ensuring secure and efficient log gathering from Windows environments.</li>
    <li>Rsyslog: Leveraged for agentless log collection from Linux/Unix systems, providing flexibility and scalability for diverse network infrastructures.</li>
</ul>

<div class="row">
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SIEM-4.png" title="LogDog Agent" class="img-fluid rounded z-depth-1" %}
    </div>
    <div class="col-sm mt-3 mt-md-0">
        {% include figure.liquid loading="eager" path="assets/img/SIEM-5.png" title="SoC Dashboard" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    LogDog is Agent-Based Log Collection Utility for Windows OS.
</div>

<b> Impact: </b>
<ul>
    <li>Enhanced SOC Monitoring Capabilities: The solution significantly improved the SOC’s ability to monitor network resources, detect anomalies, and respond to security incidents promptly.</li>
    <li>Scalable and Flexible Design: Developed a highly customizable system that can adapt to a wide range of network environments, ensuring effective security monitoring across varied systems.</li>
    <li>Real-World Applicability: By addressing critical challenges in log collection and analysis, this project contributed to creating a robust framework that aligns with the needs of modern security operations.</li>
</ul>

<div class="row justify-content-sm-center">
    <div class="col-sm-8 mt-3 mt-md-0">
        {% include figure.liquid path="assets/img/SIEM-6.png" title="Main Dashboard" class="img-fluid rounded z-depth-1" %}
    </div>
</div>
<div class="caption">
    SIEM Dashboard for SoC Analysts.
</div>

This project was a milestone in my career, blending software development and cybersecurity to deliver a practical, impactful solution for securing network environments.