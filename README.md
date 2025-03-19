# WIFIRE 3.0 Beta (Closed Release) ALL CODE IN BETA BRANCH 

## Overview
WIFIRE 3.0 Beta is the latest evolution of the WIFIRE project, designed to streamline wireless network auditing with a focus on automation, efficiency, and reliability. This closed beta version enhances attack sequencing by first attempting WPS-based exploits (if available) before falling back to handshake capture and deauthentication attacks, closely mimicking the behavior of Wifite.

## Key Features

- **Automated Attack Flow** – Prioritizes WPS attacks before switching to handshake capture, ensuring optimal attack efficiency.
- **Improved Stability** – Verifies if the monitor mode interface is successfully enabled before proceeding, reducing errors.
- **Real-Time Network Scanning** – Continuously scans and updates available networks with a user-friendly tabulated display.
- **WPS Vulnerability Detection** – Uses `wash` to check for WPS-enabled networks and launches Pixie Dust attacks when possible.
- **Enhanced Handshake Capture** – Automates `airodump-ng` and `aireplay-ng` for reliable deauthentication and handshake retrieval.
- **Failsafe Mechanisms** – Detects interface failures and prevents attacks if the network interface is down, improving stability.
## INSTALLATION
- go into beta branch and install the .py file then navigate to the file path on your linux terminal and just lunch it from terminal 

## Usage

1. Start the program and scan for available networks.WHEN U THINK THE SCAN IS DONE PRESS CONTROL C ONCE THEN WAIT 5 SECONDS AND PRESS ANOTHER TIME to get to next step.
2. Select a target network from the displayed list.
3. WIFIRE will attempt a WPS attack first (if applicable), then proceed to handshake capture and deauthentication.
4. If successful, the captured handshake can be used for further analysis.

## Notes
- Running this tool without proper authorization is illegal. Ensure you have explicit permission before using it.
- This beta version is still under development. Report any bugs or issues to the development team.

## Future Improvements
- AI-powered attack selection for optimal efficiency.
- Integration with external wordlists for automatic cracking.
- Enhanced logging and reporting features.

This version marks a major step forward in automation and usability, bringing WIFIRE closer to Wifite-level functionality while keeping it lightweight and interactive. 🚀
