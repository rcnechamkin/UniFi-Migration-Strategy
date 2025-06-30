## What I Assumed Building This Repo:
- All sites already have consistent VLANs
- UniFi installment will be pretty much plug-and-play.
- Each site is a flat, isolated deployment. No L3 roaming.
- WPA2-Enterprise with RADIUS is available and properly configured.
- UniFi APs will be adopted to a central cloud-hosted UniFi Network Controller. (This is a big one. I've read a lot of smack talk about Dream Machines, so I'd avoid where I can.)
- Firewall/VLAN/DHCP configuration is handled by upstream devices (like FortiGate), not the UniFi Gateway.
- If the OS is older, API integration would be handled by somebody more software savvy than myself (I thought about throwing together a bash script to showcase that I at least understand how to do approach doing this, but I ran out of time).
- Same can be said about other knowledge gaps on this project rollout: automation & tooling around the controller, automating the syncing of user accounts into RADIUS, implementing dashboards or alerting systems for project visibility, etc. (I have a network specialization with the heart of an ambitious software engineer.)
