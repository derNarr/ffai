# Features

FFAI currently supports the following features.
The purpose of this document is to have an overview of the road map for the project and to easily allow developers to 
identify missing features. If you want to help developing FFAI, the easiest way to get started is to implement or write 
a test for a skill.

## Game Modes

| Mode               | Implemented | Has Test(s) |
|--------------------|-------------|-------------|
| **AI vs. AI**      | YES         | YES         |
| **Human vs. AI**   | YES         | N/A         |
| **Hotseat**        | YES         | N/A         |
| **Online play**    | YES         | N/A         |
| **OpenAI Gym**     | YES         | YES         |
| **Headless**       | YES         | YES         |
| **AI Competition** | PARTIALLY   | NO          |

## Integrations

| System             | Implemented | Has Test(s) |
|--------------------|-------------|-------------|
| **OBBLM**          | NO          | NO          |
| **FUMBBL**         | NO          | NO          |

We are actively working towards and integration between FFAI and OBBLM.

## Races

A race is supported if all positions can be used and all their starting skills are supported.

| Race                   | Missing positions       | Missing skills                     | Have icons    |
|------------------------|-------------------------|------------------------------------|----------------
| **Amazon**        |                         |                                    | YES           |
| **Bretonnia**     |                         |                                    | YES           |
| **Chaos**         |                         |                                    | YES           |
| **Chaos Dwarf**   |                         |                                    | YES           |
| Dark Elf          | Assassin, Witch Elf     | Shadowing, Stab, Jump Up, Dump-off | YES           |
| Dwarf Slayer      | Skaven Slayer           | Nerves of Steel                    | NO            |
| **Elven Union**   |                         |                                    | YES           |
| Goblin            | Goblin, Troll, Pogoer, Fanatic, Looney, Bomma, Doom Diver, 'Ooligan        | Right stuff, Bombadier, Secret Weapon, Chainsaw, Ball & Chain, No Hands, Always Hungry, Throw Team-mate, Disturbing Presence, Swoop, Fan Favorite | SOME?      |
| Halfling          | Halfling, Treeman       | Right stuff, Take Root, Throw Team-Mate, Timmm-ber! | YES     |
| **High Elf**      |                         |                                    | YES              |
| **Human**         |                         |                                    | YES           |
| Human Nobility    |                         |                                    | NO            |
| Khemri            | Tomb Guardians          | Decay                              | YES           |  
| Khorne            |                         |                                    | NO           |  
| **Lizardmen**     |                         |                                    | YES           |
| Necromantic       |                         |                                    | NO           |
| Norse             | Berserkers, Yhetee      | Jump Up, Disturbing Presence            | YES        |
| Nurgle            | Rotters | Decay, Nurgle's Rot, Foul Appearance, Disturbing Presence, Tentacles | NO            |
| **Orc**           |                          |                                    | YES           |
| Ogre              | Snotling, Ogre          | Right Stuff, Titchy, Throw Team-Mate | YES           |
| **Skaven**        |                         |                                    | YES           |
| Savage Orc        | Throwers                | Nerves of Steel                    | NO            |
| Skaven: Pestilent Vermin | Novitiates, Pox-flingers, Poison-keepers | Disturbing Presence, Bombardier, Secret Weapon, Stab | NO        |
| **Undead**        |                         |                                    | YES
| Vampire           | Vampire | Blood Lust, Hypnotic Gaze                          | YES
| Wood Elf          | Treeman                 | Take Root                          | YES              |         
| Chaos Renegades   | Goblin Renegade, Orc Renegade, Skaven Renegade, Dark Elf Renegade, Chaos Troll, Chaos Ogre | Animosity, Right Stuff, Always Hungry | MAYBE?
| Slann             | Catchers, Blitzers | Diving Catch, Jump Up, Diving Tackle   | NO              |         
| Underworld        | Warpstone Troll, Underworld Goblins, Skaven Linemen, Skaven Throwers, Skaven Blitzers | Right Stuff, Animosity, Always Hungry, Throw Team-Mate | MAYBE?              |         

## Skills

| Skill             | Implemented | Has Test(s) |
|-------------------|-------------|-----------|
| **Accurate**      | YES         | YES       |
| Always Hungry     | NO          | NO        |
| Animosity         | NO          | NO        |
| Ball & Chain      | PARTIALLY   | NO        |
| **Big Hand**      | YES         | YES       |
| **Block**         | YES         | YES       |
| Blood Lust        | NO          | NO        |
| Bombardier        | NO          | NO        |
| **Bone-head**     | YES         | YES       |
| Break Tackle      | PARTIALLY   | NO        |
| **Catch**         | YES         | YES       |
| Chainsaw          | NO          | NO        |
| Claws             | YES         | NO        |
| Dauntless         | YES         | NO        |
| Decay             | NO          | NO        |
| Dirty Player      | YES         | NO        |
| Disturbing Presence | NO        | NO        |
| Diving Catch      | NO          | NO        |
| Diving Tackle     | NO          | NO        |
| **Dodge**         | YES         | YES       |
| Dump-Off          | NO          | NO        |
| **Extra Arms**    | YES         | YES       |
| Fan Favorite      | NO          | NO        |
| Fend              | YES         | NO        |
| Filthy Rich       | NO          | NO        |
| Foul Appearance   | NO          | NO        |
| **Frenzy**        | YES         | YES       |
| Grab              | YES         | NO        |
| Guard             | YES         | NO        |
| Hail Mary Pass    | YES         | NO        |
| Horns             | YES         | NO        |
| Hypnotic Gaze     | NO          | NO        |
| Juggernaut        | YES         | NO        |
| Jump Up           | NO          | NO        |
| Kick              | NO          | NO        |
| Kick Team-Mate    | NO          | NO        |
| Kick-Off Return   | NO          | NO        |
| Leader            | NO          | NO        |
| **Leap**          | YES         | YES       |
| Loner             | YES         | NO        |
| Mighty Blow       | YES         | NO        |
| Multiple Block    | NO          | NO        |
| Monstrous Mouth   | NO          | NO        |
| Nerves of Steel   | YES         | NO        |
| No Hands          | YES         | NO        |
| Nurgle's Rot      | NO          | NO        |
| Pass              | YES         | NO        |
| Pass Block        | NO          | NO        |
| Piling On         | NO          | NO        |
| Prehensile Tail   | YES         | NO        |
| Pro               | YES         | NO        |
| **Really Stupid** | YES         | YES       |
| **Regeneration**  | YES         | YES       |
| Right Stuff       | NO          | NO        |
| **Safe Throw**    | YES         | YES       |
| Secret Weapon     | NO          | NO        |
| Shadowing         | NO          | NO        |
| Side Step         | YES         | NO        |
| Sneaky Git        | NO          | NO        |
| Sprint            | YES         | NO        |
| Stab              | NO          | NO        |
| Stakes            | NO          | NO        |
| Stand Firm        | YES         | NO        |
| Strip Ball        | NO          | NO        |
| **Strong Arm**    | YES         | YES       |
| Stunty            | YES         | NO        |
| Sure Feet         | YES         | NO        |
| **Sure Hands**    | YES         | YES       |
| Swoop             | NO          | NO        |
| Tackle            | YES         | NO        |
| Take Root         | NO          | NO        |
| Tentacles         | NO          | NO        |
| Thick Skull       | YES         | NO        |
| Throw Team-Mate   | NO          | NO        |
| Timmm-ber!        | NO          | NO        |
| Titchy            | PARTIALLY   | NO        |
| Two Heads         | YES         | NO        |
| **Very Long Legs**| YES         | YES       |
| Weeping Dagger    | NO          | NO        |
| **Wild Animals**  | YES         | YES       |
| Wrestle           | YES         | NO        |

## Pre-match Sequence

| Step                    | Implemented | Has Test(s) |
|-------------------------|-------------|-------------|
| **1. Weather Table**    | YES         | YES         |
| 2. Stadium              | NO          | NO          |
| 3. Referee              | NO          | NO          |
| 4. Inducements          | NO          | NO          |
| 5. Special Play Cards   | NO          | NO          |
| 6. Referee              | NO          | NO          |
| **7. Coin Toss**        | YES         | YES         |
| **8. Fans and Fame**    | YES         | YES         |

## Kick-off Table

| Kick-off Event            | Implemented | Has Test(s) |
|---------------------------|-------------|-------------|
| **1. Weather Table**      | YES         | YES         |
| 2. Stadium                | NO          | NO          |
| 3. Referee                | NO          | NO          |
| 4. Inducements            | NO          | NO          |
| 5. Special Play Cards     | NO          | NO          |
| 6. Referee                | NO          | NO          |
| **7. Coin Toss**          | YES         | YES         |

## Post-match Sequence

| Step                      | Implemented | Has Test(s) |
|---------------------------|-------------|-------------|
| 1. Improvement Rolls      | NO          | NO          |
| 2. Report Game Result     | NO          | NO          |
| 3. Fortune and FAME       | NO          | NO          |
| 4. Hire and Fire          | NO          | NO          |
| 5. Special Play Cards     | NO          | NO          |
| 6. Prepare for Next Match | NO          | NO          |

Some of these steps should be done in a league manager rather than in FFAI if humans are playing.

## Coaching Staff
| Staff                     | Implemented | Has Test(s) |
|---------------------------|-------------|-------------|
| 1. Head Coach (Argue the call) | NO     | NO          |
| 2. Assistant Coaches      | YES         | YES         |
| 3. Cheerleaders           | YES         | YES         |
| 4. Apothecary             | PARTIALLY   | NO          |

## Star Players
Star players are not supported - mostly because the pre-match sequence isn't implemented yet.