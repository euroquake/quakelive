# 🔱 euroQuake Quake Live Factories
🔽 Go to [Instagib Capture the Flag](https://github.com/euroquake/quakelive/tree/main/factories#instagib-capture-the-flag)  
🔽 Go to [Instagib FreezeTag](https://github.com/euroquake/quakelive/tree/main/factories#instagib-freezeTag)  
🔽 Go to [Instagib Domination](https://github.com/euroquake/quakelive/tree/main/factories#instagib-domination)  

### Instagib Capture The Flag
#### Raw Factory
```
"capturelimit": "8",
"dmflags": "28",
"g_allowKill": "1",
"g_dropCmds": "1",
"g_instaGib": "1",
"g_loadout": "0",
"g_overtime": "0",
"g_startingWeapons": "65",
"g_suddenDeathRespawn": "1",
"g_timeoutCount": "3",
"g_timeoutLen": "300",
"sv_warmupReadyPercentage": "1",
"teamsize": "4",
"timelimit": "20"
```
#### Factory Info
| Entry Command | QL Value | eQ Value | Description |
| :--- | :---: | :---: | :--- |
| `capturelimit` | 8 | 8 | Amount of captures needed win the match |
| `dmflags` | 0 | 28 | Server side flags to control splash/falling-damage |
| | | | 🔽 Go to [dmflags](https://github.com/euroquake/quakelive/tree/main/factories#dmflags) info |
| `g_allowKill` | 0 | 1 | Toggle usage of the ‘kill’ command in a server |
| `g_dropCmds` | 7 | 1 | Enables the dropping of items |
| | | | 🔽 Go to [g_dropCmds](https://github.com/euroquake/quakelive/tree/main/factories#g_dropcmds) info |
| `g_instaGib` | 0 | 1 | Toggle instagib railguns-only |
| `g_loadout` | 1 | 0 | Toggle loadout selection before spawning |
| `g_overtime` | 120 | 0 | Duration of the overtime periods in seconds |
| `g_startingWeapons` | 3 | 65 | Set the starting weapons |
| | | | 🔽 Go to [g_startingWeapons](https://github.com/euroquake/quakelive/tree/main/factories#g_startingweapons) info |
| `g_suddenDeathRespawn` | 0 | 1 | Toggle respawn delay when matches enter sudden death |
| `g_timeoutCount` | 3 | 3 | Number of timeouts per team per match |
| `g_timeoutLen` | 120 | 300 | Duration of timeouts in seconds |
| `sv_warmupReadyPercentage` | 0.51 | 1 | Percentile of players ready before auto-start |
| `teamsize` | 0 | 4 | Maximum team size |
| `timelimit` | 0 | 20 | Time limit in minutes |

🔼 Go to [top](https://github.com/euroquake/quakelive/tree/main/factories#top)  

### Instagib FreezeTag
#### Raw Factory
```
"dmflags": "28",
"g_allowKill": "1",
"g_dropCmds": "0",
"g_freezeEnvironmentalRespawnDelay": "3000",
"g_freezeProtectedSpawnTime": "2000",
"g_freezeRoundDelay": "0",
"g_freezeThawThroughSurface": "0",
"g_freezeThawTick": "1",
"g_instaGib": "1",
"g_loadout": "0",
"g_overtime": "120",
"g_railjump": "670",
"g_startingWeapons": "65",
"g_suddenDeathRespawn": "1",
"g_timeoutCount": "3",
"g_timeoutLen": "300",
"roundlimit": "20",
"roundtimelimit": "0",
"sv_warmupReadyPercentage": "1",
"teamsize": "4",
"timelimit": "20"
```
#### Factory Info
| Entry Command | QL Value | eQ Value | Description |
| :--- | :---: | :---: | :--- |
| `dmflags` | 0 | 28 | Server side flags to control splash/falling-damage |
| | | | 🔽 Go to [dmflags](https://github.com/euroquake/quakelive/tree/main/factories#dmflags) info |
| `g_allowKill` | 0 | 1 | Toggle usage of the ‘kill’ command in a server |
| `g_dropCmds` | 7 | 0 | Enables the dropping of items |
| | | | 🔽 Go to [g_dropCmds](https://github.com/euroquake/quakelive/tree/main/factories#g_dropcmds) info |
| `g_freezeEnvironmentalRespawnDelay` | 0 | 3000 | Respaw time after being frozen by lava and other hazards in milliseconds |
| `g_freezeProtectedSpawnTime` | 0 | 2000 | Spawn protection in milliseconds |
| `g_freezeRoundDelay` | 4000 | 0 | Delay between rounds in milliseconds |
| `g_freezeThawThroughSurface` | 1 | 0 | Enables thawing through surfaces |
| `g_freezeThawTick` | 1 | 1| Enables thawing sound |
| `g_instaGib` | 0 | 1 | Toggle instagib railguns-only |
| `g_loadout` | 1 | 0 | Toggle loadout selection before spawning |
| `g_overtime` | 120 | 0 | Duration of the overtime periods in seconds |
| `g_railjump` | 0 | 670 | Value will enable railjump (value as ups power) |
| `g_startingWeapons` | 3 | 65 | Set the starting weapons |
| | | | 🔽 Go to [g_startingWeapons](https://github.com/euroquake/quakelive/tree/main/factories#g_startingweapons) info |
| `g_suddenDeathRespawn` | 0 | 1 | Toggle respawn delay when matches enter sudden death |
| `g_timeoutCount` | 3 | 3 | Number of timeouts per team per match |
| `g_timeoutLen` | 120 | 300 | Duration timeouts in seconds |
| `roundlimit` | 5 | 20 | Match score round limit |
| `roundtimelimit` | 180 | 0 | Round time limit |
| `sv_warmupReadyPercentage` | 0.51 | 1 | Percentile of players ready before auto-start |
| `teamsize` | 0 | 4 | Maximum team size |
| `timelimit` | 0 | 20 | Time limit in minutes |

🔼 Go to [top](https://github.com/euroquake/quakelive/tree/main/factories#top)  

### Instagib Domination
#### Raw Factory
```
"dmflags": "28",
"g_allowKill": "1",
"g_dropCmds": "0",
"g_instagib": "1",
"g_overtime": "120",
"g_startingWeapons": "65",
"g_suddenDeathRespawn": "1",
"g_timeoutCount": "3",
"g_timeoutLen": "300",
"loadout": "0",
"scorelimit": "150",
"sv_warmupReadyPercentage": "1",
"teamsize": "4",
"timelimit": "20"
```
#### Factory Info
| Entry Command | QL Value | eQ Value | Description |
| :--- | :---: | :---: | :--- |
| `dmflags` | 0 | 28 | Server side flags to control splash/falling-damage |
| | | | 🔽 Go to [dmflags](https://github.com/euroquake/quakelive/tree/main/factories#dmflags) info |
| `g_allowKill` | 0 | 1 | Toggle usage of the ‘kill’ command in a server |
| `g_dropCmds` | 7 | 0 | Enables the dropping of items |
| `g_instaGib` | 0 | 1 | Toggle instagib railguns-only |
| `g_overtime` | 120 | 0 | Duration of the overtime periods in seconds |
| `g_startingWeapons` | 3 | 65 | Set the starting weapons |
| | | | 🔽 Go to [g_startingWeapons](https://github.com/euroquake/quakelive/tree/main/factories#g_startingweapons) info |
| `g_suddenDeathRespawn` | 0 | 1 | Toggle respawn delay when matches enter sudden death |
| `g_timeoutCount` | 3 | 3 | Number of timeouts per team per match |
| `g_timeoutLen` | 120 | 300 | Duration of timeouts in seconds |
| `g_loadout` | 1 | 0 | Toggle loadout selection before spawning |
| `scorelimit` | 10 | 150 | Match score limit |
| `sv_warmupReadyPercentage` | 0.51 | 1 | Percentile of players ready before auto-start |
| `teamsize` | 0 | 4 | Maximum team size |
| `timelimit` | 0 | 20 | Time limit in minutes |

🔼 Go to [top](https://github.com/euroquake/quakelive/tree/main/factories#top)  


### Additional Entry Command Info
#### `dmflags`
Server side flags to control splash/falling-damage.  
Default Value: 0 - Combine by summing them up, 28 is all 3.
* 4 = no self splash-damage on health
* 8 = no self splash-damage on armor
* 16 = no falling damage

#### `g_dropCmds`
Enables the dropping of items.  
Default Value: 7 - Combine by summing them up, 7 is all 3.
* 1 = flags (dropflag)
* 2 = power-ups (droppowerup)
* 4 = weapons (dropweapon)

#### `g_startingWeapons`
Sets the starting weapons.  
Default Value: 3 (Gauntlet + Machinegun) - Combine by summing them up.  
All Weapons = 8191. All Weapons minus Grapple = 7679.
* 1 = Gauntlet
* 2 = Machinegun
* 4 = Shotgun
* 8 = Grenade Luncher
* 16 = Rocket Luncher
* 32 = Lightning Gun
* 64 = Railgun
* 128 = Plasmagun
* 256 = BFG
* 512 = Grappling Hook
* 1024 = Nailgun
* 2048 = Prox Launcher
* 4096 = Chaingun
* 8192 = Map Default Weapons


🔼 Go to [top](https://github.com/euroquake/quakelive/tree/main/factories#top)  
