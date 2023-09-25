# Types

## Command sender

Use `[the] console` for the console and `[the] player` for the player

{% code title="Example" %}
```
command /party:
  trigger:
    if command sender is console:
      broadcast "Time to party"
    else:
      say "Only the console can start a party"
```
{% endcode %}
