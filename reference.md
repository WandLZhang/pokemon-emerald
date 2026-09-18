# Generation III reference

Gen 3 data only. Emerald differences from Ruby and Sapphire are called out.

## Rules that break modern advice

- **Physical or special is set by type, not by move.** Normal, Fighting, Flying, Ground,
  Rock, Bug, Ghost, Poison, and Steel are physical. Fire, Water, Grass, Electric,
  Psychic, Ice, Dragon, and Dark are special. So Steel Wing runs off Attack and Spark
  runs off Special Attack.
- **Dark is immune to Psychic.** Kadabra can't touch Sableye or Carvanha.
- **Type immunity applies to status moves.** Thunder Wave fails against Ground types.
- **Confusion lasts 2-5 turns with a 50% self-hit chance.** Self-hit is a typeless
  40-power physical hit. It ignores typing, so a Ground type still gets confused.
- **Magnitude and Earthquake make no contact.** Static and Rough Skin never trigger.
  Rollout, Quick Attack, and Spark do make contact.
- **TMs are single use.**
- **The Move Deleter is in Lilycove.** A TM can't overwrite an HM move, so that's the
  only way to drop one.
- **Flash is only needed in Granite Cave.** Rusturf Tunnel, Meteor Falls, Shoal Cave,
  Seafloor Cavern, and Victory Road are all lit. Dump it at the Move Deleter.
- **Teleport warps to the last Pokemon Center.** Entering one is enough, no heal needed.
  Fly replaces it, since Fly reaches any visited town.
- **The Knuckle Badge caps obedience at lv30.**
- **Exp. Share splits 50/50.** The holder takes 50%, participants split the rest.
- **Switch-training works.** Any Pokemon sent out gets a share, even for one turn.

## Gym leaders

### Gym 2, Brawly, Dewford

Reward: Knuckle Badge, TM08 Bulk Up, $1,900. Emerald adds a third Pokemon, Meditite,
over Ruby and Sapphire.

### Gym 3, Wattson, Mauville

Emerald only. Ruby and Sapphire give him Magnemite 22, Voltorb 20, Magneton 23 instead.

| Pokemon | Lv | Ability | Item | Moves |
|---|---|---|---|---|
| Voltorb | 20 | Soundproof | none | Rollout, Spark, Selfdestruct, Shock Wave |
| Electrike | 20 | Static | none | Shock Wave, Leer, Quick Attack, Howl |
| Magneton | 22 | Magnet Pull | none | Supersonic, Shock Wave, Thunder Wave, SonicBoom |
| Manectric | 24 | Static | Sitrus Berry | Quick Attack, Thunder Wave, Shock Wave, Howl |

He uses two Super Potions. Reward: Dynamo Badge (Rock Smash in the field, +10% Speed),
TM34 Shock Wave, $2400.

Gym trainers, all lv17 with no held items:

| Trainer | Team | Doubles with |
|---|---|---|
| Battle Girl Vivian | Meditite 17, Meditite 17 | Kirk |
| Guitarist Kirk | Electrike 17, Voltorb 17 | Vivian |
| Youngster Ben | Zigzagoon 17, Gulpin 17 | — |
| Bug Maniac Angelo | Illumise 17, Volbeat 17 | Shawn |
| Guitarist Shawn | Voltorb 17, Magnemite 17 | Angelo |

Fire and Fighting both hit Magneton for 2x.

### Gym 4, Flannery, Lavaridge

Emerald gives her four. Ruby and Sapphire give three: two Slugma at 26 and Torkoal 28
with no held item.

| Pokemon | Lv | Ability | Item | Moves |
|---|---|---|---|---|
| Numel | 24 | Oblivious | — | Overheat, Take Down, Magnitude, Sunny Day |
| Slugma | 24 | Magma Armor | — | Overheat, Smog, Light Screen, Sunny Day |
| Camerupt | 26 | Magma Armor | — | Overheat, Tackle, Sunny Day, Attract |
| Torkoal | 29 | White Smoke | White Herb | Overheat, Sunny Day, Body Slam, Attract |

Two Hyper Potions. Reward: Heat Badge, TM50 Overheat, $2,900.

Numel and Camerupt are Fire/Ground, so Water is 4x on both. Every one of them carries
Sunny Day, which halves Water damage. Torkoal's White Herb cancels Overheat's own Sp. Atk
drop.

Gym trainers: Slugma at 22-23, Numel at 23, one Kecleon 23, one Meditite 23. No held
items.

### Pre-gym, Wally, outside the Mauville gym

Ralts 16. Growl, Confusion, Double Team, Teleport. He blocks the gym door.

### Rival, Route 110, Torchic pick

Emerald only. Ruby and Sapphire give Shroomish and Numel instead.

| Pokemon | Lv | Type | Moves |
|---|---|---|---|
| Lombre | 18 | Water/Grass | Astonish, Growl, Absorb, Nature Power |
| Slugma | 18 | Fire | Yawn, Smog, Ember, Rock Throw |
| Marshtomp | 20 | Water/Ground | Water Gun, Bide, Mud Shot, Foresight |

Reward is the Itemfinder and $1200. Lombre and Marshtomp both hit Geodude for 4x.
Slugma is pure Fire, so Rock Throw is 2x there.

## Move data

| Move | Type | Power | Acc | PP | Notes |
|---|---|---|---|---|---|
| Vital Throw | Fighting | 70 | never misses | 10 | -1 priority. Fails against Dig and Fly turns. The screen wrongly shows 100% |
| Arm Thrust | Fighting | 15 x 2-5 | 100 | 20 | Averages 3.0 hits, so about 45 power. 2 hits 37.5%, 3 hits 37.5%, 4 hits 12.5%, 5 hits 12.5% |
| Magnitude | Ground | 10-150 | 100 | 30 | Averages 71 power, 106 with STAB. Doubles against a target in Dig |
| Rock Throw | Rock | 50 | 90 | 15 | Free on Geodude at 11 |
| Rock Tomb | Rock | 50 | 80 | 10 | Lowers Speed by 1 |
| Steel Wing | Steel | 70 | 90 | 25 | Physical in Gen 3. 10% chance to raise the user's Defense by one stage |
| Thief | Dark | 40 | 100 | 10 | **Special**, since Dark is a special type in Gen 3. The user must hold nothing |
| Swagger | Normal | — | 90 | 15 | Confuses the target and raises its Attack by 2 |
| Disable | Normal | — | **55** | 20 | Blocks the target's last move for 2-5 turns. Fails on a fresh switch-in and ends if they switch out. 80% in Gen 4, 100% in Gen 5+ |
| Teleport | Psychic | — | — | 20 | Field: warps to the last Pokemon Center. Battle: escapes wild singles, always fails vs trainers |
| Quick Claw | item | — | — | — | 20% chance to move first **within its priority bracket** in Gen 3. It can't lift a -1 move like Vital Throw above a normal-priority one |
| Shock Wave | Electric | 60 | never misses | 20 | TM34, from Wattson |
| Mud Sport | Ground | — | — | 15 | Halves Electric power on both sides. Ends when the user switches out |

Magnitude power roll: 10 at 5%, 30 at 10%, 50 at 20%, 70 at 30%, 90 at 20%, 110 at 10%,
150 at 5%.

## Learnsets

Next milestone per Pokemon:

| Pokemon | Next move | At | Evolves |
|---|---|---|---|
| Combusken | Sand-Attack | 21 | Blaziken 36 |
| Kadabra | Psybeam | 21 | never, Alakazam needs a trade |
| Taillow | Double Team | 19 | Swellow 22 |
| Makuhita | Fake Out | 19 | Hariyama 24 |
| Geodude | Rollout **29**, as Graveler | 29 | Graveler 25. It evolves first, so the lv26 Geodude entry never fires |
| Electrike | Quick Attack 17, then **Spark 20** | 17 | Manectric 26 |
| Slakoth | Encore | 7 | Vigoroth 18. Evolving skips Faint Attack 19, since Vigoroth learns Fury Swipes at 19 instead |
| Wingull | Mist | 21 | Pelipper 25. Supersonic is level 7, not 19 |

Full runs:

**Combusken**: Scratch 1, Growl 1, Focus Energy 1/7, Ember 1/13, **Double Kick 16**,
Peck 17, Sand-Attack 21, Bulk Up 28, Quick Attack 32, Slash 39, Mirror Move 43, Sky
Uppercut 50.

**Kadabra**: Teleport 1, Kinesis 1, Confusion 1/16, Disable 18, **Psybeam 21**, Reflect
23, Recover 25, Future Sight 30, Role Play 33, **Psychic 36**, Trick 43. Calm Mind is
TM04, not a level-up move.

**Geodude**: Tackle 1, Defense Curl 1, Mud Sport 6, **Rock Throw 11**, **Magnitude 16**,
Selfdestruct 21, Rollout 26, Rock Blast 31, Earthquake 36, Explosion 41, Double-Edge 46.
**Graveler at 25.** Golem needs a trade, so Graveler is the end of the line.

**Graveler**: same up to Selfdestruct 21, then Rollout 29, Rock Blast 37, **Earthquake
45**, Explosion 53, Double-Edge 62. Evolving pushes Earthquake back nine levels. Do it
anyway. HP goes 40 to 55, Attack 80 to 95, Defense 100 to 115, and Magnitude already
hits for 106 with STAB. Don't use an Everstone.

TM26 Earthquake is no shortcut. It's in the Seafloor Cavern near Archie and Kyogre.
That opens after the Mind Badge from gym 7, and reaching the TM needs Surf, Dive,
Strength, and Rock Smash.

**Makuhita**: Tackle 1, Focus Energy 1, Sand-Attack 4, Arm Thrust 10, **Vital Throw 13**,
Fake Out 19, Whirlwind 22, Knock Off 28, SmellingSalt 31, Belly Drum 37, Endure 40,
Seismic Toss 46, Reversal 49. **Hariyama at 24.**

**Taillow**: Peck 1, Growl 1, Focus Energy 4, Quick Attack 8, **Wing Attack 13**, Double
Team 19, Endeavor 26, **Aerial Ace 34**, Agility 43. **Swellow at 22.**

**Electrike**: Tackle 1, Thunder Wave 4, Leer 9, Howl 12, Quick Attack 17, **Spark 20**,
Odor Sleuth 25, Roar 28, Bite 33, Thunder 36, Charge 41. **Manectric at 26.** Takes TM24
Thunderbolt, TM25 Thunder, TM34 Shock Wave.

**Wingull**: Growl 1, **Water Gun 1**, Supersonic 7, **Wing Attack 13**, Mist 21, Quick
Attack 31, Pursuit 43, Agility 55. **Pelipper at 25.** Water Gun at 40 power is its only
Water move by level.

**Pelipper**: Growl 1, Water Gun 1/3, Water Sport 1, Wing Attack 1/13, Supersonic 7,
Mist 21, Protect 25, Stockpile 33, Swallow 33, Spit Up 47, **Hydro Pump 61**. Takes
**HM03 Surf** and HM02 Fly, both with STAB. Surf is the reason to raise this line.

**Slakoth**: Scratch 1, Yawn 1, Encore 7, Slack Off 13, Faint Attack 19, Amnesia 25,
Covet 31, Counter 37, Flail 43. **Vigoroth at 18**, which swaps Truant for Vital Spirit.

## HM compatibility, current roster

| Pokemon | HMs it can learn |
|---|---|
| Wingull | Fly only. **Not Surf** |
| Pelipper | Fly and **Surf**, both with STAB |
| Kadabra | Flash only. **Not Cut** |
| Slakoth | Cut, Strength, Rock Smash |
| Makuhita | Surf, Strength, Rock Smash. **Not Cut** |
| Taillow | Fly |
| Geodude | Strength, Rock Smash |

Cut is the bottleneck. Slakoth is the only carrier on the team.

## Wild locations

**Granite Cave.** 1F has Zubat, Abra, Geodude, Makuhita. Lower floors add Sableye
(Sapphire and Emerald, Ruby needs a trade) and Aron. Steven's room needs only Flash. B2F
needs the Mach Bike. Steven gives TM47 Steel Wing for the Letter.

**Route 110**, Emerald grass. Zigzagoon is the Ruby and Sapphire slot. Emerald swaps in
Poochyena.

| Pokemon | Lv | Rate | vs Geodude |
|---|---|---|---|
| Electrike | 12-13 | 30% | immune |
| Poochyena | 12 | 20% | neutral, but it only has Tackle and Howl early |
| Minun | 13 | 15% | immune |
| Gulpin | 12-13 | 15% | resisted |
| **Oddish** | 13 | 10% | **4x** |
| **Wingull** | 12 | 8% | **4x** |
| Plusle | 12-13 | 2% | immune |

Surfing gives Tentacool, Wingull, Pelipper.

**Hoenn Safari Zone.** Entrance is north of Route 121, so it opens after Winona. $500
for 30 Safari Balls, 500-step limit, and it needs the Pokeblock Case. In Emerald the case
comes from the Lilycove Contest Hall. Ruby and Sapphire give it in Slateport.

| Pokemon | Area | Levels | Rate |
|---|---|---|---|
| Natu | 1 Central, 2 West | 25 | 10% |
| Natu | 4 North | 27, 29 | 15% |
| Xatu | 4 North | 29, 31 | 5% |
| **Heracross** | 4 North | 27, 29 | 5% |
| Phanpy | 4 North | 27, 29 | 30% |
| Pikachu | 1 Central, 2 West | 25, 27 | 5% |
| Pinsir | 3 Northwest | 27, 29 | 5% |

Area 3 needs the **Mach Bike**. Area 4 needs the **Acro Bike**. Rydel swaps models free,
so plan two passes or swap between them.

Heracross is the gym 7 answer. Bug hits Psychic for 2x. Xatu is a dex catch only, it
loses to Kadabra on both Special Attack and Speed.

Areas 5 and 6 are Emerald-only and need the Hall of Fame plus the National Dex.

**New Mauville.** Magnemite and Voltorb 22-26, Magneton and Electrode 26 at 1% each.
Needs Surf plus the Basement Key, and Wattson only hands over the key **after the
Balance Badge from Norman**. Three fake item balls are lv25 Voltorb.

## Item chain

| Item | Where | Trigger |
|---|---|---|
| Exp. Share | Mr. Stone, Devon Corp 3F, Rustboro | Deliver the Letter to Steven |
| TM47 Steel Wing | Steven, Granite Cave | Deliver the Letter |
| TM46 Thief | Aqua grunt, Oceanic Museum 1F | Given as soon as you walk in, before you go upstairs. He flees right after |
| Repeat Ball | Devon researcher, Route 116 | Deliver the Devon Goods. Also unlocks Repeat and Timer Ball sales in Rustboro |
| Coin Case | Woman near the Mauville Mart | Trade a Harbor Mail from the Slateport Mart |
| Itemfinder | Rival, Route 110 | Win the battle |
| TM24 Thunderbolt | Wattson | Finish the New Mauville errand, or 4000 Game Corner coins |
| Pokeblock Case | Lilycove Contest Hall | Needed to enter the Safari Zone |
| HM04 Strength | Wanda's boyfriend, mid Rusturf Tunnel | Break the rocks with Rock Smash first. Field use needs the **Heat Badge**, gym 4 |
| HM06 Rock Smash | Rock Smash Guy, southeastern house in Mauville | No prerequisite. Field use needs the Dynamo Badge |
| HM02 Fly | Brendan or May hands it over after the Route 119 battle | Field use needs the **Feather Badge**, gym 6 |
| TM43 Secret Power | Route 111 north | Also unlocks Secret Bases |
| Soot Sack | Glass Workshop, Route 113 | Collects volcanic ash |

## Item effects

| Item | Effect in Gen 3 |
|---|---|
| PP Up | Adds 1/5 of a move's base PP. Three uses per move, so +60% at most |
| Cheri Berry | Held. Cures paralysis on its own, then it's gone |
| Guard Spec. | Mist on your side for 5 turns. Blocks stat drops from opponents, not your own |
| Elixir | Restores 10 PP to every move |

## Mr. Briney's ferry

Petalburg (his cottage on Route 104) and Dewford unlock after Peeko is rescued.
Slateport unlocks after the Letter reaches Steven. He retires once you take the Balance
Badge from Norman, then reappears on the S.S. Tidal.

Petalburg and Slateport don't connect directly. Everything routes through Dewford.

## Thief targets

In Gen 3 Thief keeps the item for good, from wild Pokemon and from ordinary trainers.

| Item | Holder | Rate |
|---|---|---|
| Spell Tag | Shuppet, Duskull (Mt. Pyre) | 5%. No other source |
| Moon Stone | Lunatone (Meteor Falls) | 5% |
| Sun Stone | Solrock (Meteor Falls) | 5% |
| Dragon Scale | Bagon, Horsea | 5% |
| TwistedSpoon | Abra | 5% |
| Sitrus Berry | Linoone | 5% |

Gen 3 gives each species a common slot at 50% and a rare slot at 5%. Everything in the
table above is a rare-slot item. If one item fills both slots it appears 100% of the time.

Leading with a Compound Eyes Pokemon (Nincada) shifts those odds from **50%/5% to
60%/20%**. This starts in Emerald, and the lead counts even when fainted.

Safari Zone Pikachu hold a Light Ball 5% of the time, but moves don't work in the Safari
Zone, so you have to catch one. Wild Clamperl hold Blue Shards, not the Deep Sea items.

## Easy Chat

- **Pokemon Fan Club interview, Slateport.** Cosmetic. The words go into a TV program
  verbatim. Only the lead Pokemon changes which broadcast plays.
- **Dewford Hall trendy phrase.** Sets which six tiles of the Route 119 river hold
  Feebas.
- **Mystery Gift.** Answer the Poke Mart questionnaire with LINK TOGETHER WITH ALL.

## Sources

- [Emerald gym leaders and Elite Four, Pokemon Database](https://pokemondb.net/emerald/gymleaders-elitefour)
- [Emerald updated gyms, Serebii](https://www.serebii.net/emerald/gym.shtml)
- [Mauville Gym](https://bulbapedia.bulbagarden.net/wiki/Mauville_Gym)
- [Dewford Gym](https://bulbapedia.bulbagarden.net/wiki/Dewford_Gym)
- [Granite Cave](https://bulbapedia.bulbagarden.net/wiki/Granite_Cave)
- [Oceanic Museum](https://bulbapedia.bulbagarden.net/wiki/Oceanic_Museum)
- [Stern's Shipyard](https://bulbapedia.bulbagarden.net/wiki/Stern's_Shipyard)
- [New Mauville](https://bulbapedia.bulbagarden.net/wiki/New_Mauville)
- [Hoenn Safari Zone](https://bulbapedia.bulbagarden.net/wiki/Hoenn_Safari_Zone)
- [Mr. Briney](https://bulbapedia.bulbagarden.net/wiki/Mr._Briney)
- [Trick House](https://bulbapedia.bulbagarden.net/wiki/Trick_House)
- [Hoenn Route 110](https://bulbapedia.bulbagarden.net/wiki/Hoenn_Route_110), [Hoenn Route 103](https://bulbapedia.bulbagarden.net/wiki/Hoenn_Route_103)
- [Emerald walkthrough part 3](https://bulbapedia.bulbagarden.net/wiki/Walkthrough:Pok%C3%A9mon_Emerald/Part_3), [part 4](https://bulbapedia.bulbagarden.net/wiki/Walkthrough:Pok%C3%A9mon_Emerald/Part_4), [part 5](https://bulbapedia.bulbagarden.net/wiki/Walkthrough:Pok%C3%A9mon_Emerald/Part_5)
- Gen III learnsets: [Combusken](https://bulbapedia.bulbagarden.net/wiki/Combusken_(Pok%C3%A9mon)/Generation_III_learnset), [Geodude](https://bulbapedia.bulbagarden.net/wiki/Geodude_(Pok%C3%A9mon)/Generation_III_learnset), [Graveler](https://bulbapedia.bulbagarden.net/wiki/Graveler_(Pok%C3%A9mon)/Generation_III_learnset), [Makuhita](https://bulbapedia.bulbagarden.net/wiki/Makuhita_(Pok%C3%A9mon)/Generation_III_learnset), [Taillow](https://bulbapedia.bulbagarden.net/wiki/Taillow_(Pok%C3%A9mon)/Generation_III_learnset), [Wingull](https://bulbapedia.bulbagarden.net/wiki/Wingull_(Pok%C3%A9mon)/Generation_III_learnset), [Kadabra](https://bulbapedia.bulbagarden.net/wiki/Kadabra_(Pok%C3%A9mon)/Generation_III_learnset), [Slakoth](https://bulbapedia.bulbagarden.net/wiki/Slakoth_(Pok%C3%A9mon)/Generation_III_learnset), [Electrike](https://bulbapedia.bulbagarden.net/wiki/Electrike_(Pok%C3%A9mon)/Generation_III_learnset), [Oddish](https://bulbapedia.bulbagarden.net/wiki/Oddish_(Pok%C3%A9mon)/Generation_III_learnset)
- Moves: [Vital Throw](https://bulbapedia.bulbagarden.net/wiki/Vital_Throw_(move)), [Arm Thrust](https://bulbapedia.bulbagarden.net/wiki/Arm_Thrust_(move)), [Magnitude](https://bulbapedia.bulbagarden.net/wiki/Magnitude_(move)), [Mud Sport](https://bulbapedia.bulbagarden.net/wiki/Mud_Sport_(move)), [Thief](https://bulbapedia.bulbagarden.net/wiki/Thief_(move)), [Swagger](https://bulbapedia.bulbagarden.net/wiki/Swagger_(move)), [Thunder Wave](https://bulbapedia.bulbagarden.net/wiki/Thunder_Wave_(move))
- [Contact](https://bulbapedia.bulbagarden.net/wiki/Contact), [Confusion](https://bulbapedia.bulbagarden.net/wiki/Confusion_(status_condition))
- [Wild held items](https://bulbapedia.bulbagarden.net/wiki/List_of_Pok%C3%A9mon_by_wild_held_item)
- Items: [PP Up](https://bulbapedia.bulbagarden.net/wiki/PP_Up), [Cheri Berry](https://bulbapedia.bulbagarden.net/wiki/Cheri_Berry), [Guard Spec.](https://bulbapedia.bulbagarden.net/wiki/Guard_Spec.)
- [Easy chat system](https://bulbapedia.bulbagarden.net/wiki/Easy_chat_system), [Trend](https://bulbapedia.bulbagarden.net/wiki/Trend)
- [Route 110 encounters, Serebii](https://www.serebii.net/pokearth/hoenn/3rd/route110.shtml)
