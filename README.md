# CPTS 427 Project - Wireless Analysis

## Overview
This project aims to analyze the wireless networks of WSU's public spaces and find vulnerabilities as well as create an inventory of devices.

## Themes
The following themes relating to the course were involved in this project:
- WPA2 Network security
- OWE/WPA3 Network security
- User identity and activity exposure on public networks
- Differences between HTTP and HTTPS for security and encryption on public networks

## Design Decisions/Trade-offs:
I used Wireshark and Network Manager on Linux to create an inventory of devices and analyze packet data in monitor mode on the network.
A big trade-off I had to make was that I had to exclusively do passive analysis of the network, because attacking it directly to find vulnerabilities without permission is illegal.

## Challenges / Lessons Learned:
- A big challenge was deciding what locations to use for this assignment. I chose the SPARK, all three libraries, the CUB, and the Chinook for this project. I chose these because they were the most popular common spaces and would likely have lots of users on the Wi-Fi connections to do homework and study.
- A lesson I learned was that open/guest Wi-Fi is typically a lot less secure than people like to act like it is, and even though the invention of HTTPS has massively improved security on public networks, it is still very insecure and you should absolutely avoid non-HTTPS connections while on open networks.

## Final Notes
Please view the Project Report, available in this repository, for a more detailed analysis and my recommendations for security.
