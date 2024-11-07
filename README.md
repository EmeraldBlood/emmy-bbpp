# Cosmoteer-Emmy-BBPP
My personal mod created to allow multiple different steam workshop mods to be accessable within the Build & Battle mode. You are free to edit anything you don't like about it, such as adding or removing mods. If you did edit the game, all players must have the EXACT same copy of the mod or else it will cause issues.

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

A link to the steam collection can be found here: https://steamcommunity.com/sharedfiles/filedetails/?id=3250287374

## Most Recent Changelog
v2.0.0 - Energy Update
Game Version Support
* Supports Cosmoteer version 0.27.2
	* Basegame Large Bunks have been added to the Large Crew bucket.
New Mods
* Better Capacitors
	* Adds new capacitors of in-line with medium and large generators. Bundled them with their respecive generators.
* Super Prisms
	* Adds more powerful Prisms for the Ion Beam to use. Allows beams to better scale without requiring huge ship sizes. For the time being they are bundled with the Ion Beam itself, however it may be moved higher if it's too powerful. NOTE: combining too many beams together may crash the game.
* Laser Point Defense
	* Alternate point defense gun capiable of more accurately shooting down fast targets (missiles) in exchange for lower damage output against slower ones (shells). Added to the Basic tier.
* Autocannon
	* Turreted laser autocannon also capable of shooting down incoming Projectiles, similar to that of Flak. Placed in the Powerful tier.
* UV Lasers
	* Alternate gun to the disruptor with higher shield DPS but lower damage to armor and lacking power drain. Added to the Improved tier, as no shields exist in Basic.
* Sunflower Corporation
	* Ion Blaster, a slow-moving guided energy weapon. Placed in the Basic tier.
	* Heavy Ion Blaster, a slow-moving guided energy projectile.  Causes a penetraiting effect on impact. Placed in the Powerful tier.
	* Sunflower also includes a handful of other parts. Currently they are not being added due to being too powerful (Arc Emitters) or too situational (Ion Diffusion Lattice). Possible they might be added in the future.
* Bonible's Roof Mounted Chaingun
	* Replaces the Deck Chaingun from the General Munitions' Projectile Weaponry
New Custom Parts
* Added a 1x2 tiny command room to go alongside the tiny generator. This follows the same general philosophy as the Tiny Generator, designed to be used for smaller ships as opposed to bolstering larger ships.
	* Compared to the small command, the tiny give 40% command (20 units) at 60% cost (6k).
Late Game Buckets
* Late game buckets have been added to the Super tiers. These contain a large collection of early game techs you may have missed early on. They contain many Basic - Improved tier techs from the early game to help round out your ship. They are not made to provide you every weapon in the game, as I believe a large part of Build & Battle is the fact you will always have to forego some options. If these compete too much with other techs during the late-game, I may move it to its own category. 
	* Added Thruster Super Bucket. Contains all thrusters from the basic and improved tiers, including the Engine Room.
	* Added the Energy Weapon Super Bucket. Contains all energy weapons on the Basic and Improved tiers, including basic point defense.
	* Added the Projectile Weapon Super Bucket. Contains all Basic and Improved tier projectile weapons, including machinegun point defense.
	* Added the Missile Super Bucket. Contains all basegame missiles and Micromissiles.
	* Added the Defense Super Bucket. Contains all Basic and Improved point defense and shield techs, as well as the basegame Large Shield Generator.
	* Added the Command Super Bucket. Contains the Medium Control Bucket, Medium Crew Bucket, and Medium Power Bucket.
Balance Changes
* Starting Techs
	* The base-game Capacitor has been made a default starting item.
* Tiers Changed
	* Quad HMG has been moved up from Improved to Powerful tier.
	* TDI Advance missiles have been moved from Powerful to Deadly. This is due their expensive build cost and including all missiles by default. Their tech cost has been reduced to compensate.
	* Crippler Missiles have been moved from Improved to Powerful tier. Early game generally lacks armor or shields to counter them.
* Bucket Changes
	* AWT Light and Heavy armor are now combined into a single bucket.
Misc
* Restructured files for B&B buckets. Only a backend change for slightly better loading preformance.
* Fixed the graphical issues with the Auto Charge. Improved the visuals slightly.
* Enabled the resource factories again, just in case anyone wants to get super efficient with supply lines.
	* Mine Factory was missing and has been readded.

## Todo List
* Create a mod icon. Very important.
* Create a lobby setting format for the mode.
* Fix TDI Clusters being on the default missile launcher
* Improve the Auto Charge and add alternate versions for more control.
* Create a Steam version for easier updates. I'll have to rewrite file paths to get that done. Not hard but boring so it's low priority.

## Known Issues
* Certain buckets have overlapping parts. If you refund a bucket with an item you already own, it will revoke overlapping parts as well. You can not reverse this revoke, you will simply have to keep the bucket you just refund. As it stands, there is no plans to fix this niche issue.
* Super Prisms mod may crash the game if you combine many beams using them. This is outside my control to fix.

## Round Balancing
This is the general draft cost I balance around. It's intended for many rounds with smaller cash injections rather than a few rounds with larger cash injections. I tend to play with 2-4 players split between 2-4 teams. As such, most of my balance is based on this play experience. In the future I plan on adding a lobby config for the mode, but for now this is the policy at when I balance around. 

Weapons are priced and unlock based on how strong they are on a scale from Basic to Super. If a bundle is more/less powerful, I may make it more/less expensive. It is important to note that while I try to balance parts by making some more/less expensive, true balance is impossible for this mod to achieve. It is going to be up to the players to vary builds and avoid overpowered weapons every round. For this reason, I will never be accepting requests to balance the unlock trees.

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

## Past Changelogs
v1.4.1 - Tiny Generator & Small Tweaks
* AI Core Automated Ship Parts has been disabled for the time being. While I could go about patching the mod for weapons, the mod doesn't provide enough of a change to justify the work right now.
	* Known Issue: Spawning the GMPW Deck Chaingun will crash due to the AI modules.
* Created a Tiny Generator in place of the old Sulfur Tiny Generators. This will better allow for more tiny ships while not being so cheap as to overshadow the small generator.
	* The Tiny Generator holds about 40% capacity at 60% cost of the small generator. It is designed to be a cheaper main generator with enough strength to power thrusters and other low power rooms. It generally lacks the capacity to be a personal power generator for high power shields and energy weapons.  
* Working to add the default mode I balance the game around to the drop-down list. Currently having issues so delayed ATM.

v1.4.0 - New Mods, Basegame Changes, and Balance Patch
New Mods
* Stormforge Additional Parts
	* Adds a roof mounted Railgun. Placed in the Deadly tier.
* AI Core Automated Ship Parts
	* Adds AI nodes to replace crew. In order for the AI cores to, you require a total number of AI cores equal to required crew count for the item. The cores do not function at half control, they are all or nothing. Does not currently work with all modded rooms; perhaps in the future I will fix this. Placed in the Powerful tier.
* Dorsal Thrusters
	* Large thrusters that can be placed in the center of the ship. Placed in the Powerful tier, as to be more inline with other turrets.
Basegame Changes
* The modular Railgun has been buffed by making each segment now give double the buff it use to. Essentially every railgun is now 2x longer at half the space. Since the Railgun is very hard to build around and and extremely vulnerable, I wanted to make it really worth that risk. As Sid Meier once said, make big changes to see how they work.
	* Railgun segment multiplier from 20% up to 40% more power.
B&B Balance
* All Sulfur Generators have been removed for the time being. Any bucket with them essentially refunded more money than it cost by switching to them, as their sole function was to be cheaper. While I considered ways to balance them without directly editing their code, ultimately I decided there was no efficient way to solve this problem without doing so.
	* Removed Tiny, Small, Medium, and Large Sulfur Generators, as well as the 1x1 sulfur store room.
* Clustered all GMWP short, long, and roof weapons into a single bucket. This will help reduce the prevalence of these weapons always appearing early game.
	* Prices have been increased for the buckets compared to the base cost of the guns normally.
* Roof mounted guns/pd are moved higher due to their extreme protection and efficiency for little downside, fundamentally breaking the early game when spammed. While I do not wish to remove them outright, they are likely still too powerful and may be further modified.
	* All long weapons have been moved to the Improved tier. 
	* All GWMP roof weapons have been moved to the Deadly tier. 
	* Roof Point defense has been moved to the Deadly tier. Higher buy-in cost.
* New Buckets
	* Medium Command Center and Sensor Array are now bundled.
	* Large Command Center and Tractor Beam are now bundled.
Misc Changes
* Made the Auto Charge look a bit nicer.

v1.3.1 - Auto Charge item added
* Added offical 0.26.1 support.
* Created a new ship part, the Auto Charge. This is simply an explosive charge the AI will detonate once within 450 units (HE missile range) of an enemy.

v1.3.0 - Bucket update & QoL improvements
* Added categories to all modded weapons. Forgot to do this prior, oops.
	* Added a new category for Utility parts.
* Added custom icons for buckets of items and new names to better denote what is multiple different items included in a single cost.
* Balance
	* Flamer has been knocked up a price tier
	* EMP weapons are now considered Utility for categories
	* Sulfur genators have all been knocked up one tier. The B&B mode is too short for their fuel downside to be a problem.

v1.2.0 - Mod-Thruster Update & new weapons
* Supports version 0.26.0
* Added the Basegame Mod Trusters to the list
* Added all GM Projectile Weapons and shields
* As of now, the Sandevistan devices are NOT added due to being wonky
* Fixed a bug where Micro or Crippler lacked the ability to buy missiles.
* Elbow Magazine mod
* DIGI Modular Missiles
* Added in AWT Shields, but may be OP

v1.1.0 - More mods update
Added Mods:
* Twin PDT
* Crippler Missiles
* Micro Missiles
Base Parts:
* Cannon factories are now base
* Factories are no longer a bundle
Prices:
Tweaked all base prices based on value.
* Upped all thresholds 200,000 -> 250,000
* Prices up: tri-steel, bulkheads & reinforced corridors, nukes, large cannons, large laser, deck cannon, ion beams, railgun, large shields, small shields

v1.0.4 - Main release
* More Crew Quarter
* AWT Armor & Weapons
	* Shields and gun not added
* TDI Advance Missile Launcher
* Bulkheads
* Twin small thrusters
* Special Icons
Base Parts Moved:
* Removed part factories
* Ammo factories now draft bundle
* Standard engines now draft
* Crews Quarter now draft (with 3x2 MCQ)