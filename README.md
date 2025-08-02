# Sir-5rM8 Fix
Simple Mod to fix Sir-5rM8 getting stuck by teleporting it to the target.  
Additionally, adds options to configure weight reduction and the max radius.  
Adds functionality to all existing Sir-5rM8 and does not add new ones.  
Requires Bob's Tall Tales to function.  

## Configuration
Configuration is optional.  
By default, the variant mods default settings will be used.  
The following config options are available under the `[BotFix]` section in your `GameUserSettings.ini`:  

### Teleport Timer
The time in seconds before the Sir-5rM8 will be teleported to the target.  
Default: `60`  
Min: `10`  
Max: `3600`  
```ini
[BotFix]
TeleportTimer=60
```

#### Radius Multiplier
A multiplier to increase/reduce the radius for all Sir-5rM8s Modes.  
Default: `1.0`  
Min: `0.1`  
Max: `10.0`  
```ini
[BotFix]
RadiusMultiplier=1.0
```

### Weight Reduction
A multiplier to reduce the weight of items in the Sir-5rM8's inventory.
Zero means no weight reduction and one means full weight reduction.
Default: `0.0`  
Min: `0.0`  
Max: `1.0`  
```ini
[BotFix]
WeightReduction=0.0
```

## Support
Discord: https://discord.com/invite/K4a4DvZak5
