Allows building and upgrading without the need for resources.

## Permissions

* `freebuild.allow` - Allows player to use the `/freebuild` chat commands

## Chat Commands

* `/freebuild` - Toggles the freebuild state on and off. (by default command is "freebuild", can be changed in config).

## Configuration
```json
{
  "Give Player Hidden Resources": true,
  "Chat Command": "freebuild",
  "Require Chat Command": true,
  "Deployables Are Free": true
}
```

* **Give Player Hidden Resources** - Place raw materials into hidden slots of the player inventory to make client-side UI think that the player has enough resources to upgrade.

* **Chat Command** - The command used to toggle free building on and off.

* **Require Chat Command** - If set to false, the player will only need the permission `freebuild.allow` in order to build for free, and will not have to use the chat command to toggle on and off.

* **Deployables Are Free** - If set to true, deployables are also free and do not use/remove the item from the player's inventory when placed.