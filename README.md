# Cyber_Security-Blocklist-Compilation

## Overview

Hello, I'm Yuval Grimblat, an IT & Security Integration Specialist at Mornex LTD.
Welcome to my GitHub repository, **Cyber_Security-Blocklist-Compilation**.
This repository is dedicated to compiling and maintaining a comprehensive collection of cyber threat data, with a specific focus on Malicious IP Addresses, Malicious URLs and Malware Hashes.

Currently, it includes two main files:
1. **Auto_Updated_Threat_Feeds_FortiGate_Script**
2. **Malicious-IPs**
3. **External Resources Threat Feeds For Other FWs**
This is just the beginning of an evolving project that aims to provide valuable resources for enhancing cybersecurity measures.

## Contents

### 1. Auto_Updated_Threat_Feeds_FortiGate_Script

This script is designed to facilitate the automated update of threat feeds on FortiGate devices.
By using this script, you can ensure that your FortiGate firewalls are equipped with the latest threat intelligence, enhancing network security.

#### Instructions for Use:
- **Step 1:** Download/Copy the script.
- **Step 2:** Insert the script (copy/paste) into your FortiGate via CLI.
You can adjust the refresh rate for each Malicious IPs/URLs/Malware Hashes Repositories, from the default 43200 seconds (12 hours) to 1 second, the most frequent option.
- **Step 3:** Implement the Threat Feeds by creating Deny Policies from/to your LANs.

### Note for FortiOS Users (as of 25/10/2023):
- **Note #1:** Unfortunately, as of FortiOS versions 7.2.6 and 7.4.1, creating Groups of Threat Feeds (like Address Group or ISDB Groups) for more organized FW Policies (and not a substantial mess with many Threat Feeds that make every policy look "bulky") via the GUI is not supported.

- **Note #2:** If you have VIP Policies from WAN to your LANs (Port Forwarding), ensure using the command `set match-vip enable` in your Deny Policies from WAN to LAN.

### 2. Malicious-IPs

This file contains a constantly evolving list of malicious IP addresses sourced from various threat intelligence feeds and community contributions.
It serves as a reference for blocking or monitoring potentially harmful network traffic.

### 3. External Resources Threat Feeds For Other FWs
Enhance the security capabilities of various Firewalls with this script containing a curated list of external resources.
Tailored for Firewalls beyond FortiGate, it provides valuable threat intelligence from diverse sources.
Elevate your network defenses by leveraging these meticulously compiled feeds designed for a broader spectrum of Firewall platforms.


#### Instructions for Using External Resources Threat Feeds on Other FWs:
- **Step 1:** Download the file.
- **Step 2:** Implement the Threat Feeds on your Firewalls (with the provided links in the file).
   Each FW has its own configuration methods. For troubleshooting, ensure that you use the same naming conventions as I do.
- **Step 3:** Implement the Threat Feeds by creating Deny Policies from/to your LANs.

#### Note:
- Regularly update your firewall or security infrastructure with the IPs/URLs/Malware Hashes listed in these files to enhance protection against known threats.

## Usage Disclaimer

Using this repository is at your own responsibility.
The author and contributors are not liable for any damages or security incidents that may arise from the use of the provided scripts or data.
Exercise caution and thoroughly review and test any components before deploying them in a production environment.

## Contribution Guidelines

Contributions to this repository are highly encouraged.
If you come across new threat feeds, malicious IP addresses, or have improvements to the existing content, feel free to submit a pull request.
Please adhere to the contribution guidelines outlined in the repository.

## Future Development

The Cyber_Security-Blocklist-Compilation project is an ongoing effort.
In future releases, I plan to expand the collection, improve automation scripts, and provide additional tools to bolster cybersecurity efforts.

Your feedback and contributions are valuable in making this project more effective and comprehensive.
Let's work together to create a safer digital environment.

Thank you for your interest in my GitHub Repo "Cyber_Security-Blocklist-Compilation"!

Connect with me on [LinkedIn](https://www.linkedin.com/in/yuvalgrimblat/).

**Happy networking and stay secure!**

**Best Regards,**
**Yuval Grimblat**
**IT & Security Integration Specialist at Mornex LTD**
