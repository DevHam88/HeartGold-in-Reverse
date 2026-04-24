# Version History

## Version 1.1: Lance on a day off (Fix)
> Nb, Saves from version 1.0 are compatible with this patch.

- Fixes issue #6 (Lance incorrectly absent from gym on Thursdays before Hall of Fame)

## Version 1.0: Game Complete (Release Day)
> Nb, Saves from version 0.7 are compatible with this patch.

- No fixes identified ("formal" upversion of version 0.7)


## Version 0.7: Game Complete (Pre-Release Dialogue Adjustments)
> Nb, Saves from version 0.6 & 0.6.1 are compatible with this patch.

- Bug Fix: Corrected the spelling of Pryce's name in his gym dialogue (x3).
- Dialogue adjustments for various Gym Leaders & Elite Four members.

## Version 0.6: Game Complete (Pre-Release Bug Fixes)
> Nb, Saves from version 0.5 are compatible with this patch.

- Bug Fix: positioned the "Running Shoes" man back in Cherrygrove East (OW had accidentally been moved to Cherrygrove West during debugging of v0.5).
- Bug Fix: corrected the Pokegear Map Card location "pointers" when inside the Gym interiors that have moved locations relative to their exteriors.
- New Feature: Added the "Linking Cord" item (#113, previously unused), set with attributes for use as a pseudo evolution stone. Added new evolution methods to Machoke, Haunter, Kadabra & Graveler so that they can evolve by use of this item.
- New Feature: Edited the evolution data of all species who evolve by trade while holding an item. These all now have an additional evolution method of evolving into those target species when levelled up and holding the relevant item (day or night).
- New Item: added 1x overworld "Linking Cord" item behind the Rock Smash boulders in northern Cianwood City.
- New Item: added 3x gift "Linking Cord" items from new NPC in Pokemon League lobby (opposite the Abra guy).

## Version 0.5: Game Complete (Pre-Release)
> Nb, Saves from version 0.4 made before entering the Hall of Fame are compatible with this patch, saves from after this point could cause minor experience issues (Gym Leader rematches & Radio EXPN Card).

- Rework of first five Pokegear Phone Number: Call content, phone number acquistion process, acquisiton locations (replacing Falkner, Bugsy, Whitney, Morty & Chuck, with replacements).
- Rework of "photo opportunities" with first five vanilla Gym Leaders (now E4 & Champion) to be decoupled from Pokegear phone number acquistion.
- Inclusion of new "photo opportunities" for the new first five Gym Leaders.
- Re-scaling of the Gym Leader & Elite Four rematch teams' levels, held items and trainer items, to represent their new positions.
- Adjustments to team compositions for Lance & Clair according to requirements docs & playtesting.
- Reduce sell price of Rare Candies to 100
- Missing overworld items added (Macho Brace to Pokeathlon Dome, TM89 to Route 47)
- Bugfixes from v0.4 (minor), including text/dialogue issues and resolving "infinite" TM30 pickup.

## Version 0.4: Main Game Complete
> Nb, Saves from version 0.3 made before earning the Rising Badge are compatible with this patch, saves from after this point could cause inconsistencies due to story variable changes.

- Updates to all Johto & Kanto Gym Leader, Elite Four & Chamption VS Cut-ins & battle music to fit their types/colours/positions (including customising existing palettes and addition of four new variations).
- Edited the "Fly HM" cut-in to replace Lance with Falkner (Lake of Rage scene).
- Re-scripted the Dragon's Den sub-plot to be entirely optional, still only accessible after the eighth badge obtained.
- Reversed the order that the Kimono Girls are battled in (and minor dialogue changes to accomodate).
- Insertion of Falkner backsprite (Rocket HQ multi-battle against Ariana & Grunt).
- Update to the "arrival at Pokeathlon Dome" event, to include provision of 2500 Athlete Points (enough for a single evolution stone).
- Update 'guard' in the Pokeathlon Dome receptionist script, to allow registration only after the jersey is obtained from Bruno.
- Insertion of custom title screen.
- Additional dialogue updates (NPCs, usually passing/optional comments related to Leaders, E4 members, badges, gyms etc.).
- Changed the received species of the Goldenrod Dept Store trade from a Machop to Clefairy (nickname: Muscle>Magic; swapped Atk & Sp.Atk IVs; Held Item: Macho Brace>Moon Stone).
- Update of encounter files to include SS version exclusives (minimally disruptive to other species distribution, matching SS where possible).
- Update of Pokedex habitat/locations based on encounter file changes.

## Version 0.3: Gyms Rearranged Phase 2
> Nb, Saves from previous working versions not compatible with this patch due to story variable changes.

- Built from agreed base of v0.2.1
- Game fully playable up to an including the Rocket Takeover of the Radio Tower in Goldenrod City.
- Scripts, flags, level scripts, story variables updated for Gyms 1-7 (Violet-Mahogany)
  - Insertion of new Dragon Tamer & Ninja Boy overworld sprites for Violet & Ecruteak Gym Trainers.
  - Koga takeover of Ecruteak Gym scripting & texts
  - New trigger for preventing access to Olivine Gym before medicine story element completed (rather than empty gym, given size/gym puzzle).
  - Re-work of Olivine & Blackthorn Gym story flags & variables, including correction of Rocket Takeover variables set/incremented during the first seven gyms.
- All Gym trainers are now aligned with design docs, including additional Steel-type trainers in Blackthorn Gym.
- Completed adjustment of gym guide and gym statue texts
- Significant replacement/edits to NPC texts throughout referencing the first 6 Gym Leaders & vanilla E4.
- QoL feature: Professor Elm's aide provides free access to unlimited Rare Candies
- Olivine Lighthouse minor re-write/edits
- Lake of Rage, Mahogany Souvenir Shop & Rocket Hideout scripting and text updates (Lance to Falkner)

## Version 0.2.1: Goldenrod Narrative
- Re-configured all of Goldenrod Gym precursor and post-events to include Bruno in thematic story elements: replacing Whitney's Radio Tower & Pokéathelon Dome events.
- Radio card is no longer mandatory for story, Coin Case is now mandatory.
- All other changes from v0.2
- Story element variations first occur when the player first arrives in Goldenrod City.

## Version 0.2: Gyms Rearranged Phase 1
- Rearranged all Gym interiors & Pokémon League rooms & associated warps, as per designs
  - Swapped exterior Gym textures (Violet,Goldenrod, Cianwood, Olivine, Blackthorn)
  - Inserted new exterior Gym texture (Azalea)
  - Changed all in-Gym (and in-League) overworlds for the new Gym Leaders
  - Re-ordered the Elite Four guantlet of warps
- Gym Badge Case graphics changes for new order & leaders
- Preservation of the order of HM unlocks & obedience thresholds per badge
- Changed Gym Leader main dialogue implemented
- Some minor NPC diagloues adjusted where minimal:
  - Interior gym statue texts,
  - Exterior gym signs (Olivine & Blackthorn) swapped
  - Goldenrod flower shop NPC
- Updated first and rematch Trainer Battle triggers/ids for all Gym Leaders & Elite Four members
- Adjusted all required badge checks to account for re-ordering of the Gym interiors
- Gym Trainer updates:
  - All of Violet & some of Ecruteak gym trainers adjusted (as per current design docs)
  - All remaining trainers have team members reduced to level 1, but are otherwise as-per original interior location
- Scripts, flags, level scripts, story variables updated for Gyms 1-5 (Violet-Cianwood)
  - Custom interactions that don't match characterisations (such as Whitney/Bruno not providing badge initially) are removed.
- TM updates:
  - TM01, TM45 & TM61 have had their contents, descriptions & item sprites adjusted, as per designs (Sucker Punch, Cross Poison, Twister)
  - TM01, TM45 & TM61 learnsets have been adjusted, as per designs (based on level up, tutor & egg learnsets for Gen IV)
  - Gym Leaders now provide the updated TMs, as per designs
  - Swapped Game Corner (Celadon) prize from TM74 (Gyro Ball) to TM23 (Iron Tail)
  - TM30 (Shadow Ball) added to SE of Dragon's Den
  - Swapped Rare Candy from Olivine Lighthouse to TM51 (Roost) - exterior where player has to drop down out of the tower.
  - TM89 (U-Turn) now available in Route 47 (swapped for the Revive normally available near the route entrance)  

Not included in this patch:
- Adjustments to the Gym Leader and Elite Four rematch teams
- Adjustments to Goldenrod Radio Tower (Whitney), Pokéathelon Dome (Whitney) & Burned Tower (Morty) events.
- Functional script changes to Olivine & Blackthorn Gym swaps (progress beyond Cianwood will not be possible in a meaningful way)
- Change to VS Animations when Leader battles start

## Version 0.1: Playtesting
- Re-worked Gym Leader & Elite Four teams altered as per initial composition requirements
- No movement of battles/locations (the game is effectively "unplayable" in a normal sense due to the reversed nature)
- Debug NPC in Cherrygrove PC can be used to:
  - Acquire any Mon
  - Acquire any Badge
  - Acquire Any Items (including evolution items, rare candies, TMs etc.)
  - Initiate a trainer battle with any trainer (via trainer ID)
  - Initiate a trainer battle with any Leader or Elite Four (via dialogue wizard)
  - Note: leaders & elite four members are listed in these menus as per their vanilla locations/positions.
- Debug NPC does have some unfinished features, which will gracefully fail if attempted:
  - Acquire Eggs
  - Learn Any Move
  - Battle Rival (via dialogue wizard)
  - Battle Team Rocket (via dialogue wizard)
