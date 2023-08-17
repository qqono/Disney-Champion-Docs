# Ezreal V3

## Q

~~Ezreal is designed to be used with Orb Modifiers~~
### SBTW
```
PvP:
Spacebar To Win (SBTW): Enabled by default (essential)

  - Instead of requiring modifier inputs to allow certain casts, complex logic has been used to better understand player and enemy intentions.
  - Combo mode will now be 'Spacebar to Win', allowing users to completely disengage their brains and play how they want, without needing to press more than 1 key!
  - Basically, combo mode has less restrictions and some logic to remove the need for modifier keys.

  - Players who are used to Legacy Ezreal, or prefer to have greater control / more options, can enable this by enabling 'Flexible' Logic Mode under the Advanced panel (see below for indepth explanation).
  - If you are just going to hold spacebar, don't use Advanced.


- Note: Modifier keys still affect farming modes and W logic.
```
___

### Farm Modes

Note that this is affected by Eco/Turbo mode. I recommend setting your spell farm toggle (under orbwalker settings) to Middle Mouse Button for ease of access.

Generally, you should use Eco mode when you would rather Q the enemy instead of the wave. This is useful in the early lane phase. If you leave it on Turbo, you will miss a lot of harass opportunities.

Leave it on Turbo when you want to clear faster or stack your tear (majority of the game after the first back).

**Eco mode:**

Only use spells to secure minions you would otherwise miss.

**Turbo Mode:**

Will use spells to last hit whenever possible.

**Spam mode:**
- In mid/late game, spam mode is automatic.
- Spam mode can be forced at any point, by using Turbo Mode + Fast Clear

---

Orb Modes

**Last hit:**
- Will only target killable minions.
- **Last Hit + Modifier = Fast Last Hit/Q stack.**
- In Turbo, tapping LMB can help you kill minions at max range.
- Holding LMB will "Freeze" by trying to last hit at the last possible moment.

**Clear:**
- Will try to push the wave.
- Clear + Modifier = Fast Clear.
- In eco mode, only auto attacks are used.
- In turbo mode, Q is used whenever possible, based on a set of rules.
- While in turbo, tapping LMB will force Q to be cast immediately.
- Will also prioritize hitting enemy champions over last hits.

**Harass:**
- Harass + Modifier = Fast Harass + Passive stacking.
- Eco: Looks for Q's on champions while farming with auto attacks.
- Turbo: Prefers to auto attack to last hit but will use Q on the wave more often.
- Turbo + LMB:
- Tapping LMB will force Q to be cast at the next killable minion.
- Holding LMB in harass will use Q on every minion, useful for slow pushing while stacking tear or building passive stacks.
___

### Advanced Menu:

By default, essential settings will work well. If you are interested in configuring Karthus, use the advanced menu to make specific changes. Available options include:
```
- Overkill: SMART/Always/Off
- Ignore Target Lock: OFF/On
- Cooldown Spam: ALWAYS/Smart/Off
- Spam Modes: VERY FAST/Fast/Slow/Off
- Logic Modes: SBTW/Flexible/Advanced

- Packet Casting: allows you to cast faster than normal casting, only relevant on spells that can be spammed
	- Packet Type: Preconfigured values set by Yasmine, based on Ping and other technical metrics. Type 1 should be used by most players.
			- Only touch if you know what you are doing.
```
--- 

### Settings for Advanced/Legacy Ezreal:

Enable Legacy Ezreal by enabling the Flexible logic in advanced Q settings.

Legacy Ezreal was designed around Aggressive and Defensive modifiers, giving you MUCH more control over your Q in certain situations. Legacy Ezreal takes more skill to use, providing many solutions to different situations. The player can choose between speed or accuracy, depending on their inputs.

These modifiers apply to ALL orb modes (last hit, harass, clear, and combo). It is recommended that you experiment with the modifiers to see how the script behavior changes.
If you want to shoot out of range and keep your distance, you should use the Defensive Mode. On the other hand, if you have already won and don't mind getting hit by all spells, you should use the Aggressive Mode.
By default, the normal combo mode will be more reserved with Q, holding it longer and waiting for a high hit chance. However, this behavior can be overridden using Aggressive or Defensive mode.
If you feel like the script is holding Q too long or you see a Q opportunity, you can tap LMB to fire Q sooner. This applies to most orb modes.

Default orb mode (unmodified spacebar):
```
- Has restrictions in place to improve accuracy
- May hold Q for longer if the enemy is hard to hit
```

Aggressive Mode (LMB):
```
- Will use Q with fewer restrictions
- Disables evade
- Best used in close combat, while chasing, or during an all-in
```

Defensive Mode (Side mouse 1):
```
Will use Q with fewer restrictions
- Evade is kept on
- Best used while poking/harassing, fighting at max range, or while trying to dodge skillshots without lowering DPS.
```

---

### W

Aggressive/Defensive modifier will "request fast combo", and remove safety checks/restrictions on W.

By default, W is also held longer to ensure accuracy / value.
This can also be overridden by using a modifier key.

___

### E

**E is a highly situational ability. It is your own responsibility to cast E as you see fit.** However, there are several configuration options available.

'Essential' settings will use E as self-peel to avoid gap closers and melee enemies. **Defensive mode will use E with fewer restrictions,** configurable in advanced settings.

Evade is also allowed to use E defensively. The location is chosen based on a "Safest Position" algorithm, which prioritizes safety. The safe position algorithm is constantly being improved, and if you have any issues with it, please report them.

If you wish, this can be set to work only in defensive mode to allow the user even more control over their E usage, but it may result in unwanted deaths. How you use E is strictly up to you and your playstyle. I recommend spending the most time on E settings, so it functions how you prefer.

This is the optimal way to use E. If you want to use E aggressively or forward, you will have to input it manually.

___

### R

Disabled by default, many users prefer to cast R manually or use a "request" keybind. Override is also a good option, but I prefer Request R and casting it manually when I need to.

If you want R to be used in a combo without extra input, you can enable the "automatic" function and configure how you would like it to be used. This will allow the script to cast R without any input, but be warned that it can sometimes cast R at dangerous times. However, there are safety checks you can enable to mitigate this risk.
___

### Quick Tips

Combo = fast spell. 
Combo + mod = instant spell, no checks, shoots out of range. 
Harass = slow spell.
Harass + mod = slow spell, shoots out of range.

In Defensive mode, you want to shoot out of range and keep your distance. In Aggro mode, you want to use it when you have already won and don't mind getting hit by all spells.

Defensive mode also affects anti-gap essential, configurable in advanced settings.

X + mod = fast last hit.

Eco mode does not have a mana restriction, it simply uses the spell less often.

Spam mode is automatic once you reach mid-game + turbo mode, but you can force it from level 1 with turbo + fast clear, which is an orb aggro modifier + V.

___

## Quick Settings Guide
*For new Disney users wondering what settings they need to change*

1. **Q:** Essential (default) settings should be fine. If you like automatic spellcasts you can switch that from Disabled to Essential.
            - If you are interested in learning Legacy Ezreal, and the power of modifier keys, open the advanced menu.
2. **W:** Same as Q^
3. **E:** I recommend opening the "advanced" configuration panel and reading through the options, but switch it back to Essential afterwards.
If you have issues with E, you can configure it to your personal preference, but Essential should work best.
4. **R:** 
  - Choose a hotkey for "request R", or set it to an override.
  - Open the Automatic tab and read through the options, if you want R to be cast automatically in some scenarios, you can set it up here, or set it to "essential", which will try to only cast R automatically at ideal moments.

---

## Playstyle, Builds and Gameplay Tips:

I highly recommend watching Moana's Ezreal gameplay, found in the pinned section of the #highlights channel. 

- Ezreal has an insanely high skill ceiling, even with scripts. You can be successful with Disney Ezreal without knowing how to play Ezreal, but if you one trick it, and take time to learn its strengths and limits, you will be rewarded
- The difference between good and bad Ezreals mainly comes down to how well they use their range and positioning to gain advantages, as well as E usage.
- Gameplay footage by Hanql, a Chinese Super-Server Challenger Ezreal One-Trick can be beneficial to watch, especially regarding certain matchups.
