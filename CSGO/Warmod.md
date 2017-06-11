# Warmod Logs

Warmod outputs nice JSON lines in the log

## Round Starts
`{"timestamp": "2015-04-18 17:09:01", "event": "round_start", "freezeTime": 12}`

## Round Freeze Ends
`{"timestamp": "2015-04-18 17:09:13", "event": "round_freeze_end"}`
	
## Round Ends
`{"timestamp": "2015-04-18 17:09:13", "event": "round_freeze_end"}`
	
## Score Update
`{"timestamp": "2015-04-18 17:08:56", "event": "score_update", "teams": [{"name": "reds", "team": 2, "score": 1}, {"name": "blues", "team": 3, "score": 0}]}`

## Player Connects
```
{"timestamp": "2015-04-18 19:08:25", "event": "player_connect", "player": {"name": "[LL] D34DP00|_", "userId": 10, "uniqueId": "STEAM_1:0:1365877", "team": 0}, "address": "172.30.31.68", "country": ""}
```
	
## PLAYER SWITCH TEAM
`{"timestamp": "2015-04-18 19:08:31", "event": "player_team", "player": {"name": "[LL] D34DP00|_", "userId": 10, "uniqueId": "STEAM_1:0:1365877", "team": 0}, "oldTeam": 0, "newTeam": 2}`
	
## PLAYER DIES
```
{"timestamp": "2015-04-18 17:11:43", "event": "player_death", "attacker": {"name": "[LL] Dudsmack", "userId": 3, "uniqueId": "STEAM_1:1:3648970", "team": 3, "origin": [549.11, 1262.11, 10.03], "velocity": [-91.78, 232.54, 0.00], "view": [7.07, 116.95, 0.00], "health": 100, "armor": 100, "helmet": 1}, "assister": {"name": "Soulkiss", "userId": 5, "uniqueId": "STEAM_1:1:7767353", "team": 3, "origin": [615.46, 1553.65, -5.96], "velocity": [105.89, -212.92, 0.00], "view": [6.24, -96.00, 0.00], "health": 29, "armor": 0, "helmet": 0}, "victim": {"name": "[LL] D34DP00|_", "userId": 2, "uniqueId": "STEAM_1:0:1365877", "team": 2, "origin": [514.00, 1306.65, -7.96], "velocity": [0.00, -3.15, 0.00], "view": [6.83, 59.70, 0.00], "health": 0, "armor": 0, "helmet": 0}, "weapon": "knife_default_ct", "headshot": 0}
```
	
## PLAYER DISCONNECTS
```
{"timestamp": "2015-04-18 19:08:01", "event": "player_disconnect", "player": {"name": "[LL] D34DP00|_", "userId": 9, "uniqueId": "STEAM_1:0:1365877", "team": 2}, "reason": "Disconnect"}
```
	
## PLAYER TIMEOUT
```
{"timestamp": "2015-04-18 19:06:33", "event": "player_disconnect", "player": {"name": "[LL] D34DP00|_", "userId": 5, "uniqueId": "STEAM_1:0:1365877", "team": 2}, "reason": "[LL] D34DP00|_ timed out"}
```
	
## PLAYER NAME CHANGE
```
{"timestamp": "2015-04-18 19:09:26", "event": "player_name", "player": {"name": "[LL] D34DP00|_", "userId": 10, "uniqueId": "STEAM_1:0:1365877", "team": 2}, "newName": "[LL] Buddha *Spray N Pray*"}
```
