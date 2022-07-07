# TSC OOB Test

Simple OOB flag set test repo for TSC.

I just made a FPS counter show script cause I'm literal ***caca*** at tsc scripting :')

Usage: **<FL+{FLAG}** or **<FL-{FLAG}**

| Flag | Functionality |
| ---- | ------------- |
|9088| LArrow (NO Joystick)|
|9089| RArrow|
|9090| UArrow|
|9091| DArrow|
|9092| W - Map Shortcut|
|9093| X - Shoot (Editable in DoConfig.exe)|
|9094| Z - Jump (So is this ^^)|
|9095| S - Switch Weapon Slot Right|
|9096| A - Switch Weapon Slot Left|
|9097| Shift (Unusable)|
|9098| F1 - Resume|
|9099| F2 - Reset|
|9100| Q - Inventory|
|9101 + 9102| Unusable|
|9103| ESC - Pause|
|9104| < - Left (Alternative Keys in DoConfig.exe which don't support Joystick|
|9105| > - Down (Alternative Keys in DoConfig.exe which don't support Joystick|
|9106| ? - Right (Alternative Keys in DoConfig.exe which don't support Joystick|
|9107| L - Up? (Alternative Keys in DoConfig.exe which don't support Joystick|
|9108| = (Unused)|
| - Binary Based - | - |
|B752| Invincibility Timer?
|B800| Whimsical Stars Count (Maximum of 3 + requires <EQ+0128)
|8704| Harder Quake (Roughness significantly higher than <QUA)
|=856| Display / Hide FPS Counter
|B922| Add 100 or more to Air Count
|C008| Current Booster Fuel
|C035| Booster Temp Inf Fuel (Infinite Fuel till you touch ground)
|B992| -
|B720| Add Fake EXP to Score counter ("Fake" as in it doesn't actually add EXP)
|B688| Spur EXP Bar Flash
|B848| Extend Health Bar Visually Only
|C104| Nikumaru Time
|C120| Add to Nikumaru or OOB <FL+C104 
|B784| Get Current Health (Can be manipulated or edited)
|B816| Get Max Health (Same as ^^^)
|8800| Unsure? ("First bit in the game-timer" <FLJ adds a 50% chance to jump but don't use more than once if running multiple events or they will no longer be random.)

---

|Flag|Binary Value|
|----|------------|
| B720 | 1
| B721 | 2
| B722 | 4
| B723 | 8
| B724 | 16
| B725 | 32
| B726 | 64
| B727 | 128
| B728 | 256
| B729 | 512
| B730 | 1024

^^^ Unsure if it goes up idk :( I tested till 2048