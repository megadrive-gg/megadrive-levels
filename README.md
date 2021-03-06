# Megadrive Levels

Welcome to Megadrive Levels.

Design, development and documentation by Cyclicism.

## Overview

< Megadrive Levels overview. />

> Remember, the level system is just for fun.
> We're an archival server with a goal to keep data free and accessible to all. These levels weren't designed to hide nor restrict content, but to provide an incentive for members to interact with the server and engage in the community - and ultimately help build to our evergrowing collection of linux ISOs.<br/><br/>
> Any specific data in any channel that you happen to request, we'll get it to you. We're not trying to privatise information, and Megadrive will never participate in a false sense of exclusivity that many other servers/online forums try to advertise and enforce. Apples to oranges. The channels we offer are simply our own curations of data that is already available.<br/><br/>
> ~ Keep information free.

## Contents
1. [Introduction / Overview](#overview)
2. [Experience](#experience)<br/>
   2A. [Experience Rate](#experience-per-message)<br/>
   2B. [Experience Table](#experience-table)<br/>
3. [Gaining Experience](#gaining-experience)<br/>
   3A. [Activities](#activities)<br/>
   3B. [Timeouts](#timeouts)<br/>
   3C. [Blacklist Channels](#blacklist-channels)<br/>
4. [Reputation](#reputation)
5. [Rewards](#rewards)
6. [Autorole](#autorole)
7. [Level Cards](#level-cards)
8. [Customisation](#customisation)
9. [Developer/Staff Commands](#staff-commands)

## Experience

Experience, referred to as `xp` or `exp` is a measure of engagement in several activities @ The Megadrive. You can gain experience by contributing content, interacting with the server or simply by chatting to other members.

For a full list of activities that provide experience, see [Activities](#activities).

Once reaching a certain ammount of experience points, members advance to the next respective level - which can unlock hidden channels and server benefits.

### Experience per message
The experience you receive per message depends on your current level, the message content as well as bonus multipliers.

For reference, this simple formula rougly calculates the average given experience per message.<br/>
`current_level + random_exp * global_multiplier`.

(The default multiplier is `1`, and `random_exp` is between 5 to 10.)

For example:
- If you're level 10 - you'll receive ~ `17.5exp` per message.
- If you're level 25 - you'll receive ~ `32.5exp` per message.

In addition, each user has an individual `exp_multiplier`. If one has been set, it will overwrite the `global_multiplier`. For more info on experience multipliers, see [Multipliers](#experience-multipliers).

### Experience table

<p float="left">
  The difference between level
  <img src="https://i.imgur.com/4ECVyAG.png" width="26px"/> 
   and level
  <img src="https://i.imgur.com/CK19tWg.png" width="26px"/>
   is
  <img src="https://i.imgur.com/zH1MFAR.png" width="104px"/>
.</p>
<p float="left">
  The table below displays this experience difference for each level and also the cumulative experience from level 1 to level 
  <img src="https://i.imgur.com/CK19tWg.png" width="26px"/>
.</p>

  | Level         | Total Exp           | Exp Difference |  ...Level         | Total Exp           | Exp Difference |
  | ------------- | ------------- | -------------- |  ------------- | ------------- | -------------- |
  | 1 | 0 | Null | 64 | 407,015 | 38,416 | 
  | 2 | 83 | 83 | 65 | 449,428 | 42,413 |
  | 3 | 174 | 91 | 66 | 496,254 | 46,826 |
  | 4 | 276 | 102 | 67 | 547,953 | 51,699 |
  | 5 | 388 | 112 | 68 | 605,032 | 57,079 | 
  | 6 | 512 | 124 | 69 | 668,051 | 63,019 | 
  | 7 | 650 | 138 | 70 | 737,627 | 69,576 | 
  | 8 | 801 | 151 | 71 | 814,445 | 76,818 |
  | 9 | 969 | 168 | 72 | 889,257 | 84,812 |
  | 10 | 1,154 | 185 | 73 | 992,895 | 93,638 |
  | 11 | 1,358 | 204 | 74 | 1,096,278 | 103,383 |
  | 12 | 1,584 | 226 | 75 | 1,210,421 | 114,143 |
  | 13 | 1,833 | 249 | 76 | 1,336,443 | 126,022 |
  | 14 | 2,107 | 274 | 77 | 1,475,581 | 139,138 |
  | 15 | 2,411 | 304 | 78 | 1,629,200 | 152,619 |
  | 16 | 2,746 | 335 | 79 | 1,798,808 | 169,608 |
  | 17 | 3,115 | 369 | 80 | 1,986,068 | 187,260 |
  | 18 | 3,523 | 408 | 81 | 2,192,818 | 206,750 |
  | 19 | 3,973 | 450 | 82 | 2,421,087 | 228,269 |
  | 20 | 4,470 | 497 | 83 | 2,673,114 | 252,027 |
  | 21 | 5,018 | 548 | 84 | 2,951,373 | 278,259 |
  | 22 | 5,624 | 606 | 85 | 3,258,594 | 307,221 |
  | 23 | 6,291 | 667 | 86 | 3,597,792 | 339,198 |
  | 24 | 7,028 | 737 | 87 | 3,972,294 | 374,502 |
  | 25 | 7,842 | 814 | 88 | 4,385,776 | 413,482 |
  | 26 | 8,740 | 898 | 89 | 4,842,295 | 456,519 |
  | 27 | 9,730 | 990 | 90 | 5,346,332 | 504,037 |
  | 28 | 10,824 | 1,094 | 91 | 5,902,831 | 556,499 |
  | 29 | 12,031 | 1,207 | 92 | 6,517,253 | 614,422 |
  | 30 | 13,363 | 1,332 | 93 | 7,195,629 | 678,376 |
  | 31 | 14,833 | 1,470 | 94 | 7,944,614 | 748,985 
  | 32 | 16,456 | 1,623 | 95 | 8,771,558 | 826,944 
  | 33 | 18,247 | 1,791 | 96 | 9,684,577 | 913,019 
  | 34 | 20,224 | 1,977 | 97 | 10,692,629 | 1,008,052 
  | 35 | 22,406 | 2,182 | 98 | 11,805,606 | 1,112,977 
  | 36 | 24,815 | 2,409 | 99 | 13,034,431 | 1,228,825 
  | 37 | 27,473 | 2,658 | 100 | 14,391,160 | 1,356,729 
  | 38 | 30,408 | 2,935 | 101 | 15,889,109 | 1,497,949 
  | 39 | 33,648 | 3,240 | 102 | 17,542,976 | 1,653,867 
  | 40 | 37,224 | 3,576 | 103 | 19,368,992 | 1,826,016 
  | 41 | 41,171 | 3,947 | 104 | 21,385,073 | 2,016,081 
  | 42 | 45,529 | 4,358 | 105 | 23,611,006 | 2,225,933 
  | 43 | 50,339 | 4,810 | 106 | 26,068,632 | 2,457,626 
  | 44 | 55,649 | 5,310 | 107 | 28,782,069 | 2,713,437 
  | 45 | 61,512 | 5,863 | 108 | 31,777,943 | 2,995,874 
  | 46 | 67,983 | 6,471 | 109 | 35,085,654 | 3,307,711 
  | 47 | 75,127 | 7,144 | 110 | 38,737,661 | 3,652,007 
  | 48 | 83,014 | 7,887 | 111 | 42,769,801 | 4,032,140 
  | 49 | 91,721 | 8,707 | 112 | 47,221,641 | 4,451,840 
  | 50 | 101,333 | 9,612 | 113 | 52,136,869 | 4,915,228 
  | 51 | 111,945 | 10,612 | 114 | 57,563,718 | 5,426,849 
  | 52 | 123,660 | 11,715 | 115 | 63,555,443 | 5,991,725 
  | 53 | 136,594 | 12,934 | 116 | 70,170,840 | 6,615,397 
  | 54 | 150,872 | 14,278 | 117 | 77,474,828 | 7,303,988 
  | 55 | 166,636 | 15,764 | 118 | 85,539,082 | 8,064,254 
  | 56 | 184,040 | 17,404 | 119 | 94,442,737 | 8,903,655 
  | 57 | 203,254 | 19,214 | 120 | 104,273,167 | 9,830,430 
  | 58 | 224,466 | 21,212 | 121 | 115,126,838 | 10,853,671 
  | 59 | 247,886 | 23,420 | 122 | 127,110,260 | 11,983,422 
  | 60 | 273,742 | 25,856 | 123 | 140,341,028 | 13,230,768 
  | 61 | 302,288 | 28,546 | 124 | 154,948,977 | 14,607,949 
  | 62 | 333,804 | 31,516 | 125 | 171,077,457 | 16,128,480 
  | 63 | 368,599 | 34,795 | 126 | 188,884,740 | 17,807,283 
  |    |         |        | Max | 200,000,000 | 11,115,260 

## Gaining Experience
To start gaining experience @ The Megadrive, refer to the Activities list below.

### Activities
- Sending messages. This will net you approximately `your current level` + `7.5 exp` * `multiplier`.
- `Disabled`. ~~Reacting with stars. For a limited time, adding ??? stars will net you `5exp` * `multiplier`.~~
- More TBC.

### Timeouts
To avoid spam and level abuse, the level system has an in-built timeout feature which limits exp to one interaction per 30 seconds.<br/>
Ie. If you spam 10 messages within 30 seconds, you'll only gain exp for one message.

This is known as a `global_timout`.

The timer starts from the **first** message and resets after 30 seconds. The timeout does not stack.

If you're a common shitposter, this limit can increase (via the default `user_timeout`, overwriting the `global_timeout`.)

### Experience Multipliers

### Blacklist Channels
There is also a selection of channels which have been blacklisted from giving experience. Some of these include:
- Any active threads.
- `#bot-spam`.
- `#bot-stuff`.
- `#levels`.
- `#requests`.

In addition, all bot commands such as `>level`, `>stats`, `-whois` or `.fm` will not net experience in any channel.

## Reputation
Reputation system still in development.

## Rewards
Rewards and level milestones TBC.

## Autorole
Megadrive Levels has built-in automation to ensure all members get their respective roles.

By default, all members start at @Level 1.<br/>
This means as soon as you get your first experience, or send your first message - you'll automatically be given the @Level 1 role, which'll then begin advancing to Level 2, Level 3 and so on.

Level roles are given in intervals of 10, excluding starter Levels 1 and 5.

Here is a list of available level roles.
```
@Level 1 (Default)
@Level 5
@Level 10
@Level 20
@Level 30
@Level 40
@Level 50
```

Each time you hit a new milestone/level role, Cycbot will ping you in the `#levels` channel notifying you and granting you the respective role. To disable this, simply mute the channel.

## Level Cards
Level cards (also known as rank cards) are an easy way to display your level progress - including your current rank, level, experience and the experience difference to your next level.

To display your level card, use `>level` or `>rank` in a supported channel (currently `#bot-stuff`.)

An example of a level card can be seen below.<br/><br/>
![levelcard](https://cdn.discordapp.com/attachments/956116230274678804/960903023016693780/levelcard.png)

> Please note: This level card is temporary. New mockups will be available shortly, with faster performance and better appearance.

## Customisation
Customisation still in development.

## Staff Commands
Here is a list of available developer/staff commands.

> Note to staff:~ Do not use `setxp` or `setlevel` to boost your own levels.

### Developer
- `>config multiplier <new_multiplier>`: Updates the `global_multiplier`. For bonus exp events etc.
- `>config timeout <new_timeout>`: Updates the `global_timeout`.
- `>populate_xp_table`: Repopulates the exp table (for restoration purposes.)

### Staff
- `>resetxp <Member>`: Resets a member's experience back to 0.
- `>setlevel <Level> <Member>`: Updates a member's level. This'll also update their exp.
- `>setxp <Experience> <Member>`: Updates a member's experience. This'll also update their level.
- `>setmultiplier <Multiplier> <Member>`: Sets a new `exp_multiplier` for a user. This'll overwrite the `global_multiplier`.
- `>settimeout <Timeout> <Member>`: Sets a new default timeout for a user.

### Parameters:
- `<Member>`: Represents a discord member. This can be a mention (@Member) or `user_id` (123456789101213).
- `<Level>`: Represents an integer. Must be above 0 (Max. 127).
- `<Experience>`: Represents an integer. Must be above 0 (Max. 200000000).
- `<Multiplier>`: Represents an integer. Must be above 1 (Max. 10).
- `<Timeout>:` Represents an integer (seconds.) Must be above 0 (Max. 100).
