# Keymaster-Basic
Simple Home Assistant Lock Manager.


## Inspiration
For a more features check out [Keymaster](https://github.com/FutureTense/keymaster)
 
Combined into a package from: [HA Simple Lock Manager](https://github.com/markaggar/HA_Simple_Lock_Manager) and added logic to support lock groups for easier management.


# Install

## Package Install

1. Copy [packages/keymaster-basic.yaml](packages/keymaster-basic.yaml) into your Home Assistant package directory
2. Update keymaster-basic.yaml to include your locks and people you want to notify
3. Restart Home Assistant

## Lovelace UI Page

1. Open a Lovelace Dashboard
2. Go to Edit Dashboard
3. Go to Raw Configuration Editor
4. Copy everything below "views:" from [lovelace-keymaster-basic.yaml](lovelace-keymaster-basic.yaml) into the bottom of the editor
