
# General Notes
* All times are displayed in 24-hour format
* Day and month are always two digits (zero-filled)

# Still Need to Determine
* Any idea what the <#> is about after a player's name? Slot number? Do bots get this number as well?
* Are spectators marked as <Unassigned> or something else?
* Is starting money put in log at start?
* IS the host name in log at start?
* Money bonuses at end of round (team/player/amount)


# Player Actions
## Player Joins Server
```
L 01/10/2015 - 11:08:47: "yellowtape #lanerino<2><STEAM_1:1:26331892><>" STEAM USERID validated
L 01/10/2015 - 11:08:51: "yellowtape #lanerino<2><STEAM_1:1:26331892><>" entered the game
L 01/10/2015 - 11:08:53: "yellowtape #lanerino<2><STEAM_1:1:26331892><Unassigned>" triggered "clantag" (value "")
```
## Player Joins Team
```
L 01/10/2015 - 11:09:05: "xenomorph^<5><STEAM_1:0:10583141>" switched from team <Unassigned> to <TERRORIST>
L 01/10/2015 - 11:09:05: "xenomorph^<5><STEAM_1:0:10583141><TERRORIST>" triggered "clantag" (value "rekttt")
```

# Player Changes Name
```
L 02/04/2015 - 17:35:17: "[LL] BEan<2><STEAM_1:0:3804719><TERRORIST>" say "NAMECHANGE"
L 02/04/2015 - 17:35:31: "[LL] BEan<2><STEAM_1:0:3804719><TERRORIST>" changed name to "BEan"
L 02/04/2015 - 17:35:50: "BEan<2><STEAM_1:0:3804719><TERRORIST>" changed name to "[LL] BEan"
```

# Player Switches to spectator / lobby
*STILL NEEDED*

# Player Disconnects
*STILL NEEDED*

# Game Conditions
## Round Starts
```
L 01/10/2015 - 11:14:05: World triggered "Round_Start"
```

## Round Ends
```
L 01/10/2015 - 11:27:18: Team "TERRORIST" triggered "SFUI_Notice_Terrorists_Win" (CT "1") (T "8")
L 01/10/2015 - 11:27:18: Team "CT" scored "1" with "5" players
L 01/10/2015 - 11:27:18: Team "TERRORIST" scored "8" with "5" players
L 01/10/2015 - 11:27:18: World triggered "Round_End"
```


## Overtime Start
*STILL NEEDED*
```
L 02/04/2015 - 17:46:59: Team "TERRORIST" triggered "SFUI_Notice_Terrorists_Win" (CT "4") (T "4")
L 02/04/2015 - 17:46:59: Team "CT" scored "4" with "5" players
L 02/04/2015 - 17:46:59: Team "TERRORIST" scored "4" with "5" players
L 02/04/2015 - 17:46:59: World triggered "Round_End"
L 02/04/2015 - 17:47:13: "[LL] BEan<2><STEAM_1:0:3804719><CT>" say "OVERTIME"
L 02/04/2015 - 17:47:15: "[LL] BEan<2><STEAM_1:0:3804719><CT>" say "OVERTIME"
L 02/04/2015 - 17:47:18: "[LL] BEan<2><STEAM_1:0:3804719><CT>" say "OVERTIME"
```

## Half Time Start
*STILL NEEDED*

Bean notes: There is no obvious "world triggered half time" but its apparent here. Just need to add C to T and see if it equals 15 or half of total rounds.
```
L 01/10/2015 - 11:35:21: Team "TERRORIST" triggered "SFUI_Notice_Terrorists_Win" (CT "1") (T "14")
L 01/10/2015 - 11:35:21: Team "CT" scored "1" with "5" players
L 01/10/2015 - 11:35:21: Team "TERRORIST" scored "14" with "5" players
L 01/10/2015 - 11:35:21: World triggered "Round_End"
L 01/10/2015 - 11:35:23: "nefff :^) #lanneroni<9><STEAM_1:1:95435649><TERRORIST>" say "gh"
L 01/10/2015 - 11:35:25: "xenomorph^<5><STEAM_1:0:10583141><TERRORIST>" say "gh"
L 01/10/2015 - 11:35:25: "t1lt@LAN<6><STEAM_1:0:65344870><TERRORIST>" say "gh"
L 01/10/2015 - 11:35:25: "demo25<11><STEAM_1:0:17919002><TERRORIST>" say "gh"
L 01/10/2015 - 11:35:26: "yellowtape #lanerino<2><STEAM_1:1:26331892><CT>" say "gh"
L 01/10/2015 - 11:35:27: "Snizzy<8><STEAM_1:1:39423136><CT>" say "GH :d"
L 01/10/2015 - 11:35:51: "yellowtape #lanerino<2><STEAM_1:1:26331892>" switched from team <CT> to <TERRORIST>
L 01/10/2015 - 11:35:51: "plumB<3><STEAM_1:1:10308681>" switched from team <CT> to <TERRORIST>
L 01/10/2015 - 11:35:51: "Amish Jew #LL<4><STEAM_1:1:22788791>" switched from team <CT> to <TERRORIST>
L 01/10/2015 - 11:35:51: "xenomorph^<5><STEAM_1:0:10583141>" switched from team <TERRORIST> to <CT>
L 01/10/2015 - 11:35:51: "t1lt@LAN<6><STEAM_1:0:65344870>" switched from team <TERRORIST> to <CT>
L 01/10/2015 - 11:35:51: "Lawly<7><STEAM_1:1:46857293>" switched from team <TERRORIST> to <CT>
L 01/10/2015 - 11:35:51: "Snizzy<8><STEAM_1:1:39423136>" switched from team <CT> to <TERRORIST>
L 01/10/2015 - 11:35:51: "nefff :^) #lanneroni<9><STEAM_1:1:95435649>" switched from team <TERRORIST> to <CT>
L 01/10/2015 - 11:35:51: "rub_b3r_ducky<10><STEAM_1:1:30414055>" switched from team <CT> to <TERRORIST>
L 01/10/2015 - 11:35:51: "demo25<11><STEAM_1:0:17919002>" switched from team <TERRORIST> to <CT>
```


## Half Time End
*STILL NEEDED*

# Game Actions

## Player Buys Item
```
L 01/10/2015 - 11:26:23: "demo25<11><STEAM_1:0:17919002><TERRORIST>" purchased "vesthelm"
L 01/10/2015 - 11:26:23: "demo25<11><STEAM_1:0:17919002><TERRORIST>" purchased "ak47"
L 01/10/2015 - 11:26:23: "demo25<11><STEAM_1:0:17919002><TERRORIST>" purchased "smokegrenade"
```

## Player Kills
```
L 01/10/2015 - 11:36:25: "xenomorph^<5><STEAM_1:0:10583141><CT>" [-402 2019 -86] killed "Amish Jew #LL<4><STEAM_1:1:22788791><TERRORIST>" [-40 1974 -22] with "hkp2000" (headshot)
```

## Player Attack and Kill
```
L 02/04/2015 - 17:46:32: "[LL] BEan<2><STEAM_1:0:3804719><CT>" [1176 2682 96] attacked "Kevin<11><BOT><CT>" [1046 2689 96] with "mag7" (damage "8") (damage_armor "0") (health "0") (armor "0") (hitgroup "chest")
L 02/04/2015 - 17:46:32: "[LL] BEan<2><STEAM_1:0:3804719><CT>" [1176 2682 96] killed "Kevin<11><BOT><CT>" [1046 2689 160] with "mag7"
```

## Picked Up Bomb
```
L 01/10/2015 - 11:26:33: "nefff :^) #lanneroni<9><STEAM_1:1:95435649><TERRORIST>" triggered "Got_The_Bomb"
Dropped the bomb
L 01/10/2015 - 11:27:00: "nefff :^) #lanneroni<9><STEAM_1:1:95435649><TERRORIST>" triggered "Dropped_The_Bomb"
Planted the bomb
L 01/10/2015 - 11:16:08: "xenomorph^<5><STEAM_1:0:10583141><TERRORIST>" triggered "Planted_The_Bomb"
Defused the bomb
L 01/10/2015 - 11:26:44: "Vash<9><STEAM_1:0:5883693><CT>" triggered "Defused_The_Bomb"
L 01/10/2015 - 11:26:44: Team "CT" triggered "SFUI_Notice_Bomb_Defused" (CT "6") (T "0")
```

# Possible Win Scenarios
```
L 01/10/2015 - 11:19:24: Team "CT" triggered "SFUI_Notice_CTs_Win" (CT "1") (T "0")
L 01/10/2015 - 11:26:44: Team "CT" triggered "SFUI_Notice_Bomb_Defused" (CT "6") (T "0")
L 01/10/2015 - 11:28:54: Team "CT" triggered "SFUI_Notice_Target_Saved" (CT "7") (T "0")
L 01/10/2015 - 11:35:18: Team "TERRORIST" triggered "SFUI_Notice_Terrorists_Win" (CT "10") (T "1")
L 12/20/2014 - 16:32:33: Team "TERRORIST" triggered "SFUI_Notice_Target_Bombed" (CT "6") (T "10")
```
