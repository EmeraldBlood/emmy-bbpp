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
* AWT Armor Weapons & Technology
* TDI Advance Missile Launcher
* Twin Small Thrusters
* Twin Linked Point Defense Turret
* Bulkheads
* Micromissle Launcher
* Missile Launchyer Variant - Crippler
* Blackmian's Elbow Magazine
* General Munitions' Projectile Weapons
* DIGI Modular Missiles
* Stormforge Additional Parts
* Dorsal Thrusters
* Better Capacitors
* Super Prisms
* Laser Point Defense
* Autocannon
* UV Lasers
* Sunflower Corporation
* Bonible's Roof Mounted Chaingun
* Expanded Vanilla Armors
* Galactic Alliance

A link to the Steam collection of these mods can be found [here]( https://steamcommunity.com/sharedfiles/filedetails/?id=3250287374).
# v2.1.0 - Improved Arsenal Changelog
This update is being released as a stop-gap for the upcoming v3.0.0 release. With release of Cosmo v0.30.0 bringing a lot new content, I want to release what is done instead of having to endlessly move the goal post out.
## Game Version Support
* Supporting game version 0.30.3d.
## New Mod Support
* Galactic Alliance is now partially supported! I'll likely need to do a balance pass so expect some things to be too weak/strong.
	* Added 7 new weapons, 4 new thrusters.
	* More parts will be added in the near future.
* Expanded Vanilla Armors
	* A mostly cosmetic mod aiming to add new armor shapes. Time to expand your creative horizon.
* AWT (update)
	* Added supported for the new Blathalite Reinforced Corridors, bundled with the previous corridors and Bulkheads mod. The bucket has gone up from 7,500 to 10,000 in price due to compensate for a higher tech being in a lower tier bucket.
## New Custom Parts
* Auto Charge LR
	* A long range version of the Auto Charge designed to separate the ship a spawn range instead of close contact. Ranged for Normal mode spawn range (1500 units)
* Tiny Capacitor
	* A 1x1 capacitor designed to hold a few charges in use for low power environments. Ideal for thrusters or moving power around a tight ship.
## Balance Changes
### Tier Cost Changes
General weapon balance is decided by unlock tier and general worth. Each tier is subdivided into cost tiers of general worth: 5k, 7.5k, and 10k. While this is a fine price-point for early tiers, the cost is negligible late game. As such, I've slightly increased the base cost of parts as tiers increase. The goal isn't to limit funds, but ensure there's always a decision on what techs to pick up or leave.
* A few techs at 12.5k have been lowered to the 10k
### Item Cost Increase
While previously I held a stance of not wanting to change the values of any other author's mod out of pure simplicity, I've decided to attempt to rebalance build costs of certain parts. Select few mod parts are quite powerful while also being cheap to build (ex: small turreted weapons). My previous attempt to balance them was to increase purchase cost, however this has the inverse effect of requiring players to sink all remaining money into that part to offset this deficit. Ideally, this will allow players to more strategically utilize a smaller quantity of these powerful parts in their ships instead of excluding them from the mode all together.
### Part Changes
* Tri-Steel Armor: Tended to invalidate many early tier weapons for no downside with no interesting design process to do so. Increased cost allows for use in reinforcing critical areas while discouraging converting entire ships to it.
	* Build cost: 100% -> 200%
	* Bucket cost: 10k -> 7.5k
* Flamethrowers:  At the Improved levels, ships lack much armor or any shields to prevent flamers from igniting an entire ship. Increasing the cost to build to push the gun out of a general purpose gun and into a more specialized weapon, such as EMPs.
	* Weapon Tier: Improved -> Powerful
* Deck Chaingun: Was always intended to be one above the normal Chaingun but I forgot to change the value upon adding it.
	* Weapon Tier: Powerful -> Deadly
* Long variants of the Small Rifle, MG, and Grenade: Build cost increased since they can be placed behind armor. In compensation, they're now able to be built from the start of the game.
	* Weapon Tier: Improved -> Basic
	* Build cost: 100% -> 200%
* Roof variants of the Small Rifle, MG, and Grenade: Build cost has been greatly increased since they can be placed deep within the ship. They are also able to be built at the start of the game now.
	* Weapon Tier: Deadly -> Basic
	* Build cost: 100% -> 400%
### Bucket Changes
* Missile Super Bucket:
	* Now also unlocks Nukes.
* Small rifle, mg, and grenade launchers have been reorganized by project type (all rifles, etc) instead of gun type (long, etc).
## Bug Fixes
* Fix broken item text while holding alt.
* Fixed the Advance Missile Launcher lacking HE missiles and parts on its own.
* Added EMP missiles to the Super Missile Bucket.
## Misc
* Removed 0.5 energy from the Tiny Generator's Battery Capacity, rounding capacity to a whole number. Better matches actual capacity to the visuals.
* Standardized some file names and internal IDs for consistency.
* Changed the mod's '&' symbol to 'and' for bug fixes.
* Updated mod README. Moved changelog out of the README and into a new file.
* Maxwell is standing in for the mod icon temporarily.
* Removed some unused files.
* Removed some disabled entries not planning on returning from the code.
## Known Issues
* Mod support is in flux right now due to update 0.30.0. As such, the following mods have been disabled in the code:
	* Dorsal Thrusters
	* Stormforge
	* Twin-Linked Point Defense
	* Laser Point Defense
	* UV Lasers
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