Blacklist craft items or disable crafting altogether.

Prevents people crafting blacklisted items or gives you the option to disable crafting on your server altogether.

## Permissions

- **nocraft.bypass** -- Bypasses craft config options

## Default Configuration File
**oxide/config/NoCraft.json**
```json
{
  "BlockedItems": {
    "rock": true,
    "note": false
  },
  "BlockAll": {
    "Enabled": false,
    "SendMessage": true
  }
}
```
Blocked items usage: "item shortname to block": true = send message, false = just block the craft

FOR EASY TO FIND SHORTNAMES LOOK AT THE RUST ITEM LIST THAT OXIDE PROVIDES HERE [Oxide API for Rust](http://docs.oxidemod.org/rust/#item-list)

## Default Language File 
**oxide/lang/en/NoCraft.json**
```json
{
  "CantCraft": "You're not allowed to craft {0}",
  "CraftingDisabled": "Crafting is disabled on this server"
}
```
