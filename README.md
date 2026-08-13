# Super Mario Odyssey
This is the Manual for playing Super Mario Odyssey in [Archipelago](https://archipelago.gg/), based on the previous work of:
- RampantEpsilon
- MarioManTAW
- Empathy.mp3 
- Astro
- Squidy
- Meleneh 
## What's In It?
See the [info document](https://github.com/Haunteon/Manual-SMO/blob/main/manual_supermarioodyssey_haunteon/docs/en_Super_Mario_Odyssey.md).
## Installation & Usage
See the [setup guide](https://github.com/Haunteon/Manual-SMO/blob/main/manual_supermarioodyssey_haunteon/docs/setup_en.md).
## Why can't I do XYZ?
See [FAQ](https://github.com/Haunteon/Manual-SMO/blob/main/manual_supermarioodyssey_haunteon/docs/FAQ.md).
## Known Issues
- Lake/Wooded split logic still causing problems
- Potential softlocks in Wooded and Sand Kingdom
- Document Progressive Kingdom Unlocks
- Generic Moons option description confusing
# Not Yet Implemented
- Action Shuffle
  - Extra actions not in Action Guide
- Capture Shuffle
  - Extra Captures
- Shop Sanity (Yellow and Purple Shops)
- Regional Coin Logic (Purple Coins)
- Achievement Moons (Toadette)
- Capture Sanity
- Traps (Some ideas)
  - Return to nearest checkpoint/Odyssey/Death 
  - Challenge Trap
    - Reverse controls?
    - No Cappy: 30 Seconds
- Per Kingdom Moon Rock Items (specific moon rocks vs generic moon rock)
## Changelog
- 2.0.4
  - New Additions
    - Added/Changed Logic to Toadette Moons
	  - Princess Peach Moons
	  - Goombette Moons
	  - Slots Moon
	  - Sheep Moon
	  - 
	- New Yaml Options
	  - Individual Kingdom Moon Rock Items
  - Logic Fixes
    - From the Broken Pillar - Remove Swim (Can delay sinking with cap throw)
	- On the Lone Pillar - Add Bullet Bill (can reach with bullet bill only using motion controls)
	- Secret Path to Peach's Castle - Category was set to Post Game instead of Post Metro
	- Moon Cave Skip Event - Properly Disabled if yaml option is off

- 2.0.3
  - Logic Fixes
    - Jammin in Metro - Requires RC Car
    - Lost Kingdom timer - Incorrect Syntax
    - Overlooking a bunch of ingredients - Checks for Hammer Bro AND Cheese Area
    - Center/Edge of the galaxy - Requirements have been correctly swapped
    - It Popped Out of the Ice (Snow Kingdom Moon Rock) - Completed logic
	- Chomp through the Rocks - Added Big Chain Chomp
	- Taking Notes: Dive and Swim - Changed Logic
	- By a Babbling Brook/A Hard Rock in Deep Words - Change Logic to Ground Pound + (Coffer, Trex, or Yaml option lure Captures (not implemented))
	- Flooding Pipeway secret - Changed Logic
	- Sea Gardening: All 4 Seeds - One specific Pot always grows taller no matter which seed is put in it. logic added to all seeds to reach that height
  - Other Changes
    - Moon Per kingdom requirements minimum - Cannot be lower than default
  - Notes
    - Double checked Lighthouse Seal works with just swim (no quick swim or cheep cheep). Is possible with Life Up heart and grabbing moon in tunnel for air refill