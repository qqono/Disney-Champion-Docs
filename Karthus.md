# Karthus

## Q

Lane and Jungle Clear settings can be configured to users personal preference in the advanced panel.
- Essential settings will always cast Q for jungle clear
	- Can be changed to turbo only/fast clear only
- Last hit:
  	- will be used to secure minions you would otherwise miss
  	  

- Karthus will use Q on jungle camps through fog of war


### Advanced Options:

By default, essential settings will work well. If you are interested in configuring Karthus, use the advanced menu to make specific changes.
Available options include:
```
- Fast Prediction: Smart/Always/Off
- Skip Path Analysis: Special check to improve accuracy, disable for hyper-fast prediction at the cost of accuracy

- Heuristic Extrapolation: Adds an extra layer of spell prediction, due to the slow cast time of Karthus Q. Tries to improve accuracy by predicting enemy actions.
	Due to the natural unreliability of this metric, its impact can be tuned using a slider. By default, the value is set to a safe/moderate level.
		- 0.0f = disabled
		- 1.0f = maximum

- Packet Casting: allows you to cast faster than normal casting, only relevant on spells that can be spammed
	- Packet Type: Preconfigured values set by Yasmine, based on Ping and other technical metrics. Type 1 should be used by most players.
			- Only touch if you know what you are doing.
```
---

## W

W is automatically triggered in certain conditions, or by request. Each trigger has several configuration options. If you think W is being cast incorrectly, edit in advanced menu.

Triggers:
- Trap Events (Uses same triggers as Caitlyn traps, configurable in menu)
	- Dash
	- Pixel
	- Channel
	- Immobile
	- Cast Animation
	- Hitchance %
	- Other miscellaneous events

- Anti-Gap:
	- Will be cast for self-peel if any enemy is too close

- Combo/PvP
 	 - can be configured in advanced menu
  
---

## E

E can be configured however you prefer for lane and jungle clear. Essential settings cast E in eco mode for jungle.

- PvE:
	  - Lane Clear: Turbo only
	  - Jungle Clear: Always/Automatic, with extra logic for toggling
			- advanced logic is configurable for user preference

- PvP (combo/harass):
	  - Works as expected, essential should work well, but has a few configuration options if you need

---

## R

R will never be cast automatically for you, unless you are in passive, in which case it will cast at the last possible second, after dealing as much DPS as possible.
Drawings, warnings and indicators are configurable in the Drawings section.

---

## Auto Attacks:

- Auto attacks can be disabled based on champion level, override with aggro mode
- Logic for pulling and auto-kiting camps during jungle clear
