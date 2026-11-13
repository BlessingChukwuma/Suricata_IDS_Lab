# Suricata IDS Lab

My first Suricata Intrusion Detection System (IDS) project.

## What I Did
- Installed and configured Suricata on Ubuntu
- Used Kali Linux to generate test traffic (ping) against the Ubuntu sensor
- Created a custom rule in `rules/local.rules` to detect ICMP ping traffic
- Tested the rule and confirmed alerts in `eve.json` and `fast.log`
- Collected evidence screenshots

## Lab Setup
- Host: Windows
- VirtualBox
- Ubuntu VM - Suricata IDS Sensor (Suricata configured here)
- Kali Linux VM - Attacker/Testing Machine (used to generate traffic)

## Tools Used
- Suricata
- Ubuntu
- Kali Linux
- Git / GitHub
- VS Code
- VirtualBox

## Project Structure
- `rules/local.rules` - My custom detection rule
- `docs/` - Logs (eve.json, fast.log, stats.log)
- `evidence/screenshots/` - Screenshots of setup and alerts

  ## What I Learned
  I learnt how to set up a virtual lab, configure Suricata on Ubuntu, write a Suricata rule, generate traffic from kali, and as well detect it with Suricata
  

## What I Learned
How to write a Suricata rule, run Suricata, and check alerts to detect network traffic. 
