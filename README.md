# HeartGold in Reverse
Patch files for HeartGold in Reverse

# Attribution
| Name | Contribution |
| --- | --- |
| [OKreations](https://www.youtube.com/@Okreations) | [Concept](https://www.youtube.com/watch?v=SJDdFpz8RjU), game design & content |
| [MrHam88](https://github.com/DevHam88) | Implementation/development |
| [TrainerFromHoenn](https://www.youtube.com/channel/UC_fK0rrfrgZSKcXPi7UnNXQ) | *Support:* Guidance on badge case graphic changes |
| [PurpleZaffre](https://www.deviantart.com/purplezaffre/gallery) | *Assets:* Dragon Tamer OW sprites (maker) |
| [maicerochico](https://www.deviantart.com/maicerochico) | *Assets:* Dragon Tamer OW sprites (original commissioner) |
| [Kyledove](https://pokengine.org/users/kyledove) | *Assets:* Ninja Boy OW sprites (maker) |

| Primary Tools | Contribution |
| --- | --- |
| [DSPRE](https://github.com/DS-Pokemon-Rom-Editor/DSPRE) | Majority of edits to scripts, texts & basic trainer team compositions |
| [PDSMS](https://github.com/Trifindo/Pokemon-DS-Map-Studio) | Texture pack edits (changes to map elements such as Gym Exteriors & Champion statues) |
| [VSMaker2](https://github.com/Chvlkie/VSMaker2) | Addition of "new" trainers |

# Version History
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
- Re-configured all of Goldenrod Gym precursor and post-events to include Bruno in thematic story elements: replacing Whitney's Radio Tower & Pokeathelon Dome events.
- Radio card is no longer mandatory for story, Coin Case is now mandatory.
- All other changes from v0.2
- Story element variations first occur when the player first arrives in Goldenrod City.

## Version 0.2: Gyms Rearranged Phase 1
- Rearranged all Gym interiors & Pokemon League rooms & associated warps, as per designs
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
  - TM89 (U-Turn) now available in Route 47 (swapped for the Revive normall available near the route entrance)  

Not included in this patch:
- Adjustments to the Gym Leader and Elite Four rematch teams
- Adjustments to Goldenrod Radio Tower (Whitney), Pokeathelon Dome (Whitney) & Burned Tower (Morty) events.
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
