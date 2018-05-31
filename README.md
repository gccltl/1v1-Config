# GCC'S 1v1 Matchmaking (MM) Config.

## How-To

 **1. Create a file '(name).cfg' in /home/user/.local/share/Steam/steamapps/common/Counter-Strike Global Offensive/csgo/cfg**
 
 **2. Execute a command in game: exec (name).cfg**


```
// BY GCC
// steam64 - 76561198176712105
// http://steamcommunity.com/profiles/76561198176712105
say "Match Is Starting"
sv_cheats 1 // ON 
mp_teamname_1 Team A
mp_teamname_2 Team B
// --
mp_teamflag_1 lt
mp_teamflag_2 ru
mp_teamlogo_1 cat
mp_teamlogo_2 dog
bot_kick 
// -----------------------------------------------------------------------
mp_maxrounds "15"
sv_alltalk "1"
sv_full_alltalk "1"
mp_ct_default_primary "weapon_ak47"
mp_ct_default_secondary "weapon_p250"
mp_free_armor 100
mp_respawn_on_death_ct 0 //CHANGE TO 1 RESULTS AUTO RESPAWNS
mp_respawn_on_death_t 0 //CHANGE TO 1 RESULTS AUTO RESPAWNS
mp_t_default_primary "weapon_ak47"
mp_t_default_secondary "weapon_p250"
mp_freezetime 1.5
mp_round_restart_delay 0.5
mp_roundtime 45
bot_quota 0

// ----
mp_warmup_end
mp_restartgame 1
// ----
hostname "1v1 - GCC"
// ----

// AUTO-HOPING (BHOP) START. DO NOT TOUCH THIS.
// IF YOU WANT TO DISABLE THIS JUST COMMENT "//" OR DELETE THIS LINE
// ------------------------------------------------------------------------------
sv_airaccelerate 333; sv_staminalandcost 0; sv_staminajumpcost 0; sv_staminamax 80; sv_staminarecoveryrate 60﻿
// ------------------------------------------------------------------------------
// AUTO-HOPING (BHOP) END. DO NOT TOUCH THIS.
// IF YOU WANT TO DISABLE THIS JUST COMMENT "//" OR DELETE THIS LINE

sv_cheats 0 // OFF
// -----------------------------------------------------------------------
say "GO! GO! GO! 


// BY GCC
// steam64 - 76561198176712105
// http://steamcommunity.com/profiles/76561198176712105
``` 
