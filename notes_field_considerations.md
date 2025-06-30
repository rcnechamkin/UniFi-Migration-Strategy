# Real world findings, as pulled from reddit, Ubiquiti community boards, and the like.

## TL;DR
UniFi works great—until it doesn't. Learn from other IT folks who've been burned.

### Power Failures
- Some admins report frequent PoE injector or switch failures.
- Bring spares, especially for clinics with only 1 AP.

### Controller Quirks
- Cloud Keys can corrupt easily. Avoid if you can.
- Linux VM controller? Rock solid with proper backups.

### DHCP Nightmares
- Migrating from Aruba? Double-check VLAN interfaces and IP helper settings.
- Don't assume VLANs will behave the same.
- Run a packet capture on DHCPDISCOVER/ACK to verify correct scopes.

### Firmware Roulette
- Ubiquiti firmware is known to break things. Test before pushing.
- Subscribe to the community threads to track issues in new builds.

### Support Gaps
- Ubiquiti support is slow and mostly email-based.
- Community forums and Reddit are a lifeline.
