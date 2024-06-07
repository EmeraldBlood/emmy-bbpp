# Cosmoteer-Emmy-BBPP
 My personal mod created to allow multiple different steam workshop mods to be accessable within the Build & Battle mode. You are free to edit anything you don't like about it, such as adding or removing mods, however all players must have the EXACT same copy of the mod or else it will cause issues.

## Required Mods List:
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
* AI Core Automated Ship Parts
* Dorsal Thrusters

A link to the steam collection can be found here: https://steamcommunity.com/sharedfiles/filedetails/?id=3250287374

## Changelog:
v1.4.0 - New Mods, Basegame Changes, and Balance Patch
New Mods
* Stormforge Additional Parts
	* Adds a roof mounted Railgun. Placed in the Deadly tier.
* AI Core Automated Ship Parts
	* Adds AI nodes to replace crew. In order for the AI cores to, you require a total number of AI cores equal to required crew count for the item. The cores do not function at half control, they are all or nothing. Does not currently work with all modded rooms; perhaps in the future I will fix this. Placed in the Powerful tier.
* Dorsal Thrusters
	* Large thrusters that can be placed in the center of the ship. Placed in the Powerful tier, as to be more inline with other turrets.
Basegame Changes
* The modular Railgun has been buffed by making each segment now give double the buff it use to. Essentially every railgun is now 2x longer at half the space. Since the Railgun is very hard to build around and and extremely vulnerable, I wanted to make it really worth that risk. This may be too strong, but if so it can always be rolled back some later.
	* Railgun segment multiplier from 20% up to 40% more power.
B&B Balance
* All Sulfur Generators have been removed for the time being. Any bucket with them essentially refunded more money than it cost by switching to them, as their sole function was to be cheaper. While I considered ways to balance them without directly editing their code, ultimately I decided there was no efficient way to solve this problem without doing so.
	* Tiny, Small, Medium, and Large Sulfur Generators, as well as the 1x1 sulfur store room.
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

## Round Balancing
This is the general draft cost I balance around. It's intended for many rounds with smaller cash injections rather than a few rounds with larger cash injections. I tend to play with 2-4 players split between 2-4 teams. As such, most of my balance is based on this play experience. In the future I plan on adding a lobby config for the mode, but for now this is the policy at when I balance around.
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

## Todo List
* Create a mod icon. Very important.
* Create late game buckets that will include many lower tier guns. This will provide much more building options and hopefully free up some slots.
* Create a lobby setting format for the mode.
* Fix graphical bugs on the auto charge.