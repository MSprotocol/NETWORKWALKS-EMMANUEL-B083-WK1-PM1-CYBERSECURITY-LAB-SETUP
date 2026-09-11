# NETWORKWALKS-EMMANUEL-B083-WK1-PM1-CYBERSECURITY-LAB-SETUP

## Project Overview

This project sets up a virtual cybersecurity and penetration-testing lab using **VirtualBox** and **Kali Linux**.
The environment is designed to be safe, repeatable, and isolated, so reconnaissance, network scanning, vulnerability assessment, and other authorized security-testing activities can be performed without impacting external systems.

The lab uses a private virtual network architecture so additional virtual machines can be added later as targets for controlled testing exercises.

## Objectives

- Install and configure VirtualBox.
- Install or import Kali Linux as a virtual machine.
- Create a private NAT Network for the cybersecurity lab.
- Configure Kali Linux networking within the lab network.
- Assign a consistent IP address to the Kali VM.
- Verify network connectivity and DNS resolution.

## 🛡️ Purpose of the Lab

The lab provides an isolated and controlled environment for cybersecurity learning and authorized security testing.

It can be used for activities such as:

Network reconnaissance
Port scanning
Vulnerability assessment
Packet analysis
Web security testing
Exploitation practice
Security-tool experimentation
⚠️ Important: This laboratory must only be used for systems that you own or have explicit permission to test. Do not use the lab or its tools to attack unauthorized systems.
- Take a clean VM snapshot for recovery and rollback.
- Document the full setup process end to end.
- Prepare the environment for future cybersecurity lab projects.

## Expected Outcome

At completion, the repository documents a working baseline lab setup where Kali Linux is connected to an isolated NAT network, has validated connectivity and DNS, and includes a clean restore snapshot to support repeatable future security exercises.

## 🏗️ Lab Architecture



## Lab Configuration
````
| 🧩 Component | ⚙️ Configuration |
|---|---|
| 🖥️ Host OS | Windows 10 |
| 🧠 Host RAM | 8 GB |
| ⚡ Processor | Intel Core i5 |
| 🧰 Hypervisor | VirtualBox 7.2 |
| 🐉 Security OS | Kali Linux 2026.2 |
| 🧠 Kali RAM | 2048 MB |
| 🌐 Virtual Network | NAT Network |
| 📡 Network Address | 10.0.0.0/24 |
| 🐧 Kali IP Address | 10.0.0.2/24 |
| 🚪 Default Gateway | 10.0.0.1 |
| 🌍 DNS Server | 8.8.8.8 |
| 🔮 Future VM Range | 10.0.0.3–10.0.0.99 |
````
