# Documentation

This section provides an overview of the gameplay changes to the vanilla HeartGold game included in this ROM hack. Given the aims of the project to maintain an authentic Johto experience with minimal disruption or change except to the League member order, no fundamental gameplay mechanics such as the battle engine or field mechanics were changed.

## Table of Contents
- [Story](#story)
- [Visuals and Graphics](#visuals-and-graphics)
- [Items](#items)
- [Learnsets](#learnsets)
- [Currency](#currency)
- [Encounters](#encounters)
- [Trainers](#trainers)
- [Gym Leader Phone Numbers](#gym-leader-phone-numbers)

---

## Story

The majority of main story events unfold as per the vanilla HeartGold game, however a small number of minor story elements have been re-worked to be more appropriate to the new positions of the League members. This section will provide a high-level overview of the changes, and includes spoilers. Events which fundamentally remain as they are in vanilla, but with changed characters and dialogue only, are not listed.

- Goldenrod Gym pre-requisites: the player must talk to Bruno in the Game Corner before being able to challenge the Goldenrod Gym, acquisition of the Radio Card is now optional (but still available in the Radio Tower ground floor).
- Goldenrod Gym badge: the player must follow Bruno to the Pokéathlon Dome after victory in order to obtain the Storm Badge (3rd badge).
- Olivine Gym: gym trainers are present and must be defeated in the Olivine Gym (Clair's dragon-type gym)
- Dragon's Den: this is now a completely optional location, and is not required in order for the player to earn all eight Johto badges.
- Kimono Girls: the order of back-to-back trainer battles against the Kimono Girls in Ecruteak Dance Theatre has been reversed, and is now Kuni, Sayo, Miki, Naoko, Zuki.

The required badge order for outsider Pokémon obedience levels and HM enablement is retained, though the actual badges obtained (names and graphics have been changed to better reflect the new Gym Leaders).

| Order | Location | Name | Gym Leader | HM Enabled | Obedience Threshold | Reward TM |
| :---: | :---: | :---: | :---: | :--- | :---: | :--- |
| 1 | Violet City | Zephyr Badge | Lance | `HM06` - Rock Smash | Level 20 | `TM61` - Twister |
| 2 | Azalea Town | Fog Badge | Karen | `HM01` - Cut | Level 30 | `TM01` - Sucker Punch |
| 3 | Goldenrod City | Storm Badge | Bruno | `HM04` - Strength | n/a | `TM08` - Bulk Up |
| 4 | Ecruteak City | Hive Badge | Koga | `HM03` - Surf | Level 50 | `TM45` - Cross Poison |
| 5 | Cianwood City | Plain Badge | Will | `HM02` - Fly | n/a | `TM29` - Psychic |
| 6 | Olivine City | Rising Badge | Clair | n/a | Level 70 | `TM59` - Dragon Pulse |
| 7 | Mahogany Town | Glacier Badge | Pryce | `HM05` - Whirlpool | n/a | `TM07` - Hail |
| 8 | Blackthorn City | Mineral Badge | Jasmine | `HM07` - Waterfall | Level 100 | `TM74` - Gyro Ball |

---

## Visuals and Graphics

A number of graphics have been updated to reflect the changes in Gym Leaders / League members. These include (but are not limited to):
- Overworld sprites (including HM cut-ins where appropriate & addition of custom trainer class sprites for Ninja Boy and Dragon Tamer)
- Battle trainer sprites (front and back where appropriate)
- VS cut-in animations (names, portraits, colours), including changes to Kanto leader colours
- Badge case graphics (including order of badges & portraits)
- Gym building colour schemes
- Gym interiors & Elite Four rooms (the order and association of the the graphics), for example Bugsy's Gym interior model (Azalea Town) is now Koga's Gym interior (Ecruteak City).
- Restoration of the *appearance* of original Japanese Game Corner in Goldenrod City (the "slot machines" still initiate the Voltorb Flip minigame only).

---

## Items
This section documents only changes from the vanilla HeartGold experience. Any ground, gift or mart items that are not mentioned explicitly are unchanged from vanilla HeartGold.

| Item | Vanilla HeartGold content/location | HeartGold in Reverse content/location | 
| --- | --- | --- |
| Coin Case | *Optional* acquisition from Goldenrod Game Corner | *Mandatory* acquisition from Goldenrod Game Corner |
| Macho Brace | Held Item on the MACHOP trade in Goldenrod Dept. Store | Ground item on the West side of the exterior of the Pokéathlon Dome |
| Radio Card | *Mandatory* acquisition through quiz in ground floor of Radio Tower | *Optional* acquisition through quiz in ground floor of Radio Tower |
| Rare Candy | Limited ground items | Professor Elm's assistant will offer to give up to 999 Rare Candies to the player after starter selection, and can refill to 999 at most other points in game progression. Rare Candy sell price reduced to £100. |
| TM01 | **Focus Punch**: reward for defeating Chuck (fifth Gym Leader, Cianwood City) | **Sucker Punch**: reward for defeating Karen (second Gym Leader, Azalea Town) |
| TM23 | Iron Tail: reward for defeating Jasmine (sixth Gym Leader, Olivine City) | Iron Tail: Celadon City Game Corner Prize Exchange (10,000 Coins) |
| TM30 | Shadow Ball: reward for defeating Morty (fourth Gym Leader, Ecruteak City), Battle Frontier prize (64BP) | Shadow Ball: ground item in Dragon's Den (South-East), Battle Frontier prize (64BP) |
| TM45 | **Attract**: reward for defeating Whitney (third Gym Leader, Goldenrod City) | **Cross Poison**: reward for defeating Koga (fourth Gym Leader, Ecruteak City) |
| TM51 | Roost: reward for defeating Falkner (first Gym Leader, Violet City) | Roost: ground item on the mid-level balcony of the Glitter Lighthouse (Olivine City) |
| TM61 | **Will-O-Wisp**: Battle Frontier prize (32BP) | **Twister**: reward for defeating Lance (first Gym Leader, Violet City), Battle Frontier prize (32BP) |
| TM74 | Gyro Ball: Celadon City Game Corner Prize Exchange (10,000 Coins) | Gyro Ball: reward for defeating Jasmine (eighth Gym Leader, Blackthorn City) |
| TM89 | U-Turn: reward for defeating Bugsy (second Gym Leader, Azalea Town) | U-Turn: ground item on the East side of Route 47 |

---

## Learnsets
This section documents only changes from the vanilla HeartGold experience. Any learnsets that are not mentioned explicitly are unchanged from vanilla HeartGold.

As above, the content of three TMs has been altered. The TM compatibility of those TMs has been changed, using level-up, egg & tutor learnsets as inspiration and a baseline.

<details>
<summary>TM01: Sucker Punch TM Compatibility</summary>

| ID | Name |
| --- | :--- |
| 19 | RATTATA |
| 20 | RATICATE |
| 32 | NIDORAN(m) |
| 33 | NIDORINO |
| 34 | NIDOKING |
| 50 | DIGLETT |
| 51 | DUGTRIO |
| 69 | BELLSPROUT |
| 70 | WEEPINBELL |
| 71 | VICTREEBEL |
| 74 | GEODUDE |
| 75 | GRAVELER |
| 76 | GOLEM |
| 92 | GASTLY |
| 93 | HAUNTER |
| 94 | GENGAR |
| 100 | VOLTORB |
| 101 | ELECTRODE |
| 106 | HITMONLEE |
| 115 | KANGASKHAN |
| 151 | MEW |
| 161 | SENTRET |
| 162 | FURRET |
| 167 | SPINARAK |
| 168 | ARIADOS |
| 170 | CHINCHOU |
| 171 | LANTURN |
| 177 | NATU |
| 178 | XATU |
| 185 | SUDOWOODO |
| 197 | UMBREON |
| 198 | MURKROW |
| 200 | MISDREAVUS |
| 203 | GIRAFARIG |
| 222 | CORSOLA |
| 228 | HOUNDOUR |
| 229 | HOUNDOOM |
| 234 | STANTLER |
| 237 | HITMONTOP |
| 239 | ELEKID |
| 251 | CELEBI |
| 261 | POOCHYENA |
| 262 | MIGHTYENA |
| 275 | SHIFTRY |
| 287 | SLAKOTH |
| 288 | VIGOROTH |
| 289 | SLAKING |
| 292 | SHEDINJA |
| 300 | SKITTY |
| 301 | DELCATTY |
| 302 | SABLEYE |
| 303 | MAWILE |
| 327 | SPINDA |
| 331 | CACNEA |
| 332 | CACTURNE |
| 336 | SEVIPER |
| 352 | KECLEON |
| 353 | SHUPPET |
| 354 | BANETTE |
| 355 | DUSKULL |
| 356 | DUSCLOPS |
| 359 | ABSOL |
| 367 | HUNTAIL |
| 380 | LATIAS |
| 413 | WORMADAM |
| 425 | DRIFLOON |
| 426 | DRIFBLIM |
| 429 | MISMAGIUS |
| 430 | HONCHKROW |
| 431 | GLAMEOW |
| 432 | PURUGLY |
| 434 | STUNKY |
| 435 | SKUNTANK |
| 438 | BONSLY |
| 442 | SPIRITOMB |
| 453 | CROAGUNK |
| 454 | TOXICROAK |
| 477 | DUSKNOIR |
| 478 | FROSLASS |
| 479 | ROTOM |
| 491 | DARKRAI |

</details>

<details>
<summary>TM45: Cross Poison TM Compatibility</summary>

| ID | Name |
| --- | :--- |
| 47 | PARASECT |
| 68 | MACHAMP |
| 72 | TENTACOOL |
| 73 | TENTACRUEL |
| 123 | SCYTHER |
| 141 | KABUTOPS |
| 151 | MEW |
| 167 | SPINARAK |
| 168 | ARIADOS |
| 169 | CROBAT |
| 207 | GLIGAR |
| 212 | SCIZOR |
| 254 | SCEPTILE |
| 347 | ANORITH |
| 348 | ARMALDO |
| 416 | VESPIQUEN |
| 451 | SKORUPI |
| 452 | DRAPION |
| 454 | TOXICROAK |
| 472 | GLISCOR |

</details>

<details>
<summary>TM61: Twister TM Compatibility</summary>

| ID | Name |
| --- | :--- |
| 12 | BUTTERFREE |
| 16 | PIDGEY |
| 17 | PIDGEOTTO |
| 18 | PIDGEOT |
| 21 | SPEAROW |
| 22 | FEAROW |
| 41 | ZUBAT |
| 42 | GOLBAT |
| 49 | VENOMOTH |
| 83 | FARFETCH'D |
| 95 | ONIX |
| 116 | HORSEA |
| 117 | SEADRA |
| 120 | STARYU |
| 121 | STARMIE |
| 130 | GYARADOS |
| 142 | AERODACTYL |
| 144 | ARTICUNO |
| 145 | ZAPDOS |
| 146 | MOLTRES |
| 147 | DRATINI |
| 148 | DRAGONAIR |
| 149 | DRAGONITE |
| 151 | MEW |
| 163 | HOOTHOOT |
| 164 | NOCTOWL |
| 169 | CROBAT |
| 176 | TOGETIC |
| 177 | NATU |
| 178 | XATU |
| 198 | MURKROW |
| 208 | STEELIX |
| 226 | MANTINE |
| 227 | SKARMORY |
| 230 | KINGDRA |
| 237 | HITMONTOP |
| 249 | LUGIA |
| 250 | HO-OH |
| 267 | BEAUTIFLY |
| 269 | DUSTOX |
| 275 | SHIFTRY |
| 276 | TAILLOW |
| 277 | SWELLOW |
| 278 | WINGULL |
| 279 | PELIPPER |
| 284 | MASQUERAIN |
| 329 | VIBRAVA |
| 330 | FLYGON |
| 333 | SWABLU |
| 334 | ALTARIA |
| 350 | MILOTIC |
| 357 | TROPIUS |
| 371 | BAGON |
| 372 | SHELGON |
| 373 | SALAMENCE |
| 380 | LATIAS |
| 381 | LATIOS |
| 384 | RAYQUAZA |
| 396 | STARLY |
| 397 | STARAVIA |
| 398 | STARAPTOR |
| 414 | MOTHIM |
| 430 | HONCHKROW |
| 441 | CHATOT |
| 443 | GIBLE |
| 444 | GABITE |
| 445 | GARCHOMP |
| 456 | FINNEON |
| 457 | LUMINEON |
| 458 | MANTYKE |
| 468 | TOGEKISS |
| 483 | DIALGA |
| 484 | PALKIA |
| 487 | GIRATINA |
| 493 | ARCEUS |

</details>

---

## Currency
This section documents only changes from the vanilla HeartGold experience. Any gift of currency that are not mentioned explicitly are unchanged from vanilla HeartGold.

1. The player recieved 2,500 Athlete Points from Magnus upon first entrance to the Pokéathlon Dome.
2. The Game Corner in Goldenrod City has a restored Coin Exchange counter, facilitating easier acquistion of the Game Corner prizes.

## Encounters
The vast majority of wild encounters are exactly as they are in the vanilla HeartGold game, in order to create the "what if?" experience by changing only one fundamental component.

Two concessions have been made in terms of encounters, documented below:
1. Trade Encounter in Goldenrod Dept. Store changed as a sympathetic reflection of the Gym Leader change here.
2. The version exclusive encoutners from SoulSilver have been incorporated into this HeartGold hack.

### Trade Encounters
This section documents only changes from the vanilla HeartGold experience. If a trade is not present here, its is unchanged from vanilla HeartGold.

| Parameter | Value |
| --- | --- |
| Location | Goldenrod Dept. Store 5F (TM Corner) |
| Original Trainer | Jose (37460) |
| Requested Species | Drowzee |
| Received Species | Clefairy |
| Pokémon Nickname | Magic |
| Held Item | Moon Stone |
| HP IV | 15 |
| ATK IV | 15 |
| DEF IV | 20 |
| SPATK IV | 25 |
| SPDEF IV | 15 |
| SPE IV | 20 |

### Wild Encounters
This section documents only changes from the vanilla HeartGold experience. If a route/location is not present here, its encounters are unchanged from vanilla HeartGold.

The 'habitat' feature of the Pokédex has been updated to reflect these wild encounter changes.

- [Route 30](/documentation/encounters/encounterset_003_route_30.md)
- [Route 31](/documentation/encounters/encounterset_004_route_31.md)
- [Route 36](/documentation/encounters/encounterset_025_route_36.md)
- [Route 37](/documentation/encounters/encounterset_026_route_37.md)
- [Route 45](/documentation/encounters/encounterset_067_route_45.md)
- [Route 48](/documentation/encounters/encounterset_102_route_48.md)
- [Route 28](/documentation/encounters/encounterset_105_route_28.md)
- Victory Road
  - [1F](/documentation/encounters/encounterset_110_victory_road_1f.md)
  - [2F](/documentation/encounters/encounterset_134_victory_road_2f.md)
  - [3F](/documentation/encounters/encounterset_135_victory_road_3f.md)
- [Route 2](/documentation/encounters/encounterset_112_route_2.md)
- [Route 3](/documentation/encounters/encounterset_113_route_3.md)
- [Route 7](/documentation/encounters/encounterset_117_route_7.md)
- [Route 8](/documentation/encounters/encounterset_118_route_8.md)
- Cerulean Cave
  - [1F](/documentation/encounters/encounterset_139_cerulean_cave_1f.md)
- [Mount Silver](/documentation/encounters/encounterset_085_mt._silver.md)
- Mount Silver Cave
  - [1F](/documentation/encounters/encounterset_086_mt._silver_cave_1f.md)
  - [2F](/documentation/encounters/encounterset_080_mt._silver_cave_2f.md)
  - [3F](/documentation/encounters/encounterset_081_mt._silver_cave_3f.md)
  - [Expert Belt Chamber](/documentation/encounters/encounterset_088_mt._silver_cave_expert_belt_chamber.md)
  - [Moltres Chamber](/documentation/encounters/encounterset_079_mt._silver_cave_moltres_chamber.md)
  - [Lower Mountainside](/documentation/encounters/encounterset_087_mt._silver_cave_lower_mountainside.md)
  - [Upper Mountainside](/documentation/encounters/encounterset_089_mt._silver_cave_upper_mountainside.md)

---

## Trainers
This section documents only changes from the vanilla HeartGold experience. If a trainer is not present here, it is unchanged from vanilla HeartGold. In the interests of consistency, the Gym Trainers in Mahogany Gym (which have not been altered) have their details included in the relevant section.

- [Violet Gym](/documentation/trainers/violet_gym.md)
- [Azalea Gym](/documentation/trainers/azalea_gym.md)
- [Goldenrod Gym](/documentation/trainers/goldenrod_gym.md)
- [Ecruteak Gym](/documentation/trainers/ecruteak_gym.md)
- [Cianwood Gym](/documentation/trainers/cianwood_gym.md)
- [Olivine Gym](/documentation/trainers/olivine_gym.md)
- [Mahogany Gym](/documentation/trainers/mahogany_gym.md)
- [Blackthorn Gym](/documentation/trainers/blackthorn_gym.md)
- [Indigo Plateau](/documentation/trainers/indigo_plateau_1.md)
- [Indigo Plateau (Rematches)](/documentation/trainers/indigo_plateau_2.md)
- [Saffron Fighting Dojo](/documentation/trainers/fighting_dojo.md)

---

## Gym Leader Phone Numbers
This section documents only changes from the vanilla HeartGold experience. If a Gym Leader is not present here, the methods for acquiring their phone numbers, arranging rematches and taking photographs are unchanged from vanilla HeartGold.

### Phone Number Acquisition
After the player has entered the Hall of Fame, and until the player has acquired their phone number, Gym Leaders will be absent from their Gyms during the following periods, their locations at these times can be visited in order to acquire the phone numbers.  

| Gym Leader | Away from Gym Location | Away from Gym Days/Times | Away from Gym Conditions |
| --- | --- | --- | --- |
| Lance | Ruins of Alph | Thursdays (00:00-23:59) | Hall of Fame |
| Karen | Ilex Forest | Tuesdays (00:00-23:59) | Hall of Fame |
| Bruno | Victory Road | Wednesdays (00:00-23:59) | Hall of Fame |
| Koga | Cianwood Pharmacy | Mondays (00:00-23:59) | Hall of Fame; Soul Badge obtained; Falkner/Janine event complete (see below) |
| Will | Safari Zone Gate | Any Day (12:00-15:59) | Hall of Fame |

| Related Events | Location | Days/Times | Conditions |
| --- | --- | --- | --- |
| Falkner/Janine | Celadown Dept Store (4th) | Mondays (00:00-23:59) | Soul Badge obtained |

### Arranging Rematches
As with all other Gym Leader's in the vanilla game, once the Gym Leader's phone number is acquired, the player must call them during the following rematch call window to arrange the rematch.  
| Gym Leader | Rematch Call Window | Rematch Conditions |
| --- | --- | --- |
| Lance | Thursday Afternoons (10:00-19:59) | 16 Gym Badges |
| Karen | Tuesday Night (20:00-03:59) | 16 Gym Badges |
| Bruno | Wednesday Night (20:00-03:59) | 16 Gym Badges |
| Koga | Saturday Mornings (04:00-09:59) | 16 Gym Badges |
| Will | Saturday Afternoons (10:00-19:59) | 16 Gym Badges |

### Photo Locations
Once the Gym Leader's phone number has been acquired, the Leaders will be available to take photographs with the player. The days and times that they are absent from the Gym and can have a photograph taken are detailed below. Additionally, the Elite Four & Champion (whose phone numbers can no longer be acquired), are still available for photographs in the locations that they are in the vanilla Heartgold game. Any conditions to their photos beyond entering the Hall of Fame are shown below.  

| Photograph NPC | Location | Days/Times | Conditions |
| --- | --- | --- | --- |
| Falkner | Celadon Dept Store (4th) | Wednesdays (00:00-23:59) | Koga's Number Registered |
| Bugsy | National Park | Fridays (00:00-23:59) | Hall of Fame |
| Whitney | Goldenrod Dept Store | Any Day (18:00-20:59) | Hall of Fame |
| Morty | Bellchime Trail | Mondays or Tuesdays (00:00-23:59) | Hall of Fame |
| Chuck | Route 47 | Sundays (00:00-23:59) | Hall of Fame; Jade Orb not obtained (as per vanilla HGSS) |
| Lance | Ruins of Alph | Mondays (00:00-23:59) | Lance's Number Registered |
| Karen | Ilex Forest | Tuesdays (00:00-23:59) | Karen's Number Registered |
| Bruno | Victory Road | Fridays (00:00-23:59) | Bruno's Number Registered |
| Koga | Mahogany Town | Wednesday (00:00-23:59) | Koga's Number Registered |
| Will | Safari Zone Gate | Any Day (18:00-20:59) | Will's Number Registered |
