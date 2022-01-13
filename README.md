Allows building and upgrading without the need for resources.

## Note
The bare minimum resources will be required in the player's inventory for upgrading, since the client needs to think that the player has enough resources to present the option to upgrade.

## Permissions

* `freebuild.allow` - Allows player to use the `/freebuild` chat commands

## Chat Commands

* `/freebuild` - Toggles the freebuild state on and off. (by default command is "freebuild", can be changed in config).

## Configuration
```json
{
  "Chat Command": "freebuild",
  "Require Chat Command": true,
  "Deployables Are Free": true
}
```

* **Chat Command** - The command used to toggle free building on and off.
* **Require Chat Command** - If set to false, the player will only need the permission `freebuild.allow` in order to build for free, and will not have to use the chat command to toggle on and off.
* **Deployables Are Free** - If set to true, deployables are also free and do not use/remove the item from the player's inventory when placed.