# UniFi Device Adoption – Common Fixes

## Device Stuck: "Managed by Another Console"
- Reset with paperclip 10–15 sec
- Re-adopt in GUI

## AP Doesn’t Show Up
- Check VLAN tag on switchport
- Default to native VLAN 10 if possible

## SSID Config Not Applying
- Make sure WLAN group matches site
- SSH to AP and run `set-inform http://<controller>:8080/inform`

(Common problems and fixes gathered mostly from the Ubiquiti UniFi forums)
