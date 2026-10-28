# Cosmoteer - Emmy B&B++
Emmy B&B++ is a compatibility and quality of life enhancement for the game [Cosmoteer](https://store.steampowered.com/app/799600/Cosmoteer_Starship_Architect__Commander/). It is designed specifically for the Build & Battle PvP mode and not intended for co-op or other PvP modes, though the mod can be used in other mods with minimal/no impact.

By default, most mods do not add their content to the Build & Battle mode, leaving only the vanilla parts. I wanted to greatly extend the longevity of the mode and allow players to go down different tech combinations every game. As such, Emmy B&B++ is designed to revamp both the vanilla mode and include modded material into the rotation.

This mod is intended for use amongst friends and is not designed to appeal to every person's taste. You are free to modify, add, or disable any mod to Emmy B&B++. If you do edit the files, insure that **all** players in your lobby have your edited files for Emmy B&B++, such as the `mod-parts.rules` file. Though I'll accept requests to look at certain mods, I am **not** taking any requests to add specific mod compatibility to this mod.
## Current Mod Features
Trimmed Starting Techs 
	* You will now start with only the most basic of parts. All weapons and further improvements will need to be purchased.
Improved Tech Drafting
	* Techs are now divided into power tiers and will unlock as rounds go on. Start with basic cannons and end with powerful railguns.
	* Some techs have been bundled together and late game offers you large portions of the tech tree to unlock in a single tech.
New Custom Parts
	* Smaller parts to allow more flexibility in smaller and cheaper ship design.
	* Special Explosive Charges useable by the AI to allow for building multiple ships in B&B mode.
## Required Mods List
* Kurim's More Crew Quarters
* TDI Advance Missile Launcher
* Twin Small Thrusters
* Twin Linked Point Defense Turret
* Bulkheads
* Micromissle Launcher
* Missile Launchyer Variant - Crippler
* Blackmian's Elbow Magazine
* General Munitions' Projectile Weapons
* DIGI Modular Missiles
* Better Capacitors
* Super Prisms
* Autocannon
* Sunflower Corporation
* Bonible's Roof Mounted Chaingun Fixed
* Expanded Vanilla Armors
* Galactic Alliance

A link to the Steam collection of these mods can be found [here]( https://steamcommunity.com/sharedfiles/filedetails/?id=3250287374).
# v2.2.0 - Overclock Update
Been a while I last touched the mod. The overlock update broke many of the used mods, so I took a break to allow some to be fixed. It also broke my mod itself, so I had to fix that as well. Right now my main goal is to simply get the mod up and working once more. As such, while this update does add in the base-game overclocks, no new modded overclocks (should they exist) have been added in.

This update is also primarily a "Part 1" of the planned update. I just want to get what I have pushed so I don't need to worry about future game versions knocking me back again.
## Game Version Support
* Supporting game version 0.30.5.
## Updated Mod Support
The following mods have not been updated to support the overclock update, and as such, have been disabled. Perhaps in the future, I will take it upon myself to update these mods to work. That said, it is not a priority. 
- Twin Linked Point Defense Turret (Steam Mod ID: 2886934391)
- Stormforge Additional Parts (2915669103)
- Dorsal Thrusters (2888035272)
- Laser Point Defense (2883970407)
- UV Lasers (2885023862)
The following mod, while working with the current game version, will no longer be supported by my mod.
- AWT Armor Weapons & Technology (2882082274)
	- This mod was never balanced well in my eyes, and is a pain to support. If you ever make mods, please use a consistent naming scheme, because this mod never did and caused countless problems because of it. It might come back in the future, but no time soon.
The following mod has been swapped for a different uploaded version. The original author said it was fine for a different user to upload a fixed version, so we'll be using that for the time being.
- Bonible's Roof Mounted Chaingun (3145052003) (dropped)
- Bonible's Roof Mounted Chaingun Fixed (3817773349) (added)
## New B&B Base-Game Parts
- All 28 base-game Overclocks are now supported.
	- Added a new "Overclock" specific tech slot to each round. This should help players see overclock options without taking slots from new part options. You will only be offered overclocks to parts you have unlocked. 
	- Note that since only the base-game overclocks are added, you'll need to pick them up to see overclock options.
- Thermal Resonance Lance has been added as an option at the Powerful tier.
	- Not sure how powerful it is, so it may be moved around in the future.
- Missile Launchers should have access to the Thermal Canister Missiles by default. 
	- You will still need to invest in overclocks to have them function.
## New B&B Modded Parts
While no new mods have been in added in this update, 
- Galactic Alliance
	- Walkthrough Crew Quarters (default unlock)
	- Large Airlock (default unlock)
	- Small Phase Thrusters bucket (basic tier, 5 items)
	- Medium Phase Thrusters bucket (improved tier, 5 items)
	- Small Antigrav, bundled with both Phase Thrusters
	- Laser Miniguns (improved tier)
- General Munitions Projectile Weaponry
	- Roof Cannon bucket (improved tier, 2 items)
## New Custom Parts
- Reactor Bomb
	- If you ever wished to have your ship sacrifice itself to inefficiently damage the enemy, then dream no more. The Reactor Bomb a fragile reactor with a large blast radius, capable of being manually triggered to explode. There is a general trade-off of wanting as little armor around it to maximize blast radius, yet too little armor means you're likely to be shot down instantly.
	- This is a Utilities ship part and is unlocked by default. It is not designed to be a serious weapon, instead a gimmick you can mess around with if you really want. Perhaps for fun, I'll make a draft tech that includes a stronger core in the future.
	- Currently rather clunky and inconsistent in effectiveness. This is a known issue with the part, but I have no current plans to dedicate more time for this specific part, being a fun/gimmick part.
## Tech Changes
- The Standard Machinegun (General Munitions) now includes the roof mounted version. To help balance it compared to the Small MG, the bucket has been moved up in tier. The roof version has been increased in cost to match other roof guns.
	- Weapon Tier: Basic -> Improved
	- Tech Cost: 5k -> 7.5k
	- Build cost (Roof MG): 100% -> 400%
- The Radio Jammer (General Munitions) has been disabled. I found it was mostly a dead draw and not sure where to put it right now. Might add it into some bucket in the future.
- Particle Cannon has felt a bit weak late game so I'm moving it down a tier.
	- Weapon Tier: Powerful -> Improved
## Part Updates
- Moved the Tiny Command Room custom part from the Flight group (now Thruster group) to the Command group.
- The Tiny Reactor should now gains the effects from the Electron Nebulas. I'm not entirely certain if this is working however.
## Bug Fixes
- Fixed the Rifle, MG, and Grenade (General Munitions)  buckets missing some icons.
## Misc
- Removed the Temp Bucket from the tech rotation.
- I've been rewriting some of the backend for the mod. The mod started life as a quick project I didn't expect to continue this long. As the mod has grown, it's become fairly hard to manage the files as the grow to 1k lines of code. These changes should make it easier to manage mod support going forward. This should have no impacts on the front end.
- Updated some bucket icons to use overlays. Mostly a backend thing, but some buckets might look slight different.
# Development Information
## Todo List
* Create a lobby setting format for the mode.
* Create a Steam version for easier updates. I'll have to rewrite file paths to get that done. Not hard but boring so it's low priority.
## Known Issues
* Certain buckets have overlapping parts. If you refund a bucket with an item you already own, it will revoke overlapping parts as well. You can not reverse this revoke, you will simply have to keep the bucket you just refund. As it stands, there is no plans to fix this niche issue.
* Super Prisms mod may crash the game if you combine many beams using them. This is outside my control to fix.
## Round Balancing
This is the general draft cost I balance around. It's intended for many rounds with smaller cash injections rather than a few rounds with larger cash injections. I tend to play with 2-4 players split between 2-4 teams. As such, most of my balance is based on this play experience. In the future I plan on adding a lobby config for the mode, but for now this is the policy at when I balance around. 

Weapons are priced and unlock based on how strong they are on a scale from Basic to Super. If a bundle is more/less powerful, I may make it more/less expensive. It is important to note that while I try to balance parts by making some more/less expensive, true balance is impossible for this mod to achieve. It is going to be up to the players to vary builds and avoid overpowered weapons every round. For this reason, I will never be accepting requests to balance the unlock trees.

```
Round: $ gain / $ total
000000 - Basic
	R1: 75k
100000 - Improved
	R2: 50k / 125k 
	R3: 50k / 175k
250000 - Powerful
	R4: 75k / 250k
	R5: 75k / 325k
400000 - Deadly
	R6: 75k / 450k
	R7: 100k / 550k
550000 - Super
	R8+ repeat previous
```