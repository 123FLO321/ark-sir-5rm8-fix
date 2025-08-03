# Sir-5rM8 Fix
Simple Mod to fix Sir-5rM8 getting stuck. If a Bot is detected as stuck, it will get teleported to it's target location.  
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

### Auto Enable Sorting
Automatically enables sorting input buttons for all structures near a Sir-5rM8 docking station.  
This is helpful when mods disable the sorting inputs, but can cause visual issues.
Default: `False`  
```ini
[BotFix]
AutoEnableSorting=True
```

### Auto Enable Sorting Timer
The time in seconds between checks for structures to enable sorting inputs.  
Default: `900`  
Min: `60`  
Max: `86400`  
```ini
[BotFix]
AutoEnableSortingTimer=900
```

### Auto Enable Sorting Dedicated
If enabled, will autoconfigure sorting inputs for all nearby dedicated storages (including modded ones like VS).  
This will flip the dedicated storage between input and output mode every `AutoEnableSortingTimer` seconds.
Requires `AutoEnableSorting` to be enabled.
Default: `False`
```ini
[BotFix]
AutoEnableSorting=True
AutoEnableSortingDedicated=False
```

## Support
Discord: https://discord.com/invite/K4a4DvZak5
