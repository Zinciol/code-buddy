# Kick the player on connect

To kick the player on connect (before they have spawned in the world), use:

```
on connect:
  kick the player due to "You are banned from this server"
```

{% hint style="info" %}
This will kick the player and the reason displayed will be `You are banned from this server`
{% endhint %}
