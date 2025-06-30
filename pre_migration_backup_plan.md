# Backup Plan Before Cutover

## Strategy
Every controller config gets a full backup before anybody even thinks about migration. Store both local and cloud if possible.

## UniFi GUI Path
Settings > Console > Backups
- Enable weekly auto-backup
- Manually export `.unf` file before changes

## Restore Steps
1. Go to same console > Backups
2. Upload `.unf` file and restore
3. Devices will re-adopt and config will reload

Redundant backups are of course extremely necessary. Another lesson learned by techs publicly shaming themselves on community forums. We thank them for their sacrifices.
