# VLAN + SSID Mapping Strategy

| SSID           | VLAN | Use Case          | Notes |
|----------------|------|-------------------|-------|
| Clinic-Staff   | 20   | Internal staff     | WPA2-Enterprise, RADIUS
| Clinic-Admin   | 30   | Admin/Finance     | ACLs to critical apps
| Clinic-Guest   | 99   | Patient/Visitors  | Captive portal, DHCP only

VLANs are all arbitrary. If VLANS are predefined elsewhere, such as an upstream device (like Fortigate), then there's no reason to try to change them.
