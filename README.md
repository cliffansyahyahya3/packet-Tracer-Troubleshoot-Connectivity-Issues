Packet Tracer – Troubleshoot Connectivity Issues (PKA)

This project is a guided Cisco Packet Tracer troubleshooting lab focused on identifying and fixing network connectivity and DNS issues in a multi-network environment. The activity simulates a real-world scenario where users report they cannot access a web server after a network change.

Project Scenario

Users are unable to access the web server www.cisco.pka after a recent upgrade that added a second DNS server. The task was to troubleshoot the network, verify configurations, and restore connectivity where possible. Any issues that could not be resolved locally were documented and escalated.

Some devices (ISP router and cloud resources) were intentionally inaccessible to simulate real enterprise constraints.

Network Overview

    Two routers (R1 and ISP router R2)

    Multiple LANs connected through R1

    Web server and DNS servers located on a remote network

    End devices across different subnets

The network uses:

    Static IP addressing

    Default gateways

    DNS name resolution

    Serial WAN connection between routers

Objectives Completed

    Verified and corrected IP addresses, subnet masks, and default gateways

    Tested connectivity using ping

    Tested web access using both DNS name and IP address

    Identified DNS-related issues affecting web access

    Documented unresolved issues that required escalation

    Verified end-to-end connectivity for all PCs

Troubleshooting Steps Performed

    Used ipconfig to validate host configurations

    Tested connectivity to:

      Default gateways

      Other local PCs

      Remote PCs

      Web server by IP address

    Compared results across multiple end devices

    Isolated whether issues were caused by:

      Incorrect IP configuration

      Routing problems

      DNS resolution failures

    Confirmed which problems could and could not be fixed with local access

Key Issues Identified

    Some PCs had incorrect or missing network configuration

    Web access by IP address worked while DNS name resolution failed

    DNS2 could not be fully utilized due to limited access to ISP/cloud devices

    Certain problems required escalation because core infrastructure was outside user control

Concepts Demonstrated

    Network troubleshooting methodology

    IP addressing and subnetting

    Default gateway configuration

    DNS resolution vs direct IP access

    Layered troubleshooting (host → gateway → remote network)

    Understanding of real-world access limitations

    Clear technical documentation

Tools Used

    Cisco Packet Tracer

    Command Prompt (ipconfig, ping)

    Web browser testing

How to Open the Project

    Install Cisco Packet Tracer

    Download the .pka file from this repository

    Open it in Packet Tracer

    Follow the instructions inside the activity
