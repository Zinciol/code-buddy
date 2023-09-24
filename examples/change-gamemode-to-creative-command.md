# Change gamemode to creative command

To change the player's gamemode to creative, use:

```
command /creative:
  permission: gamemode.creative
  description: Sets your gamemode to creative
  trigger:
    execute console command "/gamemode creative %player%"
```

{% hint style="info" %}
This command will only work if the player has the `gamemode.creative` permission
{% endhint %}

This same thing can be done for the other gamemodes.
