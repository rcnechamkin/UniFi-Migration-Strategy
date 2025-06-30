# Site Migration Walkthrough

This should be used by whatever technician is in charge of on-site migration.

## Before You Go
- [ ] Verify Unifi Controller is reachable remotely
- [ ] Ensure switchports are configured (PoE, VLAN)
- [ ] Load site config template to controller

## On-Site Cutover Steps
1. Remove Aruba AP, mount Unifi in same spot
2. Plug into switch, confirm PoE and link
3. Wait for device to appear in Unifi
4. Assign to proper site config
5. Confirm SSID broadcast + VLAN isolation

## After Cutover
- [ ] Run test on Staff and Guest SSIDs
- [ ] Run `iperf` test if you have time
- [ ] Email site manager with handoff info
