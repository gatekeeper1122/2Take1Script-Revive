# 2Take1Script Revive

2Take1Script Revive is the offical fix for the 2Take1Script, a script made by [**haekkzer**](https://github.com/haekkzer/) who discontinued it and allowed me to take it over

> Big Thanks to Proddy and haekkzer himself who teached me some stuff about lua and helped me with issues!
> 
> - Thanks to Kektram for (more or less) allowing me to steal 2 globals

### Table of Contents

[**Setup**](#setup)  
[**Features List**](#features-list)  
[**Customize the Script**](#customize-the-script)  
[**Known Issues**](#known-issues)  
[**Common Questions**](#common-questions)  
[**Changelog**](#changelog)

## Setup

Download the latest script release from this git-repo [**download**](https://github.com/DemonKiya/2Take1Script-Revive/releases). The script comes in a `2Take1Script_Revive.zip` file.

Extract the `.zip` file in the `scripts` folder from the menu (see the [**Scripts Guide**](https://gta.2take1.menu/features/local/scripts) for further details).
If done right, your `scripts` folder should contain:

- `2Take1Script_Revive.lua` (main script)
- `2Take1Script_Revive\` (folder with additional assets)

Once all the above is done, you can straight go to [**Scripts**](https://gta.2take1.menu/features/local/scripts) and select **2Take1Script_Revive.lua**.

If you have a problem loading this script, have a look [**here**](#common-questions).

## Features List

### Online Players

- Unmark Modder
- Waypoint Player
- TP to Player
- TP Players Vehicle to me
- Ragdoll Player
- Vehicle Options
  - Remote Controll Vehicle
  - Repair Vehicle
  - Vehicle Godmode (Give and Remove)
  - Kick from Vehicle
  - Modify Speed (0-500)
- Attach Objects
  - Attach Entity from Aim
  - Clear Entities
  - Custom Attachments
- Lag Area with Vehicles
  - Select from a custom list of Vehicles to lag the area
  - Delete Vehicles
- Log Events
  - Log Script Events
  - Reset Script Event Log
  - Log Net Events
  - Reset Net Event Log
- Script-Events
  - Custom Script Events
    - Enter Custom Script Event with Parameters
    - Send Script Events from a Custom presaved list
  - Give Bounty (Custom Input, Anonymous or Named)
  - Send Player to Island
  - Block - Passive
  - Unblock - Passive
  - Send Player to Mission
  - CEO
    - Ban
    - Dismiss
    - Terminate
- Send PEDs (Assassins)
  - Clear PEDs
  - Send PEDs from a custom list
- Send SMSs to Player
  - Custom SMS input
  - Send his SCID & IP
  - Send SMS from a custom presaved list
- Miscellaneous
  - Falling Asteroids
  - Delete Asteroids
  - Apply random Force to Player
  - Trap in Prison
  - Trap in invisible Cage
- Kick Player
- Crash Player

### Player Options

- Random Clothes
- Force Police Outfit
- Health
  - Fill Health
  - Undead OTR
  - Unlimited health-regen!
  - Revert health after disabling Unlimited-regen
  - Health Boosts
    - Max Online Health: 328
    - Health: 100
    - Health: 500
    - Freemode Beast: 2500
    - Health: 10000
    - Health: 25000
    - Health: 50000
    - Health: 100000
    - Health: 5000000
- Ragdoll
- Ragdoll-Toggle
- Aim Protection
  - Enable Aim Protection
  - Anonymous Punishment
  - Ragdoll Player
  - Set on Fire
  - Kill Player
  - Remove Current Weapon
  - Kick Player
  - Electrocute Player
- Bodyguards
  - Godmode for Bodyguards
  - Set Health of Bodyguards (100-50000)
  - Equip Bodyguards with MG
  - Set Formation
  - Set Number
  - Enable Bodyguards

### Lobby

- Block Vehicles
  - Activate Block Vehicles
  - Select from currently 16 blockable Vehicles
- Block Areas with Objects
  - Teleport to Block Location (see [note 3](#notes))
  - Block LSCs
  - Casino
  - Maze Bank
  - Custom Locations
- Explosion Features (see [note 4](#notes))
  - Laser Beam Explode Waypoint
  - Random Explosions
    - Select Explosion Type
  - Shake Cam
- Chat Features
  - Echo Chat X times
  - Ultra Spammer
  - Punish Money Beggers (see [note 6](#notes))
  - Enable Chat-Commands
  - Chat-Commands (see [note 7](#notes))
    - `!explode <playername>`
    - `!explodeall` \[SU\]
    - `!kick <playername>`
    - `!kickall` \[SU\]
    - `!crash <playername>`   \[SU\]
    - `!crashall` \[SU\]
    - `!lag <playername>`
    - `!trap <playername>`
    - `!tp <playername>`   \[SU\]
    - `!clearwanted` \[NOT SU\]
    - `!vehicle <name>`
    - `!bigpp <playername>`
    - `!bigppall`   \[SU\]
    - `!vehiclegod <on/off>`
    - `!weaponsall`
  - Delete Vehicles from `!lag`
  - Chat Commands for Friends
  - Chat Commands Everyone
- Kill all PEDs
- Vehicles
  - Disable Control from near Vehicles
  - Modify Vehicle Speeds (-500 - 1000)
  - Reset Modifies
  - Include Self & Friends
  - Overwrite default Speedlimit
- Bounty
  - Set Bounty after Death Value (0 - 10000$)
  - Give Bounty after Death Toggle (Anonymous or Named)
  - Give Bounty (Custom Input, Anonymous or Named)
- Script Events
  - Custom Script Events
    - Enter Custom Script Event with Parameters
    - Send Script Events from a Custom presaved list
  - Send all to Island
  - Send all to Mission
  - CEO all Player
    - Ban
    - Dismiss
    - Terminate
  - Block Passive Mode
  - Unblock Passive Mode
- Send SMSs to Lobby
  - Spam SMS X Times
  - Custom SMS input
  - Send SCIDs & IPs
  - Send SMS from a custom presaved list
- Malicious
  - Karma every Script Event
  - Kick Hosts until You become Host
  - Punish Aliens in Lobby
  - Punish if Russki Char is typed
  - Geo-Block China
  - Kick Session
  - Crash Session (SE)
  - Crash Session
  - Fix loading screen after Crash

### Vehicle Options

- Teleport Own Vehicle to me
- Teleport Own Vehicle to me and drive
- Drive Own Vehicle
- Teleport to Own Vehicle
- Always apply Vehicle Mods
- Vehicle Colors
  - Set Speed in Milliseconds
  - Random Colors
    - Random Primary
    - Random Secondary
    - Random Pearlescent
    - Random Neon Lights
    - Random Smoke
    - Random Xenon
  - Rainbow Colors
    - Rainbow Primary
    - Rainbow Secondary
    - Rainbow Pearlescent
    - Rainbow Neon Lights
    - Rainbow Smoke
    - Rainbow Xenon
  - Synced Random Colors
  - Synced Rainbow Colors
  - Synced Smooth Rainbow
  - 100% Black
  - 100% Black-Toggle
  - Fade Black-Red
- Explosive Beam on Horn
  - Enable Beam on Horn
  - Select Explosion
  - Select Explosion 2
  - Select Scattering
  - Select Min Range
  - Select Max Range
  - Enable Horn for Player
- Set Heli Blades Speed 0-100%
- Boost Vehicle
- License Plate Speedometer (see [note 10](#notes))
- No collision
- Auto Repair Vehicle
- Custom Vehicles
  - Moveable Robot
    - Enable Robot
    - Controllable Blasts
    - Moveable Legs
    - Collision
    - Rocket Propulsion (Visual)
    - Equip Miniguns on hands
    - Drive Robot
    - Self Destruction
  - Custom Vehicles
    - Preview Custom Vehicles
    - Delete Custom Vehicles
    - Spawn a Custom Vehicle from a presaved list
  - Options
    - Spawn in Custom Vehicle
    - Use Own Vehicle for Custom ones
    - Godmode on Custom Vehicles
    - Disable Moveable Robot Tampa Notify

### Animal Model Changer

  - Ground Animals
  - Water Animals
  - Flying Animals
  - Standard Models
  - Safe Model Change
  - Revert back Outfit
  - Fix endless loading Screen

### Weapon Options

- Load Weapons
  - Flamethrower
    - Select Scale
    - Normal
    - Green
  - Shoot Objects
    - Enable Object Shoot
    - Delete Objects
    - Select Objects from a list
  - Delete Gun
  - Kick Gun
  - Give Demi-God for Player
  - Model Gun
    - Standard Model Gun (PEDs)
    - Add Objects and Vehicles to Model Gun
  - Rapid Fire

### PTFX

- New years eve
- Sparkling Ass
- Sparkling Tires
- Smoke Area
- Fire Circle
- Fire Fart
- Fire Ass

### Modder Detection

- Remember every Modder
- Unmark Friends
- Mark all as Modders
- UN-Mark all as Modders
- Modder Detections
  - Max Speed Bypass
  - Illegal Name
  - Modded SCID
  - Modded Net-Events
  - Explosion based blame killing
  - Modded Script Event
  - Profanity Filter Bypass

### Miscellaneous
- Teleport High in Air
- Drive/Walk on the Ocean
- Drive/Walk this Height
- Weird Entity
- Real Time (Clientside)
- Gameplay Clear Area
- Clear Area
- Auto Teleport to Waypoint
- Fake Ban Screen
- 500K Stealth Recovery
- Swap Vehicle Seat
- Stats
  - Reset Orbital-Cannon Cooldown
  - Disable Orbital-Cannon Cooldown
  - Fill Snacks and Armor
  - Set KD(Kills/Deaths)
  - Unlock Fast-Run Ability
  - Casino Heist
    - Teleport to Boards
    - Reset Heist
    - Quickstart Random
    - Quickstart Highest Payout
    - Manual Mode
      - Reset last Approach
      - Silent, BigCon, Aggressive
      - Hard, Difficulty, Approach
      - Money, Gold, Art, Diamond
      - Unlock Points of Interests
      - Unlock Access Points
      - Confirm First Board
      - Crew-Member-Weapon, Payout
      - Crew-Member-Driver, Payout
      - Crew-Member-Hacker, Payout
      - Weapon Variation
      - Vehicle Variation
      - Remove Duggan Heavy Gurds
      - Equip Heavy Armor
      - Scan Card Level
      - Mask Variation
      - Confirm Second Board
  - Player History
    - Store info in each Lobby subcategory
      - Lobby info
        - Shows number of logged Players
        - Hide Lobby from History
      - Players
        - NAME / Copy
        - SCID / Copy
        - IP / Copy
        - PlayerID
        - First Seen
        - Add to Blacklist
        - Add to Remember Modder
        - Copy Outfit
        - Is `<name>` in this lobby?
        - Were they a modder?

### Utility

- Delete Custom Outfits
- Delete Custom Vehicles
- Leave-Session
- Auto Host Kick Yourself Toggle
- Delete Entity From Aim
- Get input Hash key
- Notify & Print String from File
- Print Info from Entity @Aim to File
- Console (requires lua debug console)
  - Log Console output to File
  - Print 2T1Script log to console
  - Print Chat log to console
  - Print joining Players to console
  - Print leaving Players to console
- Logs
  - Log Modder Flags
  - Log Chat
  - Log Players
  - Log Console output
  - Enable 2T1Script logs
  - Cleanup
    - Clear All 2T1Script logs
    - Clear 2Take1Menu.log
    - Clear 2Take1Prep.log
    - Clear net_events.log
    - Clear notification.log
    - Clear player.log
    - Clear script_event.log
    - Clear All Menu Logs

### Options

- Hotkey Settings
  - Enable Hotkeys
  - Reload 2Take1Hotkeys.ini
  - Hotkey Notifications
  - Print active Hotkeys
  - Overwrite / Update File - `Hotkeys.ini`
- Menu-Wide-Hotkeys
  - Menu-Wide Hotkey Notifications
  - Exclude Navigation Keys
  - Exclude NoClip Keys
  - Exclude EditorRotation Keys
  - Exclude Keys from File
  - Reload `2Take1Exclude.ini`
- Exclude Friends from Harmful Lobby Events
- Attached Entitys No Collision
- Continuously Assassin Peds
- Spawn PED Assassins Immortal
- Disable Player-History
- 2Take1Script Parent
- Save Configuration

## Customize the Script

In order to customize the script, you have to edit the `2Take1Script_Revive\2Take1ScriptEXT.lua` file.

Although any text editor will do the work, I'd recommend a specialized code editor, such as **Notepad++**, **Visual Studio Code**, **Atom** or **Sublime Text**.

If you add something to a variable, set it to the last entry.

Here's an example:

```lua
-- This is RIGHT
local array = {
    {"Entry X", 10},
    {"Entry Y", 40},
    {"New Entry", -1},
}

-- This is WRONG
local array = {
    {"Entry X", 10},
    {"New Entry", -1},
    {"Entry Y", 40},
}
```

### Custom Script Events

Edit the `_2t1s_se_custom` global variable.

```lua
_2t1s_se_custom = {
    {"Custom Script Event 1", {
        {0xffffffff, {0, 0, 0}},
        {0xffffffff, {0, 0, 0}},
        {0xffffffff, {}},
    } },
    {"Custom Script Event 2", {
        {0xaaaaaaaa, {1, -1}},
        {0xffffffff, {0, 0, 0}},
    } },
}
```

### Attacker / Assassin PEDs

Edit the `_2t1s_ped_assassins` global variable. If you dont provide a weapon hash, the peds weapon will be a Combat MG Mk II

```lua
_2t1s_ped_assassins = {
--  {"Attacker Name", ped_Hash, ped_Type, weapon_Hash(optional)},
    {"Cop", 0x5E3DA4A4, 6, 0x1D073A89},
    {"FIB", 0x5CDEF405, 6, 0x2BE6766B},
    {"Juggernaut", 0x90EF5134, 4, 0x42BF8A85},
    {"Bigfoot", 0x61D4C771, 28},
}
```

### Punish Money Beggers

Edit the `_2t1s_begger_texts` global variable.

```lua
_2t1s_begger_texts = {
--  "Beg String 1", "Beg String 2, "Beg String 3", "...",
    "money please", "gib mal money hier", "any money dropper", "money dropper anyone?"
}
```

### License Plate Speedometer

Edit the `_2t1s_speedometer_units` global variable.

2Take1Script will convert from **meters per second** to the desired unit. Because of this, you need the **multiply factor** that will be applied in the conversion.

Don't forget to leave a blank space before the short name, otherwise the speed won't be displayed properly.

```lua
_2t1s_speedometer_units = {
--  {" Short Unit", mply_Factor, "Long Unit"},
    {" MPS", 1, "Meter per Second"},
    {" MPH", 2.23694, "Miles per Hour"},
    {" KMH", 3.6, "Kilometers per Hour"},
}
```

- The first unit, MPS, is the default unit, so it uses a multiplier of **1**.
- The third unit, KPH, equals **3.6** times the MPS unit (because 1 kph = 3.6 mps).

### Block Custom Areas

Edit the `_2t1s_block_custom` global variable.

The last line of each custom location will add a **Teleporting Position**.

Instead of setting a fixed position, you can place the objects at a random generated position.  
To do this, instead of typing the exact coordinates as shown above, use the following format:  
`{nil, X1, X2, Y1, Y2, Z1, Z2}`

- `nil` defines that the coordinates will be randomly generated within a prism, whose vertices will be specified next.
- `X1` and `X2` define the range of coordinates for the X axis.
- `Y1` and `Y2` define the range of coordinates for the Y axis.
- `Z1` and `Z2` define the range of coordinates for the Z axis.

And always remember, **the first value has to be the smaller one**.

```lua
_2t1s_block_custom = {
--  {"Example", {
--      {hash, {pos X, Y, Z}, {rot X, Y, Z}, bool_Freeze, bool_Invisible},
--      {false, {teleport_Pos X, Y, Z}, float_Heading},
--      }, },
    {"Block Orbital Room", {
        {3291218330, {335.9567565918, 4834.3325195312, -58.686454772949}, {0, 0, 35}, true, true},
        {3291218330, {326.33291625977, 4827.6704101562, -60.25874710083}, {0, -90, 0}, true, true},
        {false, {342.8, 4838.2, -57}, 121.2},
        }, },
    {"Trees Main LSC", {
        {3015194288, {nil, -415, -350, -165, -97, 36, 45}, {0, 0, 0}, true, false},
        {3015194288, {nil, -415, -350, -165, -97, 36, 45}, {0, 0, 0}, true, false},
        {3015194288, {nil, -415, -350, -165, -97, 36, 45}, {0, 0, 0}, true, false},
        {3015194288, {nil, -415, -350, -165, -97, 36, 45}, {0, 0, 0}, true, false},
        {3015194288, {nil, -415, -350, -165, -97, 36, 45}, {0, 0, 0}, true, false},
        {false, {-370.4, -104.72, 47}, -110.83449554443},
        }, },
}
```

### Custom Attachments

Edit the `_2t1s_custom_attachments` global variable.

Each attachment can be made of many entities; you only have to add more entity identifiers.

```lua
_2t1s_custom_attachments = {
--    {"Name", {
--      {hash, bone_ID, {pos X, Y, Z}, {rot X, Y, Z}, bool_Invisible},
--      }, },
    {"DEMI-GOD - Light", {
        {148511758, 0, {0, 0, 0}, {0, 0, 0}, true},
        }, },
    {"DEMI-GOD - Heavy", {
        {148511758, 0, {0, 0, 0}, {0, 0, 0}, true},
        {3291218330, 0, {0, 0, -3.5}, {0, 90, 0}, true},
        {3291218330, 0, {0, 0, 0}, {0, 90, 0}, true},
        {3291218330, 0, {0, 0, 3.5}, {0, 90, 0}, true},
        }, },
    {"Cat Cap", {
        {0x573201B8, 119, {0, -0.075, 0.3}, {0, 0, 0}},
        }, },
}
```

The third example, "Cat Cap", uses a **ped hash**.

### New Custom Vehicles

Edit the `_2t1s_custom_vehicles` global variable.

This is the most complicated part of the Lua, but let's take it step by step.

1. The first line contains all **vehicle/object hashes** you want to use for the custom vehicle.
2. The next lines will define how each vehicle/object will be placed in the custom vehicle. You have to repeat this line for every hash you defined above. Keep in mind that the first of the hashes will define the **starting vehicle**.

- `hash`  
  This is the hash to which the next parameters will be applied.
- `{pos X, Y, Z}`  
  Set the offset of the entity.
- `{rot X, Y, Z}`  
  Set the rotation of the entity.
- `{primary_Color, secondary_Color, pearlescent, wheel, window}`  
  If the entity is a vehicle, set the primary/secondary/pearlescent/wheel color (all HEX RGB) and the window tint (0 to 3).
- `bool_Invisible`  
  Set this to `true` to render the entity invisible.
- `int_SpawnHeight`  
  If you have a plane as a starting vehicle, this value will let you spawn it at a certain amount of meters above the current location.
- `int_BoneIndex`  
  Set a boneindex if you want to attach something, for example, to the wheels.
- `int_AttachToEntity`  
  By default, everything will be attached to the first (starting) vehicle. To change that, just set it to the line number defining the vehicle where it should be attached.
- `ped_Hash`  
  To get the engine of a helicopter/plane running, you can set here a ped hash. The ped will be spawned into the vehicle, and the doors will be locked after it.
- `bool_NoCollision`  
  Set it to `true` to disable the collision for this entity.
- `int_Offset`  
  Defines how many meters away the entity should be spawned in front of you (especially for the preview).
- `int_OffsetZPreview`  
  Defines the height of the vehicle during the preview.
- `int_Alpha`  
  Some vehicles will glitch put if you render them invisible. Instead, set the Alpha to `0`.

The position/rotation *should* always be `nil` for the starting vehicle.

Setting some value to `nil` will set the default setting for it.  
For example, the color for each vehicle will be randomly selected.

Setting the starting vehicle's hash to `0` will check if you're in a vehicle and if the "Use own Vehicle" option is enabled.  
If that's the case, your current vehicle will become the "base", on which the rest of the entities will be attached.

```lua
_2t1s_custom_vehicles = {
--  {"Name", {
--      {hash1, hash2, hash3, ...}
--      {hash, {pos X, Y, Z}, {rot X, Y, Z}, {primary_Color, secondary_Color, pearlescent, wheel, window}, bool_Invisible, int_SpawnHeight, int_BoneIndex, int_AttachToEntity, ped_Hash, bool_NoCollision, int_Offset, int_OffsetZPreview, int_Alpha},
--      }, },
    {"WarMachine", {
        {0x9dae1398, 1030400667, 0x2F03547B, 2971578861, 3871829598, 3229200997, 0x187D938D, 782665360},
        {0x9dae1398, nil, nil, {0, 0, 0, 0, 1}, nil, nil, nil, nil, nil, nil, 15},
        {1030400667, {0, -4, 0}, nil, {0, 0, 0, 0, 1}},
        {0x2F03547B, {0, -8, 4}, {-90, 0, 0}, {0, 0, 0, 0, 1}, true, nil, nil, nil, 0x97F5FE8D, true},
        {2971578861, {-0.3, -0.6, 9.8}, {-90, 0, 0}, nil, nil, nil, 16, 3},
        }, },
    {"Attach Ramp", {
        {3233397978},
        {0},
        {3233397978, {0, 4.5, 0.25}, {0, 0, 180}},
        }, },
}
```

### Vehicle Lag Area

Edit the `_2t1s_vehicle_lag_area` global variable.

```lua
_2t1s_vehicle_lag_area = {
--  {"Name", Hash},
    {"Cargoplanes", 0x15F27762},
    {"Volatols", 0x1AAD0DED},
}
```

### SMS List

Edit the `_2t1s_sms_texts` global variable.

```lua
_2t1s_sms_texts = {
--  "Message 1", "Message 2", "Message 3", "..."
    "Fucking bitch", "REKT", "NOOB", "GET ON MY LEVEL", "Send Nudes", "UR MOM GAY"
}
```

### Load Weapons

Edit the `_2t1s_weapons` global variable.

```lua
_2t1s_weapons = {
--  {weapon_Hash, attachment1_Hash, attachment2_Hash, attachment3_Hash, ...},
    {0x1B06D571, 0xD7391086},
    {0x22D8FE39, 0x249A17D5, 0x359B7AAE, 0xC304849A, 0x9B76C72C},
    {0xCB96392F, 0xEFBF25, 0x420FD713, 0x27077CCB},
}
```

## Known Issues

- After disabling **2Take1Script-Parent**, you have to reload the script.
- Loading the script after using `Reset State` may result in the script activating features on it own, this is a lua api bug and cannot be fixed by me. Reinjecting the menu will temporarly fix it.
- Too many **Custom Vehicles / PEDs / Objects** may cause issues! Just delete them after use.
- Some features won't work properly if the distance between you and the target is too high.
- When the script gets autoloaded (for example, with an `autoexec.lua`), the **Event Listeners** (Chat features, etc) might not work.
- Teleport to Waypoint will teleport you near a street.
- Enabling Vehicle Colors might wont apply, press the Feature a few times.
- Rapid Fire doesnt work with the guided rocket launcher.

## Common Questions

> How do I add stuff?

- See [**Customize the Script**](#customize-the-script)

> How do I enter a Custom Vehicle?

- Enable **Spawn in Vehicle** under **Settings**.

> Does it work with other scripts?

- It should work - it has been tested with a few other scripts. But i dont officially support co-loads.

> Does it work after a GTA Update?

- Chances are very high for all **Script Event** features to break; everything else *should* be fine.

> Does it work after a 2T1 Update?

- Yes, under normal circumstances.

> How do I reset the script config?

- Delete the  `2Take1Script.ini` file in the  `2Take1Script_Revive\Config` folder.

> My game crashed when i load the script?

- Delete the  `2Take1Script.ini` file in the  `2Take1Script_Revive\Config` folder.

> I dont see the Script in the menu?

- Press "Refresh Scripts"

> The kick/Crash from the script did not work on a player?

- The Kick and Crash mostly only works on normal Players. Modder with a good Menu will most likely block it.

> I downloaded the new version, but i dont see the new features?

- Clear the cache of the Browser and make sure you deleted every old file.

> I dont see the Online-Player Features?

- They are not in Local -\> Script Features located. Go to the Online Tab and select a Player. Under Script Features you will see the Features.


## Changelog

see [**releases**](https://github.com/DemonKiya/2Take1Script-Revive/releases/)
