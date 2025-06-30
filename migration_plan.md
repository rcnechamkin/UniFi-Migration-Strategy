# Aruba to UniFi Wireless Migration Plan

## Goal
To standardize all wireless infrastructure across sites using Unifi, simplify SSID structure, and use VLANs to appropriately compartmentalize network access. 

## Phase Overview
1. **Audit** - Document all existing Aruba gear and their SSIDs and VLANs. (This step assumes documentation doesn't already exist. If it does, it's still probably a good idea to verify)
2. **Design** - Define SSID/VLAN layout, create controller templates.
3. **Pilot** - Stage a couple different test sites.
4. **Rollout** – Deploy in regional waves and confirm everything actually works.
5. **Post-Mortem** – Document issues and finalize documentation.

## Potential risks
| Risk | Plan |
|------|------|
| PoE misconfig | Pre-validate switch inventory |
| Guest VLAN leak | Tag and isolate VLAN 99 properly |
| Controller adoption fails | Use Layer 3 fallback CLI |
